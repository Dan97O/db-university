1. Selezionare tutti gli studenti nati nel 1990 (160)
2. Selezionare tutti i corsi che valgono più di 10 crediti (479)
3. Selezionare tutti gli studenti che hanno più di 30 anni
4. Selezionare tutti i corsi del primo semestre del primo anno di un qualsiasi corso di
  laurea (286)
5. Selezionare tutti gli appelli d'esame che avvengono nel pomeriggio (dopo le 14) del
  20/06/2020 (21)
6. Selezionare tutti i corsi di laurea magistrale (38)
7. Da quanti dipartimenti è composta l'università? (12)
8. Quanti sono gli insegnanti che non hanno un numero di telefono? (50)
 

Es:
1. SELECT * FROM `students` WHERE YEAR(date_of_birth) = 1990;  
| id   | degree_id | name         | surname    | date_of_birth | fiscal_code      | enrolment_date | registration_number | email                            |
+------+-----------+--------------+------------+---------------+------------------+----------------+---------------------+----------------------------------+
|   55 |         4 | Lauro        | Vitale     | 1990-01-30    | BWOQAH56L35A201P | 2018-10-22     | 620087              | baldassarre.mancini@dangelo.com  |
|   86 |        12 | Matilde      | Ruggiero   | 1990-11-17    | UIFHBM73Q42E973M | 2021-02-14     | 620118              | mariagiulia18@gmail.com          |
|  217 |        16 | Marieva      | Mariani    | 1990-08-30    | CRKYAI63Z72H930S | 2020-12-13     | 620249              | wgrassi@mariani.net              |
|  247 |        14 | Marco        | Bruno      | 1990-08-12    | EPSWUQ63H25I670E | 2020-06-08     | 620279              | ubaldo70@damico.it               |
|  306 |         3 | Maika        | Bianco     | 1990-01-04    | GVOZOR19K65V944K | 2019-11-21     | 620338              | nmancini@yahoo.com               |
|  320 |        72 | Fabiano      | Riva       | 1990-08-11    | UYVLCP51Y15P902L | 2019-10-10     | 620352              | miriam.lombardi@benedetti.org    |
|  321 |        44 | Amedeo       | Valentini  | 1990-04-20    | RLYGWZ26T24Y855N | 2020-04-18     | 620353              | dimitri.mariani@neri.com         |
|  334 |        59 | Tolomeo      | Morelli    | 1990-03-30    | WCLRKV39N67J467D | 2019-12-24     | 620366              | amedeo15@bruno.it                |
|  352 |        45 | Eriberto     | Sartori    | 1990-10-14    | MVUSNM49E07E792U | 2018-07-16     | 620384              | serse67@messina.com              |
|  359 |         2 | Harry        | Riva       | 1990-09-03    | FLFQUM03P76T235N | 2018-06-12     | 620391              | hcaputo@ferraro.com              |
|  365 |        67 | Ursula       | Sanna      | 1990-09-02    | UWSWJL98Y56C153N | 2018-11-20     | 620397              | vgreco@mancini.com               |
|  410 |        32 | Pietro       | Ruggiero   | 1990-05-11    | IIXLFZ21V02C420U | 2020-04-08     | 620442              | gerlando21@libero.it             |
|  430 |         4 | Harry        | Russo      | 1990-03-23    | BOTXVQ95I30B140O | 2020-02-06     | 620462              | giulietta.parisi@gmail.com       |
|  443 |        71 | Marino       | Sartori    | 1990-10-12    | IVJSXN23A76B707B | 2018-11-01     | 620475              | gallo.vera@hotmail.com           |
|  487 |        36 | Cira         | Costantini | 1990-04-12    | GTINRS89N80F500K | 2020-11-03     | 620519              | rizzo.enrica@piras.it            |
|  519 |        63 | Damiana      | Farina     | 1990-01-12    | EYKYWC35O38O744L | 2020-07-17     | 620551              | yserra@russo.it                  |
|  527 |        43 | Elda         | Mariani    | 1990-04-29    | ZHGJNM05Z55G492M | 2021-05-21     | 620559              | antonio25@yahoo.it               |
|  528 |        69 | Maika        | Barbieri   | 1990-04-29    | VBMCXI81Q82M718M | 2020-05-11     | 620560              | ygiordano@yahoo.com              |
|  582 |        41 | Augusto      | Costantini | 1990-07-31    | FPQBKO39S99H539Q | 2018-06-26     | 620614              | radio21@grassi.com               |
|  624 |         4 | Cira         | De rosa    | 1990-04-26    | FDATYC59R80F558X | 2019-01-31     | 620656              | colombo.morgana@pellegrino.com   |
|  635 |        45 | Boris        | Riva       | 1990-12-28    | FWYSKJ18E55V673Z | 2020-10-30     | 620667              | sandro72@gmail.com               |
|  638 |         5 | Marcella     | De rosa    | 1990-08-29    | IQDFNY14D55U297S | 2018-09-11     | 620670              | assia.palumbo@libero.it          |
|  695 |        37 | Boris        | Martinelli | 1990-02-25    | LMGYIC37W94J261P | 2020-04-27     | 620727              | damiana08@bianco.org             |
|  710 |        39 | Egisto       | Amato      | 1990-06-07    | SZSUWA12R81D485V | 2020-08-24     | 620742              | qgallo@libero.it                 |
|  787 |        63 | Laura        | Coppola    | 1990-06-11    | IZINQY50C42J452U | 2020-05-17     | 620819              | rinaldi.brigitta@marchetti.com   |
|  857 |        56 | Prisca       | De luca    | 1990-03-12    | EEGCVW93W78P140E | 2019-09-26     | 620889              | enrica.pagano@gallo.it           |
|  877 |        25 | Samira       | Giuliani   | 1990-03-08    | GWKCVN98H21T451U | 2019-02-27     | 620909              | danuta16@email.it                |
|  912 |        36 | Flaviana     | Costa      | 1990-02-06    | ALEXFQ09O80M836R | 2020-08-15     | 620944              | michele.lombardi@yahoo.com       |
|  919 |        66 | Secondo      | Lombardo   | 1990-08-09    | OPZDMU62P86F655U | 2021-03-21     | 620951              | bbarone@sartori.net              |
| 1007 |        61 | Oreste       | Bianco     | 1990-07-08    | VVBTJU54P76X363N | 2021-04-18     | 621039              | alan.colombo@yahoo.com           |
| 1122 |        40 | Kociss       | De Angelis | 1990-06-01    | VQHNXM66A72G075Q | 2021-04-24     | 621154              | brigitta87@basile.it             |
| 1123 |        10 | Albino       | Riva       | 1990-11-13    | JXPRBQ67E99E968Q | 2020-03-04     | 621155              | rferraro@email.it                |
| 1130 |        68 | Mirko        | Coppola    | 1990-02-10    | SZVBTX90Y83R295A | 2018-08-10     | 621162              | grazia.negri@yahoo.com           |
| 1162 |        29 | Tancredi     | Guerra     | 1990-05-02    | DINOMU36K82R031K | 2019-09-26     | 621194              | jferrara@fontana.com             |
| 1181 |        23 | Enrica       | Bruno      | 1990-07-13    | JBYZPU73J22J109U | 2021-04-23     | 621213              | qgrassi@yahoo.it                 |
| 1190 |        57 | Gianmarco    | Rizzo      | 1990-08-26    | EZPZHW06V87Z409D | 2018-11-07     | 621222              | ebellini@yahoo.it                |
| 1214 |        40 | Miriana      | Negri      | 1990-08-15    | HKIPIX45A01G163V | 2020-09-24     | 621246              | germano18@ferri.com              |
| 1227 |        26 | Rodolfo      | Rossetti   | 1990-05-21    | NTZRPT68F75Y770Y | 2019-09-25     | 621259              | timothy.lombardi@martino.org     |
| 1291 |        23 | Iacopo       | Sorrentino | 1990-06-20    | MNITJF41I07V836B | 2018-12-05     | 621323              | giulietta49@yahoo.com            |
| 1343 |         8 | Cosetta      | Martino    | 1990-01-06    | CTSGZY69B86N969L | 2018-08-04     | 621375              | basile.zelida@testa.it           |
| 1376 |        52 | Artemide     | Bianco     | 1990-12-21    | YKIZWI45D57V431Z | 2019-08-19     | 621408              | donati.vania@gmail.com           |
| 1442 |        23 | Nayade       | Bellini    | 1990-11-18    | KPINCB99S52K194Q | 2019-06-11     | 621474              | mietta.greco@yahoo.it            |
| 1486 |        17 | Ethan        | Neri       | 1990-07-08    | XNCKTH78F26W131H | 2019-12-23     | 621518              | ipiras@libero.it                 |
| 1496 |        65 | Davis        | Ferrara    | 1990-05-09    | BNLTXY41D25N024I | 2020-02-18     | 621528              | rizzo.vitalba@ferretti.it        |
| 1497 |        64 | Olimpia      | Serra      | 1990-07-25    | XBUCEI78Y30G117T | 2020-04-01     | 621529              | vitale.noel@esposito.it          |
| 1505 |        38 | Brigitta     | Rinaldi    | 1990-11-14    | UFMWXE13H54A970A | 2020-12-15     | 621537              | xmilani@yahoo.com                |
| 1564 |        75 | Laura        | Cattaneo   | 1990-01-26    | MIMNRN14B99E364M | 2019-07-19     | 621596              | galli.ingrid@lombardi.com        |
| 1572 |        61 | Ruth         | Guerra     | 1990-07-31    | UAEVLN07P28Z561C | 2020-12-10     | 621604              | demi08@rossi.it                  |
| 1599 |        52 | Selvaggia    | Ferri      | 1990-04-26    | LJMVWF38G03A881Q | 2018-11-14     | 621631              | romano.cassiopea@yahoo.com       |
| 1657 |        53 | Nazzareno    | Fabbri     | 1990-02-06    | FXTQCL20K66N186J | 2021-06-01     | 621689              | barbieri.assia@martinelli.com    |
| 1673 |        55 | Lucia        | Martini    | 1990-11-18    | QISWZS06N00V825V | 2020-02-08     | 621705              | derosa.flaviana@email.it         |
| 1687 |        71 | Furio        | Battaglia  | 1990-10-30    | PXAVGZ01W97G783R | 2019-02-06     | 621719              | gianriccardo.mariani@yahoo.com   |
| 1695 |        67 | Carlo        | D'angelo   | 1990-11-26    | QBBYIJ82N00W683U | 2018-10-24     | 621727              | gavino90@yahoo.com               |
| 1715 |        19 | Tolomeo      | Piras      | 1990-09-17    | XNRZKQ19Z63L256T | 2019-09-10     | 621747              | fiorentino90@yahoo.it            |
| 1739 |         4 | Raniero      | De rosa    | 1990-07-04    | ORXOEI75M49L732L | 2019-06-12     | 621771              | joannes.sartori@yahoo.it         |
| 1771 |        55 | Danthon      | Longo      | 1990-05-03    | DLBXXT54A73H875F | 2020-06-21     | 621803              | brigitta.lombardi@damico.it      |
| 1855 |         3 | Erminia      | Sala       | 1990-06-01    | TZOSQM13M75Z551I | 2021-01-17     | 621887              | smoretti@barone.org              |
| 1885 |        58 | Giacinta     | Galli      | 1990-04-17    | BKZMZQ49P70W077O | 2018-08-03     | 621917              | flaviana98@yahoo.com             |
| 1921 |        66 | Ortensia     | Sartori    | 1990-04-05    | AVHKSX27U40G212X | 2019-03-14     | 621953              | qmontanari@rossetti.it           |
| 1946 |        65 | Costanzo     | Morelli    | 1990-12-18    | RJPUVA03F33I594G | 2020-04-19     | 621978              | rebecca84@giuliani.com           |
| 1978 |        14 | Elio         | Ferrari    | 1990-10-16    | KOWOHB43W49C058Y | 2020-04-16     | 622010              | deangelis.kociss@ferri.it        |
| 1979 |        25 | Ubaldo       | Galli      | 1990-09-12    | GNYFTP14E12E794J | 2018-12-26     | 622011              | fiorentino49@libero.it           |
| 1997 |         2 | Rufo         | Greco      | 1990-03-03    | VEUMII60C51P635H | 2020-03-30     | 622029              | lmancini@email.it                |
| 2028 |        32 | Rosalino     | Messina    | 1990-08-05    | ZNDKSG60A81S569Z | 2020-05-07     | 622060              | felicia80@yahoo.it               |
| 2061 |        35 | Violante     | Santoro    | 1990-01-10    | WOLHYL73W56R867R | 2019-03-27     | 622093              | valentini.michele@email.it       |
| 2104 |         5 | Samira       | Rizzo      | 1990-05-07    | DABXHS46S97J083E | 2019-07-06     | 622136              | fbarbieri@yahoo.com              |
| 2184 |        64 | Morgana      | Esposito   | 1990-05-30    | TJCYCP93Q21T068O | 2019-04-05     | 622216              | xruggiero@bruno.it               |
| 2232 |        21 | Rudy         | Caruso     | 1990-05-24    | YDMXTM21L01X925U | 2019-05-20     | 622264              | sibilla55@yahoo.com              |
| 2262 |        21 | Germano      | Pagano     | 1990-03-27    | CUWNGY34P24N905J | 2018-07-22     | 622294              | rosalba.costa@montanari.it       |
| 2289 |        18 | Elga         | Damico     | 1990-12-18    | FHGQKY20C50Z637O | 2020-03-19     | 622321              | bserra@romano.it                 |
| 2323 |        28 | Kristel      | Parisi     | 1990-10-21    | BCSGTK67O20U235F | 2020-10-12     | 622355              | deborah.messina@parisi.org       |
| 2397 |        53 | Vania        | Guerra     | 1990-09-14    | EZZRMN58O64U304A | 2021-03-14     | 622429              | ibruno@fontana.net               |
| 2407 |        15 | Rita         | Valentini  | 1990-08-14    | UKHNDX66K97I203D | 2021-02-11     | 622439              | iparisi@bruno.it                 |
| 2459 |        59 | Samira       | D'angelo   | 1990-06-28    | SDAIYB76D36C025J | 2018-06-27     | 622491              | marvin95@vitale.it               |
| 2460 |         2 | Manuele      | Bianco     | 1990-10-16    | ZMTQBT82G25S557M | 2019-04-26     | 622492              | serra.oretta@yahoo.com           |
| 2472 |        61 | Donatella    | Martini    | 1990-04-22    | IOUQGQ33V53M152G | 2021-01-17     | 622504              | miriam08@testa.org               |
| 2511 |        34 | Folco        | Sala       | 1990-01-03    | JOEICD35H21X349Q | 2020-01-08     | 622543              | ugallo@yahoo.com                 |
| 2540 |        21 | Iacopo       | Vitale     | 1990-04-29    | TMCLVH66D40C160W | 2018-10-24     | 622572              | dmessina@email.it                |
| 2559 |        69 | Pablo        | Giuliani   | 1990-04-26    | QJYPMD26I25W659P | 2019-04-30     | 622591              | mariagiulia21@gmail.com          |
| 2615 |        64 | Cleros       | Santoro    | 1990-06-08    | AELOSN94P60A939J | 2019-08-15     | 622647              | dferri@morelli.net               |
| 2616 |        71 | Silverio     | Messina    | 1990-02-27    | UPCSWC90T52D603B | 2019-10-05     | 622648              | demis.pellegrino@libero.it       |
| 2627 |        47 | Damiana      | Russo      | 1990-12-04    | PDHBTU35U55U339B | 2018-12-11     | 622659              | hferraro@romano.com              |
| 2674 |        70 | Primo        | D'angelo   | 1990-05-25    | SYRAPJ19H54Q380L | 2020-02-16     | 622706              | bianco.carmela@lombardi.com      |
| 2700 |        40 | Dindo        | Montanari  | 1990-04-04    | DDGVGI33Y33B886J | 2019-09-24     | 622732              | sarita.villa@yahoo.com           |
| 2715 |         6 | Amos         | Barone     | 1990-05-14    | VFRUII42C24D790X | 2019-06-21     | 622747              | ybianco@deangelis.net            |
| 2763 |        75 | Monia        | Galli      | 1990-07-19    | EHEBAS76W43N388S | 2020-08-18     | 622795              | moretti.gelsomina@grassi.org     |
| 2779 |        26 | Assia        | Morelli    | 1990-07-07    | WQYQHX33Z50R678E | 2018-12-16     | 622811              | ffiore@email.it                  |
| 2807 |        25 | Boris        | Mazza      | 1990-10-17    | VMOJVZ65M95G447Y | 2019-09-12     | 622839              | mariapia56@morelli.it            |
| 2901 |        36 | Olimpia      | Piras      | 1990-01-28    | LDVXVR15M88N131L | 2018-08-05     | 622933              | miriana11@email.it               |
| 2947 |         4 | Jole         | Pellegrini | 1990-09-20    | YMLFVT67H64G493P | 2019-11-26     | 622979              | martinelli.cristyn@yahoo.com     |
| 2949 |        40 | Ivano        | Farina     | 1990-04-01    | ZXFTQI13B40Y292U | 2020-03-10     | 622981              | bianchi.piersilvio@yahoo.com     |
| 2971 |        41 | Lauro        | Galli      | 1990-04-29    | RDDTNI28V51W148P | 2019-01-03     | 623003              | vania94@caputo.it                |
| 2995 |        11 | Iacopo       | Lombardo   | 1990-05-09    | RSTKOE73M68A197B | 2019-04-09     | 623027              | ursula35@gmail.com               |
| 3026 |        62 | Mauro        | Basile     | 1990-04-05    | LEKHVY04S26L005I | 2019-11-13     | 623058              | clodovea77@libero.it             |
| 3116 |        60 | Shaira       | Grassi     | 1990-05-30    | MWXZKG24P23U611A | 2020-07-06     | 623148              | laerte41@gmail.com               |
| 3227 |         3 | Gianleonardo | Ferretti   | 1990-11-28    | NBQAZJ89B07B357Y | 2020-03-09     | 623259              | grassi.gianantonio@battaglia.com |
| 3242 |        62 | Erminia      | Greco      | 1990-11-14    | XSGUZO84L49I522G | 2020-03-03     | 623274              | bianco.erminio@hotmail.com       |
| 3286 |        25 | Leone        | Marini     | 1990-01-09    | CHTWFJ25G97H875X | 2019-07-24     | 623318              | caligola.messina@silvestri.it    |
| 3309 |        40 | Noemi        | De rosa    | 1990-09-19    | XDNOAX06S15Z145X | 2019-12-17     | 623341              | mricci@costa.com                 |
| 3327 |        10 | Pietro       | Negri      | 1990-03-12    | JEWANF64V23M026T | 2019-02-11     | 623359              | ione27@ferrari.com               |
| 3332 |         8 | Silverio     | Palumbo    | 1990-03-02    | KOLWGI28O59O130N | 2020-08-24     | 623364              | naomi06@hotmail.com              |
| 3361 |        33 | Graziano     | Martini    | 1990-12-18    | XKGEWA77J64W440J | 2021-03-15     | 623393              | costa.nathan@yahoo.com           |
| 3379 |         6 | Graziano     | Riva       | 1990-01-31    | HSICLH34C60O191H | 2020-03-22     | 623411              | carmela58@coppola.com            |
| 3397 |        49 | Cassiopea    | Ferraro    | 1990-04-28    | GHGGGQ43I13A372U | 2019-04-18     | 623429              | wvilla@gallo.it                  |
| 3425 |        37 | Fortunata    | Pellegrino | 1990-05-19    | CKCMFR19L14C052T | 2020-11-22     | 623457              | cconte@palumbo.com               |
| 3479 |        49 | Maruska      | Barone     | 1990-09-07    | HQTHGC20J16T421F | 2019-01-29     | 623511              | igrasso@grassi.com               |
| 3498 |        71 | Claudia      | Lombardi   | 1990-06-02    | UUMJGO25L22C345I | 2018-10-31     | 623530              | ybianchi@libero.it               |
| 3510 |        15 | Giuliano     | Marini     | 1990-03-10    | DXLJVI11K08G312E | 2019-04-21     | 623542              | ugreco@hotmail.com               |
| 3511 |        72 | Rita         | Ricci      | 1990-04-26    | LXWBCL31I32A916N | 2019-04-27     | 623543              | sabino.martinelli@cattaneo.net   |
| 3522 |        16 | Timothy      | Marino     | 1990-07-25    | CPAFTB71C52Q471Z | 2021-05-16     | 623554              | antonino.piras@esposito.org      |
| 3643 |         1 | Fortunata    | Bianchi    | 1990-05-02    | TXNPCJ26N37B979H | 2019-06-23     | 623675              | amato.evangelista@yahoo.com      |
| 3687 |        24 | Bibiana      | Galli      | 1990-03-14    | VYIICS84C64W295T | 2018-08-10     | 623719              | cattaneo.ausonio@yahoo.it        |
| 3700 |        48 | Vitalba      | Pellegrino | 1990-10-16    | YHCHKS97R47J257I | 2021-01-26     | 623732              | tricci@ruggiero.com              |
| 3718 |        20 | Irene        | Morelli    | 1990-08-26    | XKKBWO51D05J706U | 2020-11-17     | 623750              | ferretti.gilda@bianco.org        |
| 3756 |        37 | Zelida       | Palumbo    | 1990-12-03    | YIBBLF29U85I393H | 2019-04-02     | 623788              | ovitale@gmail.com                |
| 3760 |        26 | Bibiana      | Neri       | 1990-08-28    | FZGUSZ40R71E465J | 2018-12-15     | 623792              | gallo.lorenzo@yahoo.com          |
| 3770 |         8 | Caligola     | Guerra     | 1990-03-07    | BSVEVY06Q04K151O | 2021-03-20     | 623802              | nsanna@email.it                  |
| 3835 |        37 | Ileana       | Ricci      | 1990-03-17    | OPCAIF74A88N272E | 2020-07-21     | 623867              | timoteo67@basile.com             |
| 3841 |        24 | Ausonio      | Sala       | 1990-02-23    | DPCTHN72Q38Q077G | 2019-10-18     | 623873              | arcibaldo.esposito@hotmail.com   |
| 3868 |        69 | Clea         | Bellini    | 1990-05-30    | PDGXXN04L56G048C | 2021-02-21     | 623900              | yago.moretti@yahoo.it            |
| 3869 |        31 | Cleopatra    | Parisi     | 1990-01-14    | GQYAQJ97I01U403H | 2018-08-10     | 623901              | mdamico@yahoo.com                |
| 3871 |        40 | Gaetano      | Barone     | 1990-01-31    | ZRRAGH96T10Z527L | 2019-12-09     | 623903              | tbianco@yahoo.it                 |
| 3882 |        48 | Gavino       | Conte      | 1990-08-19    | QVPHYU50U61B338H | 2020-01-08     | 623914              | lcosta@derosa.net                |
| 3894 |        71 | Egisto       | Longo      | 1990-07-18    | QOJPWF79J43U384H | 2021-04-28     | 623926              | fatima04@hotmail.com             |
| 3975 |        16 | Carlo        | Rinaldi    | 1990-10-10    | PFKGKF99F49G340R | 2020-10-26     | 624007              | felicia14@gatti.it               |
| 3987 |        53 | Vera         | Rinaldi    | 1990-04-26    | BPFBWC81E38V431C | 2019-12-23     | 624019              | luna.conti@yahoo.it              |
| 4001 |        44 | Vania        | Romano     | 1990-12-06    | BRDPYI66I91Q558X | 2018-07-29     | 624033              | amilani@yahoo.com                |
| 4032 |        54 | Ninfa        | Costa      | 1990-12-28    | ASQRHT91N10X986Z | 2020-03-05     | 624064              | ingrid.rizzi@costantini.it       |
| 4044 |        42 | Davis        | Caruso     | 1990-07-28    | LRIZFX35V95A753Z | 2021-02-23     | 624076              | riva.davide@yahoo.com            |
| 4072 |        44 | Adriano      | Sanna      | 1990-06-16    | KYUZTP79Z66B214K | 2020-09-15     | 624104              | germano.dangelo@yahoo.com        |
| 4142 |        50 | Danuta       | Greco      | 1990-04-06    | PZHHWL43K24B321N | 2018-11-24     | 624174              | ferri.marcella@hotmail.com       |
| 4205 |        71 | Noemi        | Ferri      | 1990-10-28    | WLXLAL41R35A937E | 2018-10-20     | 624237              | edvige58@hotmail.com             |
| 4240 |        17 | Carlo        | Monti      | 1990-01-29    | NUPISH63Z12B561H | 2019-05-05     | 624272              | albino03@giuliani.it             |
| 4242 |         2 | Ivano        | Longo      | 1990-08-13    | NXXFBL94J18P949D | 2021-04-04     | 624274              | pagano.maika@libero.it           |
| 4246 |        20 | Isira        | Russo      | 1990-01-27    | LUSCMA34Q51X051C | 2019-04-28     | 624278              | yorlando@libero.it               |
| 4247 |        27 | Deborah      | Fontana    | 1990-04-30    | CLYUSL87Y54W949D | 2018-11-20     | 624279              | giovanna.rossi@hotmail.com       |
| 4284 |        39 | Raniero      | Ruggiero   | 1990-08-26    | LBNTCW60V96R336A | 2019-08-18     | 624316              | sala.raoul@hotmail.com           |
| 4302 |        73 | Guendalina   | Palmieri   | 1990-04-24    | PSPNTP35I63W553G | 2020-12-03     | 624334              | caruso.cassiopea@yahoo.it        |
| 4313 |         7 | Anastasio    | Barone     | 1990-09-09    | OEUCCX11B10Y282Y | 2019-12-17     | 624345              | sibilla.marino@yahoo.com         |
| 4345 |        42 | Lidia        | Rizzo      | 1990-12-28    | DLSWZT77E26S937R | 2020-04-30     | 624377              | luna44@russo.it                  |
| 4360 |        50 | Jelena       | Montanari  | 1990-07-27    | YMYDTY40F06U075G | 2020-10-31     | 624392              | colombo.gerlando@yahoo.it        |
| 4440 |        75 | Kris         | Negri      | 1990-10-21    | TCAHFC11Z65C665U | 2019-03-20     | 624472              | marini.selvaggia@esposito.org    |
| 4511 |        37 | Leonardo     | Pellegrino | 1990-07-11    | INMMYK92C33X493N | 2020-03-23     | 624543              | gastone.silvestri@rossetti.net   |
| 4518 |        49 | Violante     | Ferrara    | 1990-03-10    | YBWMQC69S08Y335D | 2019-06-26     | 624550              | aaron21@vitali.it                |
| 4540 |        13 | Gregorio     | Fabbri     | 1990-11-21    | TEZGHJ49M20L625V | 2020-01-08     | 624572              | tancredi96@mazza.it              |
| 4560 |        72 | Marieva      | Greco      | 1990-10-03    | WRARDI30L48N985S | 2020-04-23     | 624592              | sorrentino.maria@milani.it       |
| 4571 |        45 | Ingrid       | Pagano     | 1990-07-12    | BQIMBG48O40R286L | 2021-01-30     | 624603              | abarbieri@conti.it               |
| 4594 |         3 | Concetta     | Romano     | 1990-11-27    | ISRMCP44D14N688V | 2019-12-14     | 624626              | gabriele77@yahoo.com             |
| 4613 |        55 | Valdo        | Monti      | 1990-07-27    | EOCYBU51C01G153T | 2019-10-21     | 624645              | rocco.sartori@yahoo.it           |
| 4628 |        16 | Danny        | Bianco     | 1990-03-05    | OIHSKK93C84J608D | 2018-12-14     | 624660              | unegri@hotmail.com               |
| 4782 |        74 | Giulietta    | Milani     | 1990-02-04    | QOITEH95X38H201C | 2021-03-21     | 624814              | fiore.piccarda@email.it          |
| 4831 |        74 | Giancarlo    | Serra      | 1990-03-14    | ZSCFTQ24N82P616K | 2021-04-18     | 624863              | benedetti.clea@coppola.it        |
| 4897 |         1 | Carlo        | Fontana    | 1990-08-10    | UAZJHI97G46W157O | 2018-09-27     | 624929              | naomi.palumbo@rossi.org          |
| 4900 |        16 | Bacchisio    | Morelli    | 1990-01-30    | ZHVQNB48D88S637F | 2021-05-29     | 624932              | isira.lombardi@yahoo.it          |
| 4914 |        16 | Ivano        | Gallo      | 1990-08-04    | HGVHOP45R16G539V | 2018-09-30     | 624946              | zelida47@yahoo.com               |
| 4936 |        75 | Terzo        | Martino    | 1990-01-04    | AVYRVM94Z77Y195K | 2020-07-31     | 624968              | max62@pagano.net                 |
| 4938 |        62 | Grazia       | Villa      | 1990-02-21    | QHLXFI59S74T192Y | 2020-10-21     | 624970              | testa.felicia@libero.it          |
| 4952 |        42 | Alan         | Gallo      | 1990-11-15    | PQFFOL71J23H079O | 2018-09-18     | 624984              | ferraro.silvano@yahoo.it         |
| 4961 |        56 | Cleros       | Fiore      | 1990-10-24    | GWIXJK53K54Q533N | 2021-02-26     | 624993              | battista50@benedetti.com         |
| 4972 |        13 | Silverio     | Grasso     | 1990-09-15    | IUBYYW35F09Y552P | 2019-08-17     | 625004              | luna.sartori@hotmail.com         |
















2. SELECT * FROM `courses` WHERE cfu > 10;
| id   | degree_id | name                               | description                                                                                                                                                                                             | period      | year | cfu | website                   |
+------+-----------+------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------+------+-----+---------------------------+
|    1 |         1 | provident aut non                  | Et dolorem optio nostrum quam. Nesciunt eos non molestiae deleniti. Earum amet nam minus porro aut corrupti.                                                                                            | I semestre  |    1 |  11 | www.minima.uni.it         |
|    9 |         1 | quod in aut                        | Hic a suscipit illum excepturi deleniti. Est sunt animi ut doloremque incidunt. Atque ipsa ipsa incidunt sit dolor dolorum.                                                                             | II semestre |    2 |  13 | www.sunt.uni.it           |
|   11 |         1 | beatae eveniet fugiat              | Reprehenderit aut voluptatem aliquam et consequatur. Perferendis est aut earum ut quis a. Repellendus dolor qui est. Aut a quae mollitia.                                                               | II semestre |    2 |  13 | NULL                      |
|   12 |         1 | iure qui voluptas                  | Cupiditate suscipit ab vel placeat ratione sit aut. Sed et nobis sint rerum quibusdam est sunt.                                                
                                                         | I semestre  |    3 |  11 | NULL                      |
|   13 |         1 | quo et asperiores                  | Rem sed velit et itaque at totam sed. Reprehenderit nesciunt necessitatibus aut aliquid illum voluptas. Et eius quia eligendi amet quia non.                                                            | I semestre  |    3 |  15 | www.doloribus.uni.it      |
|   16 |         1 | corporis enim doloremque           | Sed doloribus quas accusantium aut perferendis. Fugit molestias a quia quia. Quos non expedita hic dignissimos animi.                          
                                                         | II semestre |    3 |  11 | NULL                      |
|   18 |         1 | velit aut voluptatum               | Odit impedit veniam enim natus dolorum laboriosam. Repellendus eaque voluptas blanditiis consequatur vitae. Quis aut quisquam et consequatur consectetur esse.                                          | II semestre |    3 |  12 | NULL                      |
|   21 |         2 | ut rem libero                      | Eligendi qui magni aliquam molestiae ut assumenda nihil. Dolor eligendi aperiam non deleniti aliquid laborum. Tempore modi molestiae non pariatur corrupti. Eum rem autem amet expedita aut.            | I semestre  |    1 |  12 | www.earum.uni.it          |
|   22 |         2 | soluta voluptatem at               | Libero voluptas expedita quia. Quas nulla culpa similique eum. Aperiam officiis quia a sed accusamus qui qui. Nemo esse qui labore optio perspiciatis non.                                              | I semestre  |    1 |  11 | www.rerum.uni.it          |
|   25 |         2 | vero est explicabo                 | Perspiciatis autem consequatur officiis neque dolor quis dolorum reprehenderit. Sunt corporis provident debitis quaerat. Voluptatem quaerat fugit sit autem vero.                                       | II semestre |    1 |  12 | NULL                      |
|   26 |         2 | maxime laboriosam nostrum          | Odit ut aut accusantium. Sapiente id distinctio voluptatum neque vitae qui. Optio consequuntur doloribus consequatur omnis est et. Aut aut odio doloribus sed neque et provident est.                   | II semestre |    1 |  11 | www.exercitationem.uni.it |
|   27 |         2 | consectetur aut odio               | Totam voluptatem nihil nostrum commodi dolor dolorum. Pariatur impedit similique animi ut quo rerum. Suscipit fugit deleniti dolor voluptatem.                                                          | II semestre |    1 |  12 | NULL                      |
|   28 |         2 | accusantium culpa sint             | Quia autem dolor officia voluptatem ullam. Architecto deleniti ex ut ab et harum veritatis. Expedita facilis quo quidem quas eos praesentium sed voluptatum.                                            | I semestre  |    2 |  12 | www.pariatur.uni.it       |
|   29 |         2 | tempora voluptatum aut             | Accusamus quo pariatur culpa molestiae optio similique illum. Cum sit dolor aliquid earum. Ut culpa tempora qui vel laudantium. Quia culpa velit sapiente dolor nam.                                    | I semestre  |    2 |  14 | www.nisi.uni.it           |
|   30 |         2 | aliquam aliquam et                 | Doloremque illum et nulla nisi ab officia dolorem ab. Quasi quam id ea aspernatur modi molestias officia aperiam. Velit sint dolorum et adipisci.                                                       | I semestre  |    2 |  15 | NULL                      |
|   31 |         2 | atque assumenda explicabo          | Ab assumenda illo odio. Molestiae neque eum quaerat odit voluptatibus. Voluptatem reiciendis quo ea asperiores quas molestias officiis. Tempore officia dolorem hic et repellat est.                    | I semestre  |    2 |  13 | NULL                      |
|   33 |         2 | rerum quod quibusdam               | Delectus consequatur qui similique magnam et modi. Suscipit atque expedita quia qui. Est quia nesciunt et sunt minima.                         
                                                         | II semestre |    2 |  14 | NULL                      |
|   37 |         2 | expedita praesentium alias         | Consequuntur quasi ea tempora sint sunt beatae cumque rem. Error sed repellat modi enim. Quod autem nobis doloribus doloribus eos sint. Et omnis molestiae vero amet molestiae inventore.               | I semestre  |    3 |  12 | NULL                      |
|   39 |         2 | iste ullam cum                     | Qui rem minima non nisi nostrum aut. Hic omnis sunt voluptate est tempore. Aut facere nisi ea veritatis saepe nisi ut consectetur.             
                                                         | I semestre  |    3 |  12 | www.dolor.uni.it          |
|   43 |         2 | voluptatum incidunt ut             | Deserunt voluptas nemo hic sequi. Temporibus vel officiis magni. Nostrum mollitia eum molestias.                                               
                                                         | II semestre |    3 |  14 | NULL                      |
|   44 |         2 | minus beatae illo                  | Commodi quis facilis corrupti et magni. Saepe autem aut ut maxime ratione dignissimos. Et est veniam mollitia. Molestiae sunt quia magni ea harum.                                                      | II semestre |    3 |  14 | www.consequatur.uni.it    |
|   49 |         3 | odio odit id                       | Omnis excepturi ipsa modi earum aut necessitatibus. Blanditiis fugiat porro eum. Exercitationem eaque mollitia error magni ut omnis quidem. Quis et voluptas voluptas nobis temporibus placeat est ut.  | I semestre  |    1 |  15 | NULL                      |
|   57 |         3 | veniam dolorum dolor               | Id quo est est. Recusandae ipsam iure libero esse. Ut minima minima officiis ad velit commodi nihil quia.                                      
                                                         | II semestre |    2 |  11 | NULL                      |
|   62 |         3 | cupiditate deleniti nihil          | Dolorum aliquid sit natus id. Enim rerum et nihil sint. Voluptatibus possimus illo quia fuga voluptatibus aliquid quis tenetur.                
                                                         | I semestre  |    3 |  12 | NULL                      |
|   64 |         3 | eligendi sed exercitationem        | Et tempora ut quaerat unde sunt odit in. Autem quia voluptatem maiores aut quo. Minima officiis quis earum aperiam omnis.                      
                                                         | II semestre |    3 |  11 | www.voluptas.uni.it       |
|   66 |         4 | officia esse maxime                | Debitis eos veritatis aut velit et ad itaque. Sed eum et similique laborum. Quia itaque facilis quisquam ut at est magni. Officia itaque sit alias nobis maxime excepturi rerum.                        | I semestre  |    1 |  11 | www.in.uni.it             |
|   69 |         4 | voluptas culpa eos                 | Ratione ab et blanditiis sequi iure. Vel autem nobis ad aut. Placeat quia consequatur molestias asperiores quae.                               
                                                         | II semestre |    1 |  14 | www.ut.uni.it             |
|   71 |         4 | tempore molestiae et               | Rerum nihil aspernatur quidem autem autem. Fugit ducimus vitae dicta culpa atque deserunt voluptatum. A cupiditate qui et non est. Et sed dicta qui quae molestiae.                                     | I semestre  |    2 |  14 | NULL                      |
|   72 |         4 | molestiae est neque                | Nemo laudantium ut nihil. Impedit sequi deleniti aliquam dolor commodi distinctio vitae. Labore earum odio et facere et eum consequuntur.      
                                                         | I semestre  |    2 |  11 | www.facere.uni.it         |
|   76 |         4 | qui eligendi non                   | Rerum eos maxime non id aut perferendis. Blanditiis ratione sint et aspernatur in aliquid. Saepe aut est hic dicta eos. Vero aut quia officiis corrupti.                                                | II semestre |    2 |  15 | www.laudantium.uni.it     |
|   77 |         4 | dolorem laudantium minima          | Omnis quidem vero tempora. Illo voluptas eligendi sunt fugiat. Eos eum adipisci alias aliquam. Numquam sit assumenda deserunt ex.              
                                                         | II semestre |    2 |  11 | NULL                      |
|   80 |         4 | quia aut aut                       | Voluptas dignissimos cupiditate id voluptatem. Et sequi dolorem facere quam ullam quia. Temporibus ea architecto ab quod illum sequi libero.                                                            | I semestre  |    3 |  11 | NULL                      |
|   87 |         5 | id id qui                          | Laboriosam impedit odit voluptatum nisi esse aut. Ipsum repellat impedit eius exercitationem omnis. In sapiente commodi rem sit sed. Officia unde consequuntur qui nam.                                 | I semestre  |    1 |  15 | NULL                      |
|   88 |         5 | molestias minima voluptates        | In id commodi tempora quia. Et distinctio qui fugiat labore ut et saepe dolorem. Aut enim vitae deleniti et quo.                               
                                                         | I semestre  |    1 |  15 | www.nam.uni.it            |
|   92 |         5 | officiis sit sed                   | Sapiente reprehenderit quis voluptates quasi modi. Quaerat illo ea fuga. Eveniet magni ad ratione sed aut numquam eaque. Unde tempore inventore voluptatem expedita nihil dolor.                        | II semestre |    1 |  14 | NULL                      |
|   93 |         5 | magni ea tempora                   | Id earum facere ut dolorem doloribus. Pariatur modi voluptatem distinctio accusantium quo veritatis est. Non ut sint eaque. Dolorem deleniti fugit quis voluptatum et molestias iste asperiores.        | II semestre |    1 |  15 | NULL                      |
|   94 |         5 | iusto consequatur ut               | Rerum enim impedit nam et non quis saepe sapiente. Molestiae vel alias nesciunt rerum. Explicabo eius ullam aut. Blanditiis quia doloremque exercitationem voluptatem quibusdam ut.                     | I semestre  |    2 |  13 | NULL                      |
|   95 |         5 | facilis vero voluptatem            | Quas doloribus explicabo repellat nulla unde. Non necessitatibus vitae enim doloremque voluptatem voluptatem. Ipsam excepturi reprehenderit veniam expedita. Ea ut illo odit.                           | I semestre  |    2 |  12 | NULL                      |
|   96 |         5 | ipsam amet recusandae              | Ullam reiciendis aut aspernatur provident vitae quae mollitia. Sed ea quas atque sed. Doloremque dolor aut voluptates ad.                      
                                                         | I semestre  |    2 |  12 | NULL                      |
|   98 |         5 | sunt omnis asperiores              | Ut dicta expedita quasi maiores. Dolores qui quam eos explicabo. Voluptas tempora architecto sint at. Blanditiis pariatur dolorum totam eius in.                                                        | II semestre |    2 |  12 | NULL                      |
|  101 |         6 | quis quasi eos                     | Autem eaque voluptatibus magnam in et. Eos est autem ut repellat in omnis. Id fugit alias expedita qui vel qui.                                
                                                         | I semestre  |    1 |  13 | NULL                      |
|  104 |         6 | ut nam cupiditate                  | Adipisci suscipit minus quam harum. Repellat laudantium nulla modi suscipit itaque maxime.                                                     
                                                         | I semestre  |    2 |  13 | www.quia.uni.it           |
|  105 |         6 | et totam eius                      | Et aut cupiditate molestiae consequatur dolor perferendis voluptatem. Neque quibusdam molestias deleniti magnam ipsum id.                      
                                                         | I semestre  |    2 |  11 | NULL                      |
|  106 |         6 | et harum laboriosam                | Eum et voluptatem non beatae. Laborum neque eligendi repellendus. Nisi amet nihil odio itaque voluptatum sint perspiciatis. Veniam cupiditate quo sed tempora qui.                                      | I semestre  |    2 |  12 | www.aut.uni.it            |
|  109 |         6 | laborum expedita ullam             | Illo veritatis enim reprehenderit similique atque ut voluptas. Inventore dolor nihil quisquam. Ullam cupiditate esse qui molestiae provident sed veritatis qui.                                         | II semestre |    2 |  13 | www.amet.uni.it           |
|  112 |         7 | voluptas amet vitae                | Eum odit aliquid quisquam. Voluptatem odio deserunt nihil itaque omnis. Quo rerum et ea fugit.                                                 
                                                         | I semestre  |    1 |  14 | www.quo.uni.it            |
|  117 |         7 | optio corporis explicabo           | Placeat minus nobis veritatis aut dolorem autem. Adipisci error occaecati optio. Enim vel sit id iste dolores. Tempore quia dolorem modi alias vel.                                                     | I semestre  |    2 |  13 | NULL                      |
|  120 |         7 | porro optio odit                   | Exercitationem nihil quis sunt cupiditate. Est sed nesciunt asperiores similique quis sint. Quisquam libero aperiam consequatur nostrum.                                                                | I semestre  |    2 |  15 | www.dolore.uni.it         |
|  121 |         7 | adipisci ea enim                   | Ea quia vitae id qui eveniet. Reprehenderit provident ut magnam autem sed consequuntur.                                                        
                                                         | II semestre |    2 |  14 | www.est.uni.it            |
|  128 |         8 | velit ut dolorem                   | Neque labore rerum minus. Autem consequuntur sint voluptatem nobis beatae quas. Et nobis sunt quo eos est similique id. Dolor ut quia sunt est. Recusandae enim adipisci unde libero.                   | II semestre |    1 |  13 | NULL                      |
|  130 |         8 | quis aut a                         | Culpa non fuga ratione et sit facilis facere. Quos repudiandae ut molestiae tempore ea. Aliquam maiores placeat provident aut.                 
                                                         | II semestre |    1 |  14 | www.accusamus.uni.it      |
|  134 |         8 | magnam ullam doloribus             | Voluptates mollitia itaque doloribus dolorum quis expedita exercitationem. Autem sint provident fugit pariatur. Et occaecati nobis deleniti magnam.                                                     | I semestre  |    2 |  13 | www.consectetur.uni.it    |
|  141 |         9 | eaque veritatis ea                 | At quis autem eligendi qui consequatur veniam facilis. Provident molestiae tenetur deleniti est aut quae. Provident quis magni reprehenderit cumque minima nihil. Corrupti odit in fugiat.              | I semestre  |    1 |  12 | www.nesciunt.uni.it       |
|  146 |         9 | assumenda et sed                   | Molestiae culpa sed voluptas tenetur. A nulla similique beatae. Sed eum asperiores in.                                                         
                                                         | I semestre  |    2 |  11 | www.expedita.uni.it       |
|  147 |         9 | sapiente quia accusantium          | Aut perferendis similique sint velit perferendis aliquam qui. Autem occaecati velit soluta. Est exercitationem dolor dolores ducimus.          
                                                         | I semestre  |    2 |  11 | NULL                      |
|  148 |         9 | a vero voluptatibus                | Odit officiis animi quis similique qui rerum quos. Quisquam qui iure nihil rerum occaecati incidunt vel dicta. Velit nemo inventore deleniti ullam alias.                                               | I semestre  |    2 |  11 | www.aliquid.uni.it        |
|  149 |         9 | quod ut aliquid                    | Enim et aut sunt quas. Quidem ut a nesciunt repellendus sed. Occaecati modi voluptatem et omnis expedita ipsa. Quo aut eum voluptate voluptatem
 sit.                                                    | II semestre |    2 |  13 | NULL                      |
|  150 |         9 | eaque exercitationem non           | Eaque quia itaque aliquam vitae nobis quas. Eius soluta et tempora officia reprehenderit id voluptatem. Rerum aut velit sed consequatur.                                                                | II semestre |    2 |  11 | NULL                      |
|  151 |         9 | sit quis inventore                 | Quo aut deleniti est est non. Officia quidem quos a sint voluptatem tempora. Veritatis pariatur qui laudantium pariatur.                       
                                                         | II semestre |    2 |  12 | www.omnis.uni.it          |
|  152 |        10 | nesciunt esse natus                | Et nulla dolorem voluptas est debitis. Iure sunt tempora aut necessitatibus quidem natus qui explicabo. Quisquam animi atque saepe voluptatem.                                                          | I semestre  |    1 |  12 | NULL                      |
|  156 |        10 | ut voluptatibus neque              | Consequatur quam eos culpa voluptatum et. Occaecati quidem doloribus architecto quia aut doloremque. Atque autem non tempora in necessitatibus. Quia qui laboriosam harum quis.                         | I semestre  |    1 |  14 | www.aut.uni.it            |
|  157 |        10 | qui ipsa non                       | Eveniet magni ipsam quae iusto. Minima tempora voluptatem vel ut quod ipsum sunt. Esse dignissimos eligendi consequatur hic fuga quia aut mollitia.                                                     | II semestre |    1 |  13 | NULL                      |
|  161 |        10 | impedit sunt qui                   | Aut cum natus et iste et vero. Eos libero voluptates id earum autem recusandae. Dolore eum magnam quis ratione aspernatur maxime. Est et sit et ut id.                                                  | I semestre  |    2 |  11 | www.magnam.uni.it         |
|  162 |        10 | enim quas sint                     | Corrupti accusantium consectetur consequatur laboriosam porro voluptas. Modi eius et corporis perspiciatis sed. Cumque quia ut vel minima.                                                              | I semestre  |    2 |  13 | www.commodi.uni.it        |
|  169 |        10 | provident mollitia saepe           | Iusto mollitia eligendi tenetur doloribus. Aut rem ut in dolores et quia. Ratione in at voluptate magnam quaerat recusandae officia. Ipsam itaque eos et dolorum facere sint perspiciatis.              | II semestre |    2 |  11 | www.et.uni.it             |
|  172 |        11 | ratione aut quas                   | Necessitatibus molestias quis inventore quidem perferendis ipsa ratione. Doloribus enim qui non ipsa. Perferendis odio et pariatur nulla voluptas ut atque.                                             | I semestre  |    1 |  11 | www.sit.uni.it            |
|  174 |        11 | corporis odit sint                 | Eveniet cupiditate rerum doloremque consequuntur in. Ipsam in id quia ullam sed at dolor. Distinctio et molestiae modi non autem esse doloribus. Soluta numquam quia optio impedit sapiente.            | II semestre |    1 |  11 | NULL                      |
|  178 |        11 | quo similique autem                | Quia voluptas soluta accusamus eos perferendis ullam sapiente quidem. Dolor mollitia omnis laboriosam corporis illo sunt autem. Laudantium reiciendis enim est. Nisi aut vel et earum.                  | I semestre  |    2 |  12 | www.animi.uni.it          |
|  179 |        11 | provident ea molestiae             | Amet dolores quia qui. Rerum eius totam quidem sequi incidunt ea. Aut culpa qui aperiam et. Qui expedita id ex nisi. Saepe et rem numquam qui aperiam.                                                  | II semestre |    2 |  11 | www.dolorum.uni.it        |
|  180 |        11 | et quibusdam libero                | Quam ipsa culpa qui libero. Totam ratione alias excepturi necessitatibus voluptatem mollitia. Et molestiae rerum aliquam quidem voluptatem itaque illo.                                                 | II semestre |    2 |  11 | NULL                      |
|  183 |        11 | ut eum quia                        | Quisquam numquam praesentium voluptate itaque omnis. Ea quisquam dolorum velit alias unde autem rerum. Necessitatibus ducimus illo sint voluptates odio fugit sunt sapiente.                            | I semestre  |    3 |  14 | NULL                      |
|  184 |        11 | similique similique et             | Accusantium nemo odit veniam doloremque qui. Ex magni aperiam nam delectus.                                                                    
                                                         | I semestre  |    3 |  12 | NULL                      |
|  197 |        12 | vel et aut                         | Est ipsum ad soluta nam. Aspernatur iure eum dolor asperiores animi magni. Qui hic id veniam iure voluptate ea. Ut accusantium aspernatur expedita sequi.                                               | I semestre  |    2 |  11 | NULL                      |
|  200 |        12 | similique qui sapiente             | Voluptate reiciendis et beatae et iusto ad. Magni at eum mollitia sapiente. Totam quis reiciendis non dolorem sed.                             
                                                         | II semestre |    2 |  15 | NULL                      |
|  203 |        12 | architecto deleniti temporibus     | Voluptas ea omnis totam consequuntur labore possimus. Inventore natus facere iusto porro placeat amet fugit. Placeat delectus quaerat alias qui. Qui qui earum aperiam ullam velit.                     | I semestre  |    3 |  13 | www.ad.uni.it             |
|  206 |        12 | sunt ut dolorem                    | Nihil laborum laborum eligendi vel corrupti ratione. Sed suscipit et doloremque eligendi et. Enim rerum ut ut.                                 
                                                         | II semestre |    3 |  13 | NULL                      |
|  208 |        12 | voluptas excepturi aut             | Dolorem exercitationem laudantium nobis dolore. Sapiente beatae sed quasi voluptas.                                                            
                                                         | II semestre |    3 |  11 | www.sunt.uni.it           |
|  214 |        13 | ratione dolorem debitis            | Nulla similique voluptas saepe in. Beatae officiis rerum suscipit voluptate perferendis architecto. Non reiciendis omnis esse.                 
                                                         | I semestre  |    2 |  12 | NULL                      |
|  216 |        13 | exercitationem nostrum at          | Repudiandae quaerat dolores harum est. Porro dolor temporibus et. Dolorem voluptate in est ut culpa.                                           
                                                         | I semestre  |    2 |  14 | NULL                      |
|  217 |        13 | et ea beatae                       | Omnis tempora fuga molestiae impedit. Magnam inventore voluptate aliquam iste natus consequuntur. Aliquam nostrum ea iure ipsam soluta in minus. Voluptatem sit est voluptas architecto cumque.         | I semestre  |    2 |  14 | www.recusandae.uni.it     |
|  222 |        14 | quia praesentium perferendis       | Et repellendus distinctio consequatur. Voluptas in eveniet sed perspiciatis earum. At fugit est cumque sed sed.                                
                                                         | I semestre  |    1 |  12 | NULL                      |
|  223 |        14 | et autem exercitationem            | Est velit cum voluptatem aperiam harum amet velit voluptatem. Ea molestiae consequatur dolorem aut repellendus. Explicabo repudiandae quidem esse corporis ratione quisquam velit.                      | I semestre  |    1 |  12 | www.non.uni.it            |
|  224 |        14 | quo recusandae dignissimos         | Rerum earum et et quae voluptates repudiandae. Dolor et sint quisquam magnam dignissimos voluptate inventore rerum. Asperiores temporibus ut distinctio numquam esse dicta eum.                         | I semestre  |    1 |  12 | www.tenetur.uni.it        |
|  229 |        14 | deserunt delectus eos              | Ea qui omnis occaecati similique eveniet corrupti. Distinctio quis enim dicta. Voluptatem harum est inventore porro nihil qui. Animi vel eligendi natus.                                                | I semestre  |    2 |  13 | www.enim.uni.it           |
|  231 |        14 | illum non accusamus                | Nisi veritatis quis quo dolor incidunt nisi. Doloremque ullam occaecati sequi vel non deserunt. Commodi atque est soluta nihil vel eum. Numquam rerum sit odit explicabo aut ea.                        | I semestre  |    2 |  13 | NULL                      |
|  232 |        14 | voluptatem ipsa odit               | Dolorem commodi reiciendis molestiae sint in. Non aliquid sequi veritatis error. Sit ut optio iste animi omnis exercitationem quo ducimus. Placeat occaecati perferendis sit hic accusamus.             | II semestre |    2 |  12 | www.quaerat.uni.it        |
|  233 |        14 | aperiam repellat doloremque        | Voluptatem consequatur alias eum repellendus nisi quia. Praesentium laboriosam sunt laboriosam aut enim deleniti quidem. Id optio doloribus rerum optio nesciunt autem.                                 | II semestre |    2 |  12 | www.impedit.uni.it        |
|  235 |        15 | facere laboriosam quod             | Facere facere voluptas consequatur facere. Est totam ipsum corporis laborum quas perferendis animi enim. Eveniet voluptate illum ut rerum odio rem modi.                                                | I semestre  |    1 |  14 | www.dolor.uni.it          |
|  239 |        15 | rem delectus eius                  | Asperiores facere repellat deleniti rerum hic impedit. Dolor harum sequi id sed. In omnis omnis dolores cumque necessitatibus.                 
                                                         | II semestre |    1 |  11 | www.repudiandae.uni.it    |
|  241 |        15 | voluptatibus quo eligendi          | Culpa atque rem enim. Quasi sint libero et alias provident. Laboriosam voluptatum quia ducimus nostrum sunt voluptas numquam sint.             
                                                         | I semestre  |    2 |  15 | www.molestias.uni.it      |
|  245 |        15 | neque voluptas dolorum             | Sed id voluptatem et. Dolores at hic est voluptatem velit aut doloremque. Iusto aperiam tempora id sit asperiores illum eligendi. Iure error facere enim et repudiandae illo id.                        | II semestre |    2 |  14 | www.ut.uni.it             |
|  248 |        15 | asperiores odit incidunt           | Consectetur eligendi eveniet sed eos optio dolorum. Quis recusandae qui omnis et.                                                              
                                                         | II semestre |    2 |  14 | www.animi.uni.it          |
|  252 |        15 | quo explicabo quae                 | Velit temporibus impedit minima maxime. Iusto dolorem natus laborum qui. Beatae culpa distinctio atque omnis corrupti. Magnam qui sed debitis incidunt corrupti ut.                                     | I semestre  |    3 |  13 | www.ut.uni.it             |
|  253 |        15 | voluptatem rem ut                  | Officia possimus ex magni reiciendis. Repellendus architecto ut et aut voluptatem aut quia. Architecto aut sit doloremque necessitatibus.                                                               | II semestre |    3 |  15 | NULL                      |
|  255 |        15 | nemo sit eum                       | Provident aperiam hic labore quia quasi aut. Distinctio ea odit similique est enim inventore quia. Deleniti fugiat aliquid culpa non similique quo. Placeat harum voluptatem iste dolore et et.         | II semestre |    3 |  11 | www.vel.uni.it            |
|  259 |        16 | numquam deserunt quasi             | Quod dolorum molestias molestiae deserunt sed. Soluta ex vel expedita et. Id assumenda ipsum ducimus odio dolorum non alias ut. Nisi facere tenetur iure odio exercitationem est.                       | I semestre  |    1 |  15 | NULL                      |
|  264 |        16 | nam id aliquid                     | Sint alias et error libero quam aut. Nemo aliquid repudiandae doloremque officiis.                                                             
                                                         | I semestre  |    2 |  14 | www.error.uni.it          |
|  268 |        16 | sunt eum ipsam                     | Voluptates cum unde consequatur voluptatem neque explicabo. Quo minus voluptatem aut aut. Ipsam velit aut non occaecati maiores. Fuga aut quia dignissimos iure nisi.                                   | II semestre |    2 |  12 | www.voluptas.uni.it       |
|  270 |        16 | nulla cupiditate nemo              | Inventore nulla ut id ut. Non omnis exercitationem voluptas maxime. Minus illum assumenda exercitationem autem. Tenetur nostrum similique est error sunt ratione tempora.                               | II semestre |    2 |  13 | www.omnis.uni.it          |
|  278 |        17 | ea et harum                        | Pariatur laudantium cumque fuga voluptatum nihil. Dolore aliquam animi voluptatem enim. Perspiciatis qui animi veritatis velit.                
                                                         | I semestre  |    1 |  13 | NULL                      |
|  279 |        17 | distinctio quo praesentium         | Sed sit deserunt et nostrum non tempora. Fugit voluptatem sed nulla et consequatur quis. Eum qui perspiciatis exercitationem unde qui. Excepturi omnis dicta quis omnis quod veritatis laboriosam.      | I semestre  |    1 |  14 | www.rerum.uni.it          |
|  281 |        17 | nihil vero voluptas                | Ipsa eum est vel quos. Nesciunt dolorum inventore eveniet debitis expedita nisi. Dicta qui sapiente sit dolor. Dolorum in natus sequi quasi neque.                                                      | I semestre  |    1 |  15 | www.beatae.uni.it         |
|  284 |        17 | maiores cumque repudiandae         | Quo corrupti vero omnis perspiciatis porro quisquam in. Quia et odit et explicabo dolorem. Qui nisi eveniet nihil sint.                        
                                                         | II semestre |    1 |  13 | NULL                      |
|  287 |        17 | qui similique qui                  | Molestias quam sed voluptate est culpa dicta. Sapiente et nisi et eum similique voluptatem et. Nihil rerum est esse rem labore maiores provident laborum. Accusamus deserunt qui eius doloribus.        | I semestre  |    2 |  12 | NULL                      |
|  288 |        17 | quod et non                        | Incidunt quod et praesentium animi maiores. Voluptatum rem cupiditate et consequatur earum odit et. Libero atque rerum ratione et reiciendis.                                                           | I semestre  |    2 |  11 | www.omnis.uni.it          |
|  292 |        17 | nemo quis omnis                    | Vel exercitationem sed id qui. Atque magnam eligendi inventore facere voluptatibus qui eveniet. Natus cupiditate vel placeat illum quisquam reiciendis et. Aperiam quia ut eos esse eos culpa commodi.  | II semestre |    2 |  14 | NULL                      |
|  295 |        17 | sit officia accusamus              | Velit dignissimos et officiis totam sed voluptates veniam. Excepturi sed fugiat rerum incidunt corporis voluptatum. Quae aliquid qui illo quos non voluptates.                                          | I semestre  |    3 |  11 | NULL                      |
|  299 |        18 | inventore reiciendis deserunt      | Dolores voluptatem fuga nostrum quo. In error dolores vitae. Ex alias expedita mollitia consequatur temporibus.                                
                                                         | I semestre  |    1 |  13 | www.excepturi.uni.it      |
|  300 |        18 | aut ullam pariatur                 | Consequatur vel a officiis cupiditate et qui fugit. Neque dolor natus ducimus consectetur et debitis. Qui voluptates fuga eligendi sed unde ut. Autem omnis et sunt est quis quaerat.                   | I semestre  |    1 |  11 | www.qui.uni.it            |
|  301 |        18 | fugit molestiae earum              | Quo tempora dolor necessitatibus suscipit fugiat odio repellendus. Ab qui magnam modi.                                                         
                                                         | I semestre  |    1 |  11 | NULL                      |
|  302 |        18 | nisi illum vitae                   | Est est eveniet unde culpa aut nihil vitae omnis. Assumenda modi repellat ea omnis.                                                            
                                                         | I semestre  |    1 |  11 | NULL                      |
|  310 |        18 | provident cumque voluptatem        | Itaque eos sunt atque ab error similique. Porro alias et aut qui. Reiciendis id qui deleniti pariatur et eos et. Beatae fugiat nam voluptates.                                                          | I semestre  |    2 |  13 | www.quasi.uni.it          |
|  312 |        18 | officia nobis necessitatibus       | Debitis quia molestiae ipsa harum necessitatibus qui. Qui dolore voluptatem ut hic ab atque pariatur. Architecto magnam fugiat dolor.          
                                                         | II semestre |    2 |  12 | NULL                      |
|  314 |        18 | possimus earum qui                 | Quo ab minus voluptatem recusandae sed et. Maiores debitis impedit iste. Autem minima nulla totam aut sint magni. Qui voluptas doloremque eos quia totam deserunt laboriosam.                           | II semestre |    2 |  15 | NULL                      |
|  319 |        19 | adipisci aliquam dolorum           | Cum occaecati ducimus ad sed sed qui nisi. Et quasi doloribus deleniti quod rerum iste. Corporis quas error laborum similique sint ut repudiandae. Aut eos nam rem molestiae deserunt voluptatum.       | I semestre  |    1 |  11 | NULL                      |
|  323 |        19 | voluptatem quibusdam fugit         | Labore nam et possimus asperiores quo aspernatur laborum. Rerum odio quo quam dolore. Ipsam numquam iure dolor.                                
                                                         | II semestre |    1 |  11 | www.porro.uni.it          |
|  324 |        19 | placeat mollitia atque             | Illo vel dolore ex non. At et dolore quo eos iste. Voluptatem quidem quod sit asperiores. Corporis praesentium voluptatem est modi eum.                                                                 | I semestre  |    2 |  14 | www.quibusdam.uni.it      |
|  325 |        19 | cumque doloribus ducimus           | Ea debitis maxime impedit voluptatum ducimus. Neque expedita quia asperiores tempora delectus omnis fuga dolore.                               
                                                         | I semestre  |    2 |  14 | NULL                      |
|  328 |        19 | et ducimus sed                     | Rerum dolores explicabo ratione cum ut. Debitis occaecati culpa voluptatem corrupti et libero. Debitis eveniet quas eum atque ea ea sed. Commodi sit voluptatibus qui tempore harum qui sunt.           | I semestre  |    2 |  13 | NULL                      |
|  329 |        19 | voluptatem sit dolorem             | Doloremque ea qui et ducimus. Architecto harum sunt vel alias exercitationem. Vel vitae hic aliquid harum qui explicabo.                       
                                                         | II semestre |    2 |  15 | www.magni.uni.it          |
|  332 |        19 | sed quis itaque                    | Nesciunt corrupti deserunt saepe non ut esse blanditiis. Esse est qui fugiat ut. Aut dignissimos rerum excepturi sint.                         
                                                         | II semestre |    2 |  15 | NULL                      |
|  336 |        19 | nesciunt quo mollitia              | Illum quia cum ut aut aut hic. Enim qui ut eius quis veniam. Tempore ut ratione eveniet dolore alias minima labore. Corporis non saepe adipisci dolorum pariatur totam optio.                           | II semestre |    3 |  15 | www.eveniet.uni.it        |
|  338 |        20 | est ab ratione                     | Saepe architecto ut reiciendis deleniti. Molestiae consectetur et quo expedita nihil ea. Hic odio eum exercitationem consequatur dolor. Mollitia natus quo tempora at.                                  | I semestre  |    1 |  14 | www.laborum.uni.it        |
|  340 |        20 | omnis rerum tenetur                | Et ratione ut dolor dicta. Voluptas et rerum voluptatibus consequatur voluptatem voluptatum omnis reiciendis. Aut impedit veniam velit est.                                                             | I semestre  |    1 |  11 | www.nam.uni.it            |
|  341 |        20 | officiis corrupti et               | Aspernatur at non neque est dolorem. Ea eaque quo sint eum. Modi voluptatem eligendi dolorem. Culpa possimus illum est ipsum.                  
                                                         | I semestre  |    1 |  14 | NULL                      |
|  348 |        20 | ducimus laborum aliquid            | Alias voluptatem ratione aspernatur eos id. Numquam error in quia in. Facere officia culpa veniam cupiditate.                                  
                                                         | I semestre  |    2 |  13 | NULL                      |
|  349 |        20 | voluptatibus omnis et              | Voluptatem unde quas qui. Repellendus odio quis occaecati ut. Labore at aperiam necessitatibus labore neque.                                   
                                                         | II semestre |    2 |  11 | NULL                      |
|  350 |        20 | expedita consequatur nihil         | Qui voluptate nulla officiis modi delectus. Omnis necessitatibus cum assumenda temporibus quibusdam et est.                                    
                                                         | II semestre |    2 |  12 | NULL                      |
|  351 |        20 | ut dolorum soluta                  | Et excepturi et at maiores illum laborum maiores. Eius quia et tempora quia. Doloremque expedita vel qui maxime. Sed assumenda excepturi odit vero fugiat ab.                                           | II semestre |    2 |  11 | NULL                      |
|  354 |        20 | debitis in quo                     | Officiis omnis qui id maiores molestiae. Et perspiciatis voluptas quibusdam maiores aut est. Veritatis aut veniam explicabo a nulla eveniet repellendus.                                                | I semestre  |    3 |  13 | NULL                      |
|  362 |        21 | ut ea officia                      | Omnis dolorum incidunt eligendi in laudantium ducimus. Eius dolores eum nihil consequatur. Aut dolor numquam nisi numquam at. Adipisci culpa harum cum est nobis id vero.                               | I semestre  |    1 |  12 | www.autem.uni.it          |
|  369 |        21 | veniam molestiae molestias         | Harum eos vero ea ut ut aut. Aut totam sit minima iusto aperiam iste mollitia. Nostrum officiis qui est non accusamus sint sunt. Sapiente nulla qui similique dolorem id similique.                     | I semestre  |    2 |  11 | NULL                      |
|  370 |        21 | ut facilis qui                     | Ea dolores et soluta dolorem assumenda sed omnis. Eius dignissimos laboriosam hic aut. Sed aut et nam est ut omnis id. Provident provident nihil qui aut quos. Et est qui optio vel.                    | II semestre |    2 |  12 | www.autem.uni.it          |
|  371 |        21 | unde non corporis                  | Libero fugit vitae molestiae et. Pariatur incidunt rerum dolores cumque impedit vitae impedit. Asperiores quod in tenetur harum. Ex non quod omnis distinctio.                                          | II semestre |    2 |  12 | NULL                      |
|  374 |        21 | cum debitis assumenda              | Fuga dolores ab architecto ut. Eveniet temporibus voluptatum sit nisi dolorem. Cumque molestiae accusantium culpa sit porro odio iusto sed. Voluptatem autem voluptas corporis sint aut.                | I semestre  |    3 |  12 | www.ipsam.uni.it          |
|  376 |        21 | ea facere laboriosam               | Magni aperiam maxime perspiciatis incidunt esse magnam. Eos reiciendis nihil qui dolorem. Sint ut et quasi autem. Omnis esse error voluptatibus.                                                        | II semestre |    3 |  14 | www.fuga.uni.it           |
|  378 |        22 | officia dolor a                    | Dolores eius dolor fugiat aut ut et occaecati. Quod voluptatum dolor et similique. Quas nemo maiores aperiam molestiae.                        
                                                         | I semestre  |    1 |  15 | www.et.uni.it             |
|  381 |        22 | eligendi corrupti tempore          | Nobis consequatur quam neque placeat deleniti vitae. Tempore in aperiam natus eos sit distinctio. Exercitationem nam sequi aliquid suscipit in delectus distinctio.                                     | I semestre  |    1 |  11 | NULL                      |
|  382 |        22 | corrupti enim praesentium          | Quidem omnis excepturi nihil odit iusto harum. Ullam dignissimos facilis ut ullam omnis. Hic ad molestiae harum voluptatem consequatur. Ut adipisci maiores similique ut autem est eum.                 | II semestre |    1 |  14 | NULL                      |
|  383 |        22 | quisquam quo voluptas              | Necessitatibus rerum consequatur et in. Neque accusantium qui in earum. Facere aut nesciunt porro aliquid consequatur ut facere. Qui dolores rerum sed modi. Dolorem harum ut nobis ut eum porro.       | II semestre |    1 |  12 | www.aut.uni.it            |
|  384 |        22 | a quis at                          | Optio recusandae autem explicabo nihil pariatur. Tempore natus eveniet aperiam. Repellendus nulla saepe ex deleniti ut recusandae dolor placeat.                                                        | II semestre |    1 |  15 | www.dolor.uni.it          |
|  385 |        22 | aut consequatur exercitationem     | Molestiae nesciunt numquam doloremque cumque dolores sunt libero sed. Dolorum nihil quo provident voluptas itaque quam exercitationem. Fugiat occaecati architecto laboriosam fuga.                     | II semestre |    1 |  11 | NULL                      |
|  397 |        22 | et nam aut                         | Soluta unde exercitationem eligendi ea labore. Asperiores fugit et esse aut. Eius qui est eum. Dolorem et sequi voluptatibus et tempora quis qui.                                                       | II semestre |    3 |  11 | NULL                      |
|  406 |        23 | natus soluta eum                   | Vel reiciendis est repudiandae id dolorem voluptatem. Molestiae saepe aut dolorum pariatur quos. Expedita esse pariatur quo vitae et repudiandae id. Neque sequi vel repellat eum ut.                   | II semestre |    1 |  13 | www.sed.uni.it            |
|  408 |        23 | necessitatibus sed vel             | Qui neque delectus dolor modi. Explicabo totam numquam qui itaque. Tempora minus illum corporis. Enim ut dolorem culpa.                        
                                                         | I semestre  |    2 |  15 | NULL                      |
|  409 |        23 | architecto id cum                  | Officia dolorem esse debitis culpa nobis quas dolores. Voluptas a soluta vitae veritatis debitis ducimus ratione. Repellendus quo eaque libero harum. Nam earum impedit temporibus eum.                 | I semestre  |    2 |  13 | NULL                      |
|  410 |        23 | sunt fuga qui                      | Dolore reprehenderit et ut sit ex. Magni voluptas et sint similique voluptatem. Qui sit sed ipsum ex enim minima libero. Ut repellendus eaque et dolor fuga magni nam suscipit.                         | II semestre |    2 |  15 | NULL                      |
|  411 |        23 | perferendis ipsa et                | Quia autem aut earum aut vitae exercitationem dolorem. Cupiditate rerum et fuga aut et labore. Eius eaque ipsum laborum est. Dolorum aut autem omnis maxime maiores libero sed iusto.                   | II semestre |    2 |  12 | www.dicta.uni.it          |
|  414 |        24 | fugit debitis sapiente             | Corrupti et repellat iure. Aut aliquid velit iusto dicta ut aut ut. Aut et quod est omnis odio.                                                
                                                         | I semestre  |    1 |  12 | www.quam.uni.it           |
|  415 |        24 | iure impedit iusto                 | Repudiandae nam ab beatae saepe maxime corrupti qui. Distinctio doloremque amet et consequatur magni. Voluptas dignissimos itaque ut veniam dolorem veniam ea. Quaerat corporis qui et distinctio.      | I semestre  |    1 |  12 | www.cumque.uni.it         |
|  416 |        24 | quia aspernatur dolorum            | Voluptatem illum qui veniam optio deserunt itaque numquam. Vero et sit ea ab fugit alias amet dignissimos. Ut qui et dolore alias. Facilis ut dolores maiores voluptate dicta.                          | I semestre  |    1 |  13 | NULL                      |
|  418 |        24 | voluptas veniam similique          | Sunt necessitatibus consectetur voluptas omnis et voluptatem. Illo sed consequuntur at error. Veniam quia voluptatem ut consequuntur autem autem nihil.                                                 | II semestre |    1 |  13 | NULL                      |
|  419 |        24 | culpa nemo aut                     | Cupiditate dolorem sit eius expedita nemo reiciendis. Voluptatem aut sit dolorem quasi adipisci dignissimos. Voluptatem nihil commodi ut odit blanditiis aut et non.                                    | II semestre |    1 |  11 | www.et.uni.it             |
|  420 |        24 | animi aliquid consequatur          | Commodi dolor minus consequatur praesentium enim. Pariatur quasi libero atque consequatur necessitatibus. Corrupti rerum dolores perspiciatis tempore maiores eum est.                                  | II semestre |    1 |  13 | www.labore.uni.it         |
|  434 |        25 | dignissimos eos sit                | At labore magnam id enim distinctio unde. Ipsum sed aut laboriosam aut sunt illo. Et numquam ea odio et animi quia dolor. Sint vitae non dolor est ea itaque.                                           | I semestre  |    2 |  13 | www.et.uni.it             |
|  435 |        25 | cum doloremque nostrum             | Praesentium inventore ut perspiciatis quasi. Quia est beatae sunt expedita expedita odit. Ut quae cumque voluptate eius consequatur ut non. Sit omnis et quia nostrum asperiores error.                 | I semestre  |    2 |  12 | www.vitae.uni.it          |
|  436 |        25 | nesciunt eligendi sed              | Vel consequuntur deserunt ipsam nesciunt aut omnis. Accusamus officia et sit rerum. Omnis ut quo iste qui. Commodi ut id ut voluptas sint.                                                              | I semestre  |    2 |  13 | NULL                      |
|  437 |        25 | et magni voluptas                  | At sequi voluptatem debitis. Deserunt excepturi qui totam enim. Dolore recusandae eveniet maxime.                                              
                                                         | II semestre |    2 |  15 | NULL                      |
|  440 |        26 | vel deleniti tempore               | Nihil itaque ea doloribus. A qui voluptatem eum ut sit. Laboriosam eaque et debitis dolor eligendi sed. Sed assumenda veniam voluptatem temporibus est nesciunt.                                        | I semestre  |    1 |  15 | NULL                      |
|  445 |        26 | ea impedit quidem                  | Voluptas dolorum voluptatem sequi velit minus iusto provident. Et dignissimos rerum minus voluptatem. Veniam qui impedit ipsam aut amet rerum. Ut accusamus repudiandae aut aut sint est accusamus.     | II semestre |    1 |  12 | NULL                      |
|  447 |        26 | aliquid ducimus optio              | Dolore quaerat excepturi et nam qui non. Id dolor fugit quam est explicabo. Amet recusandae cumque dicta non.                                  
                                                         | II semestre |    1 |  13 | NULL                      |
|  448 |        26 | saepe harum quidem                 | Magnam est a odit rerum qui qui. Voluptatem porro nihil quo sit. Corrupti recusandae non deserunt accusamus similique delectus corporis. Quis id enim nulla nihil cupiditate est.                       | I semestre  |    2 |  15 | NULL                      |
|  450 |        26 | et sed eum                         | Ducimus ipsam nobis maxime quod at alias architecto. Ut ab quaerat exercitationem molestiae. Temporibus nobis dolor excepturi pariatur fugit perferendis.                                               | I semestre  |    2 |  12 | NULL                      |
|  452 |        26 | eligendi quia voluptatem           | Ipsam quidem sed perspiciatis et. Itaque voluptate porro dolore asperiores delectus. Et qui et ad consectetur consequuntur quia.               
                                                         | II semestre |    2 |  12 | www.illum.uni.it          |
|  458 |        27 | sit atque nulla                    | Cumque earum aperiam est sed praesentium repudiandae deleniti. Omnis eveniet voluptatem et officiis labore. Earum iure rerum non quasi earum voluptatibus.                                              | II semestre |    1 |  13 | NULL                      |
|  460 |        27 | commodi nam mollitia               | Explicabo commodi aspernatur soluta nisi quaerat. Quibusdam aliquid asperiores et. Dolorem odio quod reiciendis id voluptatem ipsum. Minus odio sunt sit odit.                                          | I semestre  |    2 |  12 | NULL                      |
|  462 |        27 | provident culpa labore             | Dolorum eaque quibusdam sit occaecati sapiente. Velit velit sit minus est sunt. Id quo qui reiciendis officiis explicabo. Aut architecto omnis maxime qui nihil temporibus vel est.                     | I semestre  |    2 |  11 | www.quia.uni.it           |
|  464 |        27 | error ut officiis                  | Aliquam sed minus voluptas velit aut qui. Aut possimus velit sint sed. Et commodi libero quaerat eos vitae officiis. Deserunt rerum et et iure amet. Iste dolores totam qui aut distinctio in.          | II semestre |    2 |  13 | www.sapiente.uni.it       |
|  473 |        28 | quas quo rem                       | Consectetur sit sed ut quis nihil quod. Iusto sit iusto ea officiis ut est. Dicta iste ut aut. Et et corporis quaerat exercitationem corrupti qui voluptas.                                             | I semestre  |    2 |  13 | www.sequi.uni.it          |
|  474 |        28 | ut dolores maiores                 | Officia consectetur illo et voluptatem nulla quae et quis. Ab in perferendis qui placeat maxime. Repellendus doloribus totam qui animi.        
                                                         | I semestre  |    2 |  14 | www.aut.uni.it            |
|  475 |        28 | facere ad rerum                    | Omnis mollitia odit ab. Aperiam est non et iste qui placeat perspiciatis voluptatem. Repudiandae sint sapiente quisquam odio voluptatem qui praesentium amet.                                           | II semestre |    2 |  14 | www.optio.uni.it          |
|  476 |        28 | quidem rerum illum                 | Et voluptates harum enim officia. Repellendus magni laborum laborum amet. Facere officia necessitatibus occaecati labore saepe quidem.         
                                                         | II semestre |    2 |  12 | NULL                      |
|  478 |        28 | vel molestiae sed                  | Nisi est quaerat repudiandae sint qui laudantium. Eius ut quos esse numquam. Fugit et illo at molestiae molestias porro.                       
                                                         | II semestre |    2 |  14 | NULL                      |
|  482 |        28 | dolor laborum optio                | Tenetur veritatis impedit numquam et ullam. Reiciendis laboriosam culpa velit et numquam eum. Et quis excepturi soluta debitis dolorem.                                                                 | I semestre  |    3 |  15 | www.dolorem.uni.it        |
|  484 |        28 | quod veritatis incidunt            | Illum eum accusantium delectus vitae est voluptatem. Aspernatur iste autem aut officiis. Labore cumque corporis consequatur excepturi enim. Ipsam totam tempora delectus quasi.                         | II semestre |    3 |  14 | NULL                      |
|  486 |        29 | sapiente nihil et                  | Illo qui adipisci quisquam ut. Iure consectetur cum iure quibusdam ipsam. Molestiae occaecati eum sunt fuga. Corrupti voluptatem nobis facere eaque nemo.                                               | I semestre  |    1 |  13 | www.voluptas.uni.it       |
|  490 |        29 | illum ex doloremque                | Voluptates maxime vel corporis saepe molestias. Nisi sed omnis dolorem qui repellendus eos consequatur. Aperiam doloribus qui sed deserunt ad reprehenderit. Assumenda quas laudantium alias.           | II semestre |    1 |  11 | NULL                      |
|  492 |        29 | laborum provident voluptatibus     | Atque voluptatem enim qui sapiente eaque. Consequatur voluptates mollitia commodi ut. Iste aliquid alias id aliquid quas quia quis.            
                                                         | I semestre  |    2 |  14 | NULL                      |
|  498 |        29 | voluptates sed eaque               | Sequi sed eligendi soluta fugit quisquam. Sit sit reiciendis aut recusandae recusandae et in. Sunt magni illo officia dignissimos omnis recusandae.                                                     | II semestre |    2 |  15 | www.soluta.uni.it         |
|  500 |        29 | quia porro consectetur             | Ut quia ut voluptatem minus ut ipsam. Ab pariatur fugit officiis illum a sed. Vero cupiditate in ut voluptas maxime eveniet.                   
                                                         | I semestre  |    3 |  12 | www.officia.uni.it        |
|  503 |        29 | sed quo delectus                   | Iusto quia tenetur consequatur in. Dolor qui exercitationem quia earum facere aperiam ad. Sit non omnis a facere architecto voluptatibus praesentium.                                                   | I semestre  |    3 |  12 | www.porro.uni.it          |
|  505 |        29 | molestiae est qui                  | Et ut eos ex iure corrupti. Adipisci rerum ut non illo. Excepturi temporibus corporis odio. Atque placeat commodi maxime reiciendis quia error.                                                         | II semestre |    3 |  12 | www.inventore.uni.it      |
|  506 |        29 | rem adipisci dolorem               | Corporis ut quia vitae est quas. Eum impedit commodi tenetur molestiae commodi minus. Sapiente quia sunt ut sed id consequuntur. Corrupti consequatur sit repellat repellat a.                          | II semestre |    3 |  15 | www.odio.uni.it           |
|  507 |        29 | et possimus assumenda              | Nobis magnam ut quia molestiae doloremque ea aut dicta. Ipsa tempore temporibus mollitia perferendis. Quod eos quo quaerat corporis dicta quia quas vero.                                               | II semestre |    3 |  11 | NULL                      |
|  509 |        30 | amet dicta et                      | Et animi corrupti quibusdam eligendi. Omnis consequatur maxime sunt exercitationem laboriosam.                                                 
                                                         | I semestre  |    1 |  14 | www.odit.uni.it           |
|  514 |        30 | et iure natus                      | Maiores modi dolorem omnis est voluptate nobis. Tempora repellat voluptatibus consequatur. Dolore aperiam quia ullam dolor dolorum consequatur sit.                                                     | I semestre  |    2 |  11 | NULL                      |
|  516 |        30 | magnam saepe nihil                 | Rem eos nisi quia laudantium et. Quia quia quos id iste suscipit minima labore. Dignissimos tempore qui aut optio adipisci. Ratione illum voluptatem et velit temporibus.                               | II semestre |    2 |  12 | NULL                      |
|  519 |        31 | distinctio numquam illum           | Dolorem sed neque inventore accusamus voluptate quae ut nihil. Minus aspernatur est error quisquam non sed porro voluptatem. Sit molestiae et placeat.                                                  | I semestre  |    1 |  14 | NULL                      |
|  520 |        31 | ducimus sapiente at                | Qui reiciendis non sint doloribus ut temporibus. Qui temporibus optio et unde aperiam incidunt. Consequuntur est qui eum dolorum. Aliquid nihil voluptatem assumenda.                                   | I semestre  |    1 |  14 | www.reprehenderit.uni.it  |
|  521 |        31 | et est porro                       | Itaque ducimus iste praesentium ut quae. Laborum ad et et et rerum fugiat. Sed enim reiciendis a accusamus molestiae esse porro.               
                                                         | I semestre  |    1 |  14 | NULL                      |
|  524 |        31 | et et saepe                        | Voluptas aliquam fuga vero provident fugiat corrupti. Laborum magni rerum officiis ex. Aspernatur sapiente qui inventore ea dignissimos dolores.                                                        | II semestre |    1 |  12 | NULL                      |
|  525 |        31 | quia eos doloremque                | Consequatur qui facilis eveniet tenetur quisquam iure nam. Distinctio nulla aut autem perspiciatis iste dignissimos harum. Qui velit aut cum id atque sapiente eveniet.                                 | II semestre |    1 |  14 | NULL                      |
|  526 |        31 | ipsa aliquid sapiente              | Veritatis quasi dolorem repellat voluptatibus rem. Atque autem quis voluptatibus sed. Rerum nulla vel et dicta et necessitatibus aperiam exercitationem. Blanditiis suscipit vitae sunt.                | II semestre |    1 |  15 | NULL                      |
|  527 |        31 | est earum iure                     | Tempore dolorum ex cumque magni corrupti. Et vero quasi et dolorem eos. Accusantium quibusdam nobis voluptas aut debitis fugit magni est. Voluptatem autem natus nostrum excepturi et ratione aperiam.  | I semestre  |    2 |  11 | NULL                      |
|  533 |        31 | esse harum quaerat                 | Suscipit consectetur aliquam asperiores at impedit. Saepe repudiandae dolores et maxime omnis unde eligendi odit. Nulla molestiae nisi maiores dolore voluptas ut veniam. Voluptatem non cum nihil non. | II semestre |    2 |  11 | NULL                      |
|  534 |        31 | nesciunt et ullam                  | Vero sint debitis magni doloremque exercitationem sapiente. Assumenda magnam voluptate qui numquam ex. Qui doloribus qui omnis ducimus id atque est. Quia sed quidem saepe eum vel eligendi sint ea.    | II semestre |    2 |  14 | NULL                      |
|  535 |        31 | rerum voluptatibus iusto           | Doloribus ex iusto et perspiciatis harum voluptatem eligendi. Totam omnis accusantium eius eum sequi quas. Laboriosam distinctio voluptatibus officia.                                                  | II semestre |    2 |  11 | NULL                      |
|  536 |        32 | culpa quis expedita                | Possimus architecto animi nihil corrupti corporis facere. Consequatur odit est vel eum iste. Nihil ex iste quasi iusto.                        
                                                         | I semestre  |    1 |  12 | NULL                      |
|  545 |        32 | rerum vel voluptatem               | Molestias impedit culpa facilis cumque odit possimus. Molestiae velit inventore debitis. Qui enim sit nemo ducimus excepturi delectus autem.                                                            | I semestre  |    2 |  12 | NULL                      |
|  547 |        32 | inventore praesentium voluptatem   | Temporibus repudiandae sunt eligendi ut tempora. Numquam laboriosam et sed fugit nemo natus pariatur. Accusantium est consequuntur qui. In quidem iusto ex magnam optio sint beatae.                    | I semestre  |    2 |  12 | NULL                      |
|  548 |        32 | illum sit dolores                  | Quis vel et expedita. Molestiae ex ea facilis qui in. Praesentium ducimus voluptates quasi omnis sit. Consequatur repudiandae perferendis sapiente et quasi laborum.                                    | I semestre  |    2 |  13 | NULL                      |
|  549 |        32 | qui dignissimos quis               | Nihil nobis provident in voluptatem. Sequi architecto facilis illo ea sint. Sed nihil sapiente dolorem est. Ipsa animi esse alias rerum omnis.                                                          | II semestre |    2 |  15 | www.tempora.uni.it        |
|  551 |        32 | atque et consectetur               | Numquam impedit sit exercitationem maxime soluta quo ut. Et facilis et cupiditate qui eveniet.                                                 
                                                         | II semestre |    2 |  13 | www.veniam.uni.it         |
|  554 |        32 | quidem voluptas est                | Itaque cum et et debitis cupiditate esse impedit. Placeat repudiandae minus sit ut. Sunt debitis soluta non aut. Et porro minus rerum et in et.                                                         | I semestre  |    3 |  11 | NULL                      |
|  557 |        32 | assumenda dolorum perspiciatis     | Molestiae et eveniet est quibusdam explicabo. Aut id dignissimos qui quis quidem quod. Quidem omnis dolores fugiat facilis praesentium quis.                                                            | II semestre |    3 |  11 | NULL                      |
|  558 |        32 | voluptate quos esse                | Soluta laborum consequuntur consequuntur ea quod. Alias et voluptatem impedit corporis. Et ut est ipsum pariatur aspernatur. Iure ullam non nihil id sint nihil sed eligendi.                           | II semestre |    3 |  13 | NULL                      |
|  561 |        33 | dolore enim eius                   | Alias aut voluptatem accusamus provident aspernatur. Corporis ratione voluptatem quaerat nobis dolorem ipsam. Magni qui incidunt veritatis quia.                                                        | I semestre  |    1 |  14 | www.ut.uni.it             |
|  563 |        33 | sed possimus expedita              | Neque et nihil et enim. Minima accusamus aut illum quia. Non aperiam quo similique vel.                                                        
                                                         | II semestre |    1 |  14 | NULL                      |
|  566 |        33 | vitae vitae aperiam                | Asperiores similique porro et. Modi qui excepturi qui hic impedit quia dolorum doloribus. Et nisi aut id praesentium tenetur magni velit alias.                                                         | I semestre  |    2 |  11 | www.itaque.uni.it         |
|  571 |        33 | tempora nesciunt aut               | Et libero unde fugiat consequuntur eius. Tempore sit voluptatem minima est et voluptate. Mollitia consequuntur fuga reiciendis est soluta aut.                                                          | I semestre  |    3 |  13 | NULL                      |
|  573 |        33 | ipsa assumenda eligendi            | Rerum beatae fugiat ipsum enim enim consequatur et. In qui magnam nobis ut exercitationem perferendis. Dolores molestias mollitia perferendis odio.                                                     | II semestre |    3 |  15 | NULL                      |
|  574 |        33 | ab error incidunt                  | Et in ut in aut quis voluptas. Fuga saepe ullam est architecto placeat soluta. Alias est illum est voluptatem eos maxime. Eos est provident sunt dolorem earum. Ea autem iste aut est quidem sed vel.   | II semestre |    3 |  11 | NULL                      |
|  577 |        34 | ut veritatis magnam                | Voluptatem quo cum autem esse id quo. Laborum nihil porro optio. Explicabo similique blanditiis unde sed veniam perferendis ea. Eum fugit culpa exercitationem quod esse est.                           | I semestre  |    1 |  15 | www.vitae.uni.it          |
|  579 |        34 | dolor ab possimus                  | Quod officiis qui laboriosam suscipit. Quaerat unde non exercitationem eum quidem voluptatem. Cum vero facilis magnam culpa amet est cumque veritatis.                                                  | I semestre  |    1 |  15 | NULL                      |
|  583 |        34 | labore qui et                      | Animi et laboriosam minima reprehenderit. Doloribus sed placeat voluptatibus voluptatum est eaque. Repudiandae fuga soluta placeat vero beatae in rerum.                                                | II semestre |    1 |  12 | www.nisi.uni.it           |
|  586 |        34 | reiciendis molestiae qui           | Voluptatem mollitia ut dolores aliquid in eius qui sapiente. Quae id id a distinctio rerum esse. Suscipit suscipit sapiente voluptates commodi.                                                         | I semestre  |    2 |  14 | www.totam.uni.it          |
|  590 |        34 | modi sed earum                     | Nisi sunt animi iste sint similique error. Aut veniam aut vero dolor. Veritatis reprehenderit et quia sit. Sit perspiciatis et nihil aut iure at dolore.                                                | II semestre |    2 |  12 | NULL                      |
|  595 |        34 | vero harum cupiditate              | Recusandae deserunt reprehenderit odio. Repellendus aut nobis quidem animi nisi. Voluptate id omnis iusto in asperiores. Id id voluptatem error expedita. Quae praesentium suscipit tenetur.            | I semestre  |    3 |  13 | www.tempore.uni.it        |
|  596 |        34 | culpa voluptas voluptatem          | Deleniti sed dolorem dolorum tempora tenetur delectus. Molestiae illo voluptatibus quos quo dignissimos. Non explicabo cum vero quaerat est id quo omnis. Est beatae et deleniti.                       | I semestre  |    3 |  13 | NULL                      |
|  597 |        34 | ad molestiae necessitatibus        | Quis praesentium deserunt nulla delectus at. Voluptates ipsum laboriosam modi quisquam recusandae sequi. Earum asperiores est et. Nulla quasi repudiandae quos.                                         | II semestre |    3 |  11 | NULL                      |
|  600 |        34 | nihil quia at                      | Molestias modi neque mollitia qui quidem. Aliquid eum hic qui velit perspiciatis corporis architecto. Enim quia qui non et rerum. Sapiente quis aliquid et voluptate nesciunt iure est voluptas.        | II semestre |    3 |  12 | www.aut.uni.it            |
|  601 |        35 | facilis adipisci provident         | Et aut id aut officia. Doloremque quaerat sit et architecto. Facere nulla dolor sit illum quae laborum. Reiciendis iure nihil tempora.         
                                                         | I semestre  |    1 |  15 | www.consequatur.uni.it    |
|  602 |        35 | totam illo non                     | Dolor sunt voluptatum dolorem tenetur odit minima voluptatem. Qui ut dolor cum hic. Quis reiciendis sed aut esse qui atque consectetur.                                                                 | I semestre  |    1 |  13 | www.nemo.uni.it           |
|  604 |        35 | facere adipisci sed                | Dolorem eum ad distinctio qui molestiae. Sapiente beatae est unde iste consectetur. Exercitationem ullam aliquid ipsam ratione magnam maiores.                                                          | II semestre |    1 |  15 | www.tenetur.uni.it        |
|  612 |        35 | non explicabo aut                  | Tenetur non non ut cupiditate. Eligendi iure ducimus tempora sequi harum quibusdam. Corrupti beatae sunt nostrum eius. Non mollitia eum harum est porro iure.                                           | II semestre |    2 |  14 | NULL                      |
|  614 |        35 | quo dolor aspernatur               | Ut molestiae ducimus nesciunt error. Blanditiis nobis doloremque alias occaecati sed aspernatur. Vero odit enim architecto ratione quam sed. Molestiae perspiciatis fugiat odio dolor fugit in.         | I semestre  |    3 |  15 | www.non.uni.it            |
|  619 |        35 | accusamus et quidem                | Qui est et aliquam. Accusantium neque amet eius maxime modi.                                                                                   
                                                         | II semestre |    3 |  14 | NULL                      |
|  621 |        35 | quia voluptatibus nisi             | Quisquam porro nobis nihil culpa non commodi. Qui illo dignissimos sit corrupti voluptatem. Hic numquam mollitia blanditiis sapiente at animi sequi.                                                    | II semestre |    3 |  12 | www.neque.uni.it          |
|  622 |        36 | aperiam ut suscipit                | Dolorem et voluptatem a sed consequatur. Et adipisci alias ea ducimus voluptatem. Culpa est omnis vero. Enim nesciunt et ut at neque consectetur animi. Fugiat et atque voluptas eum dicta.             | I semestre  |    1 |  11 | NULL                      |
|  626 |        36 | aut nesciunt deleniti              | Et aut id ut molestias. Architecto sed perferendis quos. Qui iure aspernatur error reprehenderit corrupti rerum id quis.                       
                                                         | II semestre |    1 |  11 | www.deleniti.uni.it       |
|  628 |        36 | error quia minus                   | Iure veritatis esse aut itaque adipisci quidem. Totam autem deleniti deleniti aliquid porro esse omnis alias. Commodi eos assumenda tempora dicta laborum. Unde id laudantium voluptatum nesciunt.      | II semestre |    1 |  14 | www.corrupti.uni.it       |
|  629 |        36 | dicta ducimus odit                 | Aut modi mollitia sunt nulla quia ut nobis. Beatae laudantium nesciunt at hic non ratione. Porro error aliquid harum blanditiis sed. Id eius eligendi vitae non.                                        | I semestre  |    2 |  13 | NULL                      |
|  635 |        37 | ex molestiae rerum                 | Expedita qui fugit veniam cum voluptatum a. Ut eaque nihil et ex commodi. Quia consequuntur dolor accusamus nobis aut nulla. Voluptatibus itaque mollitia non. Et et ab minus impedit fugit.            | I semestre  |    1 |  13 | www.nihil.uni.it          |
|  636 |        37 | quam voluptatem nihil              | Deleniti rerum numquam qui eos. Temporibus esse sed ut ut officiis et et. Officia omnis sed et. Sint sit unde quam ut exercitationem iste quia. Ea minus vero accusamus dignissimos rerum.              | I semestre  |    1 |  15 | www.maxime.uni.it         |
|  637 |        37 | labore sequi incidunt              | Ut et asperiores esse et amet rerum. Ut qui voluptas accusantium sint sit cum. Quibusdam excepturi saepe ipsa voluptatibus.                    
                                                         | I semestre  |    1 |  12 | www.consectetur.uni.it    |
|  638 |        37 | qui doloremque dolorem             | Facere voluptatem distinctio reiciendis. Dolorem quia placeat laudantium distinctio quasi autem. Itaque deserunt dolore non excepturi. Ea expedita aliquid dolores voluptatum sint optio.               | I semestre  |    1 |  12 | www.repellendus.uni.it    |
|  640 |        37 | ut eius error                      | Cumque maiores voluptatibus molestiae doloremque dolor. Possimus culpa quia ducimus officiis pariatur minus beatae. Consectetur voluptas beatae et est minima. Aliquam quas laudantium eligendi sed.    | II semestre |    1 |  13 | NULL                      |
|  647 |        37 | rerum aperiam ducimus              | Pariatur ea nihil alias. Eligendi officia aliquam quam quos nam quibusdam atque autem. Veritatis ipsum commodi minima aut vitae rerum. Aut qui amet nobis quae corrupti delectus in.                    | II semestre |    2 |  14 | www.ab.uni.it             |
|  649 |        37 | sapiente pariatur voluptates       | Saepe minima itaque quam amet aperiam accusamus id. Quae possimus occaecati facilis corrupti accusamus aut. Accusantium eos dolore earum aspernatur aperiam non aperiam excepturi.                      | II semestre |    2 |  13 | NULL                      |
|  652 |        38 | velit esse soluta                  | Ab quam veritatis qui odit consequatur tempore omnis exercitationem. Ut et eum aliquam est voluptatem voluptatem.                              
                                                         | I semestre  |    1 |  14 | www.dignissimos.uni.it    |
|  653 |        38 | tempore quod eum                   | Incidunt nihil explicabo repudiandae. Et adipisci voluptatem in nihil ratione. Natus possimus autem corporis.                                  
                                                         | I semestre  |    1 |  11 | NULL                      |
|  658 |        38 | accusamus nesciunt quia            | Facere ipsam reiciendis quo est labore illo nihil. Molestiae consequatur et tempora quia rerum itaque ratione.                                 
                                                         | I semestre  |    2 |  14 | www.tenetur.uni.it        |
|  659 |        38 | eum beatae earum                   | Qui sit ab suscipit autem expedita veniam. Quas magnam est fuga aspernatur facilis aut. Eligendi non qui maiores eveniet eos nihil. Aut vitae ut et qui.                                                | I semestre  |    2 |  11 | NULL                      |
|  665 |        38 | fuga at officiis                   | Et ducimus odio dolor nulla et asperiores sint molestiae. Officiis minima enim id voluptatum. Maxime ad unde et qui eos quia. Omnis vel impedit eos non.                                                | I semestre  |    3 |  15 | www.suscipit.uni.it       |
|  667 |        38 | perspiciatis voluptates veniam     | Dolorem placeat neque perferendis. Et dolores dolores impedit incidunt. Corrupti sed est et nam.                                               
                                                         | I semestre  |    3 |  11 | NULL                      |
|  668 |        38 | similique id non                   | Quibusdam corrupti labore fugiat est fuga. Laborum nostrum cupiditate delectus vitae error.                                                    
                                                         | II semestre |    3 |  13 | NULL                      |
|  669 |        38 | consequatur expedita voluptas      | Nesciunt voluptate dolorum et aut laudantium incidunt. Exercitationem dolorem et esse. Voluptas est ea eveniet necessitatibus. Non dolorum voluptas voluptatibus natus commodi fuga.                    | II semestre |    3 |  14 | www.iusto.uni.it          |
|  673 |        39 | est in officia                     | Nihil sed ratione perspiciatis facere dolorem deserunt non neque. Quo sunt explicabo sunt aut. Officia omnis atque quae.                       
                                                         | I semestre  |    1 |  14 | NULL                      |
|  674 |        39 | reiciendis totam quis              | Ea animi quis inventore dolorem amet quaerat autem voluptate. Similique et reprehenderit excepturi sunt doloribus. Ut eos est sed nesciunt aut voluptas consequuntur.                                   | I semestre  |    1 |  12 | www.pariatur.uni.it       |
|  676 |        39 | amet qui quibusdam                 | Soluta ipsum dolorum nihil. Similique reiciendis deleniti explicabo. Repellat incidunt modi fugit voluptatem esse qui dignissimos. Est repudiandae aut cum aut.                                         | II semestre |    1 |  14 | NULL                      |
|  679 |        39 | necessitatibus sit neque           | Itaque officia ut vel libero voluptatibus rerum. Quas saepe quia saepe totam enim exercitationem.                                              
                                                         | I semestre  |    2 |  14 | www.beatae.uni.it         |
|  680 |        39 | asperiores eveniet maxime          | Eaque harum officiis non eligendi quisquam. Voluptatum culpa facere enim doloribus. Porro dolores eum dicta et quasi ea.                       
                                                         | I semestre  |    2 |  15 | NULL                      |
|  682 |        39 | et in aspernatur                   | Quis suscipit eveniet ducimus ullam rem alias. Esse aliquam harum iusto. Qui qui veritatis similique mollitia voluptas.                        
                                                         | II semestre |    2 |  12 | NULL                      |
|  683 |        39 | hic inventore a                    | Deleniti officiis deleniti quae laboriosam est voluptatum omnis eos. Sed reprehenderit ut excepturi officiis. Error et nemo nulla.             
                                                         | II semestre |    2 |  15 | NULL                      |
|  687 |        39 | dolores et est                     | Repellendus et fuga facere corporis eveniet. Aliquid aut quod ab recusandae maxime ullam. Voluptatem velit temporibus aut eum. Placeat et quia accusamus.                                               | I semestre  |    3 |  12 | www.in.uni.it             |
|  692 |        39 | ea quo itaque                      | Dolor numquam omnis qui aspernatur. Eum praesentium aut nulla eaque eos. Ea est et nobis illum nulla id.                                       
                                                         | II semestre |    3 |  14 | NULL                      |
|  699 |        40 | est aspernatur et                  | Odio recusandae magnam sunt omnis. Aut dolorem ratione ratione reprehenderit impedit. Ab omnis explicabo sint dolore autem cumque.             
                                                         | II semestre |    1 |  11 | NULL                      |
|  711 |        40 | sit voluptas rem                   | Aliquid dolorum quia numquam minima. Omnis ipsum quis error. Magni omnis cupiditate non placeat quis dolores. Sed dolorem sed quos modi vero harum. Nihil dolorem tenetur qui dolores odio atque alias. | II semestre |    3 |  12 | NULL                      |
|  712 |        40 | voluptas aliquid molestiae         | Eveniet consequatur quia culpa porro. Quo ea sed voluptatem atque est id vitae quam. Ut dolores magni repellendus rerum eum ut dolorem cumque. Quis perferendis beatae nobis ut.                        | II semestre |    3 |  12 | NULL                      |
|  718 |        41 | facere sit est                     | Molestias nihil vitae quia iusto nihil perspiciatis ducimus asperiores. Nobis quia a consequuntur nostrum. Ratione vel deleniti et ipsam sint. Illo mollitia laboriosam beatae sequi modi quia odit.    | I semestre  |    1 |  11 | www.nostrum.uni.it        |
|  725 |        41 | doloribus nemo iure                | Ea quae porro laudantium ut. Explicabo et assumenda excepturi. Ex ea necessitatibus aliquid delectus eius et voluptatem ratione. Consequatur saepe voluptate id ad asperiores molestiae quia.           | I semestre  |    2 |  12 | NULL                      |
|  726 |        41 | aut cumque rerum                   | Enim provident rem dolores veniam cum. Odit tempora dolor qui. Voluptatem perferendis quia eligendi inventore omnis voluptatem corrupti. Exercitationem qui vitae nemo deserunt at corporis.            | I semestre  |    2 |  14 | NULL                      |
|  735 |        42 | perspiciatis itaque rerum          | Fugiat ut voluptatem veritatis omnis alias omnis. Dignissimos nobis illo dolores et nulla. Dolor repellendus aut maiores ex.                   
                                                         | I semestre  |    1 |  12 | www.est.uni.it            |
|  738 |        42 | saepe laudantium quia              | In ut quasi culpa id sed. Doloribus error est necessitatibus nesciunt facilis. Modi necessitatibus voluptatem qui. Laudantium animi error et labore sint.                                               | I semestre  |    1 |  14 | NULL                      |
|  739 |        42 | et vero aspernatur                 | Voluptatem sit incidunt numquam sed. Qui ipsam quia exercitationem rerum assumenda in et et. Dignissimos ipsa qui quia soluta est minima in.                                                            | I semestre  |    1 |  15 | NULL                      |
|  741 |        42 | ut ut laboriosam                   | Soluta dolorum delectus ducimus sapiente qui provident delectus. Repellendus quia cum et vero. Impedit sed distinctio magnam ducimus molestias. Beatae aut repellendus quia dolores aut natus eos.      | II semestre |    1 |  15 | www.alias.uni.it          |
|  742 |        42 | blanditiis sit doloribus           | Nesciunt est corporis omnis eligendi ea doloremque voluptates. Omnis earum quod vel veritatis esse. Sit consectetur explicabo illum rerum sequi ea dicta. Necessitatibus sint in totam quisquam quidem. | II semestre |    1 |  14 | NULL                      |
|  744 |        42 | natus unde quibusdam               | Necessitatibus in dignissimos veniam officia reprehenderit similique et. Est ratione est sint vel ut. Voluptatem dolorem minus aut rerum ipsa labore.                                                   | I semestre  |    2 |  15 | www.inventore.uni.it      |
|  747 |        42 | non voluptatibus quia              | Fugiat possimus placeat tenetur. Perferendis vel sed consequatur excepturi sit rerum. Ex eos consequatur qui veniam reprehenderit commodi.                                                              | II semestre |    2 |  13 | NULL                      |
|  748 |        42 | nam aut reprehenderit              | Magnam tempora voluptatem nemo blanditiis beatae voluptas eaque. Voluptatum explicabo magnam nostrum ut. Necessitatibus vel quo non modi quo eius ut.                                                   | II semestre |    2 |  12 | www.nihil.uni.it          |
|  750 |        42 | totam expedita vel                 | Ut magni fugit eaque sed. Necessitatibus ea aut quia ea illum harum quia est. At qui nam quia aperiam. Vitae natus sit vero blanditiis minima molestiae accusantium.                                    | I semestre  |    3 |  14 | NULL                      |
|  754 |        42 | unde veritatis a                   | Iusto ab animi officia voluptatem possimus fuga officia. Placeat rerum voluptas aut et accusamus sed aut laudantium. Qui voluptatem qui eveniet repellat beatae nam.                                    | II semestre |    3 |  12 | NULL                      |
|  755 |        42 | quaerat id possimus                | Cumque autem labore ut omnis voluptates deleniti quas. Fugit mollitia et quasi voluptatem voluptate amet. At quo similique asperiores suscipit velit ipsum dolorem et.                                  | II semestre |    3 |  11 | www.est.uni.it            |
|  756 |        42 | quidem ipsa laborum                | Ab quia velit qui sint nihil ut et. Velit accusantium voluptas sint nulla odit. Est aliquid natus autem impedit. Assumenda sit aut autem quas. Et ut reiciendis et possimus quis occaecati.             | II semestre |    3 |  15 | www.voluptatem.uni.it     |
|  757 |        43 | illum est ea                       | Ducimus sint eveniet quam molestiae et. Quia blanditiis natus dolorum quisquam et a. Qui nobis ut illo culpa voluptatem. Voluptatem omnis voluptatibus et cupiditate illum quibusdam.                   | I semestre  |    1 |  11 | NULL                      |
|  762 |        43 | natus dolores mollitia             | Rerum voluptatem earum voluptatum at molestiae sunt voluptates cumque. Sequi delectus omnis facere et amet et ex eum. Quidem quo voluptatibus labore non dolore.                                        | II semestre |    1 |  14 | NULL                      |
|  773 |        43 | omnis voluptas molestias           | Omnis quia nulla voluptates dolore. Eveniet facere quo vel quo maxime necessitatibus. Nisi accusantium omnis ut nulla aut. Quia est sapiente numquam necessitatibus sint.                               | I semestre  |    3 |  14 | NULL                      |
|  777 |        43 | tenetur est et                     | Veritatis nisi tenetur ea sint soluta veniam sint. Voluptatum quas vel et. Rem magni dolores et ratione. Non reprehenderit suscipit delectus qui.                                                       | II semestre |    3 |  14 | www.earum.uni.it          |
|  778 |        43 | voluptas exercitationem voluptates | In quia itaque ad. Enim officia aperiam consectetur dolore accusamus quam. Dolor autem tenetur reprehenderit sed quia voluptatem sed.          
                                                         | II semestre |    3 |  14 | www.in.uni.it             |
|  781 |        44 | magni in perferendis               | Repudiandae et aut non et sit nesciunt est enim. Totam cumque eum velit odio aliquid. Repellendus nam eaque fuga eos maxime necessitatibus. Ut voluptates sit laboriosam.                               | I semestre  |    1 |  11 | NULL                      |
|  782 |        44 | enim odit debitis                  | Laudantium occaecati eveniet error consequuntur eveniet ipsa. Velit quia voluptates vero dolor et qui. Sint ut ut minima explicabo deleniti quia sed.                                                   | I semestre  |    1 |  15 | www.excepturi.uni.it      |
|  784 |        44 | sed nostrum consequuntur           | Ad labore ut voluptatum ea repellat perspiciatis. Minima voluptatem maiores et in itaque. Aut quia maiores odit est dolorum. Voluptas neque sed quia repellendus.                                       | I semestre  |    1 |  15 | www.adipisci.uni.it       |
|  786 |        44 | non dolorem sequi                  | Non et sed ex et et laborum velit. Voluptas adipisci id rem dignissimos perferendis similique. Voluptas inventore explicabo labore mollitia.                                                            | II semestre |    1 |  13 | NULL                      |
|  788 |        44 | rerum cupiditate tempore           | Fuga voluptas quis sapiente quo at dolor. Deserunt est quod ea aut est molestiae nihil. Maxime omnis velit sed aliquam distinctio. Officiis aspernatur quaerat omnis alias illo beatae.                 | II semestre |    1 |  13 | www.enim.uni.it           |
|  791 |        44 | sunt qui mollitia                  | Sed dolor necessitatibus veniam qui similique quis. Voluptate perferendis enim nesciunt id similique voluptas mollitia nihil. Molestias aliquid voluptas qui ab.                                        | I semestre  |    2 |  11 | www.aliquam.uni.it        |
|  794 |        44 | animi nihil aliquam                | Dolor dolorem autem nemo quibusdam beatae voluptates sunt iure. Officiis quidem itaque ab quia blanditiis dolores sapiente. Quis cumque fuga magni placeat quaerat.                                     | II semestre |    2 |  12 | NULL                      |
|  800 |        45 | commodi praesentium repudiandae    | Rerum odio occaecati similique. Commodi cumque voluptas veritatis. Labore repellendus a eius debitis aut non. Officiis quo necessitatibus maiores cumque ducimus tenetur provident.                     | I semestre  |    1 |  13 | www.cupiditate.uni.it     |
|  810 |        45 | sint explicabo quae                | Excepturi iste corrupti molestiae consequatur similique et quis. Excepturi suscipit sit est aspernatur similique. Harum tenetur qui ipsam.                                                              | I semestre  |    3 |  12 | NULL                      |
|  812 |        45 | quidem provident praesentium       | Dignissimos earum et reprehenderit nam tenetur iure. Omnis non qui ut sint. Maiores recusandae dolores distinctio nesciunt ipsum deserunt saepe. Perferendis enim similique aliquam.                    | I semestre  |    3 |  12 | www.nam.uni.it            |
|  813 |        45 | rerum dignissimos et               | Optio minima tempora aut mollitia velit. Magni asperiores et beatae vel. Laborum quia omnis laborum beatae autem. Vero consequuntur ipsam voluptatibus ut blanditiis beatae est.                        | I semestre  |    3 |  15 | NULL                      |
|  814 |        45 | architecto eligendi consequatur    | Dolorum molestiae qui voluptas distinctio veritatis repellat architecto. Aut eos tempore ipsam numquam. Impedit eum nobis totam et nihil.                                                               | II semestre |    3 |  13 | www.natus.uni.it          |
|  816 |        45 | ea enim adipisci                   | Voluptates perferendis dolores ex aut. Voluptas cupiditate non doloribus. Dolores et sed sint omnis odit a eveniet reprehenderit. Et non cum molestias corrupti quam pariatur.                          | II semestre |    3 |  13 | NULL                      |
|  819 |        46 | dolorum quos eum                   | Voluptatem corrupti dolores accusantium voluptatum vel repudiandae. Ea animi et temporibus sit eius est et omnis. Ab corporis natus culpa dolorem. Et non non distinctio.                               | I semestre  |    1 |  13 | www.ut.uni.it             |
|  821 |        46 | aut reprehenderit deleniti         | Dolor est animi sunt. Esse quam reprehenderit officia odit est nesciunt. Laborum autem odio pariatur numquam recusandae.                       
                                                         | II semestre |    1 |  12 | www.inventore.uni.it      |
|  822 |        46 | iure qui et                        | Consequuntur sunt dolor hic veniam ut esse. Ut nulla nisi ducimus sunt eveniet. Ut aut aut eos nulla. Animi iure debitis rem dolor reprehenderit magnam.                                                | II semestre |    1 |  13 | www.ut.uni.it             |
|  824 |        46 | commodi sint fugit                 | Ipsum inventore nisi pariatur voluptatem adipisci nostrum blanditiis vitae. Numquam temporibus temporibus illo quo culpa.                      
                                                         | II semestre |    1 |  11 | www.maiores.uni.it        |
|  826 |        46 | aspernatur fugiat reprehenderit    | Dolore adipisci ab id et corrupti ut. Mollitia aliquid voluptatum corrupti. Est incidunt consectetur adipisci ea ipsa. Natus nobis ea eos earum at voluptas rerum.                                      | I semestre  |    2 |  12 | NULL                      |
|  829 |        46 | odit odio veniam                   | Qui est deserunt aspernatur. At quod aut dolorem non. Vitae ad optio earum voluptatum ratione illo in. Quod nihil quidem amet autem. Quasi nulla praesentium repudiandae ut quod sed ullam.             | II semestre |    2 |  12 | www.incidunt.uni.it       |
|  835 |        46 | magnam quis dolore                 | Illo voluptatem ut consequuntur fugit ad. Et voluptatem qui doloremque sed sequi possimus harum. Doloremque earum consectetur et distinctio cupiditate eos.                                             | II semestre |    3 |  14 | NULL                      |
|  837 |        47 | labore tempora odit                | Rerum eaque id quas quas et sint tempora. Molestiae suscipit fugiat impedit tenetur in. Ipsa sit pariatur ipsa incidunt quae. Non maxime quo est et.                                                    | I semestre  |    1 |  11 | NULL                      |
|  843 |        47 | qui nemo ad                        | Molestias sint quos necessitatibus blanditiis. Et dolorem alias numquam dicta sint et esse. Sunt harum rerum sunt nemo. Placeat voluptate nulla sit minus fuga beatae id.                               | II semestre |    1 |  13 | www.non.uni.it            |
|  846 |        47 | quaerat accusamus eos              | Sequi repellendus natus error quas eius. Rerum ut error rerum optio. Dolores amet est similique repellendus voluptates nihil iste. Quaerat laboriosam est rerum dolor molestiae ratione.                | I semestre  |    2 |  11 | www.fugiat.uni.it         |
|  847 |        47 | qui quis quam                      | Vero laboriosam ab impedit fugiat at labore nisi. Officiis asperiores sunt qui illo tempora. Numquam ut vero consequatur esse. Aut ullam blanditiis expedita dolorem error velit.                       | I semestre  |    2 |  14 | www.excepturi.uni.it      |
|  848 |        47 | neque architecto est               | Aut nostrum modi aut dolorum. Beatae dicta vero culpa dolorum consequuntur ut. Molestiae nulla in ut distinctio. Quia dolore suscipit quae et qui.                                                      | I semestre  |    2 |  11 | NULL                      |
|  849 |        47 | sapiente saepe porro               | Tempore alias ipsam porro atque voluptatem quo. Corporis eos dolor et quasi vitae modi eos. Velit necessitatibus tempora nobis placeat nostrum est. Dolorum voluptatibus quia praesentium.              | II semestre |    2 |  12 | www.laudantium.uni.it     |
|  855 |        47 | exercitationem explicabo fuga      | Odio libero unde dolores. Numquam vel et aut officiis. Nulla veniam sapiente nostrum aut hic. Eveniet incidunt reiciendis natus possimus.                                                               | II semestre |    3 |  12 | NULL                      |
|  856 |        47 | voluptatem aliquam nam             | Hic maiores libero voluptas adipisci. Numquam quia hic eveniet laborum. Distinctio ducimus vero et eum. Placeat doloribus maxime et eos qui nostrum.                                                    | II semestre |    3 |  13 | NULL                      |
|  858 |        48 | voluptatem consectetur voluptas    | Illo itaque maxime provident asperiores qui. Fuga quo non sit quo. Perspiciatis illum aliquam molestiae.                                       
                                                         | I semestre  |    1 |  13 | www.eligendi.uni.it       |
|  861 |        48 | dolorem nemo rem                   | Sint et eum amet recusandae eos earum dolor. Odit laborum tempora rerum ut consequatur. Porro consequatur dignissimos dolor nesciunt voluptatem.                                                        | II semestre |    1 |  14 | www.odio.uni.it           |
|  862 |        48 | minima aliquam numquam             | Suscipit ducimus quia nostrum vel ut voluptatem. Voluptatem incidunt voluptates laborum. Velit in magni praesentium perferendis vel odit ut.                                                            | II semestre |    1 |  12 | www.explicabo.uni.it      |
|  863 |        48 | tempora laboriosam iusto           | Magni eveniet accusantium quis sit nihil sit. Veniam cumque itaque rerum ut architecto. Omnis aliquid fugit et nesciunt et sint qui. Beatae non ut debitis labore rerum quo totam.                      | I semestre  |    2 |  13 | NULL                      |
|  868 |        48 | enim id deserunt                   | Quos earum quidem sed molestiae quam aspernatur cumque et. Cum eum in quam esse quasi harum illo voluptatem.                                   
                                                         | II semestre |    2 |  12 | NULL                      |
|  873 |        48 | molestiae incidunt facilis         | Ad et quia optio deleniti. Explicabo corporis quis ipsam quia rem illo.                                                                        
                                                         | I semestre  |    3 |  11 | www.autem.uni.it          |
|  875 |        48 | commodi suscipit perspiciatis      | Suscipit iure saepe est rerum dolor repudiandae. Debitis atque voluptatem omnis cupiditate. Fugit officia veritatis et voluptates similique nemo. Nostrum voluptatibus consequatur quibusdam qui.       | II semestre |    3 |  13 | www.at.uni.it             |
|  876 |        48 | nostrum fugiat optio               | Fugit similique tenetur esse hic nam fugit. Consectetur rerum cupiditate adipisci animi doloremque minus omnis nam. Vitae id impedit sed iusto autem numquam.                                           | II semestre |    3 |  12 | www.et.uni.it             |
|  877 |        48 | magnam vel sed                     | Quod reiciendis omnis non ab. Accusamus rem earum sit dolore id quam magni.                                                                    
                                                         | II semestre |    3 |  14 | www.est.uni.it            |
|  883 |        49 | voluptatem fuga incidunt           | Temporibus quo consectetur ratione provident dolor aut deserunt. Consequatur dignissimos autem adipisci necessitatibus voluptas dolor dolorum quaerat. Necessitatibus maiores et totam exercitationem.  | II semestre |    1 |  13 | www.placeat.uni.it        |
|  889 |        49 | explicabo quaerat ducimus          | Consequuntur quisquam perferendis dolor ipsa voluptas. Consequatur reprehenderit nobis eligendi numquam aperiam et tempore repellat.           
                                                         | II semestre |    2 |  11 | NULL                      |
|  891 |        49 | est in quasi                       | Ea in accusamus dolor exercitationem cumque aut distinctio. Et quod unde necessitatibus rem possimus dolorum. Corrupti placeat velit aut sit sint sed eum officiis.                                     | II semestre |    2 |  13 | NULL                      |
|  893 |        50 | dolorem blanditiis nemo            | Sequi nisi ut atque facilis. Et aliquam earum dolores ipsum similique. Quas aliquam adipisci vitae provident quis. Veritatis ratione sed in minima libero.                                              | I semestre  |    1 |  14 | NULL                      |
|  900 |        50 | temporibus tempore ipsam           | Voluptatem dolorum aliquid et ut molestiae est sint. Incidunt vero maiores quia rerum sed ad. Ipsam unde corrupti saepe ea sed.                
                                                         | I semestre  |    2 |  13 | NULL                      |
|  901 |        50 | est illum inventore                | Autem animi culpa libero earum. Quisquam eos ducimus maxime qui quo ea. Quis tenetur deleniti nihil corporis id saepe est.                     
                                                         | I semestre  |    2 |  12 | www.vero.uni.it           |
|  905 |        50 | delectus omnis dolores             | Magni voluptatem unde veritatis vero odio non. Modi harum velit alias impedit et. Eaque nostrum non numquam consequatur dolorem nobis. Sed est temporibus maxime laborum eum fugiat dolore.             | II semestre |    2 |  12 | NULL                      |
|  910 |        51 | est cum explicabo                  | Numquam magni et harum blanditiis repellat. Aliquam quis ex error molestiae eveniet ipsam. Velit tempore quo amet nulla sint est. Ut odio eos enim temporibus ut enim doloremque dolores.               | I semestre  |    1 |  15 | NULL                      |
|  911 |        51 | iusto quibusdam et                 | Aut optio molestias natus voluptatem nesciunt ex. Rerum hic ex dicta nostrum nobis voluptatem est nihil. Tenetur enim et id.                   
                                                         | I semestre  |    1 |  11 | www.et.uni.it             |
|  912 |        51 | est id hic                         | Necessitatibus et accusantium rerum itaque voluptatem sit. Rerum voluptatem fugiat voluptates cupiditate quisquam. Quas excepturi optio alias quis dolores.                                             | I semestre  |    1 |  14 | NULL                      |
|  915 |        51 | in perferendis non                 | Aperiam quia dolorem et velit. Ex ipsa consequatur optio repellendus quia totam. Molestiae ullam quisquam aut pariatur ut dolorem.             
                                                         | II semestre |    1 |  12 | NULL                      |
|  921 |        51 | iste in animi                      | Vel exercitationem dolor numquam aliquid. Alias harum et nam rerum velit maxime perferendis. Et perspiciatis qui est explicabo. Qui illum aut ut illo.                                                  | I semestre  |    2 |  13 | NULL                      |
|  927 |        52 | ullam voluptatem facere            | Itaque nam optio placeat. Et voluptatibus aliquam quae. Tempora voluptas doloremque et et.                                                     
                                                         | I semestre  |    1 |  14 | www.laborum.uni.it        |
|  930 |        52 | quasi occaecati nulla              | Quae cumque error libero itaque ipsa sit corrupti. Iste consequatur repellendus fugiat ipsa ex. Voluptatem numquam reiciendis quia qui incidunt consequatur. Assumenda quaerat veniam illum eos et.     | I semestre  |    1 |  15 | NULL                      |
|  933 |        52 | ipsa sint omnis                    | Et mollitia accusamus possimus autem sunt ea. Nisi aut voluptas et amet. At magnam temporibus impedit harum est. Quam sequi tempora minus repellat distinctio.                                          | II semestre |    1 |  12 | www.accusamus.uni.it      |
|  936 |        52 | quaerat et soluta                  | Suscipit iusto dolor aut est rerum. Saepe exercitationem nemo porro nihil possimus.                                                            
                                                         | I semestre  |    2 |  13 | www.eos.uni.it            |
|  940 |        52 | qui laboriosam molestiae           | Placeat soluta voluptas eaque sed consectetur dolor. Aliquid omnis necessitatibus necessitatibus excepturi quia eum qui. Voluptatum autem maxime molestiae.                                             | II semestre |    2 |  14 | NULL                      |
|  941 |        53 | sint quam unde                     | Velit nihil minima eum molestiae blanditiis iste necessitatibus. Vero at atque et vel sapiente iure. Fugit est aliquam voluptas iusto.         
                                                         | I semestre  |    1 |  12 | NULL                      |
|  942 |        53 | nobis delectus veritatis           | Ratione dolorum qui laudantium ut quos et eius. Eos quo porro quaerat aut. Et ad optio suscipit et quia pariatur.                              
                                                         | I semestre  |    1 |  14 | NULL                      |
|  945 |        53 | quidem minus minus                 | Id et tempore iure quia aspernatur ut quaerat. Distinctio nam et quo voluptatum reiciendis velit rerum veniam. Sequi magnam est quasi ratione.                                                          | II semestre |    1 |  14 | www.quia.uni.it           |
|  946 |        53 | harum illo consequatur             | Praesentium debitis quia qui veniam. Ea maxime voluptas nihil. Nisi voluptas eveniet et aliquid. Cum ullam recusandae animi ut.                
                                                         | II semestre |    1 |  11 | NULL                      |
|  949 |        53 | minus maiores porro                | Veritatis temporibus molestiae repellat eos eligendi eos. Et omnis et est amet suscipit. Natus non vel qui aut voluptatibus omnis. Quam odit sint aut.                                                  | I semestre  |    2 |  11 | NULL                      |
|  953 |        53 | qui nemo in                        | Sint laboriosam quia nemo eos in molestias impedit. Hic et maxime qui rerum deserunt dignissimos.                                              
                                                         | II semestre |    2 |  11 | NULL                      |
|  957 |        53 | blanditiis numquam quos            | Labore et ut tempore enim dolorem. Totam earum commodi delectus quidem ratione. Laudantium ipsa voluptatem quam iusto ut. A vel veritatis consequuntur excepturi quaerat quia eveniet asperiores.       | I semestre  |    3 |  11 | NULL                      |
|  960 |        53 | nemo fugiat rerum                  | Impedit vel pariatur consequatur sequi. Dicta atque aspernatur hic expedita.                                                                   
                                                         | II semestre |    3 |  12 | www.est.uni.it            |
|  962 |        53 | omnis culpa voluptatem             | Voluptatem repellendus ex ducimus. Est fuga minus hic labore. Nam accusantium et debitis ea et vitae.                                          
                                                         | II semestre |    3 |  11 | www.libero.uni.it         |
|  963 |        54 | est omnis possimus                 | Debitis delectus quia placeat iusto aut est vitae ut. Possimus nemo saepe rerum est vero numquam. Sed officia debitis cum et dolor quia quia.                                                           | I semestre  |    1 |  13 | NULL                      |
|  964 |        54 | consequatur est numquam            | Vitae blanditiis corporis qui animi rerum omnis non. Sunt earum numquam rerum id voluptas odio facere. Est nobis autem aperiam quisquam architecto.                                                     | I semestre  |    1 |  13 | NULL                      |
|  967 |        54 | atque non numquam                  | Dolorem totam fuga porro consequatur voluptates. Labore nisi in eos minima pariatur. Excepturi vero qui ut velit pariatur dolorem. Magnam qui et assumenda voluptate officia.                           | II semestre |    1 |  13 | NULL                      |
|  974 |        54 | fuga pariatur excepturi            | Incidunt corrupti maiores soluta soluta. Qui quidem totam nostrum. Perspiciatis sed velit debitis et a. Autem eum qui aperiam dolore eos sequi error.                                                   | II semestre |    2 |  12 | NULL                      |
|  976 |        54 | voluptatem architecto alias        | Expedita vitae provident aspernatur vel. Aperiam in et possimus iure. Est fugiat possimus nulla iste suscipit ab voluptatem ullam. Facilis aut qui omnis dicta sapiente.                                | II semestre |    2 |  15 | www.iusto.uni.it          |
|  978 |        55 | nihil omnis et                     | Ut et voluptate saepe temporibus. Nesciunt dolores pariatur veritatis aut molestiae et. Illum labore dignissimos sunt praesentium sed sit. Qui est consequuntur optio.                                  | I semestre  |    1 |  12 | www.non.uni.it            |
|  979 |        55 | voluptatem perferendis repellendus | Quod et et vero sed reiciendis aut. Voluptas incidunt est cupiditate cupiditate. Eius est dolorum quia ut. Totam exercitationem libero ipsam commodi nemo dolores ex.                                   | I semestre  |    1 |  13 | NULL                      |
|  982 |        55 | eveniet rerum minima               | Est at nulla quis eveniet esse. Omnis dignissimos qui debitis hic veritatis aut. Mollitia tempore eum ipsam animi est aliquid.                 
                                                         | I semestre  |    1 |  12 | NULL                      |
|  984 |        55 | earum numquam deserunt             | Amet qui corrupti maxime iure occaecati ullam. Quae adipisci quis minus quia et architecto autem. Qui ut quia sit.                             
                                                         | II semestre |    1 |  15 | www.voluptatem.uni.it     |
|  986 |        55 | labore dolorem ipsa                | Rem ad reiciendis atque dolores. Aspernatur veritatis voluptas autem sit sunt qui rem. Accusantium hic iusto suscipit omnis maiores sunt a error.                                                       | II semestre |    1 |  14 | www.ullam.uni.it          |
|  991 |        55 | est explicabo iste                 | Ratione qui dicta aut facere praesentium. Doloribus qui odit est. Et officiis optio placeat atque unde explicabo. Minus et quas ut et.         
                                                         | II semestre |    2 |  12 | www.ratione.uni.it        |
|  993 |        56 | commodi laboriosam cumque          | Sed at iusto rerum incidunt. Et modi molestias autem consequatur et eos perspiciatis inventore. Et assumenda et repellendus repellendus illum. Quia officiis qui ut sequi.                              | I semestre  |    1 |  12 | NULL                      |
|  995 |        56 | amet quod repudiandae              | Nihil omnis distinctio voluptas sequi quo fugiat aut. Magni nihil maxime tempora. Et omnis quia et.                                            
                                                         | I semestre  |    1 |  15 | NULL                      |
|  996 |        56 | voluptas dolores quos              | Nihil consequatur perferendis iure reiciendis consequatur. A omnis fuga officia sequi error molestias. Aperiam commodi aspernatur quis veritatis. Et dolorem aut dolorem nulla.                         | I semestre  |    1 |  14 | NULL                      |
| 1005 |        56 | et doloribus qui                   | Dolores at beatae eaque in. Voluptas error asperiores autem modi. Laborum aliquid rerum dolorem est nobis ullam. Quo voluptas unde ut ad eaque. Qui veritatis est id blanditiis optio ut.               | II semestre |    2 |  12 | NULL                      |
| 1007 |        57 | rerum deserunt eaque               | Cum perspiciatis velit autem voluptates beatae. Voluptate ipsam pariatur excepturi. Et in cum nemo itaque ipsam deserunt voluptatem.           
                                                         | I semestre  |    1 |  11 | NULL                      |
| 1009 |        57 | cupiditate ullam earum             | Assumenda exercitationem similique dolorum adipisci incidunt placeat distinctio tempore. Adipisci suscipit omnis est ut veniam non odio et. Corrupti autem non impedit vitae fugiat quo.                | I semestre  |    1 |  14 | www.qui.uni.it            |
| 1013 |        57 | assumenda impedit nihil            | Omnis fugiat nam ipsam ullam iste aut repudiandae. Sunt reiciendis eveniet hic porro. Voluptatem eum totam deleniti ab consequatur quis. Voluptatem ut ad maiores nemo ea.                              | I semestre  |    2 |  12 | www.totam.uni.it          |
| 1015 |        57 | nam ratione officiis               | Nesciunt quaerat laborum inventore quaerat sit. Impedit sed eveniet et quia recusandae officia. Tempora et sed vel repellat.                   
                                                         | I semestre  |    2 |  11 | NULL                      |
| 1017 |        57 | dolor repellat dignissimos         | Aut est id qui pariatur error. Nobis sint eum ut et. Dignissimos placeat totam sed. Cupiditate doloribus qui ipsam possimus porro. Laborum aspernatur sed sit exercitationem laboriosam.                | II semestre |    2 |  12 | www.dolores.uni.it        |
| 1018 |        57 | distinctio ullam aspernatur        | Maiores cum quis sint delectus sed. Saepe tempora excepturi recusandae. Debitis nemo corrupti eum magni at consequatur.                        
                                                         | II semestre |    2 |  12 | NULL                      |
| 1020 |        57 | quasi fugit est                    | Necessitatibus id culpa possimus quia iusto reiciendis. Qui dolor omnis neque. Velit unde quia qui quia quos omnis. Cumque eos accusamus blanditiis asperiores.                                         | II semestre |    2 |  12 | NULL                      |
| 1021 |        58 | nobis aut voluptas                 | Omnis et omnis est velit laborum deserunt dolor. Sunt commodi iste aut est quod in illum. Mollitia sunt nostrum ut tempore dolore nihil voluptas.                                                       | I semestre  |    1 |  12 | NULL                      |
| 1024 |        58 | quis aperiam ab                    | Rerum mollitia qui a iure velit. Quae cupiditate ratione similique voluptatem quasi sapiente. Voluptate eos nesciunt nesciunt ullam.           
                                                         | II semestre |    1 |  14 | www.cum.uni.it            |
| 1030 |        58 | quia consectetur consequatur       | Porro tenetur hic explicabo voluptate veritatis sequi. Facere laudantium sunt voluptas quaerat. Et rerum odio debitis veritatis dolorum totam esse.                                                     | II semestre |    2 |  13 | www.dolore.uni.it         |
| 1032 |        58 | porro aliquid est                  | Est est ut ut ratione dolor quis. Natus possimus sed suscipit consequatur.                                                                     
                                                         | I semestre  |    3 |  11 | www.explicabo.uni.it      |
| 1035 |        58 | natus quia recusandae              | Ut eligendi sequi voluptates cupiditate hic ea sunt. Accusamus id illo hic inventore. Eum eos veritatis nesciunt. Voluptas in et similique. Nulla ipsum sit reprehenderit. Natus qui dolor a.           | I semestre  |    3 |  12 | www.et.uni.it             |
| 1037 |        58 | veniam unde laborum                | Praesentium dignissimos laborum pariatur assumenda vitae esse voluptates nostrum. Sequi consequatur velit deleniti commodi rerum tenetur repellat. Magnam ut quas asperiores aperiam.                   | II semestre |    3 |  13 | NULL                      |
| 1041 |        59 | at dolorem temporibus              | Ea excepturi placeat dignissimos quia non ut. Quo qui ut rem accusantium praesentium. Cumque at eligendi minima voluptatem. Autem est aut assumenda nihil rerum. Accusamus sunt tempora aut blanditiis. | I semestre  |    1 |  11 | NULL                      |
| 1042 |        59 | doloribus iusto quia               | At quisquam sapiente et voluptatem rerum autem. Ipsam est id voluptatibus delectus suscipit. Impedit blanditiis mollitia fuga unde odio nobis.                                                          | I semestre  |    1 |  13 | NULL                      |
| 1045 |        59 | est et in                          | Qui sequi numquam nam voluptatem. Eligendi repellat at quia asperiores. Vitae rerum aut voluptates qui totam occaecati sed.                    
                                                         | II semestre |    1 |  15 | NULL                      |
| 1052 |        59 | ut sint qui                        | Voluptatem occaecati unde id officiis. Aliquam vel est asperiores porro atque eum omnis. Odit quia eaque fuga et temporibus.                   
                                                         | I semestre  |    3 |  12 | NULL                      |
| 1054 |        59 | alias iure possimus                | Earum ut molestias eos ab. Ea nam iure repellat voluptas nihil praesentium. Sed possimus ut exercitationem nisi ducimus rem.                   
                                                         | II semestre |    3 |  15 | www.et.uni.it             |
| 1056 |        60 | numquam aspernatur nesciunt        | Autem facilis non facilis et tempore esse doloremque. Earum rerum nihil necessitatibus et error. Eos ut esse officia occaecati.                
                                                         | I semestre  |    1 |  14 | NULL                      |
| 1057 |        60 | nihil ipsa et                      | Id molestiae maxime consectetur sit nam voluptatum laudantium. Id modi impedit quidem asperiores quisquam. Sit odio in autem et doloribus. Vel quis iste ad hic est minima et.                          | I semestre  |    1 |  13 | NULL                      |
| 1060 |        60 | labore rerum deleniti              | Et sed pariatur veritatis dolorem et. Ab esse quia ipsum. Aperiam delectus accusantium fugit ut. Officia a qui corrupti facere.                
                                                         | II semestre |    1 |  11 | NULL                      |
| 1062 |        60 | rem ut ea                          | Vero nulla deserunt pariatur quae ut. Deserunt et illum quis est et cupiditate et. Ipsa nesciunt fuga in aperiam.                              
                                                         | II semestre |    1 |  15 | www.sit.uni.it            |
| 1063 |        60 | vel et dolores                     | Rerum perspiciatis velit voluptatem et ut nobis. Est veritatis sequi voluptatem quidem dignissimos rerum. Ea culpa dolor ut omnis voluptatibus iure unde.                                               | I semestre  |    2 |  13 | www.velit.uni.it          |
| 1065 |        60 | illum ad quos                      | Temporibus voluptas facere et ea expedita placeat est. Ipsum ex quis hic autem fugiat consectetur. Numquam illo id facilis rem ut ea vitae delectus.                                                    | I semestre  |    2 |  14 | www.amet.uni.it           |
| 1068 |        60 | quisquam error aut                 | Voluptate sit placeat sint enim. Ab qui perferendis occaecati magni et. Neque rerum itaque eligendi quae animi qui. Et laboriosam sint quis omnis.                                                      | II semestre |    2 |  13 | NULL                      |
| 1071 |        60 | fugit quis rerum                   | Eum excepturi nobis cupiditate impedit enim laborum consequatur. Vel et iusto amet totam hic nemo. Minima id qui et sit libero. Occaecati nisi voluptatem eveniet sint error alias perspiciatis at.     | I semestre  |    3 |  11 | NULL                      |
| 1072 |        60 | eius provident sapiente            | Eos itaque voluptas sunt consequuntur et. Quidem in autem unde aut. Velit nesciunt laboriosam debitis nesciunt facilis assumenda. Et ea dolore eum. Qui sit fugiat recusandae eius quia.                | I semestre  |    3 |  12 | NULL                      |
| 1073 |        60 | quaerat in ut                      | Repellendus suscipit voluptatem dolor. Itaque non labore repellendus culpa. Pariatur ducimus aut doloribus ut dolores quia est.                
                                                         | I semestre  |    3 |  11 | www.est.uni.it            |
| 1074 |        60 | ut quo ducimus                     | Facilis in iure ut dolorem quaerat. Natus quia velit eum rerum voluptatibus omnis. Magnam nobis aut repudiandae quis dolore repellat nisi.                                                              | II semestre |    3 |  11 | NULL                      |
| 1075 |        60 | et occaecati eius                  | Ut quibusdam expedita ex perferendis vero aut. Accusamus distinctio totam quos dolore voluptatem. Tempora modi sint aut pariatur.              
                                                         | II semestre |    3 |  13 | NULL                      |
| 1077 |        60 | sit assumenda ut                   | Rerum beatae reiciendis consequatur iure ea neque facilis numquam. Numquam ea omnis explicabo odit. Quo quos praesentium saepe voluptate.                                                               | II semestre |    3 |  15 | www.est.uni.it            |
| 1079 |        61 | enim quae quos                     | Et aut voluptatem sit ad sed nam pariatur velit. Qui veritatis nesciunt blanditiis natus quia.                                                 
                                                         | I semestre  |    1 |  13 | NULL                      |
| 1080 |        61 | distinctio rerum dolor             | Et omnis vel rem quia. Nihil alias similique voluptas provident enim. Facilis ipsum numquam corporis rerum.                                    
                                                         | I semestre  |    1 |  14 | www.temporibus.uni.it     |
| 1082 |        61 | et earum tenetur                   | Quod et debitis totam et consectetur. Dolorem dolore ut quam molestiae et.                                                                     
                                                         | II semestre |    1 |  14 | www.sit.uni.it            |
| 1085 |        61 | et enim occaecati                  | Adipisci dolore eaque officiis sunt modi sit. Et dolores facere dolores et inventore omnis tempore voluptatem.                                 
                                                         | II semestre |    1 |  15 | www.in.uni.it             |
| 1088 |        61 | iusto consequatur quae             | Hic cum autem magnam maxime. Omnis dolores qui libero atque deserunt. Natus blanditiis aperiam molestiae occaecati quo.                        
                                                         | I semestre  |    2 |  13 | www.ut.uni.it             |
| 1089 |        61 | sequi temporibus aut               | Architecto amet quos non odio quidem. Quo saepe aut et. Amet minus quia possimus neque sit cumque hic. Quo sunt fuga totam maiores doloribus autem laudantium.                                          | II semestre |    2 |  15 | www.similique.uni.it      |
| 1090 |        61 | ea eos dolor                       | Sed dolores soluta dolore. Ad repudiandae tempore dolor doloremque voluptatum delectus deleniti. Autem magni porro atque id commodi earum.                                                              | II semestre |    2 |  13 | NULL                      |
| 1098 |        62 | voluptatem repudiandae rerum       | Ut fugiat nemo corporis omnis sequi expedita aliquid. Eum tempore eos quia rerum et debitis. Quia et mollitia facilis corrupti. Sed fugit et nobis impedit.                                             | I semestre  |    2 |  15 | NULL                      |
| 1101 |        62 | eos est dolor                      | Sint excepturi id voluptates laboriosam rerum. Nesciunt minima consequatur ipsam architecto corrupti nobis et in. Aut unde earum laboriosam. Eligendi sunt omnis dolores illo optio.                    | II semestre |    2 |  11 | www.officia.uni.it        |
| 1102 |        62 | architecto atque dolorem           | Beatae laboriosam sunt ab totam blanditiis non iure. Totam nam doloremque eum. Omnis enim non possimus ut mollitia.                            
                                                         | II semestre |    2 |  12 | www.dolores.uni.it        |
| 1110 |        63 | enim voluptate perferendis         | Vero vel aut consequatur deleniti cum ea. Facilis est ut dolores rem modi cupiditate itaque ea. Illum necessitatibus minima eius magnam cum aut.                                                        | I semestre  |    2 |  15 | NULL                      |
| 1114 |        63 | voluptas hic laboriosam            | Fugiat iusto harum nihil ut est. Et quia voluptatem at. Adipisci nobis eius molestiae quaerat.                                                 
                                                         | II semestre |    2 |  11 | www.sit.uni.it            |
| 1116 |        64 | soluta alias fugiat                | Autem sequi error rerum dolorem voluptates nemo laborum. Dolorem asperiores repellendus voluptates corporis ut harum. Consequatur et sunt eos. Omnis explicabo vitae laudantium sit est.                | I semestre  |    1 |  14 | www.officiis.uni.it       |
| 1119 |        64 | aut debitis nesciunt               | Porro a quo deserunt qui. Ipsum delectus qui harum et perferendis qui. Harum nostrum delectus ipsam rerum.                                     
                                                         | II semestre |    1 |  14 | NULL                      |
| 1122 |        64 | ex perspiciatis blanditiis         | Omnis aut aspernatur nulla sint. Cupiditate quae et ex est quis rem sunt voluptas. Voluptatem nobis perferendis pariatur voluptatem incidunt.                                                           | I semestre  |    2 |  12 | NULL                      |
| 1125 |        64 | porro illo ea                      | Odio cupiditate doloremque quidem harum placeat voluptatem placeat. Quam quis quos blanditiis maiores. Architecto suscipit veritatis impedit et nobis nesciunt quo.                                     | I semestre  |    2 |  13 | www.incidunt.uni.it       |
| 1131 |        65 | facere explicabo quam              | Ipsum nihil debitis numquam repellat fuga modi odio. Enim rerum praesentium et est cumque. Nam modi facere aliquam autem maxime ab.            
                                                         | I semestre  |    1 |  15 | www.culpa.uni.it          |
| 1134 |        65 | ullam ducimus architecto           | Corrupti vitae sequi aperiam quas. Distinctio est quisquam pariatur doloremque. Quidem corporis et non laborum et qui. At nobis dolorem totam tempora velit.                                            | I semestre  |    2 |  15 | NULL                      |
| 1135 |        65 | sunt culpa id                      | Ea aut optio nesciunt odio. Rerum impedit veritatis blanditiis et possimus ex est.                                                             
                                                         | I semestre  |    2 |  11 | www.et.uni.it             |
| 1136 |        65 | vel ipsa eos                       | Cum aut veritatis sint qui accusantium quia dicta velit. Dolor amet ut aut quos tempore molestiae laborum. Sit dolores consequuntur facilis non qui laudantium fugiat libero.                           | I semestre  |    2 |  14 | www.eos.uni.it            |
| 1137 |        65 | ut qui reiciendis                  | Recusandae non dolor in illum voluptatem. Voluptates quasi aliquam reiciendis laborum ut sunt a. Sapiente voluptatibus impedit dolorem fuga vitae veniam. Fuga dignissimos incidunt ut eligendi.        | I semestre  |    2 |  14 | NULL                      |
| 1139 |        65 | et eius occaecati                  | Qui quaerat corporis asperiores iure expedita qui. Praesentium quasi voluptas sed est et sed.                                                  
                                                         | II semestre |    2 |  14 | www.illum.uni.it          |
| 1141 |        65 | porro autem cumque                 | Sequi ut eum excepturi. Debitis et illo ut facilis. Voluptas incidunt inventore est magnam perferendis.                                        
                                                         | II semestre |    2 |  12 | www.numquam.uni.it        |
| 1143 |        66 | ex quaerat commodi                 | Et ea odit possimus deserunt. Fugit incidunt repellat a corporis ut. Vel pariatur perferendis et sed optio. Quia dolores ullam animi perferendis.                                                       | I semestre  |    1 |  13 | NULL                      |
| 1146 |        66 | omnis quibusdam et                 | Non eum iste id voluptas sit qui blanditiis labore. Dolores ipsum sunt at. Reprehenderit ipsum magni consequatur itaque et perferendis. Et quis harum doloribus quasi iste hic iste.                    | II semestre |    1 |  15 | NULL                      |
| 1148 |        66 | autem tempora ipsa                 | Placeat occaecati explicabo aspernatur eos. Ea debitis velit sit. Et quis reprehenderit sequi odit esse et placeat. Asperiores est dignissimos voluptas sed excepturi sint est.                         | I semestre  |    2 |  11 | www.quis.uni.it           |
| 1152 |        66 | corporis harum maxime              | Qui esse sapiente tempora odio aut dolor. Et aliquid cum rem et ut voluptatem qui.                                                             
                                                         | II semestre |    2 |  11 | NULL                      |
| 1154 |        66 | in blanditiis dolorum              | Debitis aliquam sed autem non doloremque porro. Voluptate voluptatem culpa vel. Sunt provident cupiditate earum eaque quas. Id non expedita doloremque vel nostrum possimus incidunt.                   | I semestre  |    3 |  13 | www.quis.uni.it           |
| 1157 |        66 | consequatur fugiat quia            | Alias est iusto deleniti atque. Ut mollitia enim animi deleniti. Voluptatibus sit at velit rem qui eligendi voluptas quasi.                    
                                                         | II semestre |    3 |  13 | www.omnis.uni.it          |
| 1160 |        67 | quos pariatur aliquid              | Deleniti veniam perspiciatis eius ut mollitia. Quod nostrum adipisci aut qui. Voluptas id eos eveniet sint in. Adipisci delectus perspiciatis ut eos.                                                   | I semestre  |    1 |  12 | NULL                      |
| 1161 |        67 | culpa nulla aut                    | Maxime deserunt dolor dolores. Esse voluptatem rem placeat eum nihil. Magnam qui reiciendis quo rerum minus placeat dolorum. Omnis autem ipsum nobis deleniti.                                          | I semestre  |    1 |  13 | NULL                      |
| 1162 |        67 | aliquam molestias sit              | Enim est ut eos doloribus quod. Saepe provident repellendus quia molestiae. Eius consectetur saepe quia et omnis cum rerum. Odio magni impedit quisquam praesentium.                                    | I semestre  |    1 |  12 | www.consequatur.uni.it    |
| 1165 |        67 | consequuntur aut pariatur          | Autem sint ad tenetur itaque molestiae sit sit. Possimus sapiente cumque modi ea harum. Consectetur quos earum minima excepturi vero dolorem. Dicta earum sit ullam vel.                                | II semestre |    1 |  15 | www.consequatur.uni.it    |
| 1166 |        67 | et deserunt vitae                  | At mollitia aut in ut. Culpa sit sit aut consequatur corporis nihil eos. In quaerat unde voluptatem autem est ducimus. Dignissimos sint rem est laudantium est eum.                                     | II semestre |    1 |  11 | NULL                      |
| 1167 |        67 | enim cupiditate laudantium         | Quas excepturi ipsum atque sed. Id sapiente quisquam rerum perspiciatis. Quidem tempore nisi omnis unde eveniet. Enim magni ut deserunt reprehenderit explicabo eum.                                    | I semestre  |    2 |  13 | www.animi.uni.it          |
| 1170 |        67 | dolores dolor voluptas             | Ut sapiente qui ut at ut quia corrupti. Quia ut et est qui et. Doloribus velit sequi laborum laboriosam omnis.                                 
                                                         | I semestre  |    2 |  15 | NULL                      |
| 1172 |        67 | ut quis illo                       | Architecto nesciunt ut sed sunt et perspiciatis ea. Optio magni ab qui. Itaque rem ut eveniet odit nulla dolore est. Eum rem laborum iste dicta facere ut.                                              | II semestre |    2 |  11 | www.aut.uni.it            |
| 1173 |        67 | consequatur aperiam illo           | Quas adipisci animi suscipit quae. In id qui aut atque. Reprehenderit accusamus voluptate vitae est est voluptatem. Veritatis laborum aspernatur qui ea.                                                | II semestre |    2 |  12 | NULL                      |
| 1175 |        67 | consequatur in ratione             | Alias rem quas eaque autem optio quis autem. Aut consequatur ratione impedit rerum. Enim ut nulla officiis porro minima dolorem. Pariatur qui sapiente labore et ut.                                    | I semestre  |    3 |  11 | NULL                      |
| 1176 |        67 | accusantium aut dicta              | Recusandae aut in expedita ea aut saepe aut omnis. Eius vitae similique quia enim et qui est architecto. Voluptatem velit aspernatur nihil ex ab.                                                       | I semestre  |    3 |  12 | NULL                      |
| 1177 |        67 | iure alias at                      | Non voluptas beatae nesciunt esse. Voluptas eius ea minus sit aspernatur ut dolor perferendis. Quaerat eos sapiente et eveniet numquam laborum.                                                         | I semestre  |    3 |  12 | NULL                      |
| 1178 |        67 | quia error voluptates              | Quo cum atque suscipit aliquam. Hic et odio voluptatem porro recusandae.                                                                       
                                                         | II semestre |    3 |  11 | NULL                      |
| 1180 |        67 | quas est repellat                  | Sit corrupti et sit enim. Minima voluptas autem dignissimos et maxime. Consequatur eos sint perspiciatis consequatur perferendis velit earum.                                                           | II semestre |    3 |  14 | NULL                      |
| 1181 |        67 | consequatur occaecati illo         | Ut reprehenderit natus esse fuga ullam id. Eius voluptatem odit consectetur doloremque quidem non. Mollitia voluptatem voluptatem optio animi non blanditiis.                                           | II semestre |    3 |  11 | www.labore.uni.it         |
| 1191 |        68 | eum et saepe                       | Earum dolore veritatis et qui dicta tenetur. Tenetur exercitationem excepturi earum ullam. Harum laboriosam dignissimos at modi. Doloremque occaecati doloribus quod ut voluptate.                      | II semestre |    2 |  11 | NULL                      |
| 1192 |        68 | ipsa quas quia                     | Occaecati incidunt rerum nisi sint laboriosam nisi. Consequuntur qui est et nemo. Est veniam accusantium voluptas fugit. Ut itaque alias aut fugiat aut mollitia nemo.                                  | II semestre |    2 |  11 | NULL                      |
| 1195 |        69 | facilis magnam rem                 | Voluptate porro est amet dolorem. Sint odit consequatur at quas doloremque. Dignissimos harum beatae omnis voluptatem magni numquam accusamus.                                                          | I semestre  |    1 |  12 | NULL                      |
| 1198 |        69 | necessitatibus consequatur aperiam | Dolore voluptas repudiandae nulla quidem voluptatem aut. Quia pariatur aut ut eum.                                                             
                                                         | II semestre |    1 |  13 | NULL                      |
| 1207 |        69 | magnam voluptatem harum            | Nulla nemo aut eligendi ducimus voluptates. Eos ut earum vitae dolores est assumenda. Inventore voluptatem doloribus rerum quia. Quo ex magni perferendis id saepe qui itaque aperiam.                  | II semestre |    2 |  11 | NULL                      |
| 1208 |        69 | rerum et qui                       | Minus minus tenetur commodi cum possimus veniam. Quis doloremque voluptatem nam in qui error quaerat. Inventore est in numquam aliquam minima aut.                                                      | II semestre |    2 |  15 | NULL                      |
| 1209 |        69 | ex totam sint                      | Id exercitationem in omnis dolorum quam. Qui et ut cum maxime et. Quia labore nisi veniam temporibus optio omnis laudantium natus. Maxime qui in fugiat amet voluptatem eos.                            | I semestre  |    3 |  12 | NULL                      |
| 1212 |        69 | vel velit non                      | Sit autem fugiat aut est omnis. Adipisci officia dolorem recusandae distinctio et quidem omnis. Tenetur quam fugiat eligendi saepe libero.                                                              | I semestre  |    3 |  15 | www.quidem.uni.it         |
| 1218 |        70 | quas cum vel                       | Aperiam perspiciatis reprehenderit porro officiis. Numquam iusto in voluptatem consequuntur numquam amet. Perferendis ipsam sint fugit similique. Earum itaque aliquam vel saepe modi odit et.          | I semestre  |    1 |  13 | www.sunt.uni.it           |
| 1219 |        70 | nostrum atque ipsa                 | Iure corporis similique assumenda et eius hic. Ut modi illum aut quam sint. Et qui nesciunt occaecati et. Sint quaerat voluptatem aperiam suscipit ducimus omnis distinctio.                            | I semestre  |    1 |  11 | www.suscipit.uni.it       |
| 1222 |        70 | consequatur architecto consequatur | Ipsam quis ullam dolore eveniet voluptate est explicabo ipsa. Est exercitationem porro nisi eum. Consequatur minus sed molestiae odio fuga.                                                             | II semestre |    1 |  13 | www.rerum.uni.it          |
| 1224 |        70 | eaque dolores est                  | Aut distinctio reprehenderit quam autem. Minima rem animi qui qui. Ad itaque numquam amet facilis.                                             
                                                         | I semestre  |    2 |  13 | NULL                      |
| 1228 |        70 | eius eum itaque                    | Quis inventore velit nemo quasi voluptas ullam. Aut neque quasi ut repellendus dolores molestias et. Quasi necessitatibus adipisci rerum voluptate non eum.                                             | I semestre  |    2 |  12 | NULL                      |
| 1229 |        70 | sunt consequatur soluta            | Cumque voluptatem labore sed accusantium modi aliquam ullam aut. Impedit aut est suscipit omnis eaque molestias. Quia quod ipsam libero facilis vitae.                                                  | II semestre |    2 |  13 | www.commodi.uni.it        |
| 1234 |        70 | nihil consectetur ex               | Accusamus nesciunt iusto fugit dolores quaerat. Rerum neque atque placeat. Ab vero adipisci quia asperiores et rem quam.                       
                                                         | I semestre  |    3 |  12 | NULL                      |
| 1240 |        70 | eveniet qui cumque                 | Repellendus aperiam voluptatem natus nulla soluta quia nisi minima. Quam laborum doloremque autem ut. Harum omnis sunt temporibus reprehenderit.                                                        | II semestre |    3 |  15 | www.quidem.uni.it         |
| 1244 |        71 | molestiae aut sit                  | Quo qui ut aut nemo. Autem aut incidunt dicta recusandae maxime. Nobis labore sapiente non rem. Ut dicta placeat animi labore eius.            
                                                         | I semestre  |    1 |  12 | www.quo.uni.it            |
| 1245 |        71 | incidunt aperiam qui               | Inventore et sit et et qui fugit. Velit iusto aut et assumenda asperiores reiciendis ut.                                                       
                                                         | I semestre  |    1 |  12 | www.enim.uni.it           |
| 1248 |        71 | aut dolorum distinctio             | Aut fuga quae aut placeat in est. Sapiente alias cum fugit odio eum. Officiis debitis quae cumque. Cumque quam inventore atque dolores dolorem.                                                         | II semestre |    1 |  14 | NULL                      |
| 1251 |        71 | fugit distinctio quibusdam         | Atque quidem consectetur fugiat aut distinctio recusandae. Repudiandae voluptatibus est voluptas. Quidem voluptatem neque iusto optio in id ab. Architecto id porro autem quod.                         | I semestre  |    2 |  14 | NULL                      |
| 1252 |        71 | autem possimus illum               | Nemo sit quia vel autem. Nesciunt quia pariatur quia quidem. Mollitia aperiam est nam.                                                         
                                                         | I semestre  |    2 |  14 | www.repellat.uni.it       |
| 1256 |        71 | officia cumque tempore             | Quia aut numquam ducimus. Exercitationem architecto est non possimus maiores voluptatibus. Nam commodi cum nam vel.                            
                                                         | II semestre |    2 |  15 | www.modi.uni.it           |
| 1261 |        72 | voluptas sit aliquam               | Voluptas sed numquam laboriosam quia non dignissimos error minus. In nobis quia asperiores rerum delectus enim. Distinctio nesciunt dolores cumque soluta.                                              | I semestre  |    1 |  11 | www.earum.uni.it          |
| 1263 |        72 | amet itaque fugit                  | Sed quia ratione autem culpa. Officia rerum voluptatem consequatur quia veniam totam. In unde repellat perspiciatis quia.                      
                                                         | II semestre |    1 |  12 | www.minima.uni.it         |
| 1267 |        72 | doloribus debitis eveniet          | Voluptas dolor quia in. Optio officia ipsa sed accusantium adipisci minus quas quibusdam. Quae dolores ea similique error delectus. Et reprehenderit voluptatum earum sapiente dolorem iste.            | I semestre  |    2 |  11 | NULL                      |
| 1274 |        73 | adipisci ut quis                   | Et voluptas maxime reprehenderit eius consequatur at. Corporis saepe recusandae temporibus. Maiores amet quaerat ab dolore nesciunt perspiciatis. Quaerat quia aut laudantium nostrum nihil alias.      | I semestre  |    1 |  12 | NULL                      |
| 1277 |        73 | voluptas corporis recusandae       | Dicta itaque natus atque aliquid dolore. Culpa voluptates id excepturi sunt autem aut exercitationem exercitationem. Voluptas possimus nihil eligendi molestias voluptate ipsa qui.                     | II semestre |    1 |  12 | www.quis.uni.it           |
| 1278 |        73 | unde at voluptas                   | Velit ullam optio aliquam. Error rem itaque dicta provident. Molestias et aperiam quisquam libero. Et explicabo adipisci ullam.                
                                                         | II semestre |    1 |  11 | NULL                      |
| 1280 |        73 | exercitationem ea omnis            | Quisquam voluptates deserunt architecto necessitatibus. Amet eum sint eum culpa in. Illum earum pariatur aut commodi ut error optio iste.                                                               | II semestre |    1 |  14 | NULL                      |
| 1282 |        73 | accusantium tempora vel            | Quos amet non et molestias quasi. Hic nam voluptatem et deserunt ea et possimus. Harum ab commodi laudantium eaque adipisci quae molestias.                                                             | I semestre  |    2 |  11 | NULL                      |
| 1284 |        73 | praesentium mollitia rerum         | Voluptas quam et beatae aut nisi voluptas. Cupiditate cum sint rem numquam iste ipsa. Velit reiciendis labore repellat omnis distinctio nihil unde accusamus. Labore cum itaque ab.                     | II semestre |    2 |  15 | www.non.uni.it            |
| 1285 |        73 | qui sapiente voluptatem            | Recusandae voluptatem quasi et necessitatibus quia in. Natus et sed reiciendis omnis ab alias. Et est ea aspernatur iure qui delectus alias. Ipsa libero magnam quia recusandae.                        | II semestre |    2 |  14 | NULL                      |
| 1289 |        74 | quia non rerum                     | Aut dicta perferendis veniam cum quia quis. Dolorem dolor repellat quo quam enim dolores. Eveniet accusantium adipisci aliquid quis quo. Neque voluptatem ipsa iusto voluptas at veritatis.             | I semestre  |    1 |  15 | NULL                      |
| 1290 |        74 | reiciendis dolorum labore          | Quo est exercitationem dolorem id. Voluptatem harum deserunt adipisci sit dolorum. Harum impedit neque officiis in. Rem dolor harum a nesciunt. Eligendi ipsam aut ea corporis.                         | I semestre  |    1 |  13 | NULL                      |
| 1291 |        74 | laboriosam aperiam ut              | Neque vero temporibus sunt beatae consequatur. Consequatur quam ut rerum dolorem repellendus iste. Quasi magnam tempora nisi error omnis. Et explicabo iure eum reiciendis quos amet.                   | II semestre |    1 |  12 | NULL                      |
| 1293 |        74 | et fugit occaecati                 | Qui dolorem quidem doloribus nihil saepe ipsam. Iusto nemo non delectus. Eius laboriosam sed officiis ab incidunt pariatur. Fuga nisi ut et incidunt dicta optio.                                       | II semestre |    1 |  15 | NULL                      |
| 1295 |        74 | repudiandae amet similique         | Ut facilis repudiandae sed perferendis. Aliquam et dolores molestias ab consequuntur accusantium voluptas. Sit fugit quas dolor et eligendi enim.                                                       | I semestre  |    2 |  14 | www.et.uni.it             |
| 1297 |        74 | debitis est saepe                  | Accusantium sapiente esse et vitae. Dolores aut id voluptas expedita dignissimos aperiam. Totam iste qui cupiditate ab.                        
                                                         | I semestre  |    2 |  11 | www.soluta.uni.it         |
| 1300 |        74 | molestiae distinctio quis          | Quisquam voluptas nemo sit iure. Consequatur labore dolorem quod quisquam quo rem. Fugit et tempora sapiente corporis sit aliquid.             
                                                         | II semestre |    2 |  14 | NULL                      |
| 1303 |        75 | quaerat in qui                     | Unde laboriosam deserunt fugit dolor. Eos fuga expedita vel eum quo.                                                                           
                                                         | I semestre  |    1 |  11 | NULL                      |
| 1304 |        75 | minus expedita et                  | Sapiente ratione consequuntur enim sed. Nemo doloribus quos architecto minus adipisci. Et sit aspernatur vel dolores.                          
                                                         | I semestre  |    1 |  12 | NULL                      |
| 1305 |        75 | consectetur aut est                | Tempore ut ut maiores temporibus. Quos molestiae expedita vitae ea veritatis et. Quis possimus mollitia ut. Voluptatem nam laborum et sint rem officia qui.                                             | I semestre  |    1 |  14 | NULL                      |
| 1307 |        75 | unde commodi qui                   | Ut architecto et nemo sed. Consequatur rerum sit totam illo dolorum blanditiis. Quo ad non laborum ad et repellendus dicta. Repellendus quod totam quia sit.                                            | I semestre  |    1 |  14 | www.quaerat.uni.it        |
| 1309 |        75 | porro et aut                       | Placeat quae unde neque consequatur dolor enim. Debitis nesciunt iste facilis tempore et tenetur. Eaque rem iusto similique iste qui explicabo.                                                         | II semestre |    1 |  14 | www.placeat.uni.it        |
| 1313 |        75 | qui vitae molestias                | Vero quisquam corrupti nesciunt veniam molestias sint nobis officia. Ea dolore perspiciatis id.                                                
                                                         | I semestre  |    2 |  14 | NULL                      |
| 1314 |        75 | enim unde dolorem                  | Voluptate modi est facilis cumque ut autem. Aut ut nulla itaque fuga. Laboriosam dolores nihil minus. Ut ullam molestias nemo aliquid vel.                                                              | I semestre  |    2 |  12 | www.repellat.uni.it       |
| 1317 |        75 | sit amet voluptatum                | Est quam et in sed et veritatis molestiae dolores. Enim est officia cumque temporibus. Deleniti qui veritatis enim possimus.                   
                                                         | II semestre |    2 |  13 | www.et.uni.it             |
+------+-----------+------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------+------+-----+---------------------------+







3. SELECT * FROM `students` WHERE YEAR(CURDATE()) - YEAR(date_of_birth) > 30; 
| 3522 |        16 | Timothy       | Marino     | 1990-07-25    | CPAFTB71C52Q471Z | 2021-05-16     | 623554              | antonino.piras@esposito.org        |
| 3524 |        52 | Eufemia       | De rosa    | 1977-03-12    | LSKMEF88C60Z229M | 2018-12-08     | 623556              | ingrid.lombardo@guerra.org         |
| 3525 |        51 | Monia         | Milani     | 1992-04-12    | OXDCYJ74V47Z119E | 2018-07-31     | 623557              | wdonati@hotmail.com                |
| 3527 |        43 | Enrico        | Rizzi      | 1986-05-25    | FWPIIQ58B50K499X | 2020-06-08     | 623559              | tancredi.marini@hotmail.com        |
| 3530 |        41 | Fabio         | Barbieri   | 1991-12-08    | UUAKOV67A59B032F | 2021-05-24     | 623562              | ruggiero.silvano@email.it          |
| 3532 |        60 | Emilia        | D'angelo   | 1973-12-07    | IYNTGZ10N39H411H | 2020-12-13     | 623564              | radio.marini@gmail.com             |
| 3533 |        49 | Miriam        | Gallo      | 1976-12-12    | XJWBDQ02M17H728X | 2021-03-16     | 623565              | cserra@riva.org                    |
| 3534 |        20 | Walter        | Galli      | 1988-03-23    | TDTVCI10F33R312A | 2020-05-07     | 623566              | sabino42@yahoo.com                 |
| 3536 |        64 | Albino        | Sanna      | 1974-10-31    | NKYBLE72C14N861O | 2020-02-28     | 623568              | piras.giuliano@gmail.com           |
| 3537 |         4 | Mercedes      | Ferraro    | 1980-08-21    | IELGDS25W02D644Z | 2019-07-10     | 623569              | alessio.serra@palumbo.it           |
| 3538 |        14 | Noel          | Piras      | 1980-09-17    | QTDEAR97Y98S277A | 2019-03-26     | 623570              | desantis.emilia@mariani.org        |
| 3539 |        56 | Giovanna      | Costa      | 1985-01-21    | PCBTYR93Z76N883E | 2018-11-13     | 623571              | fulvio26@mazza.org                 |
| 3540 |         4 | Elsa          | Sartori    | 1976-11-30    | EVWEFG15Q35K376I | 2021-05-12     | 623572              | laura.grassi@russo.it              |
| 3541 |        53 | Rosalino      | Romano     | 1974-12-09    | MHDNFJ85R53V439K | 2018-09-01     | 623573              | dorlando@galli.it                  |
| 3542 |        30 | Doriana       | De Angelis | 1979-06-20    | BQJAAU22G03B492E | 2019-10-20     | 623574              | neri.eustachio@yahoo.com           |
| 3543 |        45 | Muzio         | Esposito   | 1976-04-15    | ZHCWWW49E30T748W | 2019-03-17     | 623575              | deborah42@hotmail.com              |
| 3544 |        37 | Zelida        | Sorrentino | 1975-05-06    | UCFCFU33V91C995V | 2020-07-26     | 623576              | neri.benedetta@ricci.it            |
| 3545 |        45 | Rebecca       | Grassi     | 1972-01-31    | NKSLXA05W81F130O | 2021-03-19     | 623577              | kfabbri@benedetti.net              |
| 3546 |         2 | Nick          | Bellini    | 1987-12-08    | UZQJYD77K16N442P | 2018-10-27     | 623578              | scattaneo@barbieri.com             |
| 3548 |        59 | Gaetano       | Ferrara    | 1991-02-09    | TBWXNB56B44S160J | 2021-02-02     | 623580              | lguerra@fabbri.com                 |
| 3551 |        43 | Bibiana       | Costa      | 1977-07-29    | LHFXSG37A76I440G | 2020-03-07     | 623583              | manfredi71@gmail.com               |
| 3552 |        12 | Marino        | Ferrari    | 1988-12-12    | HLZIDQ70V08U733U | 2019-07-14     | 623584              | udesantis@hotmail.com              |
| 3553 |        28 | Max           | Ricci      | 1988-03-18    | CCBYYY73G56S637R | 2020-04-27     | 623585              | rosita99@libero.it                 |
| 3554 |        49 | Nathan        | Esposito   | 1972-04-02    | OBKUCN67G16F932J | 2020-08-02     | 623586              | ricci.flaviana@email.it            |
| 3555 |        52 | Penelope      | Ferrari    | 1984-11-04    | YLJWFW10Z04B739Y | 2020-09-12     | 623587              | egisto.morelli@fontana.org         |
| 3556 |        62 | Sasha         | Bianco     | 1978-05-29    | NMBVDT06L49Q187W | 2019-07-18     | 623588              | ysala@esposito.it                  |
| 3557 |        61 | Ippolito      | Ricci      | 1975-06-12    | BMAFGB51H35L096J | 2019-07-11     | 623589              | bellini.albino@yahoo.com           |
| 3558 |        34 | Karim         | Guerra     | 1981-04-21    | YIXJPI78O65M463M | 2020-02-02     | 623590              | omartinelli@rossi.com              |
| 3560 |        36 | Timoteo       | Sartori    | 1973-10-08    | ZAYYWY68X49Q980T | 2019-05-11     | 623592              | kgrassi@gmail.com                  |
| 3561 |        50 | Armando       | Orlando    | 1973-05-23    | VJLACJ80P29O434H | 2019-04-25     | 623593              | isabel20@libero.it                 |
| 3562 |        69 | Ursula        | Ricci      | 1972-10-16    | DBIQDI06A49Z728A | 2021-05-24     | 623594              | farina.enrico@pellegrini.com       |
| 3564 |        43 | Furio         | Pellegrini | 1988-05-01    | COLNZF38Q23P517R | 2019-09-17     | 623596              | obattaglia@ferri.com               |
| 3566 |        29 | Gerlando      | Pellegrini | 1976-01-18    | SSHDMG30W34Q355J | 2018-09-18     | 623598              | felicia.dangelo@email.it           |
| 3567 |        19 | Lidia         | Ferrara    | 1986-07-09    | LMIWJQ81X59E166H | 2020-11-07     | 623599              | romeo.gatti@costa.it               |
| 3568 |        50 | Cassiopea     | Esposito   | 1991-05-30    | MOUXVI72Z40I258U | 2021-01-06     | 623600              | grassi.rufo@yahoo.com              |
| 3569 |         9 | Alberto       | Bianchi    | 1982-09-17    | SIMINP87P29S556D | 2020-11-30     | 623601              | yrizzi@yahoo.com                   |
| 3570 |         5 | Ingrid        | Marini     | 1991-02-17    | ZPHZQZ68F05Q374X | 2018-07-28     | 623602              | serra.gerlando@caputo.com          |
| 3571 |         2 | Alighieri     | Galli      | 1977-02-05    | AQVUSO07Y43D461T | 2020-12-16     | 623603              | sebastian.bianco@longo.org         |
| 3573 |        14 | Morgana       | Sorrentino | 1983-05-09    | WEEITK62E68P101H | 2021-01-29     | 623605              | mariani.marcella@marchetti.org     |
| 3574 |        48 | Umberto       | Leone      | 1984-09-20    | YPTDQX55G16H113R | 2020-06-18     | 623606              | nunzia02@pellegrini.org            |
| 3576 |        56 | Felicia       | Rizzi      | 1974-12-14    | YMNQYV32J23H353V | 2020-09-21     | 623608              | arduino81@pellegrino.org           |
| 3577 |         9 | Gelsomina     | Pellegrini | 1973-12-18    | WQVKRN22I91F847U | 2020-06-03     | 623609              | giordano.ivonne@email.it           |
| 3578 |        16 | Jole          | Carbone    | 1983-05-07    | IGTXYD81W29F750R | 2018-10-04     | 623610              | jelena.pagano@yahoo.it             |
| 3579 |         1 | Battista      | Negri      | 1980-01-19    | BHCIHB75P18V308C | 2020-09-14     | 623611              | xcosta@libero.it                   |
| 3580 |        59 | Michele       | Marchetti  | 1984-03-27    | FMSYUT61M53X166V | 2021-02-21     | 623612              | damico.marcella@yahoo.com          |
| 3581 |        17 | Ciro          | Pagano     | 1982-08-22    | TAZATO92H68F365O | 2021-03-04     | 623613              | gaetano71@esposito.it              |
| 3582 |        67 | Trevis        | Gentile    | 1992-09-09    | MOMWCT19I78J543D | 2020-09-04     | 623614              | fatima24@email.it                  |
| 3583 |        60 | Patrizio      | Vitali     | 1986-12-19    | KROCFR88I79N818C | 2018-10-24     | 623615              | derosa.noah@email.it               |
| 3584 |        33 | Vera          | Bianco     | 1985-09-07    | YYQYRW25D28A357L | 2019-08-12     | 623616              | kayla75@russo.org                  |
| 3586 |        59 | Priamo        | Piras      | 1981-01-01    | NDLDUS34B65B809G | 2019-08-23     | 623618              | orfeo.farina@pagano.com            |
| 3587 |        19 | Pablo         | Sartori    | 1981-11-04    | EUJTVD91K94M276F | 2019-10-03     | 623619              | egisto.valentini@hotmail.com       |
| 3588 |        61 | Donatella     | Monti      | 1992-10-05    | MJDAOW33Y68F529G | 2020-06-06     | 623620              | ivonne.martino@email.it            |
| 3589 |        22 | Brigitta      | Benedetti  | 1984-01-23    | XCCFVQ72X49A272M | 2018-09-01     | 623621              | sartori.filomena@hotmail.com       |
| 3592 |        54 | Luigi         | Rossetti   | 1985-04-06    | IFEJFO28G15R725F | 2020-11-06     | 623624              | ppagano@rizzi.it                   |
| 3593 |        50 | Lamberto      | Neri       | 1975-11-27    | RAQFZB85H33G320O | 2021-05-01     | 623625              | diamante47@email.it                |
| 3594 |        33 | Miriam        | Parisi     | 1988-12-05    | MTOQPL70T90L262C | 2019-08-28     | 623626              | marianita85@yahoo.it               |
| 3595 |        72 | Matilde       | Sala       | 1979-03-02    | RVSZRH09V79T014O | 2019-03-22     | 623627              | zpellegrino@pagano.com             |
| 3596 |         6 | Deborah       | Piras      | 1981-03-17    | XJRZHI62W35X719G | 2019-02-21     | 623628              | cleopatra96@sala.it                |
| 3600 |        13 | Alan          | Bellini    | 1978-04-12    | PVJVTW73X33Q693A | 2019-02-12     | 623632              | ethan.ferraro@caruso.net           |
| 3601 |        22 | Ludovico      | De rosa    | 1980-05-18    | BZDCIN44Y59A122S | 2021-05-30     | 623633              | nestore68@yahoo.com                |
| 3602 |        37 | Pietro        | Giuliani   | 1971-12-05    | WXVVMP54Z28N758T | 2019-08-21     | 623634              | sdesantis@neri.it                  |
| 3604 |        38 | Morgana       | Donati     | 1988-06-28    | KHUVNJ28C51U650U | 2020-04-13     | 623636              | fabiano.santoro@yahoo.it           |
| 3607 |        49 | Dimitri       | Marini     | 1982-03-25    | BMEEHH60G80J569S | 2020-03-10     | 623639              | rpalumbo@longo.org                 |
| 3608 |        16 | Fatima        | Rizzi      | 1976-07-02    | WCULOE62B61Z464C | 2020-11-24     | 623640              | rosita.grassi@email.it             |
| 3609 |        11 | Max           | Milani     | 1980-07-19    | QVIGTX70E60L393Y | 2019-05-07     | 623641              | joey.martino@yahoo.com             |
| 3611 |        62 | Marina        | De Angelis | 1979-01-10    | JSJKVQ94I91W429O | 2018-12-25     | 623643              | bruno.olimpia@negri.com            |
| 3613 |         1 | Rosalba       | Grasso     | 1979-11-02    | LLBSQT61D30A846X | 2019-03-24     | 623645              | pmilani@yahoo.com                  |
| 3614 |        27 | Celeste       | Palumbo    | 1985-07-22    | GDUQDL69P72Y529O | 2018-12-10     | 623646              | bellini.giacinta@hotmail.com       |
| 3615 |        31 | Lucia         | Ferretti   | 1982-02-06    | XMKHDD35C25F607O | 2019-02-17     | 623647              | caligola.pellegrini@barone.org     |
| 3617 |         4 | Elda          | Gatti      | 1982-09-19    | JTXRPM28K27X860Y | 2020-01-14     | 623649              | battaglia.patrizio@gmail.com       |
| 3618 |        18 | Vitalba       | Rizzo      | 1973-11-29    | JAJIXT02F58R703X | 2020-01-01     | 623650              | bernardi.eufemia@yahoo.it          |
| 3621 |        71 | Damiano       | Martino    | 1975-08-17    | BOXCNS55B72R254U | 2018-12-08     | 623653              | ursula.ruggiero@pellegrini.it      |
| 3622 |        27 | Noah          | Rizzo      | 1974-06-01    | MVCCEE39W21W165K | 2020-05-08     | 623654              | negri.prisca@bianchi.com           |
| 3623 |        25 | Emilia        | Conte      | 1978-05-17    | VFRQBZ06A59N456X | 2019-03-13     | 623655              | vitale.bettino@email.it            |
| 3624 |        30 | Sibilla       | Grassi     | 1989-08-25    | KSJVUV15T73J565X | 2019-10-05     | 623656              | odone94@caputo.it                  |
| 3625 |        47 | Dylan         | Benedetti  | 1971-10-07    | CCIAOG04N72Z187M | 2019-03-14     | 623657              | filomena25@silvestri.com           |
| 3627 |        61 | Arduino       | Bianchi    | 1983-09-04    | TMUXZG15N68T239I | 2021-01-05     | 623659              | omarino@yahoo.com                  |
| 3628 |        18 | Danthon       | Rossetti   | 1972-07-22    | EFGMAV67D30G844L | 2018-09-26     | 623660              | pierfrancesco41@ricci.com          |
| 3630 |        52 | Rudy          | Grasso     | 1975-03-13    | LVCDSK82J80T461Q | 2020-01-31     | 623662              | esposito.damiana@libero.it         |
| 3631 |         2 | Vitalba       | De Angelis | 1983-09-07    | NAVYHD81C53T856C | 2020-09-01     | 623663              | gallo.jari@sorrentino.org          |
| 3632 |        35 | Cleopatra     | Greco      | 1975-02-25    | JDVFMV68G76E581L | 2020-12-11     | 623664              | martini.noemi@hotmail.com          |
| 3634 |        49 | Ulrico        | Marino     | 1991-10-16    | ITSFLF97Q97G949M | 2018-12-14     | 623666              | jvilla@battaglia.it                |
| 3635 |        24 | Rocco         | Vitale     | 1976-03-27    | IBBOPM91Y72Y727J | 2019-10-28     | 623667              | rosalino01@villa.com               |
| 3639 |        15 | Rita          | Silvestri  | 1975-01-28    | XORJSJ13H45J284F | 2019-10-16     | 623671              | artes64@libero.it                  |
| 3641 |        25 | Diana         | Barbieri   | 1984-12-23    | DHFYKC47A51K863M | 2021-05-24     | 623673              | ninfa22@libero.it                  |
| 3642 |        46 | Loretta       | Neri       | 1987-09-04    | ORDKGR84K60G329U | 2021-01-05     | 623674              | amerigo23@hotmail.com              |
| 3643 |         1 | Fortunata     | Bianchi    | 1990-05-02    | TXNPCJ26N37B979H | 2019-06-23     | 623675              | amato.evangelista@yahoo.com        |
| 3646 |        47 | Kayla         | Cattaneo   | 1980-11-04    | KBAKHN03A34Z445B | 2019-06-24     | 623678              | ddonati@basile.com                 |
| 3649 |         1 | Joshua        | Amato      | 1975-03-30    | NPMSIT57N36Y340N | 2018-08-11     | 623681              | russo.nunzia@esposito.com          |
| 3652 |        44 | Alessandro    | Pellegrino | 1986-08-29    | YSOWPP72S35S337B | 2020-02-17     | 623684              | kmessina@fabbri.it                 |
| 3653 |        50 | Isabel        | Caruso     | 1974-10-01    | YOCACX49P16P755D | 2019-12-16     | 623685              | artemide.negri@derosa.com          |
| 3654 |        67 | Penelope      | Farina     | 1985-03-17    | VDPQWV75X46W740A | 2020-05-17     | 623686              | uriva@yahoo.com                    |
| 3655 |        58 | Ivano         | Colombo    | 1989-08-17    | DFRWNW81D89M981L | 2019-08-30     | 623687              | qmessina@coppola.it                |
| 3656 |        69 | Isabel        | Ferri      | 1973-09-16    | ICWFPC66M46S508D | 2019-12-04     | 623688              | armando66@email.it                 |
| 3659 |        66 | Ruth          | Conti      | 1977-04-20    | GUMQFM97Q15B625Z | 2019-08-14     | 623691              | edamico@libero.it                  |
| 3660 |        44 | Furio         | Greco      | 1992-01-07    | KWSJCJ30W03E937B | 2019-05-06     | 623692              | ortensia.lombardo@gmail.com        |
| 3662 |        60 | Alan          | Giuliani   | 1981-04-09    | DUYPDG95O70J924E | 2018-07-23     | 623694              | jelena55@vitali.com                |
| 3663 |        48 | Flaviana      | Palmieri   | 1981-01-27    | OGVWLM13N73R562D | 2020-04-29     | 623695              | noah26@damico.com                  |
| 3665 |        40 | Romolo        | Villa      | 1981-10-12    | VBSILF89O60B559G | 2020-10-03     | 623697              | rizzi.loris@yahoo.com              |
| 3666 |        54 | Tancredi      | Grassi     | 1978-01-06    | NRFBUK99W34Y469C | 2019-02-15     | 623698              | sorrentino.ione@libero.it          |
| 3667 |        64 | Patrizio      | Conti      | 1972-01-24    | GIOHGQ95F75W541P | 2019-06-15     | 623699              | galli.zaccaria@bruno.com           |
| 3668 |        42 | Romeo         | Gallo      | 1972-08-06    | TYNFIM11G38Y929S | 2018-06-24     | 623700              | diana.pellegrini@damico.net        |
| 3670 |        27 | Rebecca       | Giordano   | 1992-06-18    | BAHYWW22X73E831K | 2021-06-04     | 623702              | vania96@yahoo.it                   |
| 3671 |        27 | Santo         | Parisi     | 1978-07-19    | WWEWJH47J92O154H | 2018-09-13     | 623703              | qgatti@bianco.org                  |
| 3672 |        36 | Abramo        | Caputo     | 1988-01-20    | BDTQDM12T33Y031J | 2021-01-11     | 623704              | rinaldi.furio@basile.com           |
| 3673 |         9 | Gastone       | Barbieri   | 1982-11-16    | SPRMTV04I73G531Q | 2018-07-24     | 623705              | lesposito@yahoo.it                 |
| 3675 |        50 | Leone         | De Angelis | 1971-08-22    | IQBPOT38I22A971S | 2018-09-19     | 623707              | eusebio.piras@bianchi.org          |
| 3679 |         7 | Miriana       | Orlando    | 1978-03-15    | OCWTUQ67F27K114D | 2019-09-04     | 623711              | genziana03@lombardi.com            |
| 3680 |        10 | Artemide      | Messina    | 1981-03-08    | LMYCVB62Y91J418B | 2018-07-08     | 623712              | isabel.testa@gmail.com             |
| 3681 |        51 | Joshua        | Lombardo   | 1975-04-13    | KALBHZ98I47H099U | 2019-04-26     | 623713              | emancini@bellini.com               |
| 3684 |        53 | Arduino       | Vitali     | 1984-07-14    | ULXQOZ69H19O089H | 2020-12-05     | 623716              | rossetti.giancarlo@libero.it       |
| 3685 |        42 | Morgana       | De Angelis | 1987-05-30    | SAMLZK51I93N340C | 2019-06-05     | 623717              | xcaputo@bianchi.it                 |
| 3686 |        71 | Armando       | Bruno      | 1974-06-23    | RWGRLM99Z19G883N | 2018-06-19     | 623718              | tolomeo.giordano@libero.it         |
| 3687 |        24 | Bibiana       | Galli      | 1990-03-14    | VYIICS84C64W295T | 2018-08-10     | 623719              | cattaneo.ausonio@yahoo.it          |
| 3688 |        60 | Rudy          | Orlando    | 1985-10-03    | FYHBUP91F12A894L | 2018-12-01     | 623720              | primo53@gmail.com                  |
| 3689 |        49 | Rocco         | Vitale     | 1982-07-07    | SXFXQN02M59O938X | 2019-05-11     | 623721              | desantis.loretta@gmail.com         |
| 3690 |        32 | Cira          | Mazza      | 1988-10-06    | TRMBRP51Y32G018D | 2020-08-21     | 623722              | npalmieri@yahoo.com                |
| 3691 |         8 | Diamante      | Ferrari    | 1977-08-09    | WHISAH02X00L588S | 2019-10-30     | 623723              | karim.grasso@grasso.org            |
| 3693 |        71 | Michele       | Villa      | 1976-10-03    | MVVWAW32S18U288Q | 2019-11-30     | 623725              | egidio.damico@amato.it             |
| 3694 |        48 | Patrizio      | Fiore      | 1991-04-28    | JPERFL63O22I950I | 2018-10-25     | 623726              | tconte@sorrentino.net              |
| 3695 |        34 | Assia         | Battaglia  | 1985-02-28    | IOLNTF81Y39R784C | 2020-05-13     | 623727              | derosa.lia@gmail.com               |
| 3696 |        44 | Rosita        | Barbieri   | 1973-01-20    | DTSVBI18W22L956U | 2019-05-28     | 623728              | rneri@vitale.it                    |
| 3697 |        67 | Flavio        | Vitali     | 1991-10-29    | CXRTRL35Q76A019G | 2021-05-02     | 623729              | costantino88@gmail.com             |
| 3698 |        51 | Vienna        | Sorrentino | 1975-04-24    | KABWWF51Q92T710B | 2018-11-27     | 623730              | cleros70@yahoo.com                 |
| 3699 |        47 | Nayade        | Valentini  | 1981-06-24    | DFARFP19M49I178A | 2020-12-26     | 623731              | amato.marcella@libero.it           |
| 3700 |        48 | Vitalba       | Pellegrino | 1990-10-16    | YHCHKS97R47J257I | 2021-01-26     | 623732              | tricci@ruggiero.com                |
| 3703 |        51 | Helga         | Lombardo   | 1976-12-01    | EJKRFS82U69R182L | 2018-08-26     | 623735              | dangelo.rebecca@libero.it          |
| 3706 |        64 | Lazzaro       | Rossetti   | 1980-06-05    | WSFFBR14Y48B469P | 2019-08-27     | 623738              | jarno.silvestri@hotmail.com        |
| 3710 |        46 | Irene         | Lombardo   | 1984-03-17    | HNSXDE74M82R895W | 2019-09-03     | 623742              | zmartinelli@vitale.it              |
| 3711 |        41 | Irene         | Esposito   | 1985-03-04    | OSSWCJ24F52I469O | 2020-11-21     | 623743              | sarita.damico@gmail.com            |
| 3712 |        18 | Tommaso       | Martini    | 1988-11-01    | YUMVXR33Z44O206J | 2018-06-17     | 623744              | barbieri.ludovico@gmail.com        |
| 3715 |        72 | Sue ellen     | Milani     | 1975-05-02    | HWEMEF43K55F712Z | 2018-10-02     | 623747              | jderosa@email.it                   |
| 3716 |        25 | Nico          | De Santis  | 1971-10-31    | KDRWUM44H88L259T | 2018-12-20     | 623748              | yferraro@hotmail.com               |
| 3717 |        36 | Cesidia       | Bellini    | 1984-06-28    | MCXSSG84K26D306B | 2020-05-23     | 623749              | mercedes78@pellegrino.it           |
| 3718 |        20 | Irene         | Morelli    | 1990-08-26    | XKKBWO51D05J706U | 2020-11-17     | 623750              | ferretti.gilda@bianco.org          |
| 3719 |        57 | Rosalba       | Gallo      | 1977-12-11    | XCJNOB77K35F096P | 2019-07-07     | 623751              | secondo07@barbieri.org             |
| 3720 |        20 | Liborio       | Caputo     | 1981-05-10    | YZWWYG24B11M369L | 2020-07-10     | 623752              | martino.loredana@hotmail.com       |
| 3723 |         7 | Kai           | Carbone    | 1992-12-19    | MARAOY52N05R598T | 2020-10-28     | 623755              | cguerra@hotmail.com                |
| 3724 |        49 | Giovanna      | Sorrentino | 1982-03-30    | KONLSM89A58U677I | 2020-09-04     | 623756              | felicia88@cattaneo.com             |
| 3725 |        75 | Rudy          | Basile     | 1984-10-18    | ZRUXCO27L62A564E | 2020-02-07     | 623757              | omar.mazza@rinaldi.com             |
| 3728 |        10 | Giacinto      | Bruno      | 1972-05-24    | NBTVPU47O85W020M | 2018-09-01     | 623760              | diana84@email.it                   |
| 3729 |        47 | Maggiore      | Messina    | 1992-06-02    | UUYYHA32K03L995Y | 2019-12-05     | 623761              | dsala@giordano.it                  |
| 3732 |        62 | Violante      | Damico     | 1977-09-04    | XRRTCS64O59X183R | 2019-02-15     | 623764              | kristel99@gmail.com                |
| 3733 |        46 | Soriana       | Bianco     | 1989-10-19    | TXZDXG96X86F211L | 2018-12-16     | 623765              | grassi.gerlando@gmail.com          |
| 3734 |        63 | Marianita     | Marini     | 1988-07-19    | QJWISX42I86H980I | 2019-07-16     | 623766              | jlombardi@lombardo.net             |
| 3736 |        56 | Amedeo        | Ferrari    | 1975-05-07    | WZSGKC29Y12D390H | 2019-07-03     | 623768              | dgatti@esposito.com                |
| 3739 |        69 | Fatima        | Leone      | 1977-09-21    | VCWTBJ95O09K446N | 2021-02-25     | 623771              | samira62@bernardi.net              |
| 3740 |        45 | Maria         | D'angelo   | 1972-11-11    | HCQQRR90W30Q868Q | 2019-12-06     | 623772              | concetta35@gmail.com               |
| 3742 |        31 | Emilia        | Rinaldi    | 1974-01-16    | JWVEEX86N22V128Q | 2020-03-18     | 623774              | fabio.gatti@hotmail.com            |
| 3746 |         8 | Nico          | Sala       | 1972-01-10    | DRDIDR05N66U284T | 2019-04-02     | 623778              | samuel.pagano@email.it             |
| 3747 |        25 | Marzio        | Battaglia  | 1977-07-27    | OXRAFW37D67E113P | 2019-08-22     | 623779              | wrossetti@hotmail.com              |
| 3748 |         8 | Giorgio       | Montanari  | 1974-02-07    | MCEBBL54C93S626L | 2019-03-10     | 623780              | sdesantis@ferretti.com             |
| 3750 |        55 | Joshua        | Martinelli | 1972-07-20    | DDIXXT53L45F292A | 2018-07-02     | 623782              | harry23@yahoo.com                  |
| 3751 |        25 | Sabatino      | Messina    | 1977-05-19    | WQSGVR90X43K715R | 2021-04-26     | 623783              | marzio.giuliani@yahoo.com          |
| 3752 |        45 | Giovanna      | De luca    | 1988-02-07    | QYTUYI13D08R718L | 2020-10-26     | 623784              | jmazza@gmail.com                   |
| 3753 |         6 | Ettore        | Guerra     | 1972-10-14    | ZQSINM79Q70B258Q | 2020-02-05     | 623785              | bferretti@yahoo.com                |
| 3754 |        22 | Terzo         | De luca    | 1980-07-02    | ZXNKYF97O72A130Z | 2018-11-13     | 623786              | obasile@negri.net                  |
| 3756 |        37 | Zelida        | Palumbo    | 1990-12-03    | YIBBLF29U85I393H | 2019-04-02     | 623788              | ovitale@gmail.com                  |
| 3757 |        22 | Bibiana       | Gallo      | 1991-05-30    | WTERLV47E52Y720F | 2019-05-19     | 623789              | mpiras@yahoo.it                    |
| 3758 |        16 | Sue ellen     | Carbone    | 1978-01-03    | BYRWNV32U50A556A | 2020-09-17     | 623790              | miriam46@yahoo.it                  |
| 3759 |        48 | Vera          | D'angelo   | 1973-12-29    | EVCHON83J23Z005V | 2020-03-23     | 623791              | rizzi.mirco@yahoo.com              |
| 3760 |        26 | Bibiana       | Neri       | 1990-08-28    | FZGUSZ40R71E465J | 2018-12-15     | 623792              | gallo.lorenzo@yahoo.com            |
| 3766 |         4 | Manuele       | Riva       | 1985-09-14    | ELDXTH94K34E111P | 2018-09-07     | 623798              | sirio.sartori@hotmail.com          |
| 3767 |        18 | Ivonne        | Rossi      | 1972-02-22    | ESIIUC34F58U068C | 2018-08-13     | 623799              | akira.moretti@greco.net            |
| 3770 |         8 | Caligola      | Guerra     | 1990-03-07    | BSVEVY06Q04K151O | 2021-03-20     | 623802              | nsanna@email.it                    |
| 3771 |        14 | Isabel        | Martini    | 1985-03-23    | TCWKWQ24E54N035T | 2020-07-28     | 623803              | shaira.leone@gmail.com             |
| 3772 |        60 | Eustachio     | Valentini  | 1989-10-31    | WABIMQ28H48Y596N | 2019-01-27     | 623804              | uorlando@amato.it                  |
| 3774 |        14 | Kai           | Donati     | 1992-07-03    | PXIMAE30I20P794L | 2019-11-28     | 623806              | soriana41@amato.com                |
| 3775 |        29 | Nestore       | Sorrentino | 1992-08-27    | NJATPC50Z80O167B | 2019-07-18     | 623807              | xrizzi@yahoo.com                   |
| 3777 |         6 | Noemi         | Ricci      | 1987-01-21    | ZTIXKA86C97W448V | 2018-10-11     | 623809              | romano.oretta@testa.it             |
| 3778 |        60 | Ausonio       | Ricci      | 1980-05-19    | RKEZYN76P61F489U | 2020-08-05     | 623810              | nmancini@yahoo.it                  |
| 3779 |        46 | Rosalino      | Morelli    | 1980-11-01    | YWQTHQ72S26I664K | 2018-11-29     | 623811              | rufo99@yahoo.com                   |
| 3780 |        38 | Augusto       | Conte      | 1988-12-11    | XJRDNP46L87K502U | 2020-11-02     | 623812              | moretti.sirio@yahoo.com            |
| 3782 |        58 | Amos          | Negri      | 1992-03-29    | EHSRLE96Y01N132M | 2020-07-31     | 623814              | giobbe.ferretti@hotmail.com        |
| 3783 |        39 | Gianleonardo  | Conti      | 1987-07-17    | FDCIKW32O14H001P | 2020-09-29     | 623815              | mmariani@libero.it                 |
| 3784 |        50 | Marieva       | Morelli    | 1980-05-16    | QYZBHU98X29V176A | 2020-10-14     | 623816              | sarita36@costa.it                  |
| 3785 |        48 | Assia         | Costa      | 1985-12-11    | DKEBZB98G29M643E | 2019-09-12     | 623817              | aferraro@conte.it                  |
| 3787 |        24 | Violante      | Pellegrini | 1988-03-15    | XHTQGW27J52E177Z | 2019-02-16     | 623819              | jbattaglia@marini.net              |
| 3788 |        20 | Osvaldo       | Palumbo    | 1991-04-01    | JGSJQK43X19E522H | 2020-03-26     | 623820              | rita56@colombo.net                 |
| 3789 |        55 | Jarno         | Fabbri     | 1974-07-10    | NHNDDK33J58N596G | 2019-01-24     | 623821              | cristyn.derosa@email.it            |
| 3790 |        17 | Irene         | Farina     | 1989-03-31    | PVHWDS75R57J844P | 2019-11-10     | 623822              | penelope.cattaneo@hotmail.com      |
| 3791 |        31 | Kayla         | Bernardi   | 1986-03-07    | HPBVLU93I16C690C | 2020-05-02     | 623823              | arturo54@sartori.com               |
| 3792 |        53 | Marina        | Martino    | 1992-08-06    | LWNASX06V45Y584S | 2019-05-25     | 623824              | nunzia89@monti.it                  |
| 3794 |        16 | Dimitri       | Ferrara    | 1986-06-07    | SICJJN05W38L549Y | 2019-04-22     | 623826              | emanuel.farina@colombo.com         |
| 3795 |        28 | Noel          | Caruso     | 1976-10-22    | TYQXJL98O00R490M | 2019-09-20     | 623827              | negri.monia@sorrentino.org         |
| 3796 |        25 | Pablo         | Rizzi      | 1977-02-17    | XOGRWP35A22T103Y | 2018-06-20     | 623828              | romolo57@pellegrino.net            |
| 3797 |        60 | Giacinto      | Mariani    | 1978-05-08    | TEYRAE65N62D361W | 2020-09-17     | 623829              | mcaputo@messina.it                 |
| 3798 |        61 | Guido         | Ferrara    | 1989-12-25    | TQUWLP40H77A143K | 2020-06-12     | 623830              | benedetti.alessandro@villa.it      |
| 3802 |        20 | Serse         | Sorrentino | 1985-09-03    | FBQMZO90B88Y550O | 2021-04-06     | 623834              | costantini.enrica@costa.com        |
| 3803 |        17 | Marina        | Valentini  | 1978-12-30    | ZKLBSZ55J63O401F | 2021-01-02     | 623835              | osala@libero.it                    |
| 3804 |        63 | Ninfa         | Vitali     | 1971-07-08    | OALLMO10Q09Q491I | 2020-09-28     | 623836              | mariani.trevis@yahoo.it            |
| 3805 |        32 | Gastone       | Grassi     | 1975-03-22    | ZZMGZI93Y12E210N | 2019-12-18     | 623837              | ferdinando.longo@sanna.net         |
| 3807 |        72 | Jole          | Longo      | 1977-10-09    | WFFAMI46D05N246W | 2020-04-09     | 623839              | ebruno@damico.it                   |
| 3809 |        19 | Ethan         | Russo      | 1977-04-20    | QDJHJD40T63P173S | 2019-11-06     | 623841              | damico.kayla@gmail.com             |
| 3810 |        73 | Antimo        | Gatti      | 1985-09-14    | VMBWHW51Q84K207O | 2018-07-30     | 623842              | sgalli@email.it                    |
| 3813 |         6 | Sabatino      | Rinaldi    | 1978-03-05    | ODWCNR58C00I495C | 2019-07-08     | 623845              | tpiras@yahoo.com                   |
| 3814 |        52 | Danthon       | De luca    | 1984-05-21    | YGYOKS39E46Z521I | 2021-05-04     | 623846              | elga29@negri.it                    |
| 3817 |        11 | Isabel        | Fontana    | 1979-03-23    | AGVLPZ04Z88L278S | 2019-01-09     | 623849              | pellegrini.sueellen@gmail.com      |
| 3819 |        29 | Nestore       | Gentile    | 1991-06-04    | ODZKBQ50I14J123D | 2018-11-23     | 623851              | barbieri.loredana@vitale.com       |
| 3820 |        13 | Hector        | Caputo     | 1974-04-19    | YAIHKO82T58T518G | 2018-07-17     | 623852              | rbellini@libero.it                 |
| 3822 |        11 | Cleopatra     | Morelli    | 1977-09-15    | BQVLXW40N55G931Y | 2021-05-29     | 623854              | lidia42@santoro.it                 |
| 3823 |        60 | Costanzo      | Lombardi   | 1985-06-28    | BISSHH59B13Q656U | 2020-05-01     | 623855              | fdeluca@bellini.it                 |
| 3824 |        32 | Jelena        | Gatti      | 1976-06-29    | NGAIMR67G10R583K | 2018-09-15     | 623856              | bgiuliani@libero.it                |
| 3827 |        43 | Tancredi      | Longo      | 1989-04-03    | KZFSLF29A23Q803K | 2019-01-16     | 623859              | parisi.michael@morelli.com         |
| 3829 |        18 | Marianita     | Coppola    | 1975-10-29    | AWKVQK94N46C427W | 2020-07-31     | 623861              | esposito.giancarlo@yahoo.it        |
| 3832 |         7 | Mariano       | Gallo      | 1987-05-08    | DRENMJ19F89A697L | 2020-10-22     | 623864              | edvige75@fabbri.com                |
| 3833 |        19 | Piererminio   | Montanari  | 1991-05-02    | XBGCVU34B94O203K | 2019-05-17     | 623865              | tcosta@yahoo.com                   |
| 3834 |        16 | Elsa          | Milani     | 1977-10-16    | KNMPKH75S46H634D | 2019-02-26     | 623866              | siro16@libero.it                   |
| 3835 |        37 | Ileana        | Ricci      | 1990-03-17    | OPCAIF74A88N272E | 2020-07-21     | 623867              | timoteo67@basile.com               |
| 3836 |         7 | Cosetta       | Gallo      | 1984-02-22    | UAVYAV15A67B212B | 2019-07-30     | 623868              | barone.eufemia@bianco.net          |
| 3838 |        40 | Evangelista   | Lombardi   | 1989-08-10    | VKPOTB27Z78M450T | 2021-04-02     | 623870              | guendalina.palumbo@colombo.it      |
| 3839 |         8 | Silverio      | Santoro    | 1982-04-28    | BPEIAL70O06Z134H | 2020-01-29     | 623871              | battaglia.laerte@ferraro.it        |
| 3840 |        27 | Giacobbe      | Donati     | 1982-04-28    | WNMQFH89Z32M198P | 2020-01-03     | 623872              | riva.nick@hotmail.com              |
| 3841 |        24 | Ausonio       | Sala       | 1990-02-23    | DPCTHN72Q38Q077G | 2019-10-18     | 623873              | arcibaldo.esposito@hotmail.com     |
| 3842 |        55 | Nicoletta     | Morelli    | 1983-01-29    | TDEPOJ57Z79C683Q | 2019-05-26     | 623874              | xmartino@montanari.com             |
| 3843 |        56 | Dylan         | Conte      | 1992-01-23    | AICPIT91J18K256V | 2020-01-28     | 623875              | ivonne.vitali@monti.org            |
| 3845 |        23 | Celeste       | Costa      | 1980-10-31    | ENTHNY28X71M380X | 2019-07-16     | 623877              | eriberto.vitale@pellegrini.it      |
| 3846 |         8 | Damiana       | Fabbri     | 1974-02-08    | WPHWGO44A71W169X | 2019-01-23     | 623878              | caligola.serra@palmieri.org        |
| 3848 |        75 | Priamo        | Vitale     | 1989-09-05    | CGRHDW44H68O105R | 2020-11-24     | 623880              | leone.alighiero@colombo.it         |
| 3851 |        30 | Carmelo       | Barone     | 1981-12-01    | YYEVTY80E72W193N | 2021-01-13     | 623883              | mguerra@lombardi.org               |
| 3852 |        48 | Marieva       | Silvestri  | 1987-11-18    | BHZGAW27G25T080T | 2021-04-24     | 623884              | ocosta@ricci.it                    |
| 3854 |        11 | Nunzia        | Fontana    | 1978-12-03    | KQTJIU91B53R662N | 2019-01-24     | 623886              | lidia.desantis@rizzo.net           |
| 3855 |        11 | Vitalba       | Marini     | 1986-02-13    | CMCFSB42H29M694O | 2019-08-08     | 623887              | rossi.soriana@yahoo.com            |
| 3856 |        74 | Luna          | Parisi     | 1978-03-07    | ARIKLO30Z00U924E | 2019-07-09     | 623888              | ycoppola@farina.it                 |
| 3857 |        73 | Audenico      | Conti      | 1974-05-16    | SAOHOH77A69H358S | 2019-08-15     | 623889              | cpiras@messina.it                  |
| 3858 |        15 | Xavier        | De luca    | 1981-10-11    | YNDKLC63X23D786U | 2018-08-30     | 623890              | ricci.giulietta@vitale.it          |
| 3859 |        57 | Nayade        | Colombo    | 1976-05-05    | GGKBBP14A50R566W | 2019-02-22     | 623891              | arturo.colombo@libero.it           |
| 3862 |         3 | Ercole        | Bruno      | 1982-12-04    | FBSFPR84U29C212C | 2019-12-25     | 623894              | martino.demi@sartori.com           |
| 3863 |        42 | Arduino       | Milani     | 1988-04-03    | IYOKMZ79G10X233S | 2020-10-13     | 623895              | marvin.fontana@marchetti.it        |
| 3864 |        46 | Piersilvio    | Donati     | 1974-05-13    | BWRUJM15O13P014R | 2021-05-29     | 623896              | vbernardi@martino.com              |
| 3865 |        53 | Romeo         | Parisi     | 1992-09-24    | DZZBLP33Q36H802P | 2020-10-16     | 623897              | cira76@libero.it                   |
| 3866 |        14 | Abramo        | Fabbri     | 1972-06-10    | CQITTL83Y18D507G | 2019-01-11     | 623898              | bferraro@valentini.it              |
| 3868 |        69 | Clea          | Bellini    | 1990-05-30    | PDGXXN04L56G048C | 2021-02-21     | 623900              | yago.moretti@yahoo.it              |
| 3869 |        31 | Cleopatra     | Parisi     | 1990-01-14    | GQYAQJ97I01U403H | 2018-08-10     | 623901              | mdamico@yahoo.com                  |
| 3871 |        40 | Gaetano       | Barone     | 1990-01-31    | ZRRAGH96T10Z527L | 2019-12-09     | 623903              | tbianco@yahoo.it                   |
| 3872 |        71 | Damiano       | Sartori    | 1980-06-16    | PTSRVF29E02O574R | 2020-05-15     | 623904              | ninfa.amato@yahoo.com              |
| 3873 |        11 | Manfredi      | Bruno      | 1977-11-09    | HZINEM43K63V399R | 2019-12-15     | 623905              | lombardo.morgana@yahoo.com         |
| 3874 |        54 | Egisto        | Bernardi   | 1972-04-21    | VTGTBZ01W84Q215E | 2020-07-28     | 623906              | damico.benedetta@fabbri.it         |
| 3875 |        39 | Nayade        | Ricci      | 1987-04-25    | ZGIAQV48R75D230R | 2019-08-08     | 623907              | martino.cristyn@email.it           |
| 3876 |        27 | Elsa          | Damico     | 1981-01-17    | JXXYYN61L10S400M | 2019-01-26     | 623908              | miriana32@grasso.it                |
| 3877 |        38 | Felicia       | Sanna      | 1986-05-17    | GXZYJB48E04L427A | 2020-05-21     | 623909              | noel.bruno@email.it                |
| 3878 |        72 | Leone         | Ferraro    | 1987-12-21    | DXRIZK29U74K273T | 2019-12-31     | 623910              | yrizzo@gmail.com                   |
| 3879 |        18 | Omar          | Bernardi   | 1984-06-25    | ZIHPCJ36Z08S100P | 2021-06-02     | 623911              | teseo.longo@yahoo.com              |
| 3880 |        15 | Miriam        | Rossetti   | 1982-02-03    | SVJFMK83N79W622N | 2019-05-09     | 623912              | marvin54@yahoo.com                 |
| 3881 |        75 | Donatella     | Rinaldi    | 1984-08-03    | CSSYJO39J85R760Z | 2018-07-29     | 623913              | damico.artemide@carbone.net        |
| 3882 |        48 | Gavino        | Conte      | 1990-08-19    | QVPHYU50U61B338H | 2020-01-08     | 623914              | lcosta@derosa.net                  |
| 3883 |        25 | Antonio       | Bianco     | 1983-01-04    | UTGINK37E14U830H | 2018-06-22     | 623915              | pbianco@bianchi.com                |
| 3884 |        67 | Naomi         | Palumbo    | 1987-09-28    | EOGAVA93A08P061N | 2020-03-23     | 623916              | giuliani.ortensia@gmail.com        |
| 3886 |        48 | Danuta        | Montanari  | 1989-02-27    | RYJTSV82B18M036C | 2018-12-22     | 623918              | fernando.messina@email.it          |
| 3887 |        37 | Alessio       | Villa      | 1986-02-12    | SKWXEL39X84K685F | 2019-07-05     | 623919              | nleone@libero.it                   |
| 3888 |        37 | Prisca        | Pellegrino | 1987-11-06    | PWWYXS18F76S804C | 2021-03-17     | 623920              | elga91@pellegrino.it               |
| 3889 |        32 | Rosita        | Caruso     | 1988-11-06    | EANJNU24X92N837J | 2018-10-09     | 623921              | rudy88@yahoo.it                    |
| 3892 |        52 | Renzo         | Mazza      | 1971-11-18    | CCCFVL01Y62Y740F | 2021-05-20     | 623924              | ndeangelis@hotmail.com             |
| 3894 |        71 | Egisto        | Longo      | 1990-07-18    | QOJPWF79J43U384H | 2021-04-28     | 623926              | fatima04@hotmail.com               |
| 3895 |         7 | Doriana       | Gallo      | 1972-06-30    | RHHCST81D03E284Z | 2019-06-01     | 623927              | zaccaria54@sorrentino.it           |
| 3896 |        21 | Selvaggia     | Gatti      | 1976-01-07    | SFZHBN62I01W486N | 2018-09-15     | 623928              | domiziano.ferrari@valentini.net    |
| 3897 |         1 | Maika         | Fontana    | 1978-03-24    | FFWHRO67L88X203H | 2020-10-14     | 623929              | ninfa.bellini@gmail.com            |
| 3898 |        41 | Timothy       | Fontana    | 1987-01-27    | EXFGEG25C94O533K | 2020-11-25     | 623930              | xlombardo@guerra.com               |
| 3899 |        73 | Giorgio       | Rossetti   | 1992-10-03    | GKDXKB29S79D194A | 2020-11-11     | 623931              | kcostantini@marini.it              |
| 3900 |        66 | Flaviana      | Rossi      | 1984-03-23    | KZCSUA06V62G607G | 2019-03-23     | 623932              | guerra.pablo@ferri.it              |
| 3903 |        69 | Iacopo        | Rizzo      | 1991-12-19    | ZBZCBI99W47T452S | 2018-12-15     | 623935              | rizzo.nayade@hotmail.com           |
| 3904 |        63 | Enrica        | Grasso     | 1984-05-13    | IXBGQF88I12R419T | 2019-09-15     | 623936              | luigi29@libero.it                  |
| 3906 |        49 | Filomena      | Caruso     | 1973-08-18    | NEQDNW43Q92G660H | 2020-10-19     | 623938              | fferretti@gmail.com                |
| 3907 |        54 | Benedetta     | Leone      | 1983-07-07    | ETPQWE13I05F209A | 2020-02-15     | 623939              | soriana82@yahoo.it                 |
| 3909 |        26 | Amedeo        | Lombardi   | 1978-11-05    | OSFXRC81W01S314A | 2021-05-26     | 623941              | carlo66@dangelo.com                |
| 3910 |        63 | Edvige        | Sorrentino | 1977-10-30    | ZTRJYO21W04I692B | 2020-10-24     | 623942              | mietta89@bruno.it                  |
| 3911 |        49 | Ruth          | Messina    | 1988-12-10    | ECWRDA57U84E368R | 2021-03-04     | 623943              | tpellegrini@ferretti.it            |
| 3912 |        22 | Davis         | Marchetti  | 1977-11-23    | OBOBIS62C90Q581R | 2020-10-05     | 623944              | ibruno@ferrara.it                  |
| 3913 |        65 | Tosca         | Piras      | 1979-12-12    | JMNYWQ85C30K327U | 2021-01-14     | 623945              | nbarone@yahoo.com                  |
| 3914 |        22 | Antimo        | D'amico    | 1973-02-02    | FXGBIL31F09J431R | 2019-10-28     | 623946              | xrizzi@gmail.com                   |
| 3915 |        17 | Ortensia      | Sartori    | 1980-02-21    | QHSPHY54J97X435H | 2021-01-04     | 623947              | tdangelo@yahoo.it                  |
| 3917 |        39 | Gianleonardo  | Morelli    | 1972-12-01    | CBSPAP12T08U533H | 2019-06-07     | 623949              | ferrara.marino@yahoo.com           |
| 3918 |        55 | Claudia       | Galli      | 1987-09-25    | GVWXYU95S35C220R | 2019-11-17     | 623950              | vgatti@email.it                    |
| 3920 |        48 | Damiana       | Marchetti  | 1989-04-08    | UNODMM20I45B527Y | 2020-01-31     | 623952              | kcosta@carbone.com                 |
| 3921 |         9 | Edilio        | Greco      | 1988-08-07    | WSKYHJ49W16D851D | 2019-01-04     | 623953              | santo45@neri.com                   |
| 3922 |        75 | Fortunata     | Leone      | 1981-05-04    | QWYCTO45F43W132W | 2020-06-23     | 623954              | oricci@hotmail.com                 |
| 3924 |        44 | Diana         | Caputo     | 1991-06-11    | WJRZUZ41M97S569Q | 2021-02-23     | 623956              | qrusso@ferretti.com                |
| 3925 |        56 | Fulvio        | Bellini    | 1987-01-21    | WGZBCH22U78F291N | 2020-09-03     | 623957              | giorgio56@leone.com                |
| 3926 |        66 | Ruth          | Milani     | 1981-06-08    | KMNHGM18I77S947S | 2018-12-25     | 623958              | evita.ferretti@gmail.com           |
| 3929 |        58 | Lia           | Ferrari    | 1981-01-11    | RZSDEG28J59O629D | 2019-12-18     | 623961              | ferrari.akira@moretti.com          |
| 3930 |        36 | Ivonne        | Moretti    | 1977-09-27    | LXASQM31Z27N311K | 2020-02-16     | 623962              | bianchi.giulio@email.it            |
| 3931 |        19 | Eufemia       | Bianchi    | 1986-11-26    | HHNAIU18J51D087T | 2019-10-05     | 623963              | zaccaria61@yahoo.com               |
| 3932 |        65 | Donatella     | Guerra     | 1991-06-09    | NNXKKW86S41Q990Y | 2021-02-21     | 623964              | bvitali@email.it                   |
| 3934 |        36 | Bibiana       | Lombardo   | 1981-08-14    | BPHHVE47J09N423C | 2019-08-07     | 623966              | piras.sibilla@libero.it            |
| 3935 |        26 | Maruska       | Rinaldi    | 1992-09-04    | LDZZWE61I95R768R | 2019-12-06     | 623967              | bruno.caio@romano.it               |
| 3936 |        59 | Rebecca       | Colombo    | 1978-08-06    | NDVYZS10V19L635N | 2020-07-29     | 623968              | italo38@santoro.it                 |
| 3937 |        37 | Enrico        | Coppola    | 1988-02-25    | PCVCNI37K98B017I | 2020-11-04     | 623969              | tosca67@riva.it                    |
| 3938 |        47 | Elda          | Ferri      | 1980-01-07    | ZIULKN77D14Q714C | 2020-07-12     | 623970              | ippolito.deluca@bruno.com          |
| 3941 |        72 | Alan          | Fiore      | 1987-09-03    | ODYUTR95O52X858J | 2020-08-29     | 623973              | damico.loretta@yahoo.com           |
| 3943 |        26 | Brigitta      | Rinaldi    | 1979-04-22    | XISBGN11C77P599N | 2020-09-05     | 623975              | vcolombo@hotmail.com               |
| 3944 |        25 | Pablo         | Galli      | 1976-07-10    | KKXQZB09Y79C004A | 2018-07-21     | 623976              | fatima55@mancini.com               |
| 3945 |        39 | Marianita     | Vitali     | 1974-12-14    | MLGCCF65R90S616B | 2018-12-21     | 623977              | odone.moretti@libero.it            |
| 3946 |        18 | Bacchisio     | Barone     | 1992-08-18    | HYPIFY35R37G494P | 2018-10-29     | 623978              | fabio.damico@marchetti.org         |
| 3947 |         2 | Doriana       | Rinaldi    | 1989-09-01    | MBXDMM87P68O608E | 2018-07-11     | 623979              | mauro.gentile@ruggiero.com         |
| 3948 |        38 | Donatella     | Galli      | 1991-02-18    | AQGVCE50Q88G548Q | 2020-10-09     | 623980              | farina.penelope@ruggiero.net       |
| 3949 |         8 | Mercedes      | Rinaldi    | 1986-11-10    | JXSXKF19C80J809Q | 2019-12-12     | 623981              | morgana.bianchi@email.it           |
| 3950 |        70 | Cosetta       | Ferrari    | 1976-03-14    | VHCXAS15L65N460A | 2020-01-12     | 623982              | olimpia02@grasso.it                |
| 3951 |        56 | Cira          | De Santis  | 1974-05-25    | IQCEAP78D27I715V | 2020-10-01     | 623983              | mariani.edvige@martinelli.com      |
| 3954 |         9 | Loredana      | Palmieri   | 1983-05-27    | UWZZEK88N28C833K | 2018-11-20     | 623986              | eruggiero@martini.org              |
| 3955 |        27 | Alessio       | Valentini  | 1983-04-20    | UBOHOS54J99M441H | 2019-06-26     | 623987              | maika.ruggiero@fiore.it            |
| 3956 |        64 | Enzo          | Conti      | 1989-05-20    | TVMILU64O51S210V | 2020-08-10     | 623988              | derosa.loretta@yahoo.com           |
| 3957 |        38 | Samira        | Martinelli | 1986-07-20    | EDPAWS84R19C398D | 2019-10-08     | 623989              | timoteo53@email.it                 |
| 3958 |         8 | Celeste       | Barone     | 1980-09-21    | LNRCYD64H99W668P | 2019-05-03     | 623990              | xruggiero@pellegrini.it            |
| 3960 |        16 | Gerlando      | Donati     | 1991-03-17    | ISSEDY86Y62Y852M | 2018-09-18     | 623992              | lucrezia76@greco.it                |
| 3962 |        48 | Aroldo        | Fontana    | 1971-12-07    | ZVWSBR11P93P713W | 2019-12-16     | 623994              | gfontana@gentile.it                |
| 3963 |        59 | Lino          | Giordano   | 1988-11-10    | PIQNFY50S11Y663J | 2018-12-01     | 623995              | rizzo.nadir@pellegrini.com         |
| 3965 |        45 | Quarto        | Bianco     | 1975-05-10    | RFHAFZ16A03D968U | 2019-09-26     | 623997              | cassiopea.vitali@russo.com         |
| 3967 |        69 | Carmela       | Donati     | 1992-07-21    | ICEMWS60J97E298Z | 2018-06-27     | 623999              | ione17@hotmail.com                 |
| 3969 |        13 | Genziana      | Amato      | 1978-05-05    | WJCHWP18F92E252N | 2019-07-08     | 624001              | dante.grassi@pellegrini.org        |
| 3971 |        67 | Emilia        | Coppola    | 1985-12-27    | AZKLDB69K78X455A | 2019-12-18     | 624003              | zbattaglia@yahoo.it                |
| 3972 |        25 | Giacinto      | Pellegrino | 1983-07-14    | WVBWQL81A40I061C | 2020-08-11     | 624004              | sorrentino.ruth@ferrara.it         |
| 3973 |        24 | Maristella    | Valentini  | 1980-04-17    | TFXJRB87S93Z682O | 2019-09-18     | 624005              | urizzo@yahoo.it                    |
| 3974 |        35 | Piererminio   | Sanna      | 1984-07-26    | XQZMUN08M52F938D | 2018-11-18     | 624006              | mietta88@email.it                  |
| 3975 |        16 | Carlo         | Rinaldi    | 1990-10-10    | PFKGKF99F49G340R | 2020-10-26     | 624007              | felicia14@gatti.it                 |
| 3976 |        41 | Rosalba       | Russo      | 1986-12-23    | YUVJTX02P56M432Y | 2019-06-23     | 624008              | naomi.desantis@milani.com          |
| 3978 |        50 | Lucia         | De Angelis | 1992-10-19    | BJTCDT26F61R162V | 2019-09-09     | 624010              | yago.bianco@damico.net             |
| 3979 |        21 | Elga          | Guerra     | 1976-05-18    | GVRQNQ02R11H373G | 2020-03-03     | 624011              | olimpia.caruso@amato.it            |
| 3980 |        13 | Aaron         | Lombardo   | 1989-06-14    | RPCUSG09A12A159B | 2020-10-13     | 624012              | mirko63@esposito.com               |
| 3982 |        36 | Noemi         | Bianchi    | 1991-12-10    | URBOWK61C39K607J | 2020-06-01     | 624014              | violante40@martini.com             |
| 3983 |        73 | Flaviana      | Ferrara    | 1986-09-20    | IYSVMO59Y06N512B | 2020-01-02     | 624015              | enrico.rizzi@conte.it              |
| 3984 |        24 | Joseph        | Piras      | 1983-12-16    | TKOCYL02O57E954H | 2020-12-12     | 624016              | hbarone@email.it                   |
| 3985 |        74 | Giorgio       | Bruno      | 1985-11-25    | XCKWEV10C98B024G | 2021-03-08     | 624017              | rmorelli@email.it                  |
| 3986 |        27 | Yago          | Damico     | 1982-12-20    | NRKJTV65K42B813A | 2019-12-08     | 624018              | gaetano35@gmail.com                |
| 3987 |        53 | Vera          | Rinaldi    | 1990-04-26    | BPFBWC81E38V431C | 2019-12-23     | 624019              | luna.conti@yahoo.it                |
| 3988 |        22 | Marina        | Serra      | 1984-10-25    | USXMAG05S32X517F | 2019-11-30     | 624020              | wruggiero@ferretti.com             |
| 3989 |        42 | Morgana       | Pellegrini | 1987-10-17    | SHORHG86H70P880E | 2020-11-26     | 624021              | ruth12@yahoo.it                    |
| 3991 |        22 | Renato        | Fiore      | 1983-06-11    | HHDHOF06G24J087F | 2019-03-22     | 624023              | ermes.ferri@gmail.com              |
| 3993 |        65 | Grazia        | Martino    | 1971-10-30    | GEVEPP98I05Y856O | 2019-06-13     | 624025              | primo10@dangelo.com                |
| 3994 |         3 | Enrico        | Sanna      | 1979-02-05    | LIPYKQ98U18W819P | 2019-04-05     | 624026              | conti.mariano@bernardi.it          |
| 3995 |        43 | Tancredi      | Rizzo      | 1971-07-01    | GHXXQJ25W75Q279Y | 2019-02-10     | 624027              | vera51@yahoo.com                   |
| 3997 |        32 | Zelida        | Santoro    | 1992-07-10    | CAFFHQ66Z69E246V | 2020-03-11     | 624029              | rocco23@gentile.it                 |
| 3998 |        42 | Ileana        | Pellegrino | 1989-07-14    | YQTYQA55C47C010I | 2018-12-08     | 624030              | edvige14@deangelis.com             |
| 3999 |        48 | Marino        | Ferraro    | 1984-09-09    | KXTXQC59P73U693M | 2020-09-26     | 624031              | grasso.cecco@email.it              |
| 4000 |        36 | Lidia         | Gatti      | 1991-03-19    | CXHNDA39G61N949M | 2020-02-03     | 624032              | lgrassi@cattaneo.it                |
| 4001 |        44 | Vania         | Romano     | 1990-12-06    | BRDPYI66I91Q558X | 2018-07-29     | 624033              | amilani@yahoo.com                  |
| 4003 |        19 | Flavio        | Morelli    | 1986-12-19    | COWEYV95D84Y404X | 2020-10-06     | 624035              | eufemia.montanari@neri.net         |
| 4004 |        51 | Fatima        | Mazza      | 1991-12-09    | GIJJCC08F46I944J | 2018-12-13     | 624036              | conti.selvaggia@ferrara.it         |
| 4006 |        52 | Eufemia       | Piras      | 1982-09-04    | PVWQOD67R36Y118F | 2019-03-11     | 624038              | erminio63@conte.it                 |
| 4009 |        67 | Giacobbe      | Ferrari    | 1976-02-19    | UEQSMN14Z98G261J | 2019-10-07     | 624041              | qdangelo@libero.it                 |
| 4011 |        69 | Violante      | Galli      | 1973-11-05    | EASFLK82M16J691B | 2019-06-19     | 624043              | samira.negri@yahoo.it              |
| 4014 |        50 | Laura         | De Angelis | 1989-01-13    | EFKJDX74B84E168L | 2020-03-26     | 624046              | leone.valentini@caputo.com         |
| 4015 |        56 | Damiana       | Ferraro    | 1971-11-04    | XDTKMD70E60L082A | 2018-09-02     | 624047              | vania.leone@silvestri.it           |
| 4016 |        11 | Dimitri       | D'amico    | 1974-09-16    | WPHARA88H77N678M | 2018-12-24     | 624048              | ymarchetti@hotmail.com             |
| 4018 |        36 | Thea          | Ferri      | 1980-02-03    | ZSOFUU53X59W707W | 2019-03-17     | 624050              | edilio.fabbri@conte.it             |
| 4019 |        56 | Tristano      | Pellegrini | 1992-04-13    | OMOYMW69W06Z924K | 2020-08-21     | 624051              | caruso.cira@hotmail.com            |
| 4020 |         1 | Muzio         | Caruso     | 1978-04-25    | VSHISP36D76G465G | 2019-08-10     | 624052              | danny.silvestri@sartori.com        |
| 4021 |        72 | Miriam        | Gallo      | 1981-07-01    | GOLHLN16F78B621W | 2018-10-20     | 624053              | bianco.jelena@yahoo.it             |
| 4022 |        70 | Amos          | Donati     | 1976-05-04    | GKDDEI28A31A779N | 2019-11-24     | 624054              | srizzi@yahoo.it                    |
| 4023 |        16 | Nico          | Carbone    | 1984-05-27    | MBONRK86X12T155P | 2020-09-07     | 624055              | romano.silverio@fabbri.org         |
| 4024 |        42 | Antimo        | Negri      | 1987-01-07    | RBMYMK39D86L728P | 2018-08-05     | 624056              | carbone.radames@hotmail.com        |
| 4025 |         2 | Celeste       | Leone      | 1985-11-04    | AXKNMI73D35Z124V | 2019-04-02     | 624057              | laura64@damico.org                 |
| 4026 |        16 | Deborah       | Bianco     | 1978-11-13    | SDSDNQ28E59U388Y | 2020-05-03     | 624058              | giacobbe27@yahoo.it                |
| 4027 |        68 | Fatima        | Mazza      | 1976-12-18    | KLGDEE70X39K618P | 2020-11-12     | 624059              | gmartini@yahoo.it                  |
| 4028 |        32 | Sue ellen     | Negri      | 1982-12-12    | MIQSGO73H83H636I | 2020-01-10     | 624060              | rosita95@coppola.com               |
| 4030 |        11 | Giacinta      | Pellegrini | 1975-05-01    | DAGEZO32E29V586D | 2020-11-12     | 624062              | giordano.caruso@montanari.net      |
| 4031 |         8 | Giuliano      | De Santis  | 1979-03-18    | OZAIBO43C65O206D | 2020-12-07     | 624063              | mpagano@moretti.it                 |
| 4032 |        54 | Ninfa         | Costa      | 1990-12-28    | ASQRHT91N10X986Z | 2020-03-05     | 624064              | ingrid.rizzi@costantini.it         |
| 4034 |        37 | Monia         | Negri      | 1976-06-17    | GVYFQN03S46F306Q | 2019-08-19     | 624066              | joshua.sorrentino@battaglia.it     |
| 4035 |        24 | Ubaldo        | Sorrentino | 1989-06-05    | YFDYBB97X26Z632R | 2021-04-30     | 624067              | avitali@libero.it                  |
| 4036 |         9 | Rosaria       | Vitale     | 1985-11-03    | UFAPRU12P07W717F | 2019-04-19     | 624068              | udamico@yahoo.com                  |
| 4037 |        50 | Tazio         | Pagano     | 1983-05-27    | TBNVXC22U82Y219R | 2019-01-08     | 624069              | noel.longo@ferrari.com             |
| 4038 |        28 | Joey          | Monti      | 1981-02-08    | ETMSGN61K38Z002A | 2020-11-11     | 624070              | marino.fernando@yahoo.it           |
| 4041 |        74 | Elsa          | De Angelis | 1981-05-11    | OPMCGM45S83K517Y | 2021-03-28     | 624073              | pierfrancesco78@santoro.it         |
| 4042 |        27 | Isira         | Sartori    | 1983-07-11    | NLSXLY29Y00L894B | 2020-08-02     | 624074              | marchetti.patrizio@deangelis.com   |
| 4043 |         4 | Lino          | Milani     | 1977-12-31    | KUTKQE84A84S729N | 2021-01-29     | 624075              | zderosa@leone.com                  |
| 4044 |        42 | Davis         | Caruso     | 1990-07-28    | LRIZFX35V95A753Z | 2021-02-23     | 624076              | riva.davide@yahoo.com              |
| 4045 |        52 | Priamo        | Marini     | 1991-08-25    | LXHIYW06O04J550G | 2018-10-09     | 624077              | hmonti@email.it                    |
| 4047 |         3 | Brigitta      | Mancini    | 1983-08-23    | MTFXLD12T11U321S | 2019-01-02     | 624079              | guerra.renato@gmail.com            |
| 4048 |        32 | Albino        | Milani     | 1989-02-07    | ILZRFB02F35A572F | 2018-12-30     | 624080              | hector.negri@martini.com           |
| 4049 |        60 | Amos          | Lombardi   | 1988-07-11    | HWUXJI87S79H672Q | 2020-09-22     | 624081              | lisa70@ferrara.it                  |
| 4050 |        37 | Radames       | Martino    | 1988-01-08    | RZWIAB54U27Y831W | 2021-02-12     | 624082              | ruth47@esposito.net                |
| 4051 |        63 | Lia           | Pellegrino | 1984-01-21    | EUHTEV69M90B300Y | 2019-11-13     | 624083              | zgrassi@ferri.com                  |
| 4052 |        48 | Fatima        | Grassi     | 1978-09-12    | RLMJGA79U51R386M | 2020-04-06     | 624084              | bellini.ortensia@ferretti.net      |
| 4053 |        50 | Marieva       | Vitali     | 1981-05-27    | NYNOAW00J33L979V | 2020-02-21     | 624085              | nferraro@ferrara.com               |
| 4057 |        22 | Mercedes      | Bianco     | 1989-09-29    | FFUAKE82H81H476X | 2019-08-13     | 624089              | desantis.thea@yahoo.com            |
| 4058 |        34 | Omar          | Negri      | 1977-09-25    | FBCSLC62V86P973F | 2020-06-13     | 624090              | imessina@leone.com                 |
| 4059 |        27 | Santo         | Longo      | 1978-09-16    | ISNZLL31R63Z003Q | 2019-02-13     | 624091              | silvestri.helga@yahoo.it           |
| 4060 |        33 | Ivonne        | Ferrara    | 1988-10-20    | CVBDHX69T22T690R | 2019-11-27     | 624092              | caio.rossetti@ferrari.org          |
| 4061 |         6 | Isabel        | Pagano     | 1971-08-08    | WOFIDF64L71E556J | 2018-09-10     | 624093              | edvige.parisi@yahoo.it             |
| 4062 |        41 | Ruth          | Giuliani   | 1973-01-18    | RUQPMK78F49U798E | 2019-04-05     | 624094              | eufemia.messina@hotmail.com        |
| 4063 |        72 | Mirko         | Costantini | 1975-02-04    | CAJLYQ81R04U591R | 2018-11-22     | 624095              | teseo.gentile@villa.com            |
| 4066 |        43 | Demian        | Vitale     | 1975-03-02    | LEJLXQ86C27D247O | 2020-08-10     | 624098              | valentini.bernardo@email.it        |
| 4067 |        27 | Odone         | Gallo      | 1979-01-25    | ISSMLG70I51W450U | 2018-12-02     | 624099              | vitali.ettore@lombardi.com         |
| 4068 |        66 | Battista      | Costa      | 1979-05-25    | GDNPBM92X04F021R | 2018-07-18     | 624100              | gianantonio21@yahoo.com            |
| 4070 |        62 | Mattia        | Conte      | 1973-05-23    | WXZBTU87S50O048E | 2019-05-10     | 624102              | zmonti@libero.it                   |
| 4071 |        62 | Vera          | Palumbo    | 1985-05-29    | FOVDRQ39I72J307J | 2019-03-06     | 624103              | basile.fulvio@libero.it            |
| 4072 |        44 | Adriano       | Sanna      | 1990-06-16    | KYUZTP79Z66B214K | 2020-09-15     | 624104              | germano.dangelo@yahoo.com          |
| 4074 |        24 | Ruth          | Montanari  | 1971-06-20    | ZCJNQM73I37U069W | 2021-01-25     | 624106              | sebastian.bellini@messina.com      |
| 4075 |        55 | Claudia       | Esposito   | 1982-07-06    | RNDFRZ47T17U226Y | 2018-12-17     | 624107              | ruggiero.benedetta@martinelli.net  |
| 4077 |        50 | Clodovea      | Fontana    | 1985-03-11    | TVHFWU37C49S170H | 2019-08-24     | 624109              | barbieri.soriana@yahoo.it          |
| 4079 |        16 | Fabio         | Lombardi   | 1978-05-02    | BPHFEQ48N04P515H | 2018-12-16     | 624111              | alighieri.caruso@hotmail.com       |
| 4082 |        22 | Lucrezia      | Sartori    | 1974-04-09    | SXAYWH41L38I365W | 2021-01-17     | 624114              | hbattaglia@mancini.org             |
| 4083 |        70 | Ermes         | Romano     | 1985-07-21    | QFLCXL92N59S244P | 2018-09-16     | 624115              | emanuel.milani@basile.com          |
| 4084 |        71 | Ian           | Caputo     | 1991-04-13    | WRUBLQ75X55P598N | 2021-04-21     | 624116              | kvilla@email.it                    |
| 4086 |        22 | Zelida        | D'amico    | 1979-11-09    | EZQXPC61B48Z219X | 2018-08-26     | 624118              | orlando.raoul@valentini.it         |
| 4087 |        64 | Ione          | Conte      | 1977-01-26    | YKIKMS63W00F564M | 2020-05-15     | 624119              | vera.villa@barone.net              |
| 4089 |        31 | Liborio       | D'amico    | 1984-06-04    | GWXJCN93S15N515G | 2021-05-05     | 624121              | bacchisio.serra@hotmail.com        |
| 4090 |        27 | Piccarda      | Palmieri   | 1979-05-24    | IXCGKJ00P07Q848E | 2019-05-31     | 624122              | bianchi.elga@libero.it             |
| 4091 |        59 | Mariapia      | Parisi     | 1985-12-20    | BLLBLC57F74B051G | 2019-01-29     | 624123              | lamberto.martino@libero.it         |
| 4092 |        39 | Ciro          | Palmieri   | 1992-09-08    | CNFZRS43A52R369E | 2020-10-04     | 624124              | qbernardi@conti.it                 |
| 4094 |        58 | Guendalina    | Bellini    | 1976-03-20    | SQGKJJ85T82A275U | 2019-06-23     | 624126              | marchetti.renato@riva.com          |
| 4095 |        53 | Assia         | Rizzo      | 1981-09-07    | ORBXGQ84J09G970A | 2020-02-18     | 624127              | omoretti@sartori.com               |
| 4097 |        40 | Ruth          | Mazza      | 1981-12-24    | BALQSW59F52O454X | 2019-04-28     | 624129              | miriana68@yahoo.it                 |
| 4100 |        64 | Marco         | Gatti      | 1988-02-16    | HAPUAE85G77W858M | 2020-05-26     | 624132              | rodolfo.galli@hotmail.com          |
| 4101 |         2 | Noemi         | Parisi     | 1986-12-08    | IQCDLQ47R81G953U | 2019-03-13     | 624133              | isabel.fiore@yahoo.it              |
| 4102 |        40 | Deborah       | Gallo      | 1988-08-31    | UCBSCE12U91O548O | 2019-09-16     | 624134              | qmariani@email.it                  |
| 4103 |        58 | Armando       | Moretti    | 1983-01-04    | NSKXDD01Q01U795W | 2020-03-01     | 624135              | renato64@cattaneo.it               |
| 4105 |        71 | Ortensia      | Pellegrino | 1991-12-02    | LZMCMW18Y54U226K | 2018-10-10     | 624137              | mderosa@gmail.com                  |
| 4108 |        57 | Egidio        | Vitale     | 1981-11-26    | WENXDO48I09P790Q | 2021-03-23     | 624140              | omar08@costantini.com              |
| 4109 |        26 | Aaron         | Esposito   | 1991-12-25    | FZYIAS77B37H221U | 2021-05-12     | 624141              | aaron.coppola@yahoo.com            |
| 4110 |        72 | Matilde       | Riva       | 1971-12-27    | EZJADL73P55T435Z | 2018-06-20     | 624142              | esposito.augusto@libero.it         |
| 4113 |        45 | Kai           | Santoro    | 1976-03-17    | GUZTNF08A50P684A | 2018-08-22     | 624145              | elda39@carbone.com                 |
| 4114 |        67 | Guido         | Vitale     | 1982-05-31    | ZENLNJ58I69H549H | 2019-11-02     | 624146              | kneri@libero.it                    |
| 4115 |        36 | Dimitri       | Parisi     | 1981-05-05    | OMMWAB50K08V108A | 2019-10-13     | 624147              | vbenedetti@hotmail.com             |
| 4117 |        51 | Quarto        | Gentile    | 1986-07-07    | NTLCCG64N00X319F | 2018-12-21     | 624149              | artemide34@marchetti.com           |
| 4118 |        18 | Morgana       | De luca    | 1975-12-11    | XOQXBC99T18E086F | 2018-12-19     | 624150              | kruggiero@gmail.com                |
| 4119 |        30 | Morgana       | Barbieri   | 1980-06-27    | CTOZKL80O41E936G | 2018-08-29     | 624151              | monia56@dangelo.it                 |
| 4120 |        16 | Filomena      | Pagano     | 1989-09-25    | BZMGUS76L81C678P | 2019-05-14     | 624152              | xmancini@derosa.com                |
| 4121 |        12 | Timothy       | Basile     | 1984-12-08    | VMHFFJ93I24D864P | 2018-11-13     | 624153              | grusso@yahoo.it                    |
| 4122 |        44 | Modesto       | Messina    | 1974-11-15    | KZTBDK14O52G703U | 2021-05-20     | 624154              | pmancini@neri.it                   |
| 4123 |        61 | Gregorio      | Ricci      | 1978-04-11    | PDESEL09K85B390S | 2020-03-20     | 624155              | palmieri.miriam@hotmail.com        |
| 4124 |        41 | Romeo         | Mariani    | 1989-07-03    | BFKCYL99N62H032C | 2019-10-11     | 624156              | fvalentini@neri.com                |
| 4125 |        28 | Elga          | Orlando    | 1973-01-25    | OPUYVH55U35R666D | 2019-01-01     | 624157              | pconti@libero.it                   |
| 4127 |        39 | Thea          | Mariani    | 1977-04-25    | JTMLUC64L02Z068R | 2021-01-31     | 624159              | benedetta56@gmail.com              |
| 4128 |        42 | Arduino       | Valentini  | 1976-03-14    | NCGFYB32J03O316A | 2020-12-13     | 624160              | dangelo.demi@gmail.com             |
| 4129 |        74 | Oretta        | Fontana    | 1975-10-05    | SHHQRJ39Q83C115G | 2018-11-29     | 624161              | miriam.guerra@palumbo.com          |
| 4130 |        39 | Giobbe        | Rizzi      | 1981-11-23    | VKQSCB68K23T700Y | 2020-12-24     | 624162              | ricci.bibiana@caputo.com           |
| 4131 |        28 | Piccarda      | Silvestri  | 1992-12-31    | UHXLXL73C55U065M | 2020-05-14     | 624163              | brizzi@gmail.com                   |
| 4132 |        11 | Modesto       | Piras      | 1975-09-24    | ZLHOBC96Z46Q059P | 2019-04-11     | 624164              | romano.demian@hotmail.com          |
| 4133 |        28 | Samira        | Barone     | 1982-05-28    | XGOWKZ13T98N531V | 2018-07-09     | 624165              | hrizzi@email.it                    |
| 4134 |        11 | Amedeo        | Parisi     | 1975-07-17    | WBYHQX84R49Y171H | 2019-11-20     | 624166              | raoul.deangelis@marchetti.com      |
| 4135 |        30 | Clea          | Fabbri     | 1979-05-15    | ITZUCD33U35A587I | 2020-03-04     | 624167              | vdesantis@farina.org               |
| 4136 |        65 | Fulvio        | Barone     | 1979-11-03    | GHZRPP53R17K726M | 2019-06-10     | 624168              | pietro06@dangelo.org               |
| 4137 |        18 | Morgana       | Fontana    | 1987-06-13    | XQJJSZ97S62B292W | 2018-08-25     | 624169              | carmela.romano@lombardi.it         |
| 4139 |        12 | Irene         | Sala       | 1973-06-19    | MBLJMA31W82O070X | 2018-08-29     | 624171              | bruno.ulrico@libero.it             |
| 4140 |        67 | Vera          | Sartori    | 1979-03-23    | EELDYB09M92A287X | 2020-01-06     | 624172              | violante.vitali@rossi.it           |
| 4141 |        65 | Noah          | Leone      | 1981-04-18    | IDKECG68C06L087E | 2019-01-07     | 624173              | rosalba42@hotmail.com              |
| 4142 |        50 | Danuta        | Greco      | 1990-04-06    | PZHHWL43K24B321N | 2018-11-24     | 624174              | ferri.marcella@hotmail.com         |
| 4143 |        25 | Cristyn       | Santoro    | 1985-11-06    | ZPDKVG35R98N340C | 2020-07-26     | 624175              | ggrasso@libero.it                  |
| 4144 |        32 | Elio          | Cattaneo   | 1985-12-18    | PTPRYA69T71K209V | 2020-01-29     | 624176              | genziana.valentini@email.it        |
| 4145 |        59 | Bibiana       | Neri       | 1982-12-19    | EOWCUR28P79M171J | 2021-05-22     | 624177              | xavier.milani@martino.com          |
| 4146 |        61 | Rita          | Marini     | 1979-10-17    | EKIOMC73D00U052V | 2019-05-02     | 624178              | ygrasso@libero.it                  |
| 4148 |        24 | Mercedes      | Vitale     | 1976-02-13    | FFZXXW66P85T205L | 2020-03-23     | 624180              | pagano.alighiero@benedetti.com     |
| 4150 |        39 | Kai           | Giordano   | 1971-06-28    | EJEKRS35T39E074W | 2018-08-23     | 624182              | marchetti.ettore@yahoo.com         |
| 4151 |        57 | Timoteo       | Lombardi   | 1977-05-26    | JOMRUO93S53R325L | 2019-07-12     | 624183              | ddeluca@derosa.com                 |
| 4153 |        56 | Ausonio       | Barone     | 1979-12-21    | JLIRAQ49J47G556X | 2019-09-10     | 624185              | monia97@yahoo.it                   |
| 4155 |         6 | Lauro         | Giuliani   | 1991-09-09    | YFBZYS71P63Z416T | 2018-11-01     | 624187              | ferrara.ulrico@deluca.com          |
| 4156 |        17 | Tancredi      | Lombardi   | 1980-02-11    | DPSJDD82Z48V404Y | 2020-04-27     | 624188              | monti.claudia@martini.net          |
| 4157 |        60 | Ivonne        | Pagano     | 1977-04-27    | ELNGVS32N36R125J | 2019-12-05     | 624189              | edvige.silvestri@gmail.com         |
| 4159 |        13 | Lazzaro       | Grasso     | 1978-04-11    | TUBJQT67W88T591Y | 2021-04-12     | 624191              | emoretti@donati.com                |
| 4160 |         9 | Ivonne        | Valentini  | 1986-05-29    | BMFRPG35P26H874J | 2020-11-29     | 624192              | deangelis.maristella@hotmail.com   |
| 4163 |        60 | Diamante      | Mancini    | 1987-09-20    | BMCXSZ21Z69X214N | 2018-07-18     | 624195              | ingrid.valentini@barone.org        |
| 4164 |        59 | Alighieri     | Longo      | 1981-08-10    | DXGKVG27O42B877G | 2019-07-29     | 624196              | ferri.albino@yahoo.it              |
| 4165 |        46 | Claudia       | Fontana    | 1984-04-13    | JFVTRG15T45V980Y | 2020-07-09     | 624197              | iconte@costa.it                    |
| 4166 |        26 | Caio          | Mazza      | 1986-09-15    | BEZEWY69F87B899D | 2020-09-11     | 624198              | ybianco@mancini.it                 |
| 4168 |        14 | Lauro         | Mariani    | 1982-07-03    | LWUBNQ04V39V515R | 2020-01-14     | 624200              | oreste41@yahoo.com                 |
| 4169 |        43 | Cassiopea     | Damico     | 1986-07-24    | GBQHXC77C11P853C | 2018-07-23     | 624201              | kristel38@yahoo.it                 |
| 4171 |        38 | Brigitta      | Bruno      | 1983-05-29    | RJRQLN13A51W717D | 2018-11-01     | 624203              | ivitale@gmail.com                  |
| 4172 |        25 | Artemide      | Ferri      | 1977-06-02    | OEGCYH98F46H406G | 2020-08-10     | 624204              | ninfa.guerra@bernardi.com          |
| 4174 |        23 | Sesto         | De Angelis | 1971-11-08    | LSVUSI72Z01X449X | 2021-05-19     | 624206              | penelope75@libero.it               |
| 4176 |        47 | Hector        | Coppola    | 1992-07-17    | ENWIHW92O44R877Q | 2019-12-21     | 624208              | lino.deangelis@gmail.com           |
| 4177 |        73 | Claudia       | Valentini  | 1976-01-07    | KWOFJD88C53D807V | 2018-07-11     | 624209              | morgana.bernardi@conte.com         |
| 4179 |        48 | Miriana       | Monti      | 1987-05-29    | WESQCZ99H55N219L | 2019-01-31     | 624211              | marchetti.loredana@hotmail.com     |
| 4181 |        72 | Tolomeo       | Palumbo    | 1977-11-26    | SPTZIF81A68D540O | 2018-10-14     | 624213              | qsorrentino@lombardi.org           |
| 4182 |        56 | Egidio        | Benedetti  | 1992-02-22    | MHEGPE82O29K692X | 2018-07-09     | 624214              | clea.riva@email.it                 |
| 4183 |        36 | Giordano      | Lombardi   | 1987-09-25    | TQUHNC74D14H544Q | 2018-08-17     | 624215              | luigi.martini@orlando.com          |
| 4188 |        65 | Mariagiulia   | Basile     | 1982-08-14    | IXZKMS26W01R706B | 2020-08-04     | 624220              | sibilla03@yahoo.com                |
| 4190 |        22 | Gioacchino    | Negri      | 1982-12-07    | JCNTUH73Z77O179K | 2021-01-20     | 624222              | carlo.monti@hotmail.com            |
| 4191 |        45 | Alighiero     | Giordano   | 1979-05-08    | AMWYZL23H47T188Z | 2020-02-02     | 624223              | clea.monti@gmail.com               |
| 4192 |         9 | Violante      | Parisi     | 1974-10-03    | UYBXCB30W70U261L | 2021-03-27     | 624224              | bernardi.penelope@yahoo.it         |
| 4193 |        35 | Sandro        | Lombardi   | 1989-02-26    | UIIHPY21G56V694Q | 2018-12-16     | 624225              | concetta.rizzo@yahoo.it            |
| 4194 |        58 | Gianmarco     | Martinelli | 1986-07-10    | ADONMZ29E40K619B | 2020-10-29     | 624226              | noel48@gmail.com                   |
| 4195 |         7 | Santo         | Mariani    | 1985-09-27    | FJQZBD67T21O843J | 2019-11-30     | 624227              | xdangelo@basile.it                 |
| 4196 |        19 | Maika         | Greco      | 1975-08-08    | BYVWVW50B95B156P | 2019-08-26     | 624228              | soriana31@costantini.org           |
| 4197 |        40 | Flaviana      | Greco      | 1975-11-30    | FUQHPV18G30R929Z | 2019-04-03     | 624229              | hmoretti@carbone.net               |
| 4198 |         7 | Miriam        | Pellegrino | 1987-07-07    | GOBSCI12W16D515G | 2019-11-01     | 624230              | maristella03@bellini.it            |
| 4201 |        34 | Giuliano      | Marino     | 1988-08-09    | ESILUZ49Z98N036T | 2019-06-28     | 624233              | jgallo@benedetti.com               |
| 4202 |        53 | Zelida        | De Angelis | 1985-07-16    | FARXUT38Q09C630V | 2019-03-30     | 624234              | scaruso@yahoo.com                  |
| 4204 |        50 | Benedetta     | Barbieri   | 1971-12-03    | RFCOOG73I95N859F | 2020-05-19     | 624236              | coppola.osvaldo@yahoo.com          |
| 4205 |        71 | Noemi         | Ferri      | 1990-10-28    | WLXLAL41R35A937E | 2018-10-20     | 624237              | edvige58@hotmail.com               |
| 4208 |        22 | Vitalba       | Pellegrini | 1977-04-11    | JDIVVN48E97C447U | 2020-10-13     | 624240              | clea17@yahoo.it                    |
| 4210 |         3 | Noemi         | Rossetti   | 1977-11-21    | EZXGEK94X28L131H | 2021-06-02     | 624242              | violante.barbieri@guerra.it        |
| 4211 |        50 | Naomi         | Vitali     | 1986-11-02    | UJFZTJ89T38O643A | 2020-01-02     | 624243              | cira19@conti.net                   |
| 4212 |         7 | Penelope      | Coppola    | 1991-07-21    | NRSLAI04T20C231J | 2019-12-11     | 624244              | concetta.neri@libero.it            |
| 4214 |        17 | Cira          | Galli      | 1981-09-06    | XIUDSV20Z22D938Z | 2020-10-14     | 624246              | gentile.vera@palmieri.com          |
| 4215 |        70 | Irene         | De rosa    | 1978-03-08    | AJGMGP17V46D435U | 2018-10-01     | 624247              | samira33@email.it                  |
| 4216 |        69 | Emilia        | Silvestri  | 1983-11-18    | ASXUKD69L11L648G | 2020-08-22     | 624248              | osea42@yahoo.it                    |
| 4218 |        61 | Vania         | Battaglia  | 1976-03-18    | HJZJWQ34S07P749I | 2019-11-28     | 624250              | bianco.sebastian@libero.it         |
| 4220 |        14 | Felicia       | Coppola    | 1977-03-27    | JHKBOX39B50Q154E | 2019-04-24     | 624252              | sarita.rizzi@riva.net              |
| 4221 |        27 | Sebastian     | Piras      | 1971-10-06    | MJGOTQ15A31U205F | 2019-12-13     | 624253              | kvalentini@gmail.com               |
| 4222 |         6 | Filomena      | Fontana    | 1991-04-18    | JHMNMH37R39K800S | 2020-04-02     | 624254              | anastasio.pagano@hotmail.com       |
| 4224 |         9 | Fernando      | Rizzo      | 1975-03-19    | TGUNLR18D32I785H | 2018-08-06     | 624256              | lmonti@ferri.org                   |
| 4226 |        33 | Fiorenzo      | Amato      | 1974-07-22    | JDQJLT16C13W046F | 2019-06-28     | 624258              | giovanna.giordano@testa.com        |
| 4227 |        38 | Erminio       | Mariani    | 1991-03-23    | WOSNCR50C96U170I | 2020-10-03     | 624259              | odino.palumbo@caruso.it            |
| 4228 |        62 | Tolomeo       | Lombardo   | 1981-09-16    | ZDCPNG52I70N122R | 2021-01-31     | 624260              | derosa.fortunata@benedetti.it      |
| 4229 |        19 | Selvaggia     | Sanna      | 1977-09-20    | UHALFQ02M66L974J | 2020-06-01     | 624261              | orlando.olo@gmail.com              |
| 4231 |        44 | Patrizio      | Sanna      | 1978-01-11    | MJGOOM39J67V899S | 2020-03-01     | 624263              | isabel.benedetti@yahoo.com         |
| 4232 |        65 | Silvano       | Marino     | 1983-09-20    | KJZHQC97O69D115U | 2019-02-28     | 624264              | derosa.bibiana@leone.com           |
| 4233 |        10 | Ursula        | Valentini  | 1972-07-19    | MXSXNX17X86H894W | 2021-05-18     | 624265              | zelida.pagano@serra.org            |
| 4234 |        70 | Lucia         | Ferrari    | 1978-12-20    | HDSBLR50N07K815W | 2019-06-28     | 624266              | rinaldi.damiano@sanna.it           |
| 4235 |        27 | Ortensia      | Ferri      | 1984-03-26    | EWINFU79A59L860L | 2021-06-06     | 624267              | testa.mietta@email.it              |
| 4237 |        23 | Timothy       | Vitali     | 1974-10-25    | JAYVOX59D87Q193M | 2021-05-17     | 624269              | vitalba.negri@rossi.it             |
| 4238 |        25 | Costanzo      | Esposito   | 1986-05-09    | GAPLVU12I13W224H | 2019-05-19     | 624270              | ione02@rossetti.com                |
| 4239 |        26 | Aaron         | De Santis  | 1978-08-21    | WABOWQ25B75K952Y | 2019-08-10     | 624271              | rizzo.egisto@giuliani.it           |
| 4240 |        17 | Carlo         | Monti      | 1990-01-29    | NUPISH63Z12B561H | 2019-05-05     | 624272              | albino03@giuliani.it               |
| 4241 |        19 | Fortunata     | Palmieri   | 1979-11-24    | VRVNJW66K74Y488Q | 2021-05-15     | 624273              | rossetti.olimpia@barbieri.com      |
| 4242 |         2 | Ivano         | Longo      | 1990-08-13    | NXXFBL94J18P949D | 2021-04-04     | 624274              | pagano.maika@libero.it             |
| 4243 |        67 | Giulietta     | Mariani    | 1982-06-08    | QNDCQN15U00J584R | 2020-04-19     | 624275              | romeo53@riva.it                    |
| 4244 |        72 | Lia           | D'angelo   | 1980-09-03    | SBMAPM16Z72I312F | 2019-10-20     | 624276              | gatti.sesto@libero.it              |
| 4245 |        32 | Miriana       | Benedetti  | 1978-02-06    | RNMKQU40S36N536K | 2018-07-14     | 624277              | gianmaria87@cattaneo.it            |
| 4246 |        20 | Isira         | Russo      | 1990-01-27    | LUSCMA34Q51X051C | 2019-04-28     | 624278              | yorlando@libero.it                 |
| 4247 |        27 | Deborah       | Fontana    | 1990-04-30    | CLYUSL87Y54W949D | 2018-11-20     | 624279              | giovanna.rossi@hotmail.com         |
| 4248 |         2 | Kai           | Moretti    | 1991-06-30    | YNWALH40T43U751S | 2018-08-03     | 624280              | pierfrancesco.rizzo@yahoo.com      |
| 4249 |        18 | Domiziano     | Milani     | 1988-11-15    | CJGQGH85F90V283Q | 2020-02-01     | 624281              | elsa.leone@testa.com               |
| 4250 |        38 | Lucia         | Costa      | 1989-04-22    | IWTNOA13T86O450A | 2019-10-14     | 624282              | omar.damico@gmail.com              |
| 4251 |        32 | Secondo       | Donati     | 1972-09-01    | KRJMRH67D05O217G | 2020-03-21     | 624283              | noah68@yahoo.com                   |
| 4252 |        44 | Zaccaria      | Rossetti   | 1982-04-17    | SGRSNC86A61B270P | 2020-10-13     | 624284              | maristella26@hotmail.com           |
| 4253 |        73 | Matilde       | Fontana    | 1985-12-09    | CVAKTE47A08C491J | 2020-10-15     | 624285              | evita.gatti@marchetti.it           |
| 4254 |        73 | Artes         | Marini     | 1977-06-09    | LRPCPA20A11X880F | 2018-06-27     | 624286              | armando20@palmieri.com             |
| 4255 |        64 | Marieva       | Costantini | 1979-02-12    | MGMFUF51J38L028X | 2021-03-19     | 624287              | moretti.danuta@ferri.com           |
| 4256 |        28 | Ninfa         | Ferri      | 1982-01-27    | ZILAUT36P21S789J | 2020-12-08     | 624288              | tconti@hotmail.com                 |
| 4259 |        72 | Enzo          | Romano     | 1979-10-06    | JFRYUN17M08O006O | 2021-01-17     | 624291              | filomena.bianchi@hotmail.com       |
| 4260 |        69 | Grazia        | Vitali     | 1983-10-17    | AEBDZW22A89O894L | 2019-05-22     | 624292              | dlombardi@gmail.com                |
| 4261 |        23 | Diana         | Gallo      | 1988-02-08    | WESXNT61L90S175K | 2020-01-16     | 624293              | rcolombo@marini.com                |
| 4262 |        58 | Michael       | Pellegrini | 1976-04-15    | ZMKIGF63D41Y804F | 2019-05-10     | 624294              | sneri@bellini.com                  |
| 4263 |        74 | Omar          | Fabbri     | 1979-07-19    | ENSKNJ59S41X471U | 2018-11-05     | 624295              | fabbri.giacobbe@yahoo.com          |
| 4264 |        67 | Vania         | Rizzo      | 1975-09-09    | PVZYCI70T31Y279H | 2020-08-24     | 624296              | giacinta.ferrari@damico.it         |
| 4265 |        10 | Fatima        | Pellegrino | 1978-03-14    | YLLLSB48X97Y406J | 2019-11-18     | 624297              | ssantoro@greco.com                 |
| 4267 |        59 | Quasimodo     | De rosa    | 1977-06-05    | DXLCHC49V22N920S | 2019-09-24     | 624299              | kmessina@hotmail.com               |
| 4268 |        17 | Umberto       | Lombardo   | 1991-10-17    | QEMQSQ62D44C565C | 2020-02-03     | 624300              | pagano.maika@costantini.org        |
| 4270 |        44 | Adriano       | Cattaneo   | 1982-11-09    | GLTZQO26F71O550F | 2018-12-25     | 624302              | qesposito@email.it                 |
| 4271 |         3 | Albino        | Bernardi   | 1987-05-23    | HIBZKL33N52T399Z | 2020-12-31     | 624303              | selvaggia.benedetti@yahoo.com      |
| 4273 |        60 | Vitalba       | Carbone    | 1974-02-17    | QTHMMH96X63V834O | 2018-12-14     | 624305              | martini.ione@hotmail.com           |
| 4274 |        54 | Jelena        | Villa      | 1983-03-31    | WZXPFS78N42C382G | 2019-07-17     | 624306              | enrica51@yahoo.it                  |
| 4275 |        33 | Manuele       | Rossetti   | 1974-12-03    | OKVPXY79Y27P040E | 2020-10-30     | 624307              | abramo.fabbri@yahoo.it             |
| 4276 |        22 | Manfredi      | Ricci      | 1980-10-29    | KCACVY39U81Q425J | 2021-03-05     | 624308              | ferrari.celeste@yahoo.com          |
| 4277 |        26 | Sandro        | Ferrara    | 1980-08-25    | KXRCUA32O04F174Y | 2019-12-10     | 624309              | egisto.sanna@barbieri.com          |
| 4278 |        48 | Pacifico      | Sanna      | 1986-09-12    | DCMDPS55N72O973J | 2020-07-08     | 624310              | romano.ermes@email.it              |
| 4279 |         9 | Lidia         | Guerra     | 1977-12-08    | EMYHAT92W84C731A | 2021-06-06     | 624311              | russo.loris@libero.it              |
| 4280 |        25 | Odone         | Lombardi   | 1984-12-06    | BXOEUB74H03G642N | 2019-07-16     | 624312              | uricci@email.it                    |
| 4281 |        30 | Helga         | Martinelli | 1971-07-23    | ZWLBEL44I02Q140S | 2018-10-12     | 624313              | dsanna@hotmail.com                 |
| 4282 |         1 | Kai           | Messina    | 1989-02-26    | UHLRNA82R41U347N | 2019-08-31     | 624314              | ricci.sabino@rinaldi.it            |
| 4283 |        32 | Muzio         | Donati     | 1972-09-26    | WWXITL17U50P769Y | 2018-08-01     | 624315              | odesantis@colombo.it               |
| 4284 |        39 | Raniero       | Ruggiero   | 1990-08-26    | LBNTCW60V96R336A | 2019-08-18     | 624316              | sala.raoul@hotmail.com             |
| 4285 |         4 | Maika         | Battaglia  | 1991-05-06    | FWWINR76Z29N455L | 2020-02-26     | 624317              | bianchi.ippolito@testa.com         |
| 4286 |        20 | Vera          | Caputo     | 1974-04-30    | OBYCEQ72L89S885Q | 2021-03-01     | 624318              | augusto33@yahoo.it                 |
| 4287 |        10 | Alessandro    | Monti      | 1974-10-22    | BQRRBX13M58K343Y | 2019-03-07     | 624319              | alighiero.vitale@rizzo.org         |
| 4288 |        58 | Primo         | Battaglia  | 1972-05-19    | ZIAWCC51C05A410U | 2019-01-17     | 624320              | audenico.conti@hotmail.com         |
| 4290 |        19 | Ione          | Martinelli | 1980-04-15    | PXQMNZ54D66H155L | 2020-08-21     | 624322              | xmancini@russo.it                  |
| 4293 |        16 | Luigi         | Martinelli | 1985-01-06    | CJJWQH73D22B426P | 2019-12-26     | 624325              | agalli@email.it                    |
| 4296 |        25 | Dylan         | Ricci      | 1985-07-20    | NOAKMR48J77P501K | 2019-10-13     | 624328              | eustachio.conte@sorrentino.it      |
| 4297 |        42 | Tosca         | Guerra     | 1975-09-24    | NHRPRK93P45A496X | 2019-04-28     | 624329              | glongo@hotmail.com                 |
| 4298 |        58 | Arduino       | Costa      | 1986-02-17    | VHWTNR36P66F160N | 2019-06-25     | 624330              | sdamico@romano.it                  |
| 4300 |        75 | Celeste       | Esposito   | 1985-10-26    | ZHRAKT65L33J753I | 2020-03-26     | 624332              | maika84@carbone.com                |
| 4301 |        67 | Lucrezia      | Messina    | 1975-05-26    | NJIROW34V20P988H | 2020-06-02     | 624333              | arossi@guerra.com                  |
| 4302 |        73 | Guendalina    | Palmieri   | 1990-04-24    | PSPNTP35I63W553G | 2020-12-03     | 624334              | caruso.cassiopea@yahoo.it          |
| 4304 |        50 | Tazio         | Caputo     | 1985-09-16    | DJXRCU54R59R786Z | 2021-01-08     | 624336              | osea.greco@email.it                |
| 4306 |        65 | Rosita        | Rizzo      | 1977-10-21    | MQBANN07K12Y476E | 2021-06-03     | 624338              | uvitale@gmail.com                  |
| 4307 |        42 | Moreno        | Vitale     | 1974-11-07    | FETAPP42A94S669N | 2021-05-02     | 624339              | rinaldi.donatella@hotmail.com      |
| 4308 |        68 | Rosalba       | Palmieri   | 1984-04-02    | ODERED54X81M050Q | 2020-11-30     | 624340              | gatti.vania@amato.org              |
| 4309 |        72 | Giuliano      | Farina     | 1976-02-01    | QEPJGZ86P70G719G | 2018-11-28     | 624341              | diamante83@coppola.com             |
| 4310 |        66 | Jelena        | Palumbo    | 1985-06-02    | LEWLHV10A49W263E | 2019-08-22     | 624342              | davide.santoro@giordano.com        |
| 4311 |        35 | Osvaldo       | De luca    | 1980-01-15    | XTSPZL36T82I213E | 2020-07-25     | 624343              | odone17@gmail.com                  |
| 4312 |         2 | Arcibaldo     | Pagano     | 1982-09-03    | UWFJQQ41L85U914U | 2021-02-02     | 624344              | mercedes15@ferrara.com             |
| 4313 |         7 | Anastasio     | Barone     | 1990-09-09    | OEUCCX11B10Y282Y | 2019-12-17     | 624345              | sibilla.marino@yahoo.com           |
| 4314 |        23 | Cesidia       | Parisi     | 1974-05-19    | FPBXOI06L58I998F | 2019-06-28     | 624346              | marieva.giuliani@desantis.com      |
| 4315 |        52 | Maria         | Benedetti  | 1983-07-21    | BCGORF04T59D687B | 2021-05-14     | 624347              | zelida57@riva.com                  |
| 4316 |         9 | Laerte        | Grassi     | 1987-07-23    | OBSRQY78Z22U512N | 2021-01-03     | 624348              | gbarbieri@rizzi.com                |
| 4318 |        66 | Umberto       | Colombo    | 1980-09-10    | ZVESYI49A50O042F | 2019-02-22     | 624350              | ydeangelis@silvestri.net           |
| 4319 |        69 | Benedetta     | Ferrari    | 1974-10-30    | XNTHIM83J90M920N | 2019-07-20     | 624351              | bettino59@colombo.com              |
| 4320 |         3 | Muzio         | Caputo     | 1980-03-02    | HXAGJV80Q00U237L | 2020-08-21     | 624352              | pbruno@morelli.org                 |
| 4321 |        46 | Rosolino      | Russo      | 1982-05-03    | HBSAND64T33B289F | 2020-04-03     | 624353              | vitalba.palmieri@conte.it          |
| 4322 |        20 | Piersilvio    | Vitale     | 1973-04-04    | VNRBMR36R55P347A | 2019-06-29     | 624354              | zelida.testa@yahoo.it              |
| 4323 |        34 | Amos          | Donati     | 1987-10-03    | KZFWLE75X73A859U | 2021-01-25     | 624355              | guido.testa@giordano.it            |
| 4324 |        36 | Clea          | Messina    | 1991-02-02    | HCEBWE16W55L633S | 2020-10-06     | 624356              | parisi.armando@gmail.com           |
| 4326 |        72 | Miriana       | D'angelo   | 1975-06-20    | CPJGUG61D03P145E | 2020-10-20     | 624358              | martino.enrico@email.it            |
| 4329 |        61 | Anastasio     | Palumbo    | 1976-06-28    | KYCUCB34Y41C556J | 2021-04-10     | 624361              | ludovico.valentini@romano.com      |
| 4330 |        60 | Mirco         | Fontana    | 1978-03-08    | FKFQLU89C20T180S | 2020-08-04     | 624362              | joshua71@gmail.com                 |
| 4333 |        25 | Tolomeo       | Palumbo    | 1988-07-16    | YCPDMW16Y53N779L | 2019-03-04     | 624365              | kristel.derosa@email.it            |
| 4334 |        48 | Emanuel       | Farina     | 1981-04-22    | YIWTLF28D37P387X | 2019-12-14     | 624366              | adangelo@hotmail.com               |
| 4337 |        47 | Anselmo       | Lombardi   | 1981-07-30    | OTMPMQ83N72Z593P | 2020-02-05     | 624369              | lidia.grasso@fontana.com           |
| 4339 |        31 | Erminio       | Rossi      | 1985-06-03    | TVHJJO81A60Q198F | 2018-09-12     | 624371              | damico.doriana@grassi.org          |
| 4341 |        57 | Gabriele      | Barbieri   | 1986-11-08    | LFEFNQ34P45Q360T | 2018-08-05     | 624373              | anegri@gmail.com                   |
| 4342 |        49 | Joseph        | Lombardi   | 1978-04-14    | ZZRWLE07C94W029N | 2018-10-15     | 624374              | loretta.rossi@yahoo.com            |
| 4343 |        42 | Shaira        | Rossi      | 1971-06-25    | WKVWDT31G10A873X | 2018-12-28     | 624375              | prisca80@email.it                  |
| 4345 |        42 | Lidia         | Rizzo      | 1990-12-28    | DLSWZT77E26S937R | 2020-04-30     | 624377              | luna44@russo.it                    |
| 4347 |        70 | Luce          | Villa      | 1973-10-16    | AAGWCA00F96G294B | 2018-08-27     | 624379              | sueellen49@galli.com               |
| 4348 |        58 | Felicia       | Ferrari    | 1979-08-02    | PLNMOT39T50A999W | 2019-03-01     | 624380              | joey15@gmail.com                   |
| 4349 |        24 | Domingo       | Amato      | 1987-11-01    | VMOTIP10C72R518D | 2020-11-08     | 624381              | evita.negri@libero.it              |
| 4350 |        75 | Osea          | Esposito   | 1982-02-04    | ZRDPXK29Y44A978V | 2019-08-24     | 624382              | guerra.moreno@yahoo.com            |
| 4351 |        70 | Nicoletta     | Morelli    | 1974-05-15    | EMAVTX51W64F804L | 2021-02-22     | 624383              | ferretti.nestore@libero.it         |
| 4352 |        31 | Doriana       | Ferri      | 1991-02-23    | QMEWWZ46C51L732N | 2019-11-25     | 624384              | felicia14@sanna.com                |
| 4354 |        60 | Maristella    | De rosa    | 1973-07-01    | CRIJMG76N94I934E | 2020-03-23     | 624386              | sriva@damico.it                    |
| 4355 |        30 | Fabio         | Rossetti   | 1983-01-29    | RBDKQZ67R53H302C | 2019-08-11     | 624387              | xgreco@guerra.com                  |
| 4356 |        64 | Romolo        | Martini    | 1986-06-18    | SGJMHQ73J96V614S | 2020-07-29     | 624388              | romano.jari@costantini.it          |
| 4357 |        31 | Prisca        | Farina     | 1985-09-29    | MWZNHD60Q97B088G | 2021-06-01     | 624389              | deangelis.ercole@yahoo.it          |
| 4359 |        38 | Luce          | Rinaldi    | 1975-04-15    | HILYWZ27V67G804P | 2020-08-24     | 624391              | jole.derosa@ricci.it               |
| 4360 |        50 | Jelena        | Montanari  | 1990-07-27    | YMYDTY40F06U075G | 2020-10-31     | 624392              | colombo.gerlando@yahoo.it          |
| 4361 |        16 | Antonino      | Bianchi    | 1976-02-29    | JBNVRU52B24U201I | 2019-01-24     | 624393              | wcattaneo@rossi.it                 |
| 4362 |        13 | Celeste       | Mancini    | 1980-04-22    | EJAIHV88C83J921B | 2020-12-31     | 624394              | tgreco@libero.it                   |
| 4365 |        54 | Lucia         | Caruso     | 1987-05-15    | ZJWOLA00O52Z987F | 2019-11-08     | 624397              | mvitali@gmail.com                  |
| 4366 |        55 | Elda          | Martino    | 1991-08-04    | LJMOZU18P06P353L | 2018-12-06     | 624398              | sbattaglia@libero.it               |
| 4367 |         9 | Nicoletta     | Parisi     | 1992-09-06    | LJCAEQ70K58K517A | 2020-10-26     | 624399              | lorenzo.messina@libero.it          |
| 4371 |        58 | Soriana       | Conte      | 1979-08-20    | LIGHLG93W79M623P | 2020-02-26     | 624403              | ercole.valentini@gmail.com         |
| 4372 |        42 | Dindo         | D'angelo   | 1984-05-19    | EZEZQS60M11N421P | 2020-10-24     | 624404              | pellegrino.arturo@ricci.com        |
| 4373 |        21 | Diana         | De Santis  | 1989-05-04    | GHLJSY82C24A973O | 2020-02-10     | 624405              | pricci@yahoo.it                    |
| 4374 |        26 | Hector        | Marino     | 1989-01-22    | UXXNUI99W98K712O | 2018-07-27     | 624406              | michele61@valentini.com            |
| 4376 |        10 | Ortensia      | Gentile    | 1977-09-27    | PMMPQG54U88Z786C | 2018-10-09     | 624408              | gcaruso@carbone.org                |
| 4379 |         6 | Alessandro    | Mancini    | 1992-10-07    | FPIQOE28B46N598T | 2020-02-07     | 624411              | rebecca89@giuliani.org             |
| 4380 |        12 | Vania         | Sorrentino | 1971-10-29    | GPHGLU46I19F770X | 2020-05-10     | 624412              | erossi@costantini.net              |
| 4382 |        71 | Lisa          | Neri       | 1977-08-25    | AMETLY56J63V997V | 2019-12-30     | 624414              | manfredi62@mariani.com             |
| 4383 |        61 | Rosita        | Rossi      | 1971-12-21    | LUYKDD22V01Z445G | 2019-02-05     | 624415              | jpellegrini@libero.it              |
| 4385 |        29 | Clodovea      | Rossetti   | 1985-02-03    | UDZQPB86H87H288V | 2021-04-09     | 624417              | zfontana@libero.it                 |
| 4386 |        44 | Ione          | Rinaldi    | 1977-04-26    | WHMGDK27P89H181D | 2018-10-11     | 624418              | pgrassi@montanari.net              |
| 4387 |        55 | Antonino      | Montanari  | 1973-01-31    | XHMQVR13F57S305D | 2019-06-07     | 624419              | coppola.samira@yahoo.com           |
| 4388 |        52 | Albino        | Messina    | 1989-10-15    | BFJPUW45C48Y415R | 2019-05-30     | 624420              | vricci@yahoo.it                    |
| 4389 |        66 | Erminio       | Rinaldi    | 1984-09-26    | OFFCAL94O03F448V | 2021-02-13     | 624421              | jack.rizzi@bianco.com              |
| 4390 |        39 | Demis         | Bianco     | 1988-07-06    | VMTITB81M67X715U | 2018-10-02     | 624422              | romeo00@conte.org                  |
| 4391 |        18 | Lucrezia      | Messina    | 1987-07-06    | TKXYCI24N65T155R | 2020-01-30     | 624423              | fserra@sartori.it                  |
| 4392 |        71 | Donatella     | Farina     | 1983-05-28    | KEKWTA54A90Y499L | 2020-05-24     | 624424              | danuta02@yahoo.it                  |
| 4393 |        36 | Gioacchino    | Pellegrino | 1989-09-23    | WLEEDD50J91B753Y | 2020-10-13     | 624425              | shaira.negri@libero.it             |
| 4394 |         7 | Gilda         | De Angelis | 1971-08-13    | XPCCUR24H22J125V | 2019-08-04     | 624426              | dylan83@neri.it                    |
| 4395 |        32 | Giulietta     | Lombardo   | 1983-09-12    | TFJFKZ62Y95N888Y | 2020-05-16     | 624427              | violante94@bernardi.com            |
| 4396 |        69 | Raoul         | Neri       | 1991-12-23    | LVYDZH05J44S993G | 2018-07-13     | 624428              | basile.radio@russo.com             |
| 4397 |         8 | Ruth          | Santoro    | 1992-08-03    | XXPRCY91Q21B389S | 2020-11-22     | 624429              | umberto41@martino.com              |
| 4399 |        29 | Deborah       | Sartori    | 1989-10-10    | JKKTJP89U30T230A | 2019-06-04     | 624431              | mazza.nestore@email.it             |
| 4403 |        31 | Domiziano     | Conti      | 1977-09-02    | FBPVWF26I44A868Y | 2020-07-08     | 624435              | brizzi@grasso.it                   |
| 4404 |        11 | Cristyn       | Riva       | 1976-05-17    | LWOSXE45M97A880M | 2020-11-28     | 624436              | conte.samira@email.it              |
| 4409 |        67 | Rosalba       | Santoro    | 1976-05-31    | YNURGU63G23R740Y | 2021-05-23     | 624441              | ecostantini@dangelo.com            |
| 4412 |        42 | Loris         | Parisi     | 1988-01-09    | MTTXYH30F58D555X | 2020-04-28     | 624444              | bconte@galli.it                    |
| 4414 |        59 | Fortunata     | Gallo      | 1979-11-10    | WXQYSN14R01A699F | 2019-12-07     | 624446              | cristyn.giuliani@email.it          |
| 4415 |        25 | Deborah       | Ricci      | 1981-03-31    | FOSSLU47U75R118B | 2019-07-10     | 624447              | egisto.grasso@gmail.com            |
| 4416 |        73 | Joseph        | Pellegrini | 1983-08-30    | TPHYIN17R86N206J | 2019-08-16     | 624448              | karim.santoro@hotmail.com          |
| 4417 |        73 | Kris          | De luca    | 1989-12-08    | MYVBUF80B21V662W | 2021-05-09     | 624449              | ldeangelis@donati.com              |
| 4420 |        21 | Donatella     | Neri       | 1976-09-04    | XYSRSO48Y23V581C | 2021-02-08     | 624452              | villa.antimo@email.it              |
| 4421 |         9 | Siro          | Testa      | 1991-09-20    | GTCRBU78I65U276Q | 2020-10-02     | 624453              | danuta.messina@libero.it           |
| 4422 |        44 | Noel          | Parisi     | 1973-03-28    | KPPYES49F02V012R | 2021-05-03     | 624454              | mlombardo@orlando.com              |
| 4423 |        68 | Ortensia      | Romano     | 1988-05-30    | TSKWPZ37G96U549Q | 2019-11-04     | 624455              | derosa.filomena@yahoo.it           |
| 4424 |        17 | Mariagiulia   | Costa      | 1987-01-27    | YAKGKM90N68D770N | 2021-05-24     | 624456              | ebenedetti@hotmail.com             |
| 4425 |        64 | Alessio       | Giuliani   | 1978-07-22    | YIIFWA99N50S309L | 2019-11-12     | 624457              | marini.piccarda@fontana.net        |
| 4426 |        14 | Zelida        | Piras      | 1983-09-10    | IKJORF30P21N889P | 2021-02-25     | 624458              | rossi.elda@libero.it               |
| 4429 |        73 | Mattia        | Lombardo   | 1984-12-29    | CHBRJH74Q43F997Y | 2018-09-22     | 624461              | rosolino27@gmail.com               |
| 4430 |         1 | Pericle       | Battaglia  | 1983-11-29    | ZRVEJD65M92O923Y | 2019-08-06     | 624462              | palumbo.kris@montanari.it          |
| 4431 |        68 | Rosaria       | Gatti      | 1979-07-07    | HOCFKY77Z29Y543D | 2021-03-17     | 624463              | selvaggia.neri@colombo.it          |
| 4432 |         1 | Ubaldo        | Villa      | 1972-08-24    | KGYQTZ45K72W232V | 2021-03-28     | 624464              | sarita.costa@basile.it             |
| 4436 |         8 | Cassiopea     | Santoro    | 1985-03-30    | QTRNWP77J04H080F | 2019-01-29     | 624468              | zbattaglia@bernardi.com            |
| 4438 |        30 | Maika         | Fontana    | 1971-11-14    | YDWTAX99X55S570H | 2020-07-25     | 624470              | gmontanari@basile.com              |
| 4440 |        75 | Kris          | Negri      | 1990-10-21    | TCAHFC11Z65C665U | 2019-03-20     | 624472              | marini.selvaggia@esposito.org      |
| 4441 |        27 | Selvaggia     | D'angelo   | 1977-05-26    | BPULEH27B15I832T | 2019-01-07     | 624473              | jarno68@gmail.com                  |
| 4442 |         7 | Diamante      | Fontana    | 1978-08-24    | MLQSUP47G60L390N | 2019-03-14     | 624474              | fmessina@guerra.it                 |
| 4443 |        17 | Ione          | Ruggiero   | 1983-09-12    | SBPKEN47G45U445M | 2018-07-26     | 624475              | costanzo.longo@email.it            |
| 4444 |        65 | Ciro          | Donati     | 1991-10-03    | SZDNME16E73F022R | 2019-02-22     | 624476              | rocco10@rinaldi.com                |
| 4445 |        25 | Tosca         | Riva       | 1984-10-25    | IVXOZT57U72M351F | 2020-06-10     | 624477              | dlombardo@yahoo.it                 |
| 4446 |        75 | Gregorio      | Morelli    | 1980-08-18    | FEMLPI54T73N635Z | 2018-10-09     | 624478              | penelope91@orlando.org             |
| 4447 |        32 | Enzo          | Ferrari    | 1984-10-14    | ZCAOCO18H90E052E | 2019-06-02     | 624479              | ermes.conti@libero.it              |
| 4449 |        39 | Giacinta      | Bernardi   | 1991-05-15    | EOGTGH76U22N445O | 2020-04-01     | 624481              | timothy27@libero.it                |
| 4450 |        50 | Pericle       | Rizzo      | 1985-09-27    | CMIDRH87T16T160N | 2021-01-11     | 624482              | sdonati@libero.it                  |
| 4451 |        39 | Harry         | Battaglia  | 1985-05-26    | TMRCFN52K61Y911O | 2018-09-29     | 624483              | jelena22@basile.it                 |
| 4452 |        49 | Sasha         | Martinelli | 1979-05-23    | MYYQJX41P08X975A | 2020-06-22     | 624484              | caputo.sebastian@libero.it         |
| 4454 |        61 | Gilda         | De Santis  | 1977-10-26    | ZOWXYW77N01B712Y | 2019-11-29     | 624486              | cpiras@yahoo.it                    |
| 4455 |        22 | Guendalina    | Damico     | 1986-08-18    | PPAASY76W26C590V | 2020-07-31     | 624487              | ferretti.lucia@desantis.it         |
| 4459 |        13 | Sue ellen     | Vitale     | 1972-08-05    | JLMQFZ44E59H763Q | 2020-12-06     | 624491              | fatima32@email.it                  |
| 4461 |         8 | Genziana      | Galli      | 1986-02-14    | TKPQMH40M95O588T | 2020-02-09     | 624493              | emanuel.giordano@rizzo.it          |
| 4462 |        28 | Gioacchino    | Gallo      | 1985-10-15    | SWVCNJ53O49S887B | 2019-11-08     | 624494              | benedetta37@battaglia.it           |
| 4463 |        26 | Miriam        | Grassi     | 1984-07-14    | AYCGAO35Q61B332O | 2020-09-22     | 624495              | ksartori@grassi.net                |
| 4464 |        49 | Graziano      | Longo      | 1976-04-29    | UMTMFS59J67B514D | 2018-07-13     | 624496              | dcostantini@milani.it              |
| 4467 |        46 | Michele       | Martino    | 1983-07-21    | KVPENI71F38V540P | 2019-02-21     | 624499              | martinelli.akira@email.it          |
| 4468 |        33 | Emanuel       | Parisi     | 1991-10-01    | ZGPUBX05V43L206L | 2019-10-22     | 624500              | battaglia.alberto@yahoo.com        |
| 4469 |        11 | Sarita        | Parisi     | 1984-09-28    | ENXXLY72K07C118C | 2020-06-10     | 624501              | neri38@grasso.it                   |
| 4471 |        30 | Noemi         | Ruggiero   | 1987-09-23    | DPMNJA15I35L816X | 2018-10-11     | 624503              | bibiana.rossi@valentini.com        |
| 4472 |        20 | Laura         | Donati     | 1973-09-26    | ADNGRY23K13U419B | 2019-11-30     | 624504              | silverio56@gmail.com               |
| 4474 |        19 | Luce          | Villa      | 1974-01-23    | WKUSKU28U96N807X | 2020-07-18     | 624506              | amonti@donati.it                   |
| 4475 |        33 | Mauro         | De luca    | 1981-03-05    | UYFSOE91F70M758C | 2019-05-07     | 624507              | negri.artes@giuliani.com           |
| 4476 |        42 | Grazia        | Lombardi   | 1991-12-24    | VVYOSB75A58M485E | 2021-04-26     | 624508              | dserra@email.it                    |
| 4477 |        16 | Penelope      | Pellegrino | 1983-01-11    | IWVOIJ56J41G383C | 2018-09-24     | 624509              | deangelis.marina@hotmail.com       |
| 4478 |        30 | Lidia         | Gallo      | 1978-07-11    | IDLVNK21Y78Z866B | 2020-09-03     | 624510              | oferretti@yahoo.it                 |
| 4479 |        71 | Vania         | Rizzo      | 1986-01-21    | ATUGIK77J32P772W | 2021-05-08     | 624511              | pellegrini.lucia@russo.net         |
| 4481 |         6 | Elsa          | Sala       | 1979-01-15    | HFKKFX07K70L258C | 2019-06-27     | 624513              | cattaneo.claudia@grasso.com        |
| 4482 |        56 | Mariano       | Ricci      | 1986-04-10    | AXDIQV24B53C100I | 2020-02-23     | 624514              | bellini.costanzo@neri.com          |
| 4484 |        63 | Tazio         | Barone     | 1972-02-07    | YUOMWC33I06L111G | 2021-04-28     | 624516              | loredana89@montanari.it            |
| 4486 |        23 | Ione          | Orlando    | 1981-07-18    | OTLKOQ61M89P954I | 2018-06-14     | 624518              | obenedetti@email.it                |
| 4487 |        66 | Quarto        | Ferrara    | 1979-11-04    | HBZSYZ33W62O417C | 2021-06-01     | 624519              | negri.gianantonio@yahoo.it         |
| 4488 |        25 | Tosca         | Russo      | 1977-08-03    | LAHRKU82D32Q966W | 2019-07-12     | 624520              | graziano44@yahoo.it                |
| 4491 |        16 | Marieva       | Gatti      | 1976-07-13    | VAIZSQ84Q63J863N | 2018-07-20     | 624523              | soriana69@libero.it                |
| 4492 |        23 | Selvaggia     | Caruso     | 1980-09-13    | BLURMO73W99U383G | 2021-04-27     | 624524              | maruska14@hotmail.com              |
| 4493 |         3 | Giordano      | Villa      | 1984-06-02    | SJMXAF10A87W678Z | 2020-01-21     | 624525              | fiore.rocco@yahoo.com              |
| 4494 |        45 | Raniero       | Fiore      | 1989-08-05    | WFROFJ22P92N468K | 2019-07-16     | 624526              | tbasile@yahoo.it                   |
| 4495 |        36 | Clea          | Carbone    | 1975-08-02    | PIFVFK29L25Y754O | 2021-05-01     | 624527              | mauro44@bellini.it                 |
| 4496 |        49 | Rita          | Negri      | 1980-05-14    | FLIDXQ83T50W443X | 2020-09-02     | 624528              | galli.eufemia@milani.com           |
| 4497 |         5 | Kociss        | Palumbo    | 1992-09-25    | FSMTKI64X60A419V | 2020-02-15     | 624529              | serra.zelida@neri.com              |
| 4498 |        69 | Helga         | Fiore      | 1977-02-10    | PLROTT27G41B247H | 2021-01-30     | 624530              | druggiero@orlando.it               |
| 4500 |        73 | Gaetano       | Leone      | 1985-02-08    | FQUBVI47J21M640X | 2019-09-14     | 624532              | lombardo.nestore@gmail.com         |
| 4501 |         6 | Lorenzo       | Palmieri   | 1979-07-17    | ZNDMVY76C09T663K | 2019-11-03     | 624533              | raniero21@pellegrini.it            |
| 4502 |         3 | Antimo        | Carbone    | 1988-06-25    | CTBNKE48K47V014U | 2018-07-19     | 624534              | arcibaldo91@marino.org             |
| 4503 |        23 | Donatella     | Martini    | 1975-07-09    | MYJVGH79N92D818D | 2020-02-28     | 624535              | marzio.ferri@email.it              |
| 4504 |         4 | Grazia        | Negri      | 1975-01-11    | QYIIBO08A70U972E | 2020-07-04     | 624536              | vitale.lucrezia@costa.it           |
| 4505 |        75 | Gastone       | Martino    | 1976-10-08    | BIDTKQ19J91G377A | 2020-11-07     | 624537              | jmazza@yahoo.it                    |
| 4508 |         6 | Alighieri     | Giordano   | 1983-06-23    | FJQXGR19L17D780F | 2019-06-12     | 624540              | osvaldo.sorrentino@pellegrini.org  |
| 4509 |        57 | Maruska       | De Angelis | 1978-01-09    | QBZPPE52P87I097R | 2020-01-14     | 624541              | ferri.tolomeo@benedetti.com        |
| 4511 |        37 | Leonardo      | Pellegrino | 1990-07-11    | INMMYK92C33X493N | 2020-03-23     | 624543              | gastone.silvestri@rossetti.net     |
| 4512 |        49 | Mauro         | Gentile    | 1976-04-17    | YXLUNI31R29U982N | 2019-04-30     | 624544              | silverio79@libero.it               |
| 4513 |        48 | Edipo         | Coppola    | 1987-10-25    | QHWBWA91U47K450Z | 2018-12-01     | 624545              | nadir39@libero.it                  |
| 4515 |         2 | Ippolito      | Bianchi    | 1986-05-17    | GXDNIV74L57G165W | 2019-10-03     | 624547              | gentile.gianriccardo@morelli.it    |
| 4517 |        60 | Cesidia       | Mancini    | 1980-08-30    | KINFGO69O31F729F | 2018-09-17     | 624549              | mmarchetti@galli.com               |
| 4518 |        49 | Violante      | Ferrara    | 1990-03-10    | YBWMQC69S08Y335D | 2019-06-26     | 624550              | aaron21@vitali.it                  |
| 4519 |        67 | Dindo         | Parisi     | 1979-08-11    | DGCSSP83R28D423C | 2019-10-29     | 624551              | hpellegrino@valentini.com          |
| 4521 |        58 | Lisa          | Martini    | 1984-03-30    | RAEUUC80B79I016H | 2019-09-28     | 624553              | penelope27@grasso.it               |
| 4522 |        42 | Olimpia       | Conte      | 1976-06-03    | VTJOHV94W69B077B | 2018-06-14     | 624554              | dbernardi@yahoo.it                 |
| 4523 |        19 | Brigitta      | Cattaneo   | 1974-03-07    | WFAJGY22Y85X372P | 2018-07-31     | 624555              | edvige.rizzo@damico.com            |
| 4524 |        74 | Shaira        | De luca    | 1981-02-28    | PTUMQQ25M48R973K | 2019-09-24     | 624556              | ferdinando.mancini@yahoo.com       |
| 4525 |        75 | Carmela       | Fontana    | 1975-07-02    | CJUJDO93V18Y810R | 2019-09-08     | 624557              | gpiras@santoro.com                 |
| 4526 |        73 | Cira          | Caruso     | 1979-08-11    | PXTHMZ68F56F080S | 2020-09-16     | 624558              | gelsomina56@marino.org             |
| 4527 |        48 | Mattia        | Villa      | 1991-02-05    | DLFMGN10L47D860X | 2021-05-27     | 624559              | renzo60@bellini.com                |
| 4528 |        60 | Abramo        | Ferri      | 1978-08-09    | YWWUIC53W09G599I | 2019-04-05     | 624560              | valdo.giordano@gmail.com           |
| 4529 |        21 | Moreno        | Grassi     | 1979-10-07    | NSXOJB88H23J207P | 2020-03-07     | 624561              | rizzo.nazzareno@hotmail.com        |
| 4535 |        39 | Ursula        | Benedetti  | 1972-02-11    | OTWQRG88P61C176P | 2020-03-13     | 624567              | eufemia.martini@email.it           |
| 4536 |        11 | Erminia       | Marini     | 1981-10-31    | CAMYIU95G54G425J | 2018-12-30     | 624568              | anselmo22@bellini.it               |
| 4540 |        13 | Gregorio      | Fabbri     | 1990-11-21    | TEZGHJ49M20L625V | 2020-01-08     | 624572              | tancredi96@mazza.it                |
| 4541 |        59 | Bibiana       | Grassi     | 1978-10-09    | ZXYJDY67A69V568K | 2018-11-21     | 624573              | celeste.piras@mazza.com            |
| 4542 |        67 | Renato        | Battaglia  | 1992-03-26    | JVGHEI21D25J591Z | 2019-06-05     | 624574              | namato@email.it                    |
| 4543 |        72 | Radames       | Bellini    | 1983-09-17    | JXVPAE44X16D092O | 2020-10-18     | 624575              | giulietta67@email.it               |
| 4544 |        23 | Iacopo        | Romano     | 1977-12-08    | MIYPQS48R54Q535G | 2018-06-09     | 624576              | gianantonio12@yahoo.it             |
| 4545 |        68 | Artemide      | Sorrentino | 1976-06-14    | FBPXQL53X92U114K | 2020-12-11     | 624577              | dante80@rinaldi.com                |
| 4546 |        58 | Egidio        | Sala       | 1977-03-11    | PZGUZH03T51B642G | 2019-12-12     | 624578              | ocarbone@yahoo.it                  |
| 4547 |        38 | Radames       | Fiore      | 1981-02-27    | HIOEAZ76M89C041B | 2021-01-09     | 624579              | ecoppola@yahoo.it                  |
| 4548 |        36 | Antonino      | Sala       | 1984-07-10    | XJKZGZ84P68E703K | 2019-06-01     | 624580              | aricci@hotmail.com                 |
| 4551 |        67 | Emanuel       | Barone     | 1991-10-14    | IYOAYF73S98S721A | 2020-05-24     | 624583              | ncattaneo@yahoo.com                |
| 4555 |        27 | Secondo       | Pellegrini | 1977-06-17    | IBCYNJ76M96G544Z | 2020-07-24     | 624587              | gcarbone@ferretti.it               |
| 4556 |        37 | Gilda         | Vitale     | 1992-05-12    | WCWMUF65Y07G529Z | 2018-07-13     | 624588              | caruso.arduino@yahoo.it            |
| 4557 |        67 | Rudy          | Marchetti  | 1975-11-09    | DEAWSQ50T66G207G | 2019-10-03     | 624589              | nadir.martini@yahoo.it             |
| 4558 |        73 | Maruska       | Mazza      | 1982-05-01    | VBWAFJ45T34K399Z | 2019-12-16     | 624590              | ztesta@mancini.com                 |
| 4560 |        72 | Marieva       | Greco      | 1990-10-03    | WRARDI30L48N985S | 2020-04-23     | 624592              | sorrentino.maria@milani.it         |
| 4561 |        32 | Samuel        | Marino     | 1973-06-02    | XARPVA09N55M688I | 2018-07-20     | 624593              | uferrari@yahoo.com                 |
| 4562 |        23 | Filomena      | D'angelo   | 1974-04-26    | RBWPIV44P11A683I | 2020-10-03     | 624594              | radames26@martino.net              |
| 4563 |        38 | Walter        | Battaglia  | 1978-03-27    | CNUHKE10O18M651N | 2019-09-14     | 624595              | danthon65@sala.it                  |
| 4564 |        59 | Donatella     | Sanna      | 1983-06-23    | YQJPYE65K73N681R | 2021-05-30     | 624596              | prisca.vitali@parisi.com           |
| 4565 |        20 | Kai           | Rizzo      | 1983-06-19    | MBFGTR80S16F436Y | 2018-07-14     | 624597              | violante04@email.it                |
| 4566 |        18 | Kayla         | Rossi      | 1980-09-04    | MODMXW98B31P061Z | 2019-01-19     | 624598              | sarita.gentile@gmail.com           |
| 4568 |        45 | Gelsomina     | Colombo    | 1987-06-26    | XIXCRK87C78O538V | 2020-03-11     | 624600              | kconte@ferrara.it                  |
| 4569 |        71 | Kayla         | Bernardi   | 1974-04-18    | WALCTK55O76K222K | 2019-10-17     | 624601              | gelsomina99@libero.it              |
| 4570 |        45 | Diamante      | Sorrentino | 1985-03-21    | NQMWRK82M71U370V | 2020-11-01     | 624602              | ivano88@neri.com                   |
| 4571 |        45 | Ingrid        | Pagano     | 1990-07-12    | BQIMBG48O40R286L | 2021-01-30     | 624603              | abarbieri@conti.it                 |
| 4572 |        35 | Ursula        | Amato      | 1984-08-22    | ZZIUKC77L95W498L | 2020-03-04     | 624604              | arcibaldo.desantis@gmail.com       |
| 4573 |         5 | Lucia         | Ruggiero   | 1981-01-05    | LOAXRA75H58S634Z | 2019-03-17     | 624605              | tesposito@gallo.it                 |
| 4575 |        31 | Laura         | Coppola    | 1989-03-29    | NHVCYX26A18H914V | 2019-06-10     | 624607              | erminio21@hotmail.com              |
| 4576 |        22 | Artes         | Sorrentino | 1974-08-08    | ZSOOMD87Q93B019Z | 2021-04-05     | 624608              | damiana48@carbone.it               |
| 4578 |        54 | Flavio        | Vitali     | 1981-10-20    | SRFQSV96R89M999I | 2018-07-06     | 624610              | kriva@yahoo.com                    |
| 4581 |        69 | Loris         | Negri      | 1976-03-01    | KPWBNJ42A00O698O | 2020-03-13     | 624613              | ferretti.diamante@gmail.com        |
| 4582 |        63 | Ortensia      | Grasso     | 1977-04-26    | MOUJBQ57K59S362Z | 2019-10-08     | 624614              | irene51@hotmail.com                |
| 4583 |        61 | Demian        | Pellegrino | 1987-03-20    | ANQEQE53M80H288K | 2020-12-09     | 624615              | vitale.elda@montanari.com          |
| 4584 |         7 | Renato        | Leone      | 1988-07-16    | EPEWOI31C51J399N | 2019-12-08     | 624616              | evangelista46@libero.it            |
| 4585 |        36 | Assia         | Riva       | 1977-07-06    | AUQWVC68Z37R871T | 2020-04-05     | 624617              | rmartino@conte.com                 |
| 4586 |        43 | Secondo       | Barbieri   | 1976-05-15    | PUXSJF54N85E933E | 2018-07-25     | 624618              | fricci@gmail.com                   |
| 4587 |        46 | Piccarda      | Serra      | 1988-11-21    | SOYEJG18U39C148S | 2019-01-14     | 624619              | artemide.mariani@email.it          |
| 4589 |        45 | Naomi         | De rosa    | 1983-07-05    | ZONIEO43H80J284Y | 2020-09-19     | 624621              | orlando.silverio@mancini.org       |
| 4590 |        67 | Clodovea      | Pellegrino | 1978-05-04    | PGSCYR13C19J864W | 2020-06-27     | 624622              | tbasile@bellini.net                |
| 4592 |        67 | Benedetta     | De rosa    | 1984-06-16    | GMQUTI58L68U758W | 2019-11-22     | 624624              | xmontanari@ferrari.net             |
| 4594 |         3 | Concetta      | Romano     | 1990-11-27    | ISRMCP44D14N688V | 2019-12-14     | 624626              | gabriele77@yahoo.com               |
| 4595 |        65 | Maruska       | Grasso     | 1972-03-25    | QGTPDO70Q30A554F | 2018-06-27     | 624627              | pagano.oretta@marchetti.it         |
| 4596 |        71 | Kayla         | Testa      | 1988-02-21    | POTEGY10D57D961W | 2019-01-17     | 624628              | eufemia.caputo@yahoo.it            |
| 4597 |        29 | Shaira        | Riva       | 1979-10-08    | YVHLFH84S57S148N | 2018-06-15     | 624629              | mgalli@libero.it                   |
| 4598 |        58 | Jarno         | D'angelo   | 1976-02-28    | VXRNTW22A73K946C | 2020-06-18     | 624630              | idamico@fontana.it                 |
| 4599 |        23 | Davis         | Donati     | 1983-09-28    | ZDXVMV10P40I428X | 2021-03-05     | 624631              | gatti.marco@martinelli.org         |
| 4601 |        30 | Iacopo        | Riva       | 1977-04-29    | CBKGQP41Y86L176F | 2021-03-16     | 624633              | giordano.samuel@libero.it          |
| 4604 |        17 | Clea          | Grassi     | 1976-07-14    | VJATDP47D59C813D | 2019-01-04     | 624636              | irene80@rizzo.net                  |
| 4605 |        39 | Omar          | Bernardi   | 1985-10-18    | VVSDKI27Z93U457K | 2019-01-01     | 624637              | conti.mariagiulia@galli.it         |
| 4608 |        19 | Tazio         | Cattaneo   | 1981-02-28    | FXCEGE53C94D546Z | 2018-11-22     | 624640              | gianleonardo90@yahoo.com           |
| 4609 |         5 | Baldassarre   | Sanna      | 1972-05-31    | QMELYS88W91F890G | 2020-12-20     | 624641              | gianantonio.caruso@ferretti.it     |
| 4611 |        14 | Ileana        | De Angelis | 1979-04-02    | VFUAZA55K07D869L | 2020-10-06     | 624643              | pellegrini.tosca@gatti.com         |
| 4613 |        55 | Valdo         | Monti      | 1990-07-27    | EOCYBU51C01G153T | 2019-10-21     | 624645              | rocco.sartori@yahoo.it             |
| 4616 |        69 | Ileana        | Neri       | 1973-10-02    | GSRUEG60F27B358E | 2019-04-09     | 624648              | luna.ferri@email.it                |
| 4618 |        44 | Genziana      | Basile     | 1981-07-18    | LQDMHL29M24E726G | 2020-06-15     | 624650              | baldassarre41@gmail.com            |
| 4620 |        21 | Matilde       | Piras      | 1975-03-06    | VFOFVF38B18F049P | 2019-10-29     | 624652              | giuliani.deborah@rizzo.it          |
| 4621 |         9 | Morgana       | Palmieri   | 1983-03-26    | PHUZVY06M98U911P | 2019-06-19     | 624653              | marchetti.cirino@marchetti.net     |
| 4622 |        58 | Nicoletta     | Barone     | 1972-03-24    | UIGDVA19X78M179C | 2019-07-15     | 624654              | ramato@yahoo.it                    |
| 4624 |        59 | Maria         | Cattaneo   | 1985-03-16    | ZIOIEW91Q79J681O | 2021-01-19     | 624656              | vgalli@hotmail.com                 |
| 4625 |        60 | Sasha         | Ferri      | 1976-04-29    | FWCILH71J21Z211S | 2018-08-02     | 624657              | aleone@amato.com                   |
| 4627 |        74 | Fulvio        | Vitale     | 1991-11-23    | SATGZU00Q16L769J | 2020-08-24     | 624659              | zcaruso@yahoo.com                  |
| 4628 |        16 | Danny         | Bianco     | 1990-03-05    | OIHSKK93C84J608D | 2018-12-14     | 624660              | unegri@hotmail.com                 |
| 4629 |        62 | Evangelista   | Barbieri   | 1976-12-07    | ODFFAX55D94F478R | 2020-11-15     | 624661              | hbruno@grasso.it                   |
| 4630 |        65 | Marianita     | Milani     | 1986-12-27    | OMXLLU57T84J376V | 2021-02-19     | 624662              | ileana73@hotmail.com               |
| 4632 |        50 | Arturo        | Parisi     | 1976-01-07    | XLGENP23X25J763J | 2018-10-11     | 624664              | piras.romolo@vitale.com            |
| 4633 |        27 | Filomena      | Coppola    | 1989-06-03    | TUWDNB09K54E086E | 2018-08-17     | 624665              | nicoletta40@yahoo.it               |
| 4634 |        41 | Kayla         | Neri       | 1989-01-17    | XGEBIX62R10D834O | 2020-08-03     | 624666              | cbattaglia@gatti.net               |
| 4635 |        43 | Giacinta      | Bianchi    | 1986-05-19    | LERADE12X63H197R | 2019-05-06     | 624667              | giovanna08@gmail.com               |
| 4636 |        59 | Clodovea      | De luca    | 1983-04-13    | JCSPRX58G14P972X | 2018-11-08     | 624668              | donatella83@email.it               |
| 4637 |        10 | Tristano      | Vitale     | 1972-01-21    | IXSLTC62T86C877T | 2020-12-09     | 624669              | tgentile@gmail.com                 |
| 4639 |        70 | Evita         | Greco      | 1988-05-22    | IJXZUU26X56A575Z | 2020-01-18     | 624671              | cira59@libero.it                   |
| 4640 |        22 | Jack          | Esposito   | 1977-03-25    | POIWGD93A36X767Z | 2019-12-21     | 624672              | conti.ileana@yahoo.com             |
| 4641 |         3 | Mariapia      | Messina    | 1975-04-23    | PGEVAE97U76M564W | 2019-07-28     | 624673              | rosalba.vitali@gmail.com           |
| 4642 |        24 | Concetta      | D'angelo   | 1974-02-28    | RRKNMF10M17C013Q | 2020-06-02     | 624674              | rosolino61@ferrari.it              |
| 4644 |         2 | Gerlando      | Gallo      | 1984-03-13    | BPNNHC95W92X493X | 2018-06-20     | 624676              | kayla07@yahoo.com                  |
| 4647 |        41 | Pietro        | Rizzo      | 1980-04-20    | FRJQZL91A00H040T | 2020-08-06     | 624679              | drusso@serra.com                   |
| 4649 |        10 | Ingrid        | Leone      | 1976-10-06    | TROMXN38S71U718M | 2018-09-28     | 624681              | pbellini@martini.com               |
| 4650 |        24 | Alighiero     | Colombo    | 1982-05-17    | WLVYMR00N83M533G | 2021-04-17     | 624682              | osea18@yahoo.com                   |
| 4651 |        51 | Damiana       | Marini     | 1982-01-19    | ATXINE27Q77I382W | 2020-07-22     | 624683              | tmorelli@hotmail.com               |
| 4652 |         5 | Alberto       | Pagano     | 1986-03-18    | GVTOKT09P87F946S | 2019-04-05     | 624684              | lombardo.laerte@caruso.com         |
| 4655 |        63 | Ian           | Sorrentino | 1980-03-05    | OXWFKZ42O25Q856T | 2020-05-31     | 624687              | oretta.vitale@hotmail.com          |
| 4656 |        46 | Danthon       | Palumbo    | 1983-10-15    | SVSUUX69F72N344V | 2020-04-11     | 624688              | quarto.morelli@email.it            |
| 4658 |        58 | Loretta       | Carbone    | 1984-10-21    | JLYCWL12M31U477N | 2021-01-03     | 624690              | giacinto32@damico.net              |
| 4659 |        60 | Vera          | Villa      | 1980-12-20    | FNNRJM25W77X209M | 2020-01-24     | 624691              | dsantoro@negri.com                 |
| 4660 |        54 | Mariagiulia   | Coppola    | 1973-09-19    | GCRFGR85S48K514D | 2021-04-03     | 624692              | ursula15@yahoo.com                 |
| 4662 |        39 | Giacinta      | Donati     | 1976-04-07    | SGOCDT94B09U779L | 2019-07-29     | 624694              | coppola.miriam@hotmail.com         |
| 4663 |        59 | Noah          | Galli      | 1991-04-18    | DBUYQD90A25G006E | 2020-07-11     | 624695              | ercole.bellini@libero.it           |
| 4664 |        21 | Amos          | Serra      | 1979-02-03    | WXSVTG42E03R523O | 2020-05-22     | 624696              | elga88@gmail.com                   |
| 4666 |        26 | Nayade        | Ferraro    | 1971-12-15    | SFSOHP19Q91E534R | 2021-02-27     | 624698              | ramato@email.it                    |
| 4667 |        10 | Osea          | Marino     | 1984-11-16    | DNJQFV79E39W855Q | 2020-04-21     | 624699              | aferrara@gatti.it                  |
| 4674 |        21 | Ruth          | Amato      | 1981-10-17    | EIMSKW54A23D437N | 2020-05-24     | 624706              | gianriccardo06@gmail.com           |
| 4677 |        61 | Giacinta      | Carbone    | 1989-12-01    | TQPTIC40I88C639M | 2021-01-22     | 624709              | eustachio.ferrari@yahoo.it         |
| 4679 |        10 | Piccarda      | De rosa    | 1986-07-05    | FWFVXZ78S05E538P | 2018-10-25     | 624711              | colombo.rosalba@milani.com         |
| 4680 |        22 | Ortensia      | Martinelli | 1988-06-08    | DJZDPC58T32D216G | 2021-02-27     | 624712              | nneri@email.it                     |
| 4682 |        58 | Fiorenzo      | Parisi     | 1980-10-31    | JQMIMG89N25Q131D | 2020-06-30     | 624714              | zaccaria55@ferri.net               |
| 4683 |        36 | Ethan         | Pellegrini | 1980-11-22    | EHJVYI54T88H500A | 2020-10-17     | 624715              | amerigo54@yahoo.it                 |
| 4686 |        28 | Amedeo        | Fiore      | 1975-06-15    | DWZSMU77X59O454P | 2018-12-13     | 624718              | serse54@palmieri.it                |
| 4687 |        71 | Ferdinando    | De rosa    | 1988-12-07    | GYBVRI66K46X738Y | 2019-11-28     | 624719              | giacinta70@libero.it               |
| 4688 |        15 | Deborah       | Romano     | 1981-04-29    | LEQKCX42I16B947P | 2019-09-21     | 624720              | pablo34@fiore.com                  |
| 4691 |        60 | Cosetta       | Galli      | 1991-05-14    | NTFXQV81W80Y943U | 2020-02-14     | 624723              | tneri@yahoo.com                    |
| 4692 |        58 | Fabiano       | Caruso     | 1992-04-07    | JYTSXG63W28D283W | 2019-01-22     | 624724              | trevis.pellegrini@gmail.com        |
| 4693 |        20 | Zelida        | Parisi     | 1971-10-27    | SHQRDM67T68I074P | 2019-09-19     | 624725              | sartori.luna@gmail.com             |
| 4694 |        32 | Marina        | Sorrentino | 1973-07-18    | ZQVMVF61D21I155S | 2018-12-26     | 624726              | xbruno@bianchi.net                 |
| 4695 |        64 | Umberto       | Giuliani   | 1980-11-15    | VVLSFS55A78I520W | 2020-01-01     | 624727              | doriana.carbone@yahoo.com          |
| 4698 |        30 | Ninfa         | Milani     | 1987-10-21    | XXGDZM01B32T322S | 2019-07-04     | 624730              | furio69@monti.org                  |
| 4699 |        22 | Nick          | Costantini | 1974-10-20    | ECHJXB75K51U057N | 2018-08-20     | 624731              | santoro.vitalba@yahoo.it           |
| 4700 |        43 | Grazia        | Grassi     | 1979-04-28    | BSEJZO89S59V492A | 2021-01-18     | 624732              | ldonati@yahoo.com                  |
| 4701 |        18 | Trevis        | Fontana    | 1982-09-12    | LAYWBY50M22B532X | 2020-02-23     | 624733              | vania34@gmail.com                  |
| 4702 |        63 | Danny         | Conte      | 1986-04-30    | EHRKSQ07G56X366U | 2021-05-23     | 624734              | davide24@yahoo.it                  |
| 4704 |        71 | Olimpia       | Colombo    | 1985-07-14    | HRSXXF64W75G536R | 2019-06-16     | 624736              | nayade06@barbieri.com              |
| 4705 |        54 | Miriana       | Marino     | 1972-05-06    | EOMHVA97H47A262G | 2019-11-09     | 624737              | cleopatra.piras@yahoo.com          |
| 4713 |        50 | Marvin        | Moretti    | 1980-12-24    | HEXQMD83N79E118Q | 2018-10-14     | 624745              | gatti.marvin@coppola.org           |
| 4714 |        61 | Sasha         | Marino     | 1981-12-14    | LDZWTW85V32K043J | 2018-09-08     | 624746              | marcella.bianco@rinaldi.com        |
| 4715 |        50 | Kai           | D'amico    | 1971-09-22    | RYDGRM49F60S344R | 2021-04-11     | 624747              | cira47@email.it                    |
| 4716 |        52 | Emidio        | Milani     | 1992-06-16    | NGECWN61R54B560I | 2019-09-09     | 624748              | shaira.sorrentino@mariani.com      |
| 4719 |         1 | Mietta        | Negri      | 1989-06-13    | REAZTN24V09X517L | 2019-03-20     | 624751              | serra.violante@basile.it           |
| 4721 |        58 | Luna          | Silvestri  | 1988-02-14    | ITVBMT79V36K154K | 2019-02-16     | 624753              | ruth96@email.it                    |
| 4722 |        54 | Lisa          | Orlando    | 1975-05-06    | IHZFYY47I68T499J | 2019-04-18     | 624754              | piccarda17@yahoo.com               |
| 4723 |         4 | Kociss        | Amato      | 1991-11-27    | MCJRVQ42B03H335Z | 2019-12-14     | 624755              | maristella.derosa@hotmail.com      |
| 4724 |        18 | Ciro          | Bernardi   | 1976-06-26    | PUTUGN03K96Y659N | 2018-12-15     | 624756              | battista44@farina.it               |
| 4725 |        35 | Quarto        | Giordano   | 1975-02-04    | NZKOWR60T23I447J | 2020-10-20     | 624757              | ileana.orlando@gmail.com           |
| 4726 |         4 | Santo         | Grassi     | 1980-04-14    | ZPUEKY08M83Y426W | 2021-02-20     | 624758              | aroldo00@rizzi.com                 |
| 4728 |        75 | Gerlando      | Fiore      | 1991-08-01    | SGVHVD52N40R995H | 2021-05-06     | 624760              | marco90@dangelo.org                |
| 4730 |        58 | Rosita        | Damico     | 1979-11-06    | JFHPMO31E59G655Y | 2021-03-20     | 624762              | gianriccardo.sartori@libero.it     |
| 4731 |        11 | Laura         | Marini     | 1975-03-17    | CJKCIV98Q29Y703H | 2019-02-17     | 624763              | alessio.romano@email.it            |
| 4732 |        56 | Alessandro    | Bernardi   | 1980-09-12    | ZIGXLO75Q20G017S | 2020-12-02     | 624764              | mariagiulia79@hotmail.com          |
| 4733 |        12 | Emilia        | Villa      | 1976-03-09    | EPMSAB64L45S000S | 2019-09-14     | 624765              | nfontana@sartori.net               |
| 4734 |        57 | Soriana       | Ruggiero   | 1992-02-12    | XDTNZX39A24A113W | 2019-08-12     | 624766              | michele68@yahoo.com                |
| 4735 |        69 | Sasha         | Monti      | 1976-07-18    | CADIBG15A75W690Y | 2018-11-02     | 624767              | jmarini@romano.com                 |
| 4736 |        10 | Noah          | Barone     | 1982-11-18    | MOOUVC13G16N591A | 2019-11-01     | 624768              | nestore92@libero.it                |
| 4737 |        18 | Ivonne        | Caputo     | 1988-04-22    | NIQXCN43U53V969I | 2021-03-03     | 624769              | marcella34@libero.it               |
| 4740 |        25 | Aaron         | Vitale     | 1987-12-31    | HYLWOQ89M25D574W | 2020-09-06     | 624772              | marianita.vitale@hotmail.com       |
| 4741 |        17 | Miriana       | Montanari  | 1980-05-15    | NJKZVJ61E94X786M | 2021-01-18     | 624773              | tommaso34@hotmail.com              |
| 4742 |        46 | Cosetta       | Cattaneo   | 1985-10-10    | KZKNHL92W60T093O | 2019-07-16     | 624774              | conte.antonio@dangelo.net          |
| 4743 |        46 | Ione          | Caruso     | 1971-06-19    | BZWUKC67X11M385O | 2018-07-16     | 624775              | brigitta84@yahoo.com               |
| 4745 |        12 | Irene         | Barone     | 1986-02-08    | QEOIVY72S30H825P | 2020-11-20     | 624777              | pagano.miriana@yahoo.com           |
| 4748 |        45 | Mattia        | Conti      | 1971-11-26    | CCFWUY47N98D734Z | 2020-07-20     | 624780              | jole86@yahoo.it                    |
| 4749 |        13 | Sarita        | Benedetti  | 1992-10-16    | SYWNMN12A03K433F | 2021-06-07     | 624781              | yago.farina@costa.com              |
| 4750 |         4 | Giobbe        | Fiore      | 1977-03-19    | GPHGKF89O69K222T | 2020-01-06     | 624782              | cristyn.parisi@marini.it           |
| 4751 |        30 | Pietro        | Battaglia  | 1978-06-19    | WPBKHJ32Q75V938X | 2021-06-02     | 624783              | rinaldi.graziano@sorrentino.it     |
| 4752 |        27 | Noel          | Pagano     | 1992-10-25    | GEXGDX15I38G463H | 2020-02-13     | 624784              | deangelis.quirino@yahoo.it         |
| 4753 |        62 | Kayla         | Martinelli | 1982-08-08    | MMILLO95K74Y607Q | 2020-12-06     | 624785              | gavino.moretti@email.it            |
| 4754 |        36 | Dimitri       | D'amico    | 1992-06-09    | NACQHL67Q52R618T | 2019-10-27     | 624786              | rsanna@hotmail.com                 |
| 4757 |         6 | Vitalba       | Ferrara    | 1983-02-26    | WNYRIU02Z01Y595V | 2020-08-22     | 624789              | lia.piras@grassi.org               |
| 4759 |        12 | Danuta        | Pellegrino | 1972-05-11    | TITCRP17Q94S632M | 2019-07-12     | 624791              | donati.costantino@libero.it        |
| 4760 |        13 | Cristyn       | Bellini    | 1984-09-08    | FFBHJC65T49B096D | 2018-11-12     | 624792              | farina.piccarda@email.it           |
| 4761 |        28 | Nick          | Sorrentino | 1983-09-06    | DACWSW64G27R384S | 2020-10-14     | 624793              | morelli.assia@damico.it            |
| 4762 |        18 | Ursula        | Orlando    | 1978-10-18    | AGANKF15U40Q749B | 2019-07-15     | 624794              | flavio.rizzo@bernardi.com          |
| 4764 |        47 | Quirino       | Basile     | 1979-11-16    | CVGPDV06J63H828B | 2019-08-20     | 624796              | gianmarco25@gmail.com              |
| 4765 |        67 | Romeo         | Mazza      | 1981-01-16    | VGTGMA19T11U215M | 2018-10-07     | 624797              | eusebio95@gmail.com                |
| 4768 |        50 | Aroldo        | Valentini  | 1982-10-14    | PBKBLZ52O36Z179V | 2019-12-24     | 624800              | zcostantini@grassi.org             |
| 4769 |         2 | Claudia       | Carbone    | 1989-09-14    | VNKGTK55M76V058P | 2020-03-05     | 624801              | noel28@ferraro.it                  |
| 4770 |        17 | Audenico      | Negri      | 1976-01-26    | MLVAFC03Z95T222M | 2018-12-26     | 624802              | galli.amedeo@ferrara.it            |
| 4771 |        44 | Rufo          | Morelli    | 1987-04-07    | TYIAED66P57V932R | 2020-10-04     | 624803              | nromano@marino.it                  |
| 4772 |         8 | Ione          | Ferri      | 1983-12-05    | OYAZLA98K68F578D | 2019-09-25     | 624804              | mercedes.monti@libero.it           |
| 4773 |        19 | Silverio      | Mazza      | 1992-04-20    | ZUNPYB98K82G057Z | 2020-01-27     | 624805              | rebecca.deluca@costantini.it       |
| 4774 |        42 | Elga          | Longo      | 1971-08-28    | QUQVMZ59H34Z559A | 2020-02-27     | 624806              | ninfa.marchetti@marchetti.net      |
| 4775 |        53 | Eufemia       | Fiore      | 1989-06-21    | FEBFEX79N11I792T | 2018-12-05     | 624807              | radames.amato@email.it             |
| 4777 |         2 | Genziana      | Caputo     | 1979-09-20    | OCHALP92M74H534A | 2020-07-26     | 624809              | barone.deborah@riva.it             |
| 4780 |        26 | Albino        | Farina     | 1985-09-04    | CCMBAF20U84Z356B | 2018-12-12     | 624812              | rufo.moretti@dangelo.it            |
| 4781 |        55 | Sue ellen     | Milani     | 1984-06-25    | BIUNXR68E14X384I | 2020-11-30     | 624813              | bruno.nabil@hotmail.com            |
| 4782 |        74 | Giulietta     | Milani     | 1990-02-04    | QOITEH95X38H201C | 2021-03-21     | 624814              | fiore.piccarda@email.it            |
| 4784 |        60 | Sue ellen     | Longo      | 1974-01-14    | XXURQA89N33E316N | 2019-01-01     | 624816              | eliziario.martino@pagano.it        |
| 4785 |        65 | Claudia       | Ricci      | 1980-08-23    | TQPNYB10B14K831I | 2019-11-29     | 624817              | luce64@yahoo.it                    |
| 4786 |        32 | Valdo         | Serra      | 1991-09-08    | XKBVZI96K40R351V | 2021-03-09     | 624818              | santoro.luigi@email.it             |
| 4787 |        10 | Costanzo      | Rizzo      | 1979-04-01    | JRARLC79Y92B519S | 2018-10-23     | 624819              | fernando.palumbo@hotmail.com       |
| 4789 |        29 | Marzio        | Martinelli | 1976-08-09    | QWXPUK93Y63Z410W | 2020-11-12     | 624821              | santo.caruso@yahoo.it              |
| 4790 |        66 | Genziana      | Negri      | 1989-09-15    | CBQJAX53G28J800L | 2021-04-26     | 624822              | mancini.anselmo@yahoo.it           |
| 4791 |        66 | Fiorenzo      | Palmieri   | 1987-04-15    | LNWXKC13N48X919V | 2018-06-20     | 624823              | guendalina.valentini@silvestri.it  |
| 4794 |        61 | Rosaria       | Pagano     | 1987-02-12    | WQNVWR75Z14C798L | 2020-09-01     | 624826              | nunzia.morelli@villa.it            |
| 4795 |        57 | Ursula        | Mariani    | 1974-07-05    | KPMRCF18V10G848S | 2020-10-16     | 624827              | damico.clea@gmail.com              |
| 4796 |        44 | Antonino      | Rinaldi    | 1975-04-24    | INRHZG35D77K493A | 2019-05-09     | 624828              | rocco.barbieri@libero.it           |
| 4798 |        29 | Nico          | Rossi      | 1985-08-16    | TSGCIK97U90T556T | 2019-08-06     | 624830              | xmartini@yahoo.com                 |
| 4799 |        26 | Claudia       | Gatti      | 1977-02-25    | PBUKJR61W81D841F | 2021-03-19     | 624831              | edvige.vitali@yahoo.com            |
| 4800 |        13 | Elda          | De Angelis | 1979-05-23    | GQRNZI49L37E751X | 2018-06-22     | 624832              | matteo.parisi@libero.it            |
| 4802 |        59 | Nadir         | Monti      | 1980-01-13    | PLQNEL47T12Y653V | 2019-09-09     | 624834              | lpagano@guerra.com                 |
| 4803 |        62 | Sirio         | Marini     | 1989-03-14    | AWZILS27C31Y431M | 2018-06-14     | 624835              | battaglia.bibiana@yahoo.com        |
| 4805 |        22 | Vienna        | Damico     | 1992-12-15    | YBKPHT50W48K674F | 2018-08-06     | 624837              | esilvestri@hotmail.com             |
| 4806 |        16 | Zelida        | Bianco     | 1992-01-10    | YGPYKR00M48U227J | 2018-08-25     | 624838              | brossetti@email.it                 |
| 4807 |        52 | Edilio        | Caruso     | 1975-04-03    | ELRSKO20H71D864O | 2020-09-15     | 624839              | yago.benedetti@esposito.org        |
| 4808 |        10 | Gianleonardo  | Bianco     | 1971-07-07    | HLFJAN78J82D662K | 2020-11-07     | 624840              | hpellegrino@gmail.com              |
| 4811 |        47 | Trevis        | Conte      | 1986-06-09    | RQBETS83X00V132E | 2020-04-30     | 624843              | farina.cesidia@bianco.com          |
| 4813 |        56 | Ariel         | Mancini    | 1977-07-29    | BVWISQ03E42S444J | 2018-07-02     | 624845              | gregorio29@costantini.com          |
| 4817 |         5 | Genziana      | Longo      | 1972-05-24    | YSTVLA88U90I373J | 2020-07-06     | 624849              | wlombardi@hotmail.com              |
| 4818 |        22 | Ippolito      | Valentini  | 1972-03-05    | VSWXJR83X26O999I | 2019-02-19     | 624850              | kconti@yahoo.com                   |
| 4819 |        47 | Vitalba       | Costa      | 1973-06-30    | CTHQJQ96M39M960E | 2020-01-16     | 624851              | ubaldo39@guerra.com                |
| 4820 |        46 | Noel          | Bianco     | 1973-10-23    | QDGUNK20H64I502P | 2020-03-21     | 624852              | bibiana.cattaneo@hotmail.com       |
| 4821 |        54 | Demi          | Esposito   | 1979-12-04    | FEOKJV06B27R409P | 2020-11-24     | 624853              | ethan.carbone@rizzi.it             |
| 4822 |        34 | Elio          | Ferretti   | 1972-03-24    | PDFKWO01E96Y083F | 2018-07-25     | 624854              | gerlando.rizzo@email.it            |
| 4824 |         2 | Jack          | Caruso     | 1975-10-20    | QWFFVP28L45X556T | 2019-06-12     | 624856              | ortensia38@donati.net              |
| 4826 |        31 | Gregorio      | Rossi      | 1987-01-23    | MJIBGI75Y59S846J | 2019-04-22     | 624858              | giancarlo16@derosa.com             |
| 4827 |        36 | Arcibaldo     | Cattaneo   | 1985-07-04    | GWMHQC36E90Q849G | 2018-08-05     | 624859              | mazza.grazia@libero.it             |
| 4829 |        59 | Soriana       | Sala       | 1981-01-02    | AMTSRE02V17H630I | 2019-08-18     | 624861              | rbianco@yahoo.it                   |
| 4830 |        46 | Selvaggia     | Longo      | 1972-07-23    | GOMXDV38I28I436V | 2019-09-05     | 624862              | epellegrini@deangelis.it           |
| 4831 |        74 | Giancarlo     | Serra      | 1990-03-14    | ZSCFTQ24N82P616K | 2021-04-18     | 624863              | benedetti.clea@coppola.it          |
| 4832 |        33 | Rosaria       | Moretti    | 1973-11-25    | ZVTFPV03R76T492I | 2019-09-06     | 624864              | italo.rizzi@martini.com            |
| 4833 |        52 | Neri          | Fontana    | 1983-03-04    | CSLUUN64W38C745V | 2020-10-23     | 624865              | ferretti.loretta@yahoo.it          |
| 4834 |        23 | Rosaria       | Martini    | 1976-03-16    | WZWOGR75U39M781A | 2020-10-23     | 624866              | bbattaglia@hotmail.com             |
| 4837 |        30 | Bacchisio     | Russo      | 1977-11-04    | CSGLDP76C22Y609W | 2020-11-17     | 624869              | ferretti.emilia@sorrentino.it      |
| 4838 |         5 | Vinicio       | De Angelis | 1979-09-06    | ZOTKXL43I54J174U | 2019-02-28     | 624870              | romano.alan@yahoo.it               |
| 4839 |        66 | Mercedes      | Vitale     | 1981-08-20    | JMBXIF03S31G551W | 2020-02-26     | 624871              | lpellegrino@gallo.it               |
| 4841 |        43 | Demi          | Marini     | 1987-11-03    | RLWCJZ11T60U463E | 2019-10-28     | 624873              | demi.rizzi@yahoo.it                |
| 4843 |        61 | Augusto       | Marini     | 1978-01-03    | OHYEMV26H40S943W | 2019-10-22     | 624875              | demi65@marchetti.org               |
| 4845 |        56 | Giulietta     | De rosa    | 1978-03-27    | NHBUEP46V16T766V | 2020-10-17     | 624877              | pneri@libero.it                    |
| 4846 |        37 | Neri          | Testa      | 1973-03-03    | TAEGCM36C61W724U | 2020-04-13     | 624878              | marino.rufo@hotmail.com            |
| 4848 |        29 | Vienna        | Grasso     | 1972-06-14    | TEBEIW94V10F050Q | 2020-06-21     | 624880              | gallo.cassiopea@yahoo.com          |
| 4849 |        46 | Siro          | Martinelli | 1992-10-18    | GASOEV97T11Z835F | 2019-03-05     | 624881              | teseo.sartori@marini.it            |
| 4850 |        46 | Lino          | Monti      | 1981-10-07    | UTCAPI82O47V780T | 2021-04-02     | 624882              | soriana21@yahoo.com                |
| 4853 |        67 | Odino         | De Angelis | 1983-05-11    | RBNXOB81R49K849E | 2018-12-28     | 624885              | fortunata.guerra@mazza.com         |
| 4854 |        36 | Giordano      | Grasso     | 1981-04-02    | XPVVKF95H91A586V | 2018-11-09     | 624886              | ippolito.sartori@ruggiero.it       |
| 4857 |        54 | Romeo         | Rossetti   | 1975-04-26    | QTBOXN01C55S847B | 2020-09-18     | 624889              | danuta30@esposito.it               |
| 4858 |        70 | Piccarda      | Colombo    | 1972-07-28    | PFVPRL97J80A363Y | 2019-12-07     | 624890              | irene.sorrentino@sanna.com         |
| 4859 |        39 | Kristel       | Donati     | 1972-05-22    | ERIWGZ70A44T069S | 2019-05-30     | 624891              | druggiero@yahoo.com                |
| 4860 |        40 | Gelsomina     | De rosa    | 1975-09-24    | NZGHEH36T76X277E | 2021-02-05     | 624892              | sesto70@libero.it                  |
| 4861 |        49 | Rosalba       | Giuliani   | 1983-08-08    | PQLOQW94K00D246O | 2019-01-04     | 624893              | giancarlo61@derosa.com             |
| 4863 |        20 | Ippolito      | Bernardi   | 1977-03-12    | SNTVOQ79G19I724V | 2019-01-07     | 624895              | ninfa.pagano@email.it              |
| 4864 |        45 | Luce          | Sala       | 1972-11-23    | OUHUMU61I21A363K | 2021-03-11     | 624896              | gianriccardo.russo@palumbo.net     |
| 4868 |        36 | Kristel       | Riva       | 1971-08-25    | VYUVTL27W29Q627T | 2021-01-24     | 624900              | unegri@gmail.com                   |
| 4869 |        24 | Samira        | Grassi     | 1984-10-17    | UPOPES85M70L463M | 2019-04-30     | 624901              | npagano@gmail.com                  |
| 4870 |        21 | Mariano       | Orlando    | 1975-05-23    | CZUUEC45K03G607R | 2020-06-04     | 624902              | fulvio.esposito@libero.it          |
| 4871 |        26 | Costantino    | Coppola    | 1973-05-01    | RGBXUV00Z21U863I | 2021-01-04     | 624903              | egatti@gentile.it                  |
| 4872 |        71 | Giobbe        | De Angelis | 1987-02-20    | QTBYBX40G80R145R | 2021-01-17     | 624904              | irene.deangelis@gmail.com          |
| 4873 |        57 | Cira          | De Angelis | 1976-05-03    | KEBLDN99Y78L019H | 2019-09-13     | 624905              | manuele41@giordano.org             |
| 4875 |        37 | Alessandro    | Vitale     | 1972-09-04    | VCFHMP41M85I328W | 2018-09-27     | 624907              | naomi79@marchetti.it               |
| 4876 |        21 | Alessio       | Grassi     | 1982-09-13    | IHURRL89Q81F223P | 2019-12-04     | 624908              | ycosta@email.it                    |
| 4877 |        33 | Mietta        | Leone      | 1984-12-10    | VDAWXU73G39C278I | 2021-04-26     | 624909              | gnegri@testa.org                   |
| 4878 |        14 | Priamo        | Bianco     | 1987-10-17    | GQNJWE20O07U932G | 2019-05-19     | 624910              | lorenzo.benedetti@riva.org         |
| 4879 |        30 | Cirino        | Bruno      | 1971-10-09    | ZZQEPZ67J18R881A | 2019-07-14     | 624911              | qcattaneo@email.it                 |
| 4881 |        46 | Fiorentino    | D'angelo   | 1984-11-30    | HFYFBI00Z41G778V | 2018-11-28     | 624913              | lucrezia.mazza@gmail.com           |
| 4882 |        72 | Flaviana      | Esposito   | 1986-01-18    | YTJWQT62I45F013X | 2019-01-18     | 624914              | benedetti.laerte@gentile.it        |
| 4883 |        13 | Ludovico      | Mancini    | 1989-12-16    | JTOSCU41O06F080S | 2021-01-11     | 624915              | alessandro88@gmail.com             |
| 4886 |        70 | Jelena        | Ferrara    | 1983-11-30    | XUULMQ40Z14T504F | 2020-06-29     | 624918              | basile.cesidia@longo.com           |
| 4888 |        29 | Deborah       | Farina     | 1977-06-25    | CFPHNG50G92F265I | 2019-09-13     | 624920              | lombardo.alessandro@marchetti.com  |
| 4889 |         4 | Primo         | Rinaldi    | 1992-03-18    | XMVVRO64V68X921V | 2018-11-29     | 624921              | germano55@messina.com              |
| 4891 |        68 | Concetta      | Marini     | 1976-07-26    | BFRKQC07G06D511H | 2019-07-10     | 624923              | vmessina@email.it                  |
| 4892 |        65 | Pacifico      | Grassi     | 1975-03-22    | QIRZZZ92L83I556D | 2021-04-22     | 624924              | sartori.maria@barone.org           |
| 4893 |        68 | Giovanna      | Villa      | 1987-05-21    | URCXCN43S54V486B | 2019-07-02     | 624925              | kai.palumbo@yahoo.com              |
| 4894 |        74 | Mariagiulia   | Santoro    | 1981-06-04    | FJESTP28E44N106P | 2019-12-03     | 624926              | maria83@piras.com                  |
| 4895 |        51 | Osvaldo       | Sorrentino | 1989-06-06    | IKNMYX76J38Z065V | 2018-09-22     | 624927              | damico.antonio@yahoo.it            |
| 4896 |        61 | Joseph        | Cattaneo   | 1985-02-24    | APIGSK81T80N687I | 2018-12-12     | 624928              | criva@gallo.com                    |
| 4897 |         1 | Carlo         | Fontana    | 1990-08-10    | UAZJHI97G46W157O | 2018-09-27     | 624929              | naomi.palumbo@rossi.org            |
| 4898 |        49 | Amedeo        | Russo      | 1971-09-17    | GDUDNB44T86W326P | 2021-03-29     | 624930              | miriam12@gmail.com                 |
| 4899 |        11 | Eufemia       | Sartori    | 1973-10-02    | PNARFO37A06W701C | 2020-11-10     | 624931              | nayade.vitali@pellegrino.com       |
| 4900 |        16 | Bacchisio     | Morelli    | 1990-01-30    | ZHVQNB48D88S637F | 2021-05-29     | 624932              | isira.lombardi@yahoo.it            |
| 4904 |        65 | Laerte        | Palmieri   | 1989-03-24    | RZVREY34B98X557O | 2019-12-09     | 624936              | fvilla@yahoo.it                    |
| 4905 |        11 | Ivonne        | Serra      | 1973-08-21    | NGJNBZ41L04E726X | 2018-07-14     | 624937              | loredana10@silvestri.org           |
| 4906 |        34 | Kristel       | Fiore      | 1974-08-16    | HHBFNU73W95N800J | 2019-11-16     | 624938              | giordano.jarno@yahoo.it            |
| 4908 |        61 | Brigitta      | Greco      | 1992-07-07    | QOIGMW26Q00A534E | 2020-02-04     | 624940              | jacopo.vitali@greco.it             |
| 4909 |        69 | Cesidia       | Lombardo   | 1973-11-19    | JCVKLK95Z00D980X | 2019-05-05     | 624941              | rmonti@martini.com                 |
| 4911 |        51 | Vienna        | Mazza      | 1991-05-30    | ANRWLD67X52D246Z | 2020-02-21     | 624943              | furio.neri@giuliani.com            |
| 4913 |        75 | Laura         | Gatti      | 1988-01-28    | FWEAAA95N54K550L | 2020-09-07     | 624945              | luna69@serra.it                    |
| 4914 |        16 | Ivano         | Gallo      | 1990-08-04    | HGVHOP45R16G539V | 2018-09-30     | 624946              | zelida47@yahoo.com                 |
| 4915 |        55 | Erminia       | Pellegrino | 1980-03-15    | TOWEEY73H30A888T | 2019-07-30     | 624947              | lombardo.sebastian@bianchi.net     |
| 4916 |        52 | Radio         | Morelli    | 1991-09-04    | GMSIXL85T32I739I | 2019-11-22     | 624948              | ncoppola@orlando.net               |
| 4917 |         3 | Cecco         | D'amico    | 1985-07-15    | RLVEGR06E83F392I | 2019-02-13     | 624949              | maria44@yahoo.com                  |
| 4919 |        18 | Olo           | Gatti      | 1975-06-15    | LRBZCG05S10T822Z | 2021-02-22     | 624951              | vitalba.ferrara@yahoo.com          |
| 4920 |         3 | Cassiopea     | Bianchi    | 1984-01-30    | TBSCCQ94T46X058K | 2020-10-30     | 624952              | bdonati@carbone.it                 |
| 4922 |        36 | Walter        | Palumbo    | 1975-09-02    | GOMWNT86G86C372U | 2021-01-26     | 624954              | sferri@yahoo.com                   |
| 4923 |        44 | Oreste        | Galli      | 1987-04-16    | IJPNFQ22I93U834F | 2020-02-07     | 624955              | amos23@lombardo.com                |
| 4924 |        39 | Aroldo        | Romano     | 1987-04-15    | JHQEWW50G40B461W | 2020-08-30     | 624956              | enrica.costantini@libero.it        |
| 4925 |        75 | Luce          | Gatti      | 1977-12-11    | UQCMPV50U90I650P | 2019-08-08     | 624957              | enrica.moretti@libero.it           |
| 4926 |        60 | Monia         | Conte      | 1984-05-19    | AYHREY66G22W750V | 2018-08-31     | 624958              | cira.parisi@sorrentino.com         |
| 4929 |        60 | Bortolo       | Guerra     | 1988-02-04    | NDTIWB94P12Z115C | 2019-08-04     | 624961              | santoro.cesidia@coppola.com        |
| 4956 |        35 | Orfeo         | Negri      | 1980-12-05    | GKICKG67D12K535Q | 2020-08-02     | 624988              | lisa60@yahoo.com                   |
| 4961 |        56 | Cleros        | Fiore      | 1990-10-24    | GWIXJK53K54Q533N | 2021-02-26     | 624993              | battista50@benedetti.com           |
| 4963 |        67 | Muzio         | Fiore      | 1975-12-04    | HIGIHO65T09Y359H | 2018-11-18     | 624995              | cleopatra.romano@libero.it         |
| 4964 |        12 | Umberto       | Barbieri   | 1972-02-24    | JLJCBK76Y87S995K | 2021-02-08     | 624996              | olombardi@gmail.com                |
| 4967 |        75 | Assia         | Costantini | 1984-03-16    | BOKMUD67W45B623S | 2019-11-30     | 624999              | xpalmieri@valentini.com            |
| 4968 |        56 | Nunzia        | Bianchi    | 1991-10-21    | QGFDBL63E55V998K | 2019-01-13     | 625000              | lruggiero@yahoo.it                 |
| 4969 |        26 | Battista      | Lombardi   | 1987-04-23    | IKLPDW87H46U917K | 2018-08-24     | 625001              | ilario21@hotmail.com               |
| 4970 |        74 | Gianleonardo  | Grassi     | 1984-07-10    | PJGEUM79F99E968Z | 2021-01-11     | 625002              | ideangelis@gentile.com             |
| 4971 |         5 | Anastasio     | Rizzo      | 1989-02-09    | IXUBUV90J78U803M | 2019-12-29     | 625003              | bricci@ruggiero.com                |
| 4972 |        13 | Silverio      | Grasso     | 1990-09-15    | IUBYYW35F09Y552P | 2019-08-17     | 625004              | luna.sartori@hotmail.com           |
| 4973 |         2 | Domingo       | Rizzo      | 1980-03-16    | TASDKD33O64U508U | 2020-11-04     | 625005              | testa.evangelista@bianchi.com      |
| 4974 |        11 | Timothy       | Sartori    | 1985-03-27    | KTWFXD79X35S634K | 2021-03-24     | 625006              | ileana39@yahoo.it                  |
| 4977 |         3 | Evita         | Palumbo    | 1974-04-12    | EGDCXY92O89T601U | 2021-04-25     | 625009              | rossi.cleopatra@lombardo.com       |
| 4979 |        60 | Celeste       | Carbone    | 1983-10-20    | WPLHYA28R23E611D | 2021-04-20     | 625011              | enrico85@cattaneo.it               |
| 4981 |         2 | Quasimodo     | Silvestri  | 1987-11-23    | NKXNES81X52K064R | 2019-06-13     | 625013              | edvige.deangelis@palumbo.com       |
| 4982 |        53 | Matteo        | Bruno      | 1987-03-08    | JKSRTI53W29G885W | 2021-05-02     | 625014              | penelope63@libero.it               |
| 4983 |         3 | Marvin        | Vitale     | 1986-08-15    | XXPHUD58X09C980C | 2020-02-07     | 625015              | rosalba11@benedetti.com            |
| 4984 |        34 | Felicia       | Barone     | 1981-11-17    | OIDEXQ32O47B952M | 2020-05-09     | 625016              | martinelli.loredana@yahoo.it       |
| 4985 |        35 | Antonio       | Leone      | 1988-03-29    | BLJXIV87K51E490B | 2019-09-14     | 625017              | ian87@parisi.it                    |
| 4986 |        42 | Filomena      | Pagano     | 1977-09-28    | KNWHGN80G16G666V | 2018-09-04     | 625018              | zelida.monti@gmail.com             |
| 4987 |        38 | Tosca         | Farina     | 1981-08-11    | USKWRG25Z16J942B | 2020-05-26     | 625019              | ferretti.kris@villa.com            |
| 4988 |        56 | Gastone       | Martino    | 1982-06-30    | BALRMG85J32J931U | 2020-11-22     | 625020              | sferrara@negri.org                 |
| 4990 |         6 | Diana         | Giordano   | 1989-10-10    | DBYYRL43W79J432K | 2019-08-10     | 625022              | pellegrini.luna@derosa.com         |
| 4992 |        37 | Ulrico        | Lombardi   | 1989-08-06    | YKKJGY65C36V069Y | 2019-06-20     | 625024              | efarina@rossi.it                   |
| 4993 |        51 | Gioacchino    | De Santis  | 1979-11-20    | DKRINM30K95B079B | 2018-08-23     | 625025              | rossetti.clodovea@email.it         |
| 4996 |         2 | Oretta        | De rosa    | 1978-09-13    | IARGWD46G18V822V | 2019-10-21     | 625028              | vitali.maggiore@email.it           |
| 4999 |        49 | Cristyn       | Marino     | 1979-10-02    | XTFLOV75M99L623F | 2019-10-03     | 625031              | carmelo.rossi@yahoo.com            |
| 5000 |        50 | Ferdinando    | Ferrari    | 1986-03-10    | AUGUYZ94P14C703K | 2020-08-02     | 625032              | dimitri95@libero.it                |
+------+-----------+---------------+------------+---------------+------------------+----------------+---------------------+------------------------------------+
3501 rows in set (0.01 sec)









4. SELECT * FROM `courses` WHERE year = 1 AND period = 'I semestre';
+------+-----------+------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------+------+-----+--------------------------+
| id   | degree_id | name                               | description                                                                                                                                    
                                                         | period     | year | cfu | website                  |
+------+-----------+------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------+------+-----+--------------------------+
|    1 |         1 | provident aut non                  | Et dolorem optio nostrum quam. Nesciunt eos non molestiae deleniti. Earum amet nam minus porro aut corrupti.                                   
                                                         | I semestre |    1 |  11 | www.minima.uni.it        |
|    2 |         1 | et doloremque omnis                | Itaque quos aut repellat et amet et. Ipsum itaque laboriosam est earum unde id ea facilis. Eos placeat adipisci ipsam et. Ut ipsa ducimus sit sed ut provident facilis.                                 | I semestre |    1 |   4 | NULL                     |
|    3 |         1 | nam nostrum et                     | Eligendi expedita repellendus debitis iusto. Omnis est et non laboriosam tempora. Architecto laborum quas nisi quia hic sed ea autem.          
                                                         | I semestre |    1 |   3 | www.nisi.uni.it          |
|   20 |         2 | ut animi adipisci                  | Dolorem eligendi sit eius quas. Voluptas corrupti et deserunt ex et. Nostrum nemo numquam ut ratione non tempore voluptatum.                   
                                                         | I semestre |    1 |   4 | www.et.uni.it            |
|   21 |         2 | ut rem libero                      | Eligendi qui magni aliquam molestiae ut assumenda nihil. Dolor eligendi aperiam non deleniti aliquid laborum. Tempore modi molestiae non pariatur corrupti. Eum rem autem amet expedita aut.            | I semestre |    1 |  12 | www.earum.uni.it         |
|   22 |         2 | soluta voluptatem at               | Libero voluptas expedita quia. Quas nulla culpa similique eum. Aperiam officiis quia a sed accusamus qui qui. Nemo esse qui labore optio perspiciatis non.                                              | I semestre |    1 |  11 | www.rerum.uni.it         |
|   23 |         2 | impedit et eaque                   | Ut autem omnis repellendus officiis. Quia optio est voluptatum aspernatur.                                                                     
                                                         | I semestre |    1 |  10 | www.illum.uni.it         |
|   46 |         3 | perspiciatis quae eveniet          | Eaque pariatur magnam veritatis sit quis animi ut. Sed in voluptates fugit ut qui qui. Neque mollitia eius vitae dolor qui. Magnam hic ipsa magni debitis eum optio consequuntur.                       | I semestre |    1 |   3 | www.ipsum.uni.it         |
|   47 |         3 | enim qui ea                        | Perspiciatis qui voluptatum quo. Id impedit porro aliquid commodi sint ea corrupti. Et asperiores eum praesentium amet dolorem quo. Accusantium non esse eveniet ab minima.                             | I semestre |    1 |  10 | www.odio.uni.it          |
|   48 |         3 | earum aperiam nihil                | Itaque cupiditate omnis tempore sunt voluptatem. Et laudantium consectetur cum omnis quibusdam quidem.                                                                                                  | I semestre |    1 |   4 | www.ratione.uni.it       |
|   49 |         3 | odio odit id                       | Omnis excepturi ipsa modi earum aut necessitatibus. Blanditiis fugiat porro eum. Exercitationem eaque mollitia error magni ut omnis quidem. Quis et voluptas voluptas nobis temporibus placeat est ut.  | I semestre |    1 |  15 | NULL                     |
|   66 |         4 | officia esse maxime                | Debitis eos veritatis aut velit et ad itaque. Sed eum et similique laborum. Quia itaque facilis quisquam ut at est magni. Officia itaque sit alias nobis maxime excepturi rerum.                        | I semestre |    1 |  11 | www.in.uni.it            |
|   67 |         4 | corporis incidunt ex               | Esse at asperiores provident consectetur quos. Ea voluptatem porro dignissimos. A iure quis libero explicabo alias architecto.                 
                                                         | I semestre |    1 |   9 | NULL                     |
|   68 |         4 | quam repellat enim                 | Sed qui quis corporis quibusdam odit. Placeat aut molestias perferendis quam odio aut. Cumque nostrum explicabo dolore voluptatem ut quia officia.                                                      | I semestre |    1 |   4 | www.eos.uni.it           |
|   85 |         5 | et harum nulla                     | Sed dignissimos vel id delectus eveniet qui fugiat. Deserunt repudiandae iure iure odio. Quis error aspernatur dolorem quo.                    
                                                         | I semestre |    1 |   5 | NULL                     |
|   86 |         5 | debitis vel pariatur               | Esse non et rem quis laborum qui vel autem. Aliquid accusantium ratione voluptas. Doloremque quo optio sint est. Non similique sunt et fuga non numquam assumenda. Qui eius autem quis.                 | I semestre |    1 |   5 | NULL                     |
|   87 |         5 | id id qui                          | Laboriosam impedit odit voluptatum nisi esse aut. Ipsum repellat impedit eius exercitationem omnis. In sapiente commodi rem sit sed. Officia unde consequuntur qui nam.                                 | I semestre |    1 |  15 | NULL                     |
|   88 |         5 | molestias minima voluptates        | In id commodi tempora quia. Et distinctio qui fugiat labore ut et saepe dolorem. Aut enim vitae deleniti et quo.                               
                                                         | I semestre |    1 |  15 | www.nam.uni.it           |
|   89 |         5 | ipsam atque animi                  | In deserunt voluptatem a voluptate omnis rerum maiores. Eum voluptas voluptas repellat labore quaerat. Omnis id sed et vel deleniti.           
                                                         | I semestre |    1 |   5 | NULL                     |
|   99 |         6 | corporis consequatur labore        | Sed modi ad qui consequatur nihil numquam. Laborum eos aut perferendis consectetur veritatis voluptatum. Harum est nesciunt natus placeat quia deserunt. Earum eum ipsam placeat dolor unde est error.  | I semestre |    1 |   9 | NULL                     |
|  100 |         6 | minima iste veniam                 | Architecto voluptatem sed et nobis eum. Minus aut assumenda accusantium autem officiis.                                                        
                                                         | I semestre |    1 |   5 | NULL                     |
|  101 |         6 | quis quasi eos                     | Autem eaque voluptatibus magnam in et. Eos est autem ut repellat in omnis. Id fugit alias expedita qui vel qui.                                
                                                         | I semestre |    1 |  13 | NULL                     |
|  110 |         7 | sint nulla ut                      | Impedit ad voluptas sit architecto. Recusandae doloribus molestiae et quia. Dolorem quia voluptatum odio. Nemo dolorum ratione aut voluptatem nihil ullam. Omnis eius modi ad vero sint repellendus et. | I semestre |    1 |   3 | www.vel.uni.it           |
|  111 |         7 | ut sit est                         | Deleniti animi id aut quo ea magnam sit. Ipsa vel velit sint reiciendis. Consequuntur molestias sint autem officia.                            
                                                         | I semestre |    1 |   6 | www.quos.uni.it          |
|  112 |         7 | voluptas amet vitae                | Eum odit aliquid quisquam. Voluptatem odio deserunt nihil itaque omnis. Quo rerum et ea fugit.                                                 
                                                         | I semestre |    1 |  14 | www.quo.uni.it           |
|  113 |         7 | non aperiam ab                     | Est dicta dicta earum perspiciatis voluptatum earum. Repudiandae saepe corporis dolore animi accusamus. Aut voluptas ipsa ut tenetur et et est quia.                                                    | I semestre |    1 |   3 | www.consectetur.uni.it   |
|  124 |         8 | quia vero illum                    | Repudiandae amet porro quis necessitatibus amet porro ut. Corrupti ea voluptas est qui laudantium est. Accusamus corporis laudantium unde eos reiciendis aut.                                           | I semestre |    1 |   3 | NULL                     |
|  125 |         8 | est ab dolores                     | Est dolorem quia qui. Eaque consequatur beatae rem sunt et. Quod et sed dolor ut dolores commodi repudiandae est.                              
                                                         | I semestre |    1 |   8 | www.fuga.uni.it          |
|  126 |         8 | quibusdam dolor alias              | Voluptas sed perferendis et consequatur sapiente laboriosam. Maiores quae tenetur ipsa in. Quidem omnis corporis deleniti sit suscipit fugit. Occaecati velit aliquam voluptatem aperiam eaque sint.    | I semestre |    1 |   4 | NULL                     |
|  127 |         8 | temporibus voluptatem magni        | Mollitia adipisci eveniet qui perspiciatis quidem eum soluta laborum. Tenetur eaque qui cum et quia.                                           
                                                         | I semestre |    1 |   5 | NULL                     |
|  139 |         9 | deleniti et ullam                  | Aperiam qui non illum provident natus. Distinctio officiis modi quo illum nobis. Eaque laboriosam quia et omnis vero dolor. Ex nihil repudiandae tempore.                                               | I semestre |    1 |   4 | NULL                     |
|  140 |         9 | nihil aut voluptatem               | Quo id sed distinctio. Iste dolores ipsum est ipsam. Ad odit sapiente velit ea saepe vitae. Eos quia quibusdam veniam nemo. Reprehenderit et nemo corrupti quis sequi quasi sint.                       | I semestre |    1 |   4 | www.numquam.uni.it       |
|  141 |         9 | eaque veritatis ea                 | At quis autem eligendi qui consequatur veniam facilis. Provident molestiae tenetur deleniti est aut quae. Provident quis magni reprehenderit cumque minima nihil. Corrupti odit in fugiat.              | I semestre |    1 |  12 | www.nesciunt.uni.it      |
|  142 |         9 | soluta placeat asperiores          | Tempore quia veniam accusamus est et assumenda. Voluptas dolore ipsum vitae sit qui. Nihil et maxime tempora rerum molestiae.                  
                                                         | I semestre |    1 |   8 | www.esse.uni.it          |
|  152 |        10 | nesciunt esse natus                | Et nulla dolorem voluptas est debitis. Iure sunt tempora aut necessitatibus quidem natus qui explicabo. Quisquam animi atque saepe voluptatem. 
                                                         | I semestre |    1 |  12 | NULL                     |
|  153 |        10 | accusamus ducimus saepe            | Rerum perferendis omnis dolores hic molestiae voluptas. Maiores dignissimos aperiam quia est incidunt sed vel. Voluptates enim ad voluptatem sed.                                                       | I semestre |    1 |   8 | NULL                     |
|  154 |        10 | quae non voluptate                 | Minima tenetur ut non aliquid qui aut. Non itaque inventore nemo. Dolor asperiores incidunt ut animi. Voluptates ut illo soluta explicabo.                                                              | I semestre |    1 |   6 | NULL                     |
|  155 |        10 | explicabo ab voluptas              | Nam molestias iste sed error. Ullam veniam maxime dolorum hic aperiam. Similique sint numquam sequi voluptates at ipsa ea. Culpa nesciunt et et deleniti.                                               | I semestre |    1 |   3 | www.consequuntur.uni.it  |
|  156 |        10 | ut voluptatibus neque              | Consequatur quam eos culpa voluptatum et. Occaecati quidem doloribus architecto quia aut doloremque. Atque autem non tempora in necessitatibus. Quia qui laboriosam harum quis.                         | I semestre |    1 |  14 | www.aut.uni.it           |
|  170 |        11 | ullam ullam dignissimos            | Perferendis voluptate et ratione sunt. Laborum harum sunt possimus porro veritatis. Iste incidunt ipsam laborum fugiat.                        
                                                         | I semestre |    1 |   9 | NULL                     |
|  171 |        11 | omnis aut ab                       | Minima ad corrupti repellendus quas velit. Et aut quidem aut occaecati. Et sapiente eum sit sed iusto omnis veritatis. Et dolorem iste aut praesentium. Sed vel nesciunt ullam autem facilis vitae.     | I semestre |    1 |   6 | NULL                     |
|  172 |        11 | ratione aut quas                   | Necessitatibus molestias quis inventore quidem perferendis ipsa ratione. Doloribus enim qui non ipsa. Perferendis odio et pariatur nulla voluptas ut atque.                                             | I semestre |    1 |  11 | www.sit.uni.it           |
|  187 |        12 | at id rerum                        | Tenetur et molestiae est molestiae quasi in asperiores. Sed est iure omnis qui. Natus eaque voluptas voluptates et dolorem nesciunt quasi. Aut velit eaque dolor eum quia unde est.                     | I semestre |    1 |   8 | www.id.uni.it            |
|  188 |        12 | aliquid aut excepturi              | Deserunt ut quibusdam et. Repudiandae ut temporibus magnam porro sed. Occaecati ducimus maiores beatae excepturi.                              
                                                         | I semestre |    1 |   3 | NULL                     |
|  189 |        12 | fugit odio sapiente                | Molestiae enim libero incidunt eaque officia. Ea nobis ipsum vero ratione hic placeat optio. Officiis animi minima sit maiores neque. A ut et numquam deleniti ab.                                      | I semestre |    1 |  10 | www.itaque.uni.it        |
|  190 |        12 | eligendi temporibus sit            | Eum voluptas eos voluptatibus voluptatem nulla repudiandae aut. Aut quas consequatur dolore est est. Totam nulla sunt voluptas rem et iusto similique assumenda.                                        | I semestre |    1 |   6 | NULL                     |
|  209 |        13 | fugit dolorem voluptas             | Et autem in expedita error veniam sed consequatur. Dolorum dignissimos sit maxime accusantium a hic perferendis.                               
                                                         | I semestre |    1 |   7 | www.sit.uni.it           |
|  210 |        13 | fuga et aut                        | Eveniet beatae nisi quibusdam ex. Praesentium et ea deserunt numquam inventore eligendi quaerat.                                               
                                                         | I semestre |    1 |   3 | www.consequuntur.uni.it  |
|  211 |        13 | officiis fugiat voluptatem         | Voluptas ut quia et odio asperiores eos eaque. Ullam quidem in quis.                                                                           
                                                         | I semestre |    1 |   3 | NULL                     |
|  222 |        14 | quia praesentium perferendis       | Et repellendus distinctio consequatur. Voluptas in eveniet sed perspiciatis earum. At fugit est cumque sed sed.                                
                                                         | I semestre |    1 |  12 | NULL                     |
|  223 |        14 | et autem exercitationem            | Est velit cum voluptatem aperiam harum amet velit voluptatem. Ea molestiae consequatur dolorem aut repellendus. Explicabo repudiandae quidem esse corporis ratione quisquam velit.                      | I semestre |    1 |  12 | www.non.uni.it           |
|  224 |        14 | quo recusandae dignissimos         | Rerum earum et et quae voluptates repudiandae. Dolor et sint quisquam magnam dignissimos voluptate inventore rerum. Asperiores temporibus ut distinctio numquam esse dicta eum.                         | I semestre |    1 |  12 | www.tenetur.uni.it       |
|  235 |        15 | facere laboriosam quod             | Facere facere voluptas consequatur facere. Est totam ipsum corporis laborum quas perferendis animi enim. Eveniet voluptate illum ut rerum odio rem modi.                                                | I semestre |    1 |  14 | www.dolor.uni.it         |
|  236 |        15 | et modi aliquid                    | Enim laborum sunt mollitia aliquam. Perferendis omnis placeat ut. Temporibus laudantium dolor maxime excepturi ipsam odio repellat. Itaque incidunt labore consequatur est.                             | I semestre |    1 |   3 | www.aut.uni.it           |
|  237 |        15 | ut perferendis sunt                | Voluptatum unde deleniti voluptatem ea ut qui. Quia consequatur molestiae reprehenderit aperiam. Consequatur inventore animi laboriosam reiciendis voluptatibus repellendus.                            | I semestre |    1 |   3 | NULL                     |
|  257 |        16 | est tempora aliquid                | Qui rerum aut reprehenderit sint earum sint quia. Quaerat quo sapiente tempora. Molestiae mollitia qui molestiae beatae dolores minus reiciendis qui. Corporis vel officiis et quia ipsam id libero.    | I semestre |    1 |   4 | www.tempore.uni.it       |
|  258 |        16 | illo qui culpa                     | Sint nulla sed assumenda dolorem. Modi placeat illo nobis impedit quia.                                                                        
                                                         | I semestre |    1 |   8 | www.quisquam.uni.it      |
|  259 |        16 | numquam deserunt quasi             | Quod dolorum molestias molestiae deserunt sed. Soluta ex vel expedita et. Id assumenda ipsum ducimus odio dolorum non alias ut. Nisi facere tenetur iure odio exercitationem est.                       | I semestre |    1 |  15 | NULL                     |
|  260 |        16 | occaecati officiis aliquid         | Illo iusto consequuntur cupiditate modi nostrum qui quia nesciunt. Blanditiis praesentium dolor sint. Ipsa voluptas omnis repellendus voluptatem qui tempora animi omnis.                               | I semestre |    1 |   3 | NULL                     |
|  277 |        17 | ad qui qui                         | Sunt explicabo molestias ea culpa voluptas. Libero neque in quo saepe ut molestias. Vel quaerat cum quo vel totam sapiente exercitationem. Sequi rem et asperiores fugiat. Temporibus animi amet et.    | I semestre |    1 |   5 | www.doloremque.uni.it    |
|  278 |        17 | ea et harum                        | Pariatur laudantium cumque fuga voluptatum nihil. Dolore aliquam animi voluptatem enim. Perspiciatis qui animi veritatis velit.                
                                                         | I semestre |    1 |  13 | NULL                     |
|  279 |        17 | distinctio quo praesentium         | Sed sit deserunt et nostrum non tempora. Fugit voluptatem sed nulla et consequatur quis. Eum qui perspiciatis exercitationem unde qui. Excepturi omnis dicta quis omnis quod veritatis laboriosam.      | I semestre |    1 |  14 | www.rerum.uni.it         |
|  280 |        17 | rerum sint voluptates              | Ratione voluptatem ipsum a commodi molestias. Sit voluptas distinctio cupiditate dolores sint omnis rem. Accusamus aut aut in sapiente sit. Enim vel placeat et doloribus.                              | I semestre |    1 |   4 | NULL                     |
|  281 |        17 | nihil vero voluptas                | Ipsa eum est vel quos. Nesciunt dolorum inventore eveniet debitis expedita nisi. Dicta qui sapiente sit dolor. Dolorum in natus sequi quasi neque.                                                      | I semestre |    1 |  15 | www.beatae.uni.it        |
|  299 |        18 | inventore reiciendis deserunt      | Dolores voluptatem fuga nostrum quo. In error dolores vitae. Ex alias expedita mollitia consequatur temporibus.                                
                                                         | I semestre |    1 |  13 | www.excepturi.uni.it     |
|  300 |        18 | aut ullam pariatur                 | Consequatur vel a officiis cupiditate et qui fugit. Neque dolor natus ducimus consectetur et debitis. Qui voluptates fuga eligendi sed unde ut. Autem omnis et sunt est quis quaerat.                   | I semestre |    1 |  11 | www.qui.uni.it           |
|  301 |        18 | fugit molestiae earum              | Quo tempora dolor necessitatibus suscipit fugiat odio repellendus. Ab qui magnam modi.                                                         
                                                         | I semestre |    1 |  11 | NULL                     |
|  302 |        18 | nisi illum vitae                   | Est est eveniet unde culpa aut nihil vitae omnis. Assumenda modi repellat ea omnis.                                                            
                                                         | I semestre |    1 |  11 | NULL                     |
|  316 |        19 | est magni explicabo                | Blanditiis nihil explicabo molestias. Fugit et dolore ad qui eaque eaque. Ducimus impedit iure aut beatae perferendis. Et deserunt architecto voluptatem quia at soluta.                                | I semestre |    1 |   8 | www.beatae.uni.it        |
|  317 |        19 | hic omnis dolore                   | Unde est reiciendis sit quia. Quaerat rerum excepturi quidem corporis in voluptatem. Incidunt quia consequatur enim voluptates non.            
                                                         | I semestre |    1 |  10 | www.magnam.uni.it        |
|  318 |        19 | non occaecati voluptatem           | Sed expedita voluptates facilis doloribus omnis provident. Quas et odio perferendis veritatis ipsa libero aut. Hic accusamus atque temporibus vero animi suscipit.                                      | I semestre |    1 |   5 | www.et.uni.it            |
|  319 |        19 | adipisci aliquam dolorum           | Cum occaecati ducimus ad sed sed qui nisi. Et quasi doloribus deleniti quod rerum iste. Corporis quas error laborum similique sint ut repudiandae. Aut eos nam rem molestiae deserunt voluptatum.       | I semestre |    1 |  11 | NULL                     |
|  338 |        20 | est ab ratione                     | Saepe architecto ut reiciendis deleniti. Molestiae consectetur et quo expedita nihil ea. Hic odio eum exercitationem consequatur dolor. Mollitia natus quo tempora at.                                  | I semestre |    1 |  14 | www.laborum.uni.it       |
|  339 |        20 | natus et hic                       | Laborum quia earum possimus impedit et iure eveniet. Quod laborum aut maiores itaque perspiciatis. Aut esse maxime quod vel aut. Iusto quod ut sunt ut nostrum veritatis animi.                         | I semestre |    1 |   9 | www.qui.uni.it           |
|  340 |        20 | omnis rerum tenetur                | Et ratione ut dolor dicta. Voluptas et rerum voluptatibus consequatur voluptatem voluptatum omnis reiciendis. Aut impedit veniam velit est.                                                             | I semestre |    1 |  11 | www.nam.uni.it           |
|  341 |        20 | officiis corrupti et               | Aspernatur at non neque est dolorem. Ea eaque quo sint eum. Modi voluptatem eligendi dolorem. Culpa possimus illum est ipsum.                  
                                                         | I semestre |    1 |  14 | NULL                     |
|  359 |        21 | impedit nobis exercitationem       | Ducimus molestiae quis aut molestiae qui. Fugit optio accusamus omnis consequuntur accusamus sit aliquid saepe. Non ut et deserunt ratione quia.                                                        | I semestre |    1 |   5 | www.vel.uni.it           |
|  360 |        21 | ex vero sunt                       | Reiciendis consequuntur natus illo omnis qui. Consequuntur dignissimos debitis sed eveniet. Aspernatur quia modi blanditiis.                   
                                                         | I semestre |    1 |   6 | www.similique.uni.it     |
|  361 |        21 | vel ut corporis                    | Ipsam labore aperiam architecto et excepturi at. Officiis dolorem qui dolores eligendi. Eum debitis reprehenderit qui ex a quibusdam ut nulla. Fugiat vero porro est molestiae repellendus veritatis.   | I semestre |    1 |   8 | www.vel.uni.it           |
|  362 |        21 | ut ea officia                      | Omnis dolorum incidunt eligendi in laudantium ducimus. Eius dolores eum nihil consequatur. Aut dolor numquam nisi numquam at. Adipisci culpa harum cum est nobis id vero.                               | I semestre |    1 |  12 | www.autem.uni.it         |
|  378 |        22 | officia dolor a                    | Dolores eius dolor fugiat aut ut et occaecati. Quod voluptatum dolor et similique. Quas nemo maiores aperiam molestiae.                        
                                                         | I semestre |    1 |  15 | www.et.uni.it            |
|  379 |        22 | nisi error temporibus              | Aspernatur facere ut earum iste sed. Sit magni iure officia laboriosam voluptas omnis. Quo deleniti molestias magni quam voluptatem. Id dolorum illum non qui.                                          | I semestre |    1 |   9 | www.porro.uni.it         |
|  380 |        22 | ut fuga sapiente                   | Minus eius commodi quis in. Iusto culpa ipsa sint odit eaque. Sed aliquam in exercitationem. Consectetur laudantium illo exercitationem eveniet et et eius quia.                                        | I semestre |    1 |  10 | NULL                     |
|  381 |        22 | eligendi corrupti tempore          | Nobis consequatur quam neque placeat deleniti vitae. Tempore in aperiam natus eos sit distinctio. Exercitationem nam sequi aliquid suscipit in delectus distinctio.                                     | I semestre |    1 |  11 | NULL                     |
|  400 |        23 | est accusantium vitae              | Quis et adipisci consequatur. Modi ex natus dolorem alias quidem voluptatem. Impedit sapiente fugit dolor et.                                  
                                                         | I semestre |    1 |   3 | NULL                     |
|  401 |        23 | ipsa omnis temporibus              | Sit adipisci qui quo temporibus. Iure ipsum a dolor esse et et. Ea quibusdam dicta earum aut esse aut. Occaecati eum odio enim natus vel est enim. Officia optio aut tempora in rerum non eligendi.     | I semestre |    1 |   7 | www.soluta.uni.it        |
|  402 |        23 | reprehenderit numquam et           | Non vel distinctio possimus ut aut illum. Dolorum laboriosam et similique labore. Mollitia reiciendis laboriosam minima pariatur earum.                                                                 | I semestre |    1 |   3 | NULL                     |
|  403 |        23 | qui quibusdam accusantium          | Sed quos eius vel eos. Dolor ut molestias et aut eum. Nostrum quisquam voluptatem est ullam ab.                                                
                                                         | I semestre |    1 |  10 | NULL                     |
|  412 |        24 | ipsum dolor suscipit               | Saepe libero sit consequatur eaque aspernatur. Qui est error dolore inventore molestias repudiandae. Repellat ut voluptas commodi repudiandae. Eos unde id voluptas et.                                 | I semestre |    1 |   9 | NULL                     |
|  413 |        24 | est atque et                       | Facere corrupti dolor quaerat voluptatem at. Perferendis porro ullam et voluptatem voluptatem. Laboriosam nemo non in blanditiis est aut et. Veniam quas repellat quidem est.                           | I semestre |    1 |   3 | www.inventore.uni.it     |
|  414 |        24 | fugit debitis sapiente             | Corrupti et repellat iure. Aut aliquid velit iusto dicta ut aut ut. Aut et quod est omnis odio.                                                
                                                         | I semestre |    1 |  12 | www.quam.uni.it          |
|  415 |        24 | iure impedit iusto                 | Repudiandae nam ab beatae saepe maxime corrupti qui. Distinctio doloremque amet et consequatur magni. Voluptas dignissimos itaque ut veniam dolorem veniam ea. Quaerat corporis qui et distinctio.      | I semestre |    1 |  12 | www.cumque.uni.it        |
|  416 |        24 | quia aspernatur dolorum            | Voluptatem illum qui veniam optio deserunt itaque numquam. Vero et sit ea ab fugit alias amet dignissimos. Ut qui et dolore alias. Facilis ut dolores maiores voluptate dicta.                          | I semestre |    1 |  13 | NULL                     |
|  428 |        25 | ducimus numquam rerum              | Praesentium pariatur perferendis excepturi consequatur mollitia. Dolore placeat repellendus vero minima amet earum quam voluptatem.            
                                                         | I semestre |    1 |   6 | www.magnam.uni.it        |
|  429 |        25 | unde voluptas delectus             | Nulla natus occaecati omnis laudantium nihil optio quaerat. Harum nostrum placeat officia impedit. Rerum nisi reiciendis inventore dolore.                                                              | I semestre |    1 |   6 | NULL                     |
|  430 |        25 | et officia sunt                    | Omnis voluptate officia incidunt fugit. Quaerat est sit et quas molestiae corporis voluptatem. Praesentium aut officia provident inventore. Consequatur dolores amet ipsum rerum dolores harum iure.    | I semestre |    1 |   8 | NULL                     |
|  440 |        26 | vel deleniti tempore               | Nihil itaque ea doloribus. A qui voluptatem eum ut sit. Laboriosam eaque et debitis dolor eligendi sed. Sed assumenda veniam voluptatem temporibus est nesciunt.                                        | I semestre |    1 |  15 | NULL                     |
|  441 |        26 | laboriosam ut iusto                | Magnam reprehenderit et mollitia velit sed. Sint voluptatem numquam fuga veniam. Et culpa eius et et ipsa accusantium.                         
                                                         | I semestre |    1 |   5 | NULL                     |
|  442 |        26 | consequatur ea ipsam               | Neque et debitis vitae aspernatur magni. Fugit aut quis rerum repellendus et ratione. Aliquid et fuga incidunt aliquid facilis tempore.                                                                 | I semestre |    1 |   8 | NULL                     |
|  443 |        26 | tenetur et itaque                  | Quia quidem vitae ut quis ea veritatis est. Magnam et nihil dicta et provident laborum. Suscipit necessitatibus vero similique sit quia. Voluptatibus est odio aut sint quos.                           | I semestre |    1 |   4 | NULL                     |
|  455 |        27 | minima est et                      | Maxime aut qui ut est. Sit illum sunt voluptas repellat quia. Molestiae non porro aut ipsa velit quidem soluta.                                
                                                         | I semestre |    1 |   3 | www.aut.uni.it           |
|  456 |        27 | dolores facilis aliquid            | Quibusdam et eveniet fuga. Ipsum autem ut vel non ex iusto velit. Quos laboriosam qui autem. Harum molestiae velit asperiores.                 
                                                         | I semestre |    1 |   6 | NULL                     |
|  457 |        27 | sequi saepe iure                   | Placeat accusamus quis officiis non. Aliquam reiciendis ut maiores laboriosam eos ipsa. Aut ipsa numquam et et debitis quia officia qui.                                                                | I semestre |    1 |   9 | www.iste.uni.it          |
|  466 |        28 | ipsam sed rem                      | Et et esse nam. Aut minus distinctio voluptates nisi modi eaque. Eaque voluptas inventore veniam. Et sint cum et.                              
                                                         | I semestre |    1 |   9 | NULL                     |
|  467 |        28 | vel beatae illum                   | Natus eligendi tempora quia amet in. Rerum in tempore numquam libero aut qui. Et nulla nostrum consectetur eius. Qui animi et sint ullam.                                                               | I semestre |    1 |   5 | www.incidunt.uni.it      |
|  468 |        28 | et non molestiae                   | Magni tenetur repellat non dolorum dolorum. Est voluptas sit omnis perferendis blanditiis voluptates accusantium quos. Dignissimos et ipsam earum iure explicabo et ea omnis.                           | I semestre |    1 |   9 | NULL                     |
|  486 |        29 | sapiente nihil et                  | Illo qui adipisci quisquam ut. Iure consectetur cum iure quibusdam ipsam. Molestiae occaecati eum sunt fuga. Corrupti voluptatem nobis facere eaque nemo.                                               | I semestre |    1 |  13 | www.voluptas.uni.it      |
|  487 |        29 | aliquam voluptas reiciendis        | Quia quaerat nihil quibusdam quia deserunt quos. Aut ea et animi consequatur. Illum veritatis sed cumque non adipisci labore nisi.             
                                                         | I semestre |    1 |   9 | www.a.uni.it             |
|  488 |        29 | minus facilis accusantium          | Non est sequi distinctio aut. Unde sint et blanditiis qui. Omnis consectetur occaecati excepturi est ea facilis adipisci. Unde laudantium laborum asperiores et vitae non deserunt.                     | I semestre |    1 |   8 | www.nesciunt.uni.it      |
|  508 |        30 | voluptatibus dicta odit            | Nostrum et qui et ipsum cupiditate hic. Et cum autem libero nostrum repellendus reprehenderit in. Modi magnam modi hic.                        
                                                         | I semestre |    1 |   6 | NULL                     |
|  509 |        30 | amet dicta et                      | Et animi corrupti quibusdam eligendi. Omnis consequatur maxime sunt exercitationem laboriosam.                                                 
                                                         | I semestre |    1 |  14 | www.odit.uni.it          |
|  510 |        30 | sit ipsum accusamus                | Aut sit consequatur adipisci asperiores amet fuga accusamus. Minus sit nemo animi voluptatem natus sit omnis et. Amet iure possimus adipisci cum temporibus animi.                                      | I semestre |    1 |   6 | www.at.uni.it            |
|  519 |        31 | distinctio numquam illum           | Dolorem sed neque inventore accusamus voluptate quae ut nihil. Minus aspernatur est error quisquam non sed porro voluptatem. Sit molestiae et placeat.                                                  | I semestre |    1 |  14 | NULL                     |
|  520 |        31 | ducimus sapiente at                | Qui reiciendis non sint doloribus ut temporibus. Qui temporibus optio et unde aperiam incidunt. Consequuntur est qui eum dolorum. Aliquid nihil voluptatem assumenda.                                   | I semestre |    1 |  14 | www.reprehenderit.uni.it |
|  521 |        31 | et est porro                       | Itaque ducimus iste praesentium ut quae. Laborum ad et et et rerum fugiat. Sed enim reiciendis a accusamus molestiae esse porro.               
                                                         | I semestre |    1 |  14 | NULL                     |
|  522 |        31 | quos voluptatem quis               | Itaque id sapiente et libero. Quisquam non voluptas accusantium consequatur. Ullam eos quaerat unde. Voluptatem nemo possimus ut rerum enim magnam earum vitae.                                         | I semestre |    1 |  10 | www.consequuntur.uni.it  |
|  536 |        32 | culpa quis expedita                | Possimus architecto animi nihil corrupti corporis facere. Consequatur odit est vel eum iste. Nihil ex iste quasi iusto.                        
                                                         | I semestre |    1 |  12 | NULL                     |
|  537 |        32 | aut enim nesciunt                  | Est vel qui cum dolor a. Consequatur soluta quia nisi molestiae. Dolor repudiandae ad adipisci ut.                                             
                                                         | I semestre |    1 |   4 | NULL                     |
|  538 |        32 | voluptas nihil nesciunt            | Et aperiam quia dolorem suscipit nulla iure sed. Ex quia quidem quia vitae. Maiores consectetur animi cumque maiores nam dicta.                
                                                         | I semestre |    1 |   7 | www.sunt.uni.it          |
|  539 |        32 | aut dolores ut                     | Dolor ab optio qui quisquam dolorum natus vitae. Esse unde iste sed reiciendis suscipit. Consequatur quia omnis ratione aperiam et quae cum ut.                                                         | I semestre |    1 |   7 | www.qui.uni.it           |
|  540 |        32 | laboriosam fugit et                | Autem aut recusandae incidunt odio atque libero exercitationem rerum. Velit deserunt odit sunt. Non aut non aut ipsum qui deserunt.            
                                                         | I semestre |    1 |   3 | www.a.uni.it             |
|  559 |        33 | est aut qui                        | Et quod omnis consectetur et autem. Libero qui necessitatibus voluptate quidem ducimus et itaque. Maxime quia consequatur laboriosam quidem. Dolorum quia odit enim atque harum.                        | I semestre |    1 |  10 | NULL                     |
|  560 |        33 | quibusdam nobis architecto         | Soluta ut exercitationem magni. Aspernatur quasi illo voluptatem. Omnis dolorem et iusto aut numquam voluptatem corporis explicabo.            
                                                         | I semestre |    1 |   4 | NULL                     |
|  561 |        33 | dolore enim eius                   | Alias aut voluptatem accusamus provident aspernatur. Corporis ratione voluptatem quaerat nobis dolorem ipsam. Magni qui incidunt veritatis quia.                                                        | I semestre |    1 |  14 | www.ut.uni.it            |
|  577 |        34 | ut veritatis magnam                | Voluptatem quo cum autem esse id quo. Laborum nihil porro optio. Explicabo similique blanditiis unde sed veniam perferendis ea. Eum fugit culpa exercitationem quod esse est.                           | I semestre |    1 |  15 | www.vitae.uni.it         |
|  578 |        34 | distinctio deleniti minus          | Aspernatur non est commodi. Eaque qui blanditiis dolorem. Voluptatum quos non sit facere consequatur deserunt ipsa. Voluptas qui molestiae iusto natus qui quam. Nulla qui aut fugiat aut eos ratione.  | I semestre |    1 |   5 | www.eaque.uni.it         |
|  579 |        34 | dolor ab possimus                  | Quod officiis qui laboriosam suscipit. Quaerat unde non exercitationem eum quidem voluptatem. Cum vero facilis magnam culpa amet est cumque veritatis.                                                  | I semestre |    1 |  15 | NULL                     |
|  580 |        34 | eius animi atque                   | Sed assumenda recusandae maiores harum iusto labore reiciendis. Aut porro id sit saepe. Nemo non ea ea doloribus nam aut odio. Enim veniam soluta et dolor et.                                          | I semestre |    1 |   7 | www.est.uni.it           |
|  581 |        34 | est magni quos                     | Aut expedita beatae qui aut. Dolore et adipisci voluptatem fugit adipisci eum est dicta. Sed et pariatur sit eveniet.                          
                                                         | I semestre |    1 |   3 | www.dolorum.uni.it       |
|  601 |        35 | facilis adipisci provident         | Et aut id aut officia. Doloremque quaerat sit et architecto. Facere nulla dolor sit illum quae laborum. Reiciendis iure nihil tempora.         
                                                         | I semestre |    1 |  15 | www.consequatur.uni.it   |
|  602 |        35 | totam illo non                     | Dolor sunt voluptatum dolorem tenetur odit minima voluptatem. Qui ut dolor cum hic. Quis reiciendis sed aut esse qui atque consectetur.                                                                 | I semestre |    1 |  13 | www.nemo.uni.it          |
|  603 |        35 | dolor ea voluptatem                | Laudantium provident aperiam ex. Officiis vero nesciunt omnis corrupti voluptatem. Excepturi qui eos qui rerum facilis.                        
                                                         | I semestre |    1 |   5 | NULL                     |
|  622 |        36 | aperiam ut suscipit                | Dolorem et voluptatem a sed consequatur. Et adipisci alias ea ducimus voluptatem. Culpa est omnis vero. Enim nesciunt et ut at neque consectetur animi. Fugiat et atque voluptas eum dicta.             | I semestre |    1 |  11 | NULL                     |
|  623 |        36 | dolorem voluptatem consequuntur    | Facere est facilis quam illum. Qui molestias ipsam incidunt a voluptatum magni quo.                                                            
                                                         | I semestre |    1 |   9 | www.nisi.uni.it          |
|  624 |        36 | eaque vero sapiente                | Et iste consectetur facere voluptas. Minus recusandae nobis quod culpa nihil dolores dolores. Quo nihil quae id quia incidunt praesentium deleniti.                                                     | I semestre |    1 |   8 | NULL                     |
|  625 |        36 | necessitatibus aut quis            | Quas dolores aut libero ipsa eveniet error maxime. Magni qui in ut repudiandae possimus eum non libero. Omnis optio et fugiat.                 
                                                         | I semestre |    1 |   7 | www.asperiores.uni.it    |
|  634 |        37 | et assumenda nihil                 | Quo est hic molestiae nemo. Officiis similique omnis natus iure ea. Illo consequatur quia rerum officia repellendus accusantium. Ipsum et neque itaque est quae accusantium.                            | I semestre |    1 |   8 | www.temporibus.uni.it    |
|  635 |        37 | ex molestiae rerum                 | Expedita qui fugit veniam cum voluptatum a. Ut eaque nihil et ex commodi. Quia consequuntur dolor accusamus nobis aut nulla. Voluptatibus itaque mollitia non. Et et ab minus impedit fugit.            | I semestre |    1 |  13 | www.nihil.uni.it         |
|  636 |        37 | quam voluptatem nihil              | Deleniti rerum numquam qui eos. Temporibus esse sed ut ut officiis et et. Officia omnis sed et. Sint sit unde quam ut exercitationem iste quia. Ea minus vero accusamus dignissimos rerum.              | I semestre |    1 |  15 | www.maxime.uni.it        |
|  637 |        37 | labore sequi incidunt              | Ut et asperiores esse et amet rerum. Ut qui voluptas accusantium sint sit cum. Quibusdam excepturi saepe ipsa voluptatibus.                    
                                                         | I semestre |    1 |  12 | www.consectetur.uni.it   |
|  638 |        37 | qui doloremque dolorem             | Facere voluptatem distinctio reiciendis. Dolorem quia placeat laudantium distinctio quasi autem. Itaque deserunt dolore non excepturi. Ea expedita aliquid dolores voluptatum sint optio.               | I semestre |    1 |  12 | www.repellendus.uni.it   |
|  650 |        38 | necessitatibus voluptas ut         | Provident officia officia sunt illum odit. Et magni odit temporibus quia quae enim. Ea in nam ullam. Ut corporis corporis qui tempore.         
                                                         | I semestre |    1 |   6 | www.non.uni.it           |
|  651 |        38 | deleniti nesciunt amet             | Similique commodi dolores dolorem qui facilis. Accusantium ipsam ipsum facilis nesciunt eos porro. Mollitia velit qui quis voluptatum corporis vel.                                                     | I semestre |    1 |  10 | NULL                     |
|  652 |        38 | velit esse soluta                  | Ab quam veritatis qui odit consequatur tempore omnis exercitationem. Ut et eum aliquam est voluptatem voluptatem.                              
                                                         | I semestre |    1 |  14 | www.dignissimos.uni.it   |
|  653 |        38 | tempore quod eum                   | Incidunt nihil explicabo repudiandae. Et adipisci voluptatem in nihil ratione. Natus possimus autem corporis.                                  
                                                         | I semestre |    1 |  11 | NULL                     |
|  671 |        39 | qui quasi recusandae               | Suscipit nesciunt nesciunt dolores dolorem odio iste iste fugit. Quasi et optio porro et consequatur animi amet. Et impedit velit quis voluptas omnis consequuntur sequi maxime.                        | I semestre |    1 |   7 | www.libero.uni.it        |
|  672 |        39 | incidunt et velit                  | Ullam voluptatibus sit magnam quod. Dolores eos sunt eos ut. Repellat eius eum molestiae qui sunt. Mollitia magni molestiae tempora maxime est ut.                                                      | I semestre |    1 |   7 | NULL                     |
|  673 |        39 | est in officia                     | Nihil sed ratione perspiciatis facere dolorem deserunt non neque. Quo sunt explicabo sunt aut. Officia omnis atque quae.                       
                                                         | I semestre |    1 |  14 | NULL                     |
|  674 |        39 | reiciendis totam quis              | Ea animi quis inventore dolorem amet quaerat autem voluptate. Similique et reprehenderit excepturi sunt doloribus. Ut eos est sed nesciunt aut voluptas consequuntur.                                   | I semestre |    1 |  12 | www.pariatur.uni.it      |
|  694 |        40 | error nobis similique              | Sint amet in enim facilis quas. Cupiditate reiciendis dolores qui libero voluptatibus perspiciatis. Et laboriosam iste quia voluptatem veniam natus. Quo aliquam culpa non sed et beatae.               | I semestre |    1 |   8 | www.consequatur.uni.it   |
|  695 |        40 | dolor optio non                    | Rerum dolores eos neque quidem ut optio consequatur. Quaerat consequatur aut sunt magnam. Nihil tempora sapiente et voluptas et. Molestiae voluptas alias provident voluptas nam et.                    | I semestre |    1 |   7 | www.repudiandae.uni.it   |
|  696 |        40 | architecto accusamus dolores       | Sit quam ea dolorem ut. Doloremque dolor dolorem assumenda pariatur. Quisquam velit ipsa excepturi excepturi tempore voluptas.                 
                                                         | I semestre |    1 |   6 | www.et.uni.it            |
|  715 |        41 | adipisci ut suscipit               | Quis dolorum corrupti aperiam. Molestiae amet deleniti ut suscipit odit et nisi. Dolores reiciendis atque minima at accusamus expedita.                                                                 | I semestre |    1 |   9 | www.non.uni.it           |
|  716 |        41 | nemo esse placeat                  | Voluptas qui maxime similique provident reiciendis. Molestiae quo quam qui. Quia quidem quod nulla corporis id sequi eaque aperiam. Aspernatur sunt nobis molestias reiciendis est nobis asperiores.    | I semestre |    1 |   5 | www.rerum.uni.it         |
|  717 |        41 | magnam aut repellat                | In rerum atque et repudiandae ut. Excepturi autem laboriosam magnam magnam quae et. Quo eveniet mollitia maxime magnam ipsam praesentium dolorem.                                                       | I semestre |    1 |   8 | NULL                     |
|  718 |        41 | facere sit est                     | Molestias nihil vitae quia iusto nihil perspiciatis ducimus asperiores. Nobis quia a consequuntur nostrum. Ratione vel deleniti et ipsam sint. Illo mollitia laboriosam beatae sequi modi quia odit.    | I semestre |    1 |  11 | www.nostrum.uni.it       |
|  719 |        41 | molestias autem similique          | Sint dicta perferendis et distinctio enim nihil. Nisi autem ipsa rem et ut fugiat assumenda et. Veritatis dolorem sed error voluptas fuga numquam numquam ratione.                                      | I semestre |    1 |   4 | www.qui.uni.it           |
|  735 |        42 | perspiciatis itaque rerum          | Fugiat ut voluptatem veritatis omnis alias omnis. Dignissimos nobis illo dolores et nulla. Dolor repellendus aut maiores ex.                   
                                                         | I semestre |    1 |  12 | www.est.uni.it           |
|  736 |        42 | ratione placeat vel                | Quia officia consequatur in sit voluptatem. Vero et molestiae debitis. Ad enim minus id esse.                                                  
                                                         | I semestre |    1 |   5 | www.alias.uni.it         |
|  737 |        42 | quis asperiores rem                | Sit molestiae est est et a qui commodi. Minima omnis atque sed. Aut et ea aut minima.                                                          
                                                         | I semestre |    1 |   8 | www.corrupti.uni.it      |
|  738 |        42 | saepe laudantium quia              | In ut quasi culpa id sed. Doloribus error est necessitatibus nesciunt facilis. Modi necessitatibus voluptatem qui. Laudantium animi error et labore sint.                                               | I semestre |    1 |  14 | NULL                     |
|  739 |        42 | et vero aspernatur                 | Voluptatem sit incidunt numquam sed. Qui ipsam quia exercitationem rerum assumenda in et et. Dignissimos ipsa qui quia soluta est minima in.                                                            | I semestre |    1 |  15 | NULL                     |
|  757 |        43 | illum est ea                       | Ducimus sint eveniet quam molestiae et. Quia blanditiis natus dolorum quisquam et a. Qui nobis ut illo culpa voluptatem. Voluptatem omnis voluptatibus et cupiditate illum quibusdam.                   | I semestre |    1 |  11 | NULL                     |
|  758 |        43 | commodi esse voluptas              | Perspiciatis sit eos dolorem voluptas in fuga laborum. Impedit sit velit laborum non eligendi ullam. Facilis voluptas voluptate in pariatur. Et quidem et neque neque.                                  | I semestre |    1 |   6 | NULL                     |
|  759 |        43 | et nesciunt fugit                  | Molestiae rerum soluta facilis perferendis amet. Dolorem iure amet deleniti. Quibusdam sed quia dicta quia explicabo laudantium cum.           
                                                         | I semestre |    1 |   5 | www.nulla.uni.it         |
|  760 |        43 | cumque omnis ullam                 | Nisi illo porro et. Aliquid sint sed consequatur enim porro. Sapiente ab doloremque magni vero fugiat.                                         
                                                         | I semestre |    1 |   3 | NULL                     |
|  780 |        44 | provident aspernatur aliquid       | Repudiandae sed nostrum nostrum perferendis qui. Totam velit ut odit officia. Earum veniam et et cumque voluptate temporibus.                  
                                                         | I semestre |    1 |   8 | NULL                     |
|  781 |        44 | magni in perferendis               | Repudiandae et aut non et sit nesciunt est enim. Totam cumque eum velit odio aliquid. Repellendus nam eaque fuga eos maxime necessitatibus. Ut voluptates sit laboriosam.                               | I semestre |    1 |  11 | NULL                     |
|  782 |        44 | enim odit debitis                  | Laudantium occaecati eveniet error consequuntur eveniet ipsa. Velit quia voluptates vero dolor et qui. Sint ut ut minima explicabo deleniti quia sed.                                                   | I semestre |    1 |  15 | www.excepturi.uni.it     |
|  783 |        44 | eligendi est rerum                 | Consectetur optio labore id maiores modi. Odio sunt aut debitis. Rerum est ea voluptas voluptas. Ratione id facilis quibusdam aut et neque.                                                             | I semestre |    1 |   9 | www.est.uni.it           |
|  784 |        44 | sed nostrum consequuntur           | Ad labore ut voluptatum ea repellat perspiciatis. Minima voluptatem maiores et in itaque. Aut quia maiores odit est dolorum. Voluptas neque sed quia repellendus.                                       | I semestre |    1 |  15 | www.adipisci.uni.it      |
|  798 |        45 | odio et sed                        | Eius dolorum dolorem maiores. Aspernatur aliquid impedit nam et vel iste vel.                                                                  
                                                         | I semestre |    1 |  10 | www.qui.uni.it           |
|  799 |        45 | ipsam qui quo                      | Nisi cum ea quia rem. Animi non et omnis dolor nulla explicabo nemo. Maiores perferendis nihil sint.                                           
                                                         | I semestre |    1 |   6 | www.et.uni.it            |
|  800 |        45 | commodi praesentium repudiandae    | Rerum odio occaecati similique. Commodi cumque voluptas veritatis. Labore repellendus a eius debitis aut non. Officiis quo necessitatibus maiores cumque ducimus tenetur provident.                     | I semestre |    1 |  13 | www.cupiditate.uni.it    |
|  817 |        46 | aperiam nostrum sint               | Magni alias laborum earum sunt. Nemo dolor rerum quia recusandae.                                                                              
                                                         | I semestre |    1 |   4 | NULL                     |
|  818 |        46 | illo delectus repellendus          | Excepturi non ut omnis rerum eos. Libero eaque dignissimos officiis qui repellat atque quos. Perspiciatis odit assumenda commodi fugiat non. Et saepe voluptatem natus consequuntur veritatis.          | I semestre |    1 |   3 | www.nihil.uni.it         |
|  819 |        46 | dolorum quos eum                   | Voluptatem corrupti dolores accusantium voluptatum vel repudiandae. Ea animi et temporibus sit eius est et omnis. Ab corporis natus culpa dolorem. Et non non distinctio.                               | I semestre |    1 |  13 | www.ut.uni.it            |
|  820 |        46 | rerum sed animi                    | Voluptas velit est quisquam. Et distinctio voluptatibus rerum et. Adipisci eos quas deleniti error veniam delectus.                            
                                                         | I semestre |    1 |   6 | NULL                     |
|  837 |        47 | labore tempora odit                | Rerum eaque id quas quas et sint tempora. Molestiae suscipit fugiat impedit tenetur in. Ipsa sit pariatur ipsa incidunt quae. Non maxime quo est et.                                                    | I semestre |    1 |  11 | NULL                     |
|  838 |        47 | quia omnis et                      | Et expedita cumque iusto dolore nihil illum. Nam eaque expedita sed distinctio consectetur. Numquam ab sit molestias cum. Inventore facere dolore debitis saepe qui nihil.                              | I semestre |    1 |  10 | www.aut.uni.it           |
|  839 |        47 | non rerum molestiae                | Sunt ut quam earum quia totam consequuntur. Earum eos tempore molestiae maiores fugiat aliquid.                                                
                                                         | I semestre |    1 |  10 | www.blanditiis.uni.it    |
|  840 |        47 | sit aut aliquam                    | Nam quis et et sit. Eius doloremque dolore esse vitae numquam. Qui aspernatur eos reiciendis ab quis veniam.                                   
                                                         | I semestre |    1 |   4 | www.voluptatem.uni.it    |
|  841 |        47 | consequatur rerum asperiores       | Tempora et ut veniam saepe velit labore. Corrupti qui odit quam fugit saepe minima. Dolorum voluptatem explicabo dignissimos quibusdam. Corporis odit magnam dolores et ex.                             | I semestre |    1 |  10 | www.aut.uni.it           |
|  858 |        48 | voluptatem consectetur voluptas    | Illo itaque maxime provident asperiores qui. Fuga quo non sit quo. Perspiciatis illum aliquam molestiae.                                       
                                                         | I semestre |    1 |  13 | www.eligendi.uni.it      |
|  859 |        48 | consequatur eius et                | Accusamus est aliquid vel aut rerum. Sapiente hic voluptatibus non dolorum laborum iure beatae nam. Occaecati numquam corrupti voluptatem doloribus at tenetur.                                         | I semestre |    1 |   8 | NULL                     |
|  860 |        48 | nihil in rem                       | Optio voluptatibus voluptas autem est provident sapiente nostrum. Est illum molestiae exercitationem et repudiandae architecto. Rerum recusandae laboriosam et officia molestiae et.                    | I semestre |    1 |   4 | www.consequuntur.uni.it  |
|  878 |        49 | sed est autem                      | Voluptas cumque qui quis officiis quam. Molestias labore iure quod numquam at. Quia quo quae quaerat molestiae. Cumque eum incidunt et qui voluptatem sit ea.                                           | I semestre |    1 |   9 | www.veniam.uni.it        |
|  879 |        49 | nobis nesciunt fugit               | Veniam enim harum reiciendis dolores. Laboriosam qui voluptate ut voluptas. Aut magni asperiores eum repellendus eos rerum molestiae.                                                                   | I semestre |    1 |   4 | www.aliquam.uni.it       |
|  880 |        49 | eum pariatur quia                  | Eos beatae unde doloribus asperiores voluptatem non qui. Sequi maxime aut id quibusdam soluta. Harum magnam molestiae omnis neque aut odio. In dolore sit earum quisquam.                               | I semestre |    1 |   3 | NULL                     |
|  893 |        50 | dolorem blanditiis nemo            | Sequi nisi ut atque facilis. Et aliquam earum dolores ipsum similique. Quas aliquam adipisci vitae provident quis. Veritatis ratione sed in minima libero.                                              | I semestre |    1 |  14 | NULL                     |
|  894 |        50 | veniam occaecati et                | Iusto omnis ea voluptatum distinctio minus rerum earum. Dolore magnam voluptates suscipit eaque nihil. Eos et dolores autem enim eius iure.                                                             | I semestre |    1 |   6 | www.et.uni.it            |
|  895 |        50 | quia mollitia voluptates           | Praesentium rerum dignissimos neque quod dolorum. Sed consequatur fugit cumque et. Cum dolore adipisci aperiam asperiores. Dolorem tempore dolores mollitia ea maxime.                                  | I semestre |    1 |   3 | NULL                     |
|  896 |        50 | excepturi blanditiis fugiat        | Consequuntur possimus tenetur sint ullam. In aut est est voluptate animi. Ut quisquam ut ab quo asperiores consequuntur. Saepe quis eos veritatis necessitatibus perspiciatis ratione est.              | I semestre |    1 |  10 | www.unde.uni.it          |
|  909 |        51 | sequi ut libero                    | Laborum facilis velit et ipsa. Recusandae doloremque ab enim aut. Quasi distinctio et saepe dolorem magnam.                                    
                                                         | I semestre |    1 |   6 | NULL                     |
|  910 |        51 | est cum explicabo                  | Numquam magni et harum blanditiis repellat. Aliquam quis ex error molestiae eveniet ipsam. Velit tempore quo amet nulla sint est. Ut odio eos enim temporibus ut enim doloremque dolores.               | I semestre |    1 |  15 | NULL                     |
|  911 |        51 | iusto quibusdam et                 | Aut optio molestias natus voluptatem nesciunt ex. Rerum hic ex dicta nostrum nobis voluptatem est nihil. Tenetur enim et id.                   
                                                         | I semestre |    1 |  11 | www.et.uni.it            |
|  912 |        51 | est id hic                         | Necessitatibus et accusantium rerum itaque voluptatem sit. Rerum voluptatem fugiat voluptates cupiditate quisquam. Quas excepturi optio alias quis dolores.                                             | I semestre |    1 |  14 | NULL                     |
|  913 |        51 | deleniti et consectetur            | Deleniti corrupti animi quos sint. Sunt assumenda magnam cumque excepturi cum est.                                                             
                                                         | I semestre |    1 |  10 | NULL                     |
|  927 |        52 | ullam voluptatem facere            | Itaque nam optio placeat. Et voluptatibus aliquam quae. Tempora voluptas doloremque et et.                                                     
                                                         | I semestre |    1 |  14 | www.laborum.uni.it       |
|  928 |        52 | et rem natus                       | Qui fugit qui qui ea. Sit nostrum labore sapiente at atque dolor quidem. Illum non corrupti amet fuga et quam molestiae. Sint quod et et est minima cum minima.                                         | I semestre |    1 |   3 | www.optio.uni.it         |
|  929 |        52 | error odio enim                    | Et ullam necessitatibus velit laborum. Ducimus mollitia harum molestias possimus itaque dolorem. Dignissimos consectetur veritatis eum assumenda molestiae vel culpa qui.                               | I semestre |    1 |  10 | NULL                     |
|  930 |        52 | quasi occaecati nulla              | Quae cumque error libero itaque ipsa sit corrupti. Iste consequatur repellendus fugiat ipsa ex. Voluptatem numquam reiciendis quia qui incidunt consequatur. Assumenda quaerat veniam illum eos et.     | I semestre |    1 |  15 | NULL                     |
|  941 |        53 | sint quam unde                     | Velit nihil minima eum molestiae blanditiis iste necessitatibus. Vero at atque et vel sapiente iure. Fugit est aliquam voluptas iusto.         
                                                         | I semestre |    1 |  12 | NULL                     |
|  942 |        53 | nobis delectus veritatis           | Ratione dolorum qui laudantium ut quos et eius. Eos quo porro quaerat aut. Et ad optio suscipit et quia pariatur.                              
                                                         | I semestre |    1 |  14 | NULL                     |
|  943 |        53 | cupiditate dolor et                | Qui consectetur ut quod placeat. Quia sit quaerat sequi. Eaque ut in modi quibusdam voluptas. Reprehenderit nulla veritatis aspernatur vitae.                                                           | I semestre |    1 |  10 | www.qui.uni.it           |
|  963 |        54 | est omnis possimus                 | Debitis delectus quia placeat iusto aut est vitae ut. Possimus nemo saepe rerum est vero numquam. Sed officia debitis cum et dolor quia quia.                                                           | I semestre |    1 |  13 | NULL                     |
|  964 |        54 | consequatur est numquam            | Vitae blanditiis corporis qui animi rerum omnis non. Sunt earum numquam rerum id voluptas odio facere. Est nobis autem aperiam quisquam architecto.                                                     | I semestre |    1 |  13 | NULL                     |
|  965 |        54 | provident nemo est                 | Reprehenderit qui omnis perspiciatis repudiandae ut voluptas. Iusto maxime repellat commodi excepturi. Ea laboriosam aliquam et ea fugiat accusantium et sed.                                           | I semestre |    1 |   3 | www.commodi.uni.it       |
|  978 |        55 | nihil omnis et                     | Ut et voluptate saepe temporibus. Nesciunt dolores pariatur veritatis aut molestiae et. Illum labore dignissimos sunt praesentium sed sit. Qui est consequuntur optio.                                  | I semestre |    1 |  12 | www.non.uni.it           |
|  979 |        55 | voluptatem perferendis repellendus | Quod et et vero sed reiciendis aut. Voluptas incidunt est cupiditate cupiditate. Eius est dolorum quia ut. Totam exercitationem libero ipsam commodi nemo dolores ex.                                   | I semestre |    1 |  13 | NULL                     |
|  980 |        55 | unde architecto pariatur           | Ipsum odit rerum et ullam accusamus a quis. Libero ex eum qui. Error praesentium blanditiis velit atque deserunt nobis esse. Sint et vel mollitia sint.                                                 | I semestre |    1 |   9 | www.et.uni.it            |
|  981 |        55 | dolor quia ex                      | Eveniet rerum quasi eius reiciendis sit vero. Voluptatem rerum odit iusto rem. Vero consectetur sint consequuntur molestiae et quaerat.                                                                 | I semestre |    1 |  10 | www.repudiandae.uni.it   |
|  982 |        55 | eveniet rerum minima               | Est at nulla quis eveniet esse. Omnis dignissimos qui debitis hic veritatis aut. Mollitia tempore eum ipsam animi est aliquid.                 
                                                         | I semestre |    1 |  12 | NULL                     |
|  993 |        56 | commodi laboriosam cumque          | Sed at iusto rerum incidunt. Et modi molestias autem consequatur et eos perspiciatis inventore. Et assumenda et repellendus repellendus illum. Quia officiis qui ut sequi.                              | I semestre |    1 |  12 | NULL                     |
|  994 |        56 | sit sint eveniet                   | Ullam libero velit aliquid fugit ut. Est qui et aut soluta. Voluptate aliquid mollitia quo animi. Ea quae corrupti velit et voluptatem. Hic voluptates laborum quasi adipisci.                          | I semestre |    1 |   7 | NULL                     |
|  995 |        56 | amet quod repudiandae              | Nihil omnis distinctio voluptas sequi quo fugiat aut. Magni nihil maxime tempora. Et omnis quia et.                                            
                                                         | I semestre |    1 |  15 | NULL                     |
|  996 |        56 | voluptas dolores quos              | Nihil consequatur perferendis iure reiciendis consequatur. A omnis fuga officia sequi error molestias. Aperiam commodi aspernatur quis veritatis. Et dolorem aut dolorem nulla.                         | I semestre |    1 |  14 | NULL                     |
| 1006 |        57 | et eos optio                       | Molestiae fugit ullam deserunt ratione quia. Consequuntur tenetur et accusamus quia. Nihil ut dolorem architecto quia vitae suscipit.          
                                                         | I semestre |    1 |   8 | NULL                     |
| 1007 |        57 | rerum deserunt eaque               | Cum perspiciatis velit autem voluptates beatae. Voluptate ipsam pariatur excepturi. Et in cum nemo itaque ipsam deserunt voluptatem.           
                                                         | I semestre |    1 |  11 | NULL                     |
| 1008 |        57 | iusto fuga et                      | Vel aperiam occaecati consequatur voluptas nesciunt. Nihil consequatur optio ut cum. Ratione rerum maiores aut expedita alias. Possimus tenetur qui ea illum voluptatum.                                | I semestre |    1 |   4 | NULL                     |
| 1009 |        57 | cupiditate ullam earum             | Assumenda exercitationem similique dolorum adipisci incidunt placeat distinctio tempore. Adipisci suscipit omnis est ut veniam non odio et. Corrupti autem non impedit vitae fugiat quo.                | I semestre |    1 |  14 | www.qui.uni.it           |
| 1021 |        58 | nobis aut voluptas                 | Omnis et omnis est velit laborum deserunt dolor. Sunt commodi iste aut est quod in illum. Mollitia sunt nostrum ut tempore dolore nihil voluptas.                                                       | I semestre |    1 |  12 | NULL                     |
| 1022 |        58 | autem aut occaecati                | Libero voluptas ex non alias ea sequi. Quis aut ut eum odit. Sequi nihil sed nihil amet sit sed. Perspiciatis veritatis ducimus accusamus sit ipsa facere consequuntur.                                 | I semestre |    1 |  10 | NULL                     |
| 1023 |        58 | perspiciatis magnam dolores        | Commodi minima ex voluptates. Aut nesciunt provident in ut deserunt et rerum.                                                                  
                                                         | I semestre |    1 |  10 | NULL                     |
| 1039 |        59 | sint et perferendis                | Nisi hic dolores enim enim animi ducimus. Suscipit dolorem cum quia in consequatur sed voluptates. Voluptas et eligendi saepe quibusdam. Vel veniam expedita repellendus non.                           | I semestre |    1 |  10 | www.natus.uni.it         |
| 1040 |        59 | iusto sed quas                     | Eveniet labore excepturi est dicta aut modi. Aliquam impedit omnis aperiam temporibus iusto sint. Debitis voluptatibus voluptatem eaque soluta enim aut aut.                                            | I semestre |    1 |   8 | www.consequatur.uni.it   |
| 1041 |        59 | at dolorem temporibus              | Ea excepturi placeat dignissimos quia non ut. Quo qui ut rem accusantium praesentium. Cumque at eligendi minima voluptatem. Autem est aut assumenda nihil rerum. Accusamus sunt tempora aut blanditiis. | I semestre |    1 |  11 | NULL                     |
| 1042 |        59 | doloribus iusto quia               | At quisquam sapiente et voluptatem rerum autem. Ipsam est id voluptatibus delectus suscipit. Impedit blanditiis mollitia fuga unde odio nobis.                                                          | I semestre |    1 |  13 | NULL                     |
| 1056 |        60 | numquam aspernatur nesciunt        | Autem facilis non facilis et tempore esse doloremque. Earum rerum nihil necessitatibus et error. Eos ut esse officia occaecati.                
                                                         | I semestre |    1 |  14 | NULL                     |
| 1057 |        60 | nihil ipsa et                      | Id molestiae maxime consectetur sit nam voluptatum laudantium. Id modi impedit quidem asperiores quisquam. Sit odio in autem et doloribus. Vel quis iste ad hic est minima et.                          | I semestre |    1 |  13 | NULL                     |
| 1058 |        60 | ipsam sit ut                       | Illum qui sit animi ea dolores illum. Hic distinctio vel occaecati accusamus. Quo neque qui vero adipisci.                                     
                                                         | I semestre |    1 |   7 | www.excepturi.uni.it     |
| 1059 |        60 | consequatur et eum                 | Tempore ducimus ea dolore deleniti et. Dolorem optio neque est iusto dignissimos. Odit vero porro iusto. Repellat necessitatibus nisi iusto quidem.                                                     | I semestre |    1 |   3 | www.labore.uni.it        |
| 1078 |        61 | voluptas consequatur sit           | Quo consequuntur voluptatem neque et necessitatibus dolor rem. Velit quis qui velit exercitationem est. Ex labore recusandae consequatur debitis voluptatem. Dignissimos doloribus et aliquid aut hic.  | I semestre |    1 |  10 | NULL                     |
| 1079 |        61 | enim quae quos                     | Et aut voluptatem sit ad sed nam pariatur velit. Qui veritatis nesciunt blanditiis natus quia.                                                 
                                                         | I semestre |    1 |  13 | NULL                     |
| 1080 |        61 | distinctio rerum dolor             | Et omnis vel rem quia. Nihil alias similique voluptas provident enim. Facilis ipsum numquam corporis rerum.                                    
                                                         | I semestre |    1 |  14 | www.temporibus.uni.it    |
| 1081 |        61 | perspiciatis fuga praesentium      | Voluptas est omnis voluptatum et sed omnis aliquid et. Saepe voluptates delectus qui dolorem. Voluptatum ut eveniet nam et eligendi enim.                                                               | I semestre |    1 |  10 | www.architecto.uni.it    |
| 1092 |        62 | libero eius cum                    | Fugiat tenetur repellat expedita. Voluptatem qui est nesciunt voluptatum vel. Ab natus in in quaerat sint.                                     
                                                         | I semestre |    1 |   6 | NULL                     |
| 1093 |        62 | magni vitae exercitationem         | Molestiae repudiandae voluptas omnis nisi officiis. Nihil dicta blanditiis magnam et exercitationem. Sunt laboriosam autem minima ut et fugiat quos est. Qui ut in nulla.                               | I semestre |    1 |   9 | www.aut.uni.it           |
| 1094 |        62 | excepturi vero ad                  | Fugiat alias ex harum voluptas. Beatae quisquam aut ut ipsum natus sit. Sequi est tenetur cum et et.                                           
                                                         | I semestre |    1 |  10 | NULL                     |
| 1103 |        63 | ducimus voluptatibus asperiores    | Dolorem enim totam non cupiditate molestiae consequatur aut. Nobis quibusdam consectetur est sed qui repellendus et et.                        
                                                         | I semestre |    1 |   7 | NULL                     |
| 1104 |        63 | consequatur ut architecto          | Doloremque cumque necessitatibus recusandae odit. Atque voluptatem quasi consequatur totam incidunt natus. Necessitatibus quaerat illo suscipit sint. Et corrupti hic quia soluta sed culpa.            | I semestre |    1 |   9 | www.aut.uni.it           |
| 1105 |        63 | porro suscipit incidunt            | Corporis incidunt qui tenetur aut. Qui occaecati nemo culpa maxime. Aut illo omnis ipsa sit fugiat qui vero ut. Soluta at aliquam necessitatibus qui et alias voluptatem sed.                           | I semestre |    1 |   3 | NULL                     |
| 1116 |        64 | soluta alias fugiat                | Autem sequi error rerum dolorem voluptates nemo laborum. Dolorem asperiores repellendus voluptates corporis ut harum. Consequatur et sunt eos. Omnis explicabo vitae laudantium sit est.                | I semestre |    1 |  14 | www.officiis.uni.it      |
| 1117 |        64 | doloremque aut nihil               | Voluptatem nostrum a dolores consequuntur nobis. Maxime eius in cum repellendus qui eos maxime cumque.                                         
                                                         | I semestre |    1 |   7 | www.excepturi.uni.it     |
| 1118 |        64 | consectetur eos voluptatum         | Perspiciatis expedita omnis autem minus consequatur ad dolore. Voluptas qui quibusdam dolore repellat.                                         
                                                         | I semestre |    1 |   4 | www.quisquam.uni.it      |
| 1129 |        65 | rerum dolor quia                   | Rem magnam facere sed sed amet in. Dolores numquam minima magni non iure.                                                                      
                                                         | I semestre |    1 |  10 | NULL                     |
| 1130 |        65 | reprehenderit occaecati eum        | Dicta ut praesentium et cupiditate odio. Laboriosam quia culpa ad aut quae omnis. Rerum earum magni mollitia sit. Officia doloribus rem enim dolorum temporibus quod. Qui minus iste laboriosam cum.    | I semestre |    1 |   7 | www.a.uni.it             |
| 1131 |        65 | facere explicabo quam              | Ipsum nihil debitis numquam repellat fuga modi odio. Enim rerum praesentium et est cumque. Nam modi facere aliquam autem maxime ab.            
                                                         | I semestre |    1 |  15 | www.culpa.uni.it         |
| 1142 |        66 | quidem deleniti omnis              | Perspiciatis est quo architecto omnis qui. Id repellat consequatur velit corrupti. Voluptatem est saepe nihil repudiandae corporis corrupti repellat.                                                   | I semestre |    1 |  10 | NULL                     |
| 1143 |        66 | ex quaerat commodi                 | Et ea odit possimus deserunt. Fugit incidunt repellat a corporis ut. Vel pariatur perferendis et sed optio. Quia dolores ullam animi perferendis.                                                       | I semestre |    1 |  13 | NULL                     |
| 1144 |        66 | tempore voluptates eaque           | Cupiditate ratione sapiente porro libero. Et et enim repellat commodi. Ullam sit eum soluta eos exercitationem ad aut. Eum minima aliquam aut atque et molestias quis.                                  | I semestre |    1 |   9 | NULL                     |
| 1159 |        67 | alias voluptates dignissimos       | Eum eligendi facilis natus nihil quaerat. Explicabo non suscipit laudantium aut et dolorem. Quibusdam omnis sunt qui eum reiciendis odit ut. Esse nemo ut doloremque.                                   | I semestre |    1 |   8 | www.nostrum.uni.it       |
| 1160 |        67 | quos pariatur aliquid              | Deleniti veniam perspiciatis eius ut mollitia. Quod nostrum adipisci aut qui. Voluptas id eos eveniet sint in. Adipisci delectus perspiciatis ut eos.                                                   | I semestre |    1 |  12 | NULL                     |
| 1161 |        67 | culpa nulla aut                    | Maxime deserunt dolor dolores. Esse voluptatem rem placeat eum nihil. Magnam qui reiciendis quo rerum minus placeat dolorum. Omnis autem ipsum nobis deleniti.                                          | I semestre |    1 |  13 | NULL                     |
| 1162 |        67 | aliquam molestias sit              | Enim est ut eos doloribus quod. Saepe provident repellendus quia molestiae. Eius consectetur saepe quia et omnis cum rerum. Odio magni impedit quisquam praesentium.                                    | I semestre |    1 |  12 | www.consequatur.uni.it   |
| 1182 |        68 | alias explicabo amet               | Voluptatem autem et ipsum suscipit. Quisquam quam debitis deserunt labore velit. Nam quia aut sed qui.                                         
                                                         | I semestre |    1 |   6 | NULL                     |
| 1183 |        68 | at exercitationem libero           | Nam sunt sit aut a aut voluptas. Laborum ipsa ipsam error minima et. Alias rerum consectetur natus quibusdam similique praesentium. Enim animi dolores magni reprehenderit in adipisci neque.           | I semestre |    1 |   3 | NULL                     |
| 1184 |        68 | molestias animi vel                | Consequatur rerum nam qui nihil. Iste quibusdam atque eum et. Rerum voluptatem dolores dolores dolor reiciendis ducimus nemo. Consectetur dolorem consequatur saepe dicta ipsam aspernatur.             | I semestre |    1 |   6 | NULL                     |
| 1195 |        69 | facilis magnam rem                 | Voluptate porro est amet dolorem. Sint odit consequatur at quas doloremque. Dignissimos harum beatae omnis voluptatem magni numquam accusamus.                                                          | I semestre |    1 |  12 | NULL                     |
| 1196 |        69 | quae inventore voluptatem          | Qui hic natus nihil. Impedit dignissimos laboriosam sed unde libero temporibus sed. Animi nihil expedita labore vitae et.                      
                                                         | I semestre |    1 |  10 | www.impedit.uni.it       |
| 1197 |        69 | voluptas dicta qui                 | Est autem culpa tempora. Autem dolorem voluptatem saepe similique facere. Ut nisi est consequuntur rerum alias laudantium.                     
                                                         | I semestre |    1 |   6 | NULL                     |
| 1217 |        70 | et provident culpa                 | Eum ullam blanditiis necessitatibus. Est aliquid vel debitis at. Molestiae qui dicta deleniti est quia quas.                                   
                                                         | I semestre |    1 |   5 | www.unde.uni.it          |
| 1218 |        70 | quas cum vel                       | Aperiam perspiciatis reprehenderit porro officiis. Numquam iusto in voluptatem consequuntur numquam amet. Perferendis ipsam sint fugit similique. Earum itaque aliquam vel saepe modi odit et.          | I semestre |    1 |  13 | www.sunt.uni.it          |
| 1219 |        70 | nostrum atque ipsa                 | Iure corporis similique assumenda et eius hic. Ut modi illum aut quam sint. Et qui nesciunt occaecati et. Sint quaerat voluptatem aperiam suscipit ducimus omnis distinctio.                            | I semestre |    1 |  11 | www.suscipit.uni.it      |
| 1220 |        70 | minus consequatur culpa            | Voluptate velit autem atque error. Eos animi laudantium ratione error recusandae est. Amet est nam cupiditate autem dolorum ratione ratione. Ab nemo dignissimos iusto dignissimos magnam.              | I semestre |    1 |   6 | NULL                     |
| 1242 |        71 | dolor error porro                  | Non harum aut odio quae. Et eos reprehenderit fuga consequatur sunt dolores veritatis et. Eos molestias eius ut eos error ad aut.              
                                                         | I semestre |    1 |   9 | NULL                     |
| 1243 |        71 | earum repellat et                  | Ex voluptatibus repellendus et accusantium consequatur. Aut est quo quae dolorem pariatur voluptates. Possimus rem totam vitae unde aut totam.                                                          | I semestre |    1 |   8 | NULL                     |
| 1244 |        71 | molestiae aut sit                  | Quo qui ut aut nemo. Autem aut incidunt dicta recusandae maxime. Nobis labore sapiente non rem. Ut dicta placeat animi labore eius.            
                                                         | I semestre |    1 |  12 | www.quo.uni.it           |
| 1245 |        71 | incidunt aperiam qui               | Inventore et sit et et qui fugit. Velit iusto aut et assumenda asperiores reiciendis ut.                                                       
                                                         | I semestre |    1 |  12 | www.enim.uni.it          |
| 1258 |        72 | eos quisquam dolores               | Animi enim labore repellat quidem. Ut incidunt et maiores. Nam quia ipsam cum eligendi blanditiis. Esse eos corporis omnis voluptatibus.                                                                | I semestre |    1 |   3 | www.commodi.uni.it       |
| 1259 |        72 | magni magni omnis                  | Maxime est est vitae. Natus ut reiciendis veniam. Voluptas dolor accusamus harum sapiente occaecati dolorum iusto.                             
                                                         | I semestre |    1 |   5 | www.ea.uni.it            |
| 1260 |        72 | rerum molestiae provident          | Nesciunt adipisci voluptas soluta voluptas. Ut quis sequi et. Fuga voluptas corrupti necessitatibus nostrum. Atque incidunt id beatae.         
                                                         | I semestre |    1 |   8 | NULL                     |
| 1261 |        72 | voluptas sit aliquam               | Voluptas sed numquam laboriosam quia non dignissimos error minus. In nobis quia asperiores rerum delectus enim. Distinctio nesciunt dolores cumque soluta.                                              | I semestre |    1 |  11 | www.earum.uni.it         |
| 1273 |        73 | porro cupiditate qui               | Eaque voluptates voluptatibus possimus magnam omnis eos. Illum quam dolorem vel reiciendis suscipit deleniti sunt. Voluptatibus quis sed asperiores ex in fugit. Dolor ut voluptas quia.                | I semestre |    1 |   3 | NULL                     |
| 1274 |        73 | adipisci ut quis                   | Et voluptas maxime reprehenderit eius consequatur at. Corporis saepe recusandae temporibus. Maiores amet quaerat ab dolore nesciunt perspiciatis. Quaerat quia aut laudantium nostrum nihil alias.      | I semestre |    1 |  12 | NULL                     |
| 1275 |        73 | quidem vero eaque                  | Sed ut culpa repellendus consequuntur. Et eligendi est magnam vel rerum at temporibus. Iure et et iste.                                        
                                                         | I semestre |    1 |   7 | NULL                     |
| 1276 |        73 | impedit vitae laboriosam           | Tempora provident a eaque reprehenderit ipsum. Voluptatem dolorum quia et omnis. Maiores repellat voluptatum beatae quos suscipit.             
                                                         | I semestre |    1 |  10 | www.voluptas.uni.it      |
| 1287 |        74 | reprehenderit rerum eaque          | Sit officia id possimus aperiam earum hic. Vel ut eos veritatis repudiandae incidunt odio.                                                     
                                                         | I semestre |    1 |   8 | www.quo.uni.it           |
| 1288 |        74 | quia totam sunt                    | Temporibus est et et ut occaecati facilis. Porro aut magnam quis repellendus culpa iste.                                                       
                                                         | I semestre |    1 |  10 | www.ipsam.uni.it         |
| 1289 |        74 | quia non rerum                     | Aut dicta perferendis veniam cum quia quis. Dolorem dolor repellat quo quam enim dolores. Eveniet accusantium adipisci aliquid quis quo. Neque voluptatem ipsa iusto voluptas at veritatis.             | I semestre |    1 |  15 | NULL                     |
| 1290 |        74 | reiciendis dolorum labore          | Quo est exercitationem dolorem id. Voluptatem harum deserunt adipisci sit dolorum. Harum impedit neque officiis in. Rem dolor harum a nesciunt. Eligendi ipsam aut ea corporis.                         | I semestre |    1 |  13 | NULL                     |
| 1303 |        75 | quaerat in qui                     | Unde laboriosam deserunt fugit dolor. Eos fuga expedita vel eum quo.                                                                           
                                                         | I semestre |    1 |  11 | NULL                     |
| 1304 |        75 | minus expedita et                  | Sapiente ratione consequuntur enim sed. Nemo doloribus quos architecto minus adipisci. Et sit aspernatur vel dolores.                          
                                                         | I semestre |    1 |  12 | NULL                     |
| 1305 |        75 | consectetur aut est                | Tempore ut ut maiores temporibus. Quos molestiae expedita vitae ea veritatis et. Quis possimus mollitia ut. Voluptatem nam laborum et sint rem officia qui.                                             | I semestre |    1 |  14 | NULL                     |
| 1306 |        75 | distinctio rem quis                | Repellat provident laboriosam consectetur et quo mollitia. Mollitia aut sed rem ut. Consequatur vitae voluptatem quos quaerat iste illo.                                                                | I semestre |    1 |   3 | NULL                     |
| 1307 |        75 | unde commodi qui                   | Ut architecto et nemo sed. Consequatur rerum sit totam illo dolorum blanditiis. Quo ad non laborum ad et repellendus dicta. Repellendus quod totam quia sit.                                            | I semestre |    1 |  14 | www.quaerat.uni.it       |
+------+-----------+------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------+------+-----+--------------------------+
286 rows in set (0.00 sec)



5. SELECT * FROM `exams` WHERE date = '2020-06-20' AND hour > '14:00:00';
+------+-----------+------------+----------+-----------------+----------------------------------+
| id   | course_id | date       | hour     | location        | address                          |
+------+-----------+------------+----------+-----------------+----------------------------------+
|   48 |        10 | 2020-06-20 | 14:15:00 | Piano 2         | Rotonda Loredana 103 Piano 3     |
|  368 |        74 | 2020-06-20 | 14:20:00 | Appartamento 94 | Strada Pellegrini 53             |
|  598 |       120 | 2020-06-20 | 15:20:00 | Appartamento 24 | Incrocio Cristyn 66 Piano 5      |
| 1078 |       216 | 2020-06-20 | 16:40:00 | Appartamento 42 | Strada Lorenzo 2 Appartamento 63 |
| 1463 |       293 | 2020-06-20 | 16:00:00 | Piano 6         | Via Monia 86                     |
| 1578 |       316 | 2020-06-20 | 14:45:00 | Piano 8         | Borgo Jelena 1                   |
| 1663 |       333 | 2020-06-20 | 14:40:00 | Piano 2         | Strada Kayla 16                  |
| 1988 |       398 | 2020-06-20 | 15:20:00 | Appartamento 28 | Via Sarita 3 Appartamento 56     |
| 2298 |       460 | 2020-06-20 | 15:45:00 | Appartamento 36 | Contrada Alessio 44 Piano 4      |
| 2433 |       487 | 2020-06-20 | 16:00:00 | Appartamento 78 | Strada Gallo 7 Piano 7           |
| 2578 |       516 | 2020-06-20 | 16:45:00 | Piano 2         | Borgo Noah 404 Piano 2           |
| 2873 |       575 | 2020-06-20 | 14:45:00 | Piano 2         | Strada Mercedes 84               |
| 3423 |       685 | 2020-06-20 | 15:30:00 | Appartamento 87 | Via Rizzo 7                      |
| 3948 |       790 | 2020-06-20 | 16:45:00 | Piano 7         | Contrada Russo 240               |
| 4558 |       912 | 2020-06-20 | 16:40:00 | Piano 7         | Strada D'amico 7 Appartamento 15 |
| 5013 |      1003 | 2020-06-20 | 14:45:00 | Appartamento 10 | Piazza Costa 7                   |
| 5473 |      1095 | 2020-06-20 | 16:00:00 | Piano 7         | Via Vinicio 89                   |
| 5593 |      1119 | 2020-06-20 | 16:20:00 | Piano 4         | Via Raniero 306 Piano 0          |
| 6103 |      1221 | 2020-06-20 | 14:40:00 | Piano 1         | Incrocio Sorrentino 1            |
| 6328 |      1266 | 2020-06-20 | 16:30:00 | Piano 5         | Via Ileana 1 Appartamento 27     |
| 6403 |      1281 | 2020-06-20 | 16:00:00 | Piano 4         | Rotonda Giobbe 4                 |
+------+-----------+------------+----------+-----------------+----------------------------------+
21 rows in set (0.00 sec)


