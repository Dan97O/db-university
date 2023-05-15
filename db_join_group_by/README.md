Query con Join:
1. Selezionare tutti gli studenti iscritti al Corso di Laurea in Economia
SELECT `students`.*, `degrees`.`name`
FROM `students`
JOIN `degrees` ON `students`.`degree_id` = `degrees`.`id`
WHERE `degrees`.`name` = 'Corso di Laurea in Economia';

2. Selezionare tutti i Corsi di Laurea Magistrale del Dipartimento di Neuroscienze
SELECT `degrees`.`name` AS `degrees_name`, `departments`.`name` AS `department_name`
FROM `degrees`
JOIN `departments` ON `degrees`.`department_id` = `departments`.`id`
WHERE `degrees`.`level` ='magistrale' AND `departments`.`name` = 'Dipartimento di Neuroscienze';

3. Selezionare tutti i corsi in cui insegna Fulvio Amato (id=44)
SELECT `courses`.`name` AS `courses_name`, `teachers`.`name` AS `teachers_name`
FROM `courses`
JOIN `course_teacher` ON `courses`.`id` = `course_teacher`.`course_id`
JOIN `teachers` ON `course_teacher`.`teacher_id` = `teachers`.`id`
WHERE `teachers`.id = 44;

4. Selezionare tutti gli studenti con i dati relativi al corso di laurea a cui sono iscritti e il
  relativo dipartimento, in ordine alfabetico per cognome e nome
SELECT `students`.*, `degrees`.`name` AS `degree_name`, `departments`.`name` AS `department_name`
FROM `students`
JOIN `degrees` ON `students`.`degree_id` = `degrees`.id
JOIN `departments` ON `degrees`.`department_id` = `departments`.id
ORDER BY `students`.`surname` ASC, `students`.`name` ASC;

5. Selezionare tutti i corsi di laurea con i relativi corsi e insegnanti
SELECT `degrees`.`name` AS `degree_name`, `courses`.`name` AS `course_name`, `teachers`.`surname` AS `teacher_surname`, `teachers`.`name` AS `teacher_name`
FROM `course_teacher`
JOIN `courses` ON `course_teacher`.`course_id` = `courses`.`id`
JOIN `teachers` ON `course_teacher`.`teacher_id` = `teachers`.`id`
JOIN `degrees` ON `courses`.`degree_id` = `degrees`.`id`;

6. Selezionare tutti i docenti che insegnano nel Dipartimento di Matematica (54)
SELECT DISTINCT `teachers`.*, `departments`.`name` AS `department_name`
FROM `teachers`
JOIN `course_teacher` ON `teachers`.`id` = `course_teacher`.`teacher_id`
JOIN `courses` ON `course_teacher`.`course_id` = `courses`.`id`
JOIN `degrees` ON `courses`.`degree_id` = `degrees`.`id`
JOIN `departments` ON `degrees`.`department_id` = `departments`.`id`
WHERE `departments`.`name` = 'Dipartimento di Matematica';

7. BONUS: Selezionare per ogni studente quanti tentativi d’esame ha sostenuto per
  superare ciascuno dei suoi esami
SELECT students.id AS student_id, students.name AS student_name, students.surname AS student_surname, exams.id AS exam_id, exam_student.vote AS vote,
COUNT(*) AS num_attempts
FROM students
JOIN exam_student ON students.id = exam_student.student_id
JOIN exams ON exam_student.exam_id = exams.id
GROUP BY students.id, students.name, exams.id;

Query con Group by:
1. Contare quanti iscritti ci sono stati ogni anno
SELECT YEAR(enrolment_date) AS year, COUNT(*) AS num_students
FROM students
GROUP BY YEAR(enrolment_date);

2. Contare gli insegnanti che hanno l'ufficio nello stesso edificio
SELECT office_address, COUNT(*) AS num_teachers
FROM teachers
GROUP BY office_address
HAVING COUNT(*) > 1;

3. Calcolare la media dei voti di ogni appello d'esame
SELECT exam_id, AVG(vote) AS average_vote
FROM exam_student
GROUP BY exam_id;

4. Contare quanti corsi di laurea ci sono per ogni dipartimento
SELECT departments.name AS department_name, COUNT(degrees.id) AS num_degrees
FROM departments
JOIN degrees ON departments.id = degrees.department_id
GROUP BY departments.name;


