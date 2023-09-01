# db

Drugi kolokvijum – pitanja za P6, P7, P8, P9, P10, P11, P12
1. Na čemu je zasnovna model kolonski orjentisanih baza podataka?
Model podataka je zasnovan na redovima koji imaju mnogo kolona povezanih sa ključem reda. Svaki red ima svoj jedinstveni ključ koji se zove ključ reda. Red se sastoji od određenog broja kolona koje su ograničene na taj red. Kolone se ne proširuju na ostale redove, kao što je slučaj sa kolonama u relacionim bazama podataka.
2. Navesti elemente kolone za model kolonski orjentisanih baza podataka Naziva kolone, vrednosti, vremenske oznake.
3. Šta je porodica kolona?
Porodica kolona predstavlja skup kolona koje sadrže povezane podatke i koje pripadaju istom redu. Obično se ponašaju kao kontejneri za sortirani niz redova.
4. Šta je super kolona?
Super kolona je kolona čija je vrednost sastavljena od grupe kolona. Sastoji se od sortiranog niza kolona. Postoje vremenske oznake za kolone koje su u sastavu super kolone, ali ne postoji jedna jedinstvena vremenska oznaka.
5. Šta je keyspace?
Keyspace predstavlja kontejner za više različitih porodica kolona. Omogućava zajedničko grupisanje svih porodica kolona koji unutar sistema pripadaju istoj aplikaciji. Ima sličnu ulogu kao i baza podataka unutra nekog relacionog sistema.
6. Navesti sisteme zasnovne na modelu kolonski orjentisanih baza podataka. HBase, Cassandra, Hypertable, Amazon SimpleDB
7. Šta su graf baze podataka?
Graf baze podataka predstavljaju sisteme koji koriste graf model podataka za skladištenje i obradu podataka. Kod graf baza podataka shema nije definisana unapred, tačnije rečeno shema je odraz unesenih podataka. Kako se unose raznovrsniji podaci, i shema raste u skladu s tim.
8. Navesti osnovne koncepte graf modela podataka sa atributima.
Osnovni koncepti graf model podataka sa atributima su: čvorovi, veze, atributi, oznake.
9. Za koju namenu se koriste oznake kod graf baza podataka?
Oznake se koriste za grupisanje čvorova u skupove, pri čemu jedan čvor može imati više oznaka.
10. Navedi pravila modelovanja graf baza podataka.
Svaki čvor i veza (grana) imaju svoje jedinstvene identifikatore. Svaki čvor ima veze (grane) koji u njega ulaze i iz njega izlaze. Svaki čvor i veza (grana) imaju skup atributa (svojstava) koji se čuvaju po principu ključ-vrednost. Svaka veza (grana) ima početni čvor -vrh (izvorište) i završni čvor (odredište). Svaka veza ima oznaku koja označava tip veze koja povezuje dva čvora.
11. Šta predstavlja traverziranje?
Traverziranje ili prolazak kroz graf predstavlja “putovanje” kroz određeni deo grafa polazeći od određenog čvora u grafu, prateći izlaznu vezu koja vodi do sledećeg čvora, pa se iz tog čvora prati sledeća veza do sledećeg čvora i tako dalje. Traverziranjem se zapravo „čita” graf ili neki njegov deo.
12. Šta predstavlja putanju u graf modelu baza podataka?
Putanja predstavlja niz naizmenično poređanih čvorova i veza. Čvor koji prethodi nekoj vezi u tom nizu je polazni čvor te veze u grafu, a čvor koji sledi toj vezi je njen krajnji čvor u grafu. Putanja je rezultat prolaska kroz graf.
 13. Kako se definiše poslovna inteligencija?
Poslovna inteligencija se definiše kao skup procesa za prikupljanje i analizu poslovnih podataka u cilju donošenja boljih poslovnih odluka i identifikaciju novih poslovnih mogućnosti. Poslovni podaci
 i istraživanja pružaju primarne i naknadne informacije o tržištu, potrošačima, konkurenciji, kao i o ostalim činiocima poslovanja na osnovu kojih se može definisati strategija poslovanja. U dinamičnom poslovnom okruženju da širokom krugu poslovnih korisnika obezbedi efikasan, brz, jeftin i jednostavan pristup potrebnim informacijama.
14. Šta uključuje opšti model poslovne inteligencije?
Selekciju podataka iz transakcione baze; Ekstrakciju, transformaciju i čišćenje podataka; Smeštanje podataka u skladište podataka; Formiranje OLAP kocke; Kreiranje izveštaja; Rudarenje podataka
15. Kako se definiše skladište podataka?
Skladište podataka se definiše tako da je predmetno orijentisano, integrisano, trajno, promenljivo u vremenu.
16. Šta predstavlja analitika velikih podataka?
Analitika velikih podataka se definiše kao proces prikupljanja, ispitivanja i analize velikih skupova podataka različitih tipova i formata kako bi se otkrili obrasci od značaja, korelacije među podacima i
 ostale značajne informacije koje su u funkciji sistema za odlučivanje. 17. Šta je desktiptivna analitika?
Deskriptivna analitika je statistička metoda koja se koristi za pretraživanje i sumiranje istorijskih podataka u cilju identifikacije obrazaca ili značenja. Sastoji se od postavljanja pitanja: Šta se dešava? Akcenat je na dijagnostičkom problemu, ali i na opisu uzroka i posledica nastalih problema, kao i pronalaženju načina za njihovo rešavanje. Deskriptivna analitika ima za cilj da odgovori na pitanja o događajima koji su se već desili.
18. Šta je dijagnostička analitika?
Dijagnostička analitika traži osnovni uzrok problema. Sastoji se od postavljanja pitanja: Zašto se to dogodilo? Pokušava da otkrije uzrok fenomena koji se desio u prošlosti korišćenjem pitanja koji se odnose na razloge. Cilj je odrediti koja informacija se odnosi na fenomen da bi odgovorili na pitanje zašto se nešto desilo.
19. Šta je prediktivna analitika?
Prediktivna analitika je statistička metoda koja koristi algoritme mašinskog učenje za identifikaciju trendova u podacima i predviđanja budućeg ponašanja. Zasniva se na pitanju: šta će se verovatno dogoditi? Akcenat je na predviđanju budućih problema na bazi prethodnih iskustava, kao i na merama prevencije posledica. Predstavlja skup naprednih alata i tehnika koje se koriste u analizi velikih serija sadašnjih i prošlih podataka kako bi se predvideli budući događaji na bazi identifikovanih obrazaca ponašanja. U osnovi Big Data prediktivne analitike je upotreba savremenih informacionih tehnologija kao što je Hadoop ekosistem.
20. Šta je preskriptivna analitika?
Preskriptivna analitika je statistički metod koji se koristi za generisanje preporuka i donošenje odluka zasnovanih na rezultatima modela zasnovanih na algoritmima. Generisanje automatizovanih odluka ili preporuka zahteva specifične i jedinstvene algoritamske modele i jasnije smernice od onih koji koriste analitičku tehniku. Preporuka se ne može generisati bez znanja šta tražiti ili koji problem se želi rešiti. Na ovaj način, preskriptivna analitika počinje problemom. Sastoji se od postavljanja
 pitanja: Šta treba učiniti? Preskriptivna analitika je zasnovana na rezultatima prediktivne analitike predlaganjem akcije koje treba izvesti. Fokus je ne samo koju predloženu opciju je najbolje pratiti, nego i zašto. Cilj je ostvarivanje prednosti ili smanjivanje rizika.
21. Navesti faze u procesu otkrivanja znanja
Razumevanje domena, Predprocesiranje podataka, Otkrivanje obrazaca, Postprocesiranje podataka, Prikaz modela.

 22. Šta predstavlja rudarenje podataka?
Proces izdvajanja novih, potencijalno korisnih, interesantnih, razumljivih informacija ili uzoraka sadržanih u podacima, a sve u cilju donošenja ispravnih poslovnih odluka
23. Iz kojih faza se sastoji process rudarenja podataka?
Sakupljanje podataka i kreiranje skupa za analizu, priprema i predprocesiranje podataka, primene algoritama za rudarenje podataka, tumačenje i vrednovanje rezultata.
24. Šta obuhvata priprema podataka?
Obuhvata postupak obrade šuma u podacima (ispravka nepravilnosti u podacima), rešavanje problema nedostajućih vrednosti u podacima, obradu izuzetaka, izbor relevantnog podskupa obeležja transformaciju kontinulanih obeležja primenom odgovarajućih metoda diskretizacije.
25. Na čemu se zasniva izbor obeležja skupa za analizu?
Zasniva se na rešavanju problema izdvajanja optimalnog vektora obeležja iz orginalnog skupa za analizu, a koji su potrebni i dovoljni da opišu koncept sistema.
 26. Kako se dele algoritmi za izbor obeležja? Filter modeli, Modeli omotača, Hibridni modeli.
27. Šta je osnovni cilj diskretizacije?
Osnovni cilj diskretizacije je usmeren na smanjenje broja mogućih vrednosti kontinualnih karakteristika čime se utiče na brzinu i efikasnost procesa.
28. Šta predstavlja klasifikacija?
Predstavlja zadatak nadgledanog učenja kojim se vrši predviđanje vrednosti klasnog izlaznog atributa na osnovu vrednosti ulaznih atributa.
29. Šta je klasifikator?
Algoritam koji je zasnovan na funkciji koja predviđa oznaku klase za dati instancu.
30. Kako se deli skup za analizu prilikom primene izabranog klasifikatora? Na obučavajući skup i skup za testiranje.
31. Šta predstavlja podrška, a šta poverenje pravila udruživanja?
Podrška (support, sup, s) pravila udruživanja predstavlja procenat transakcija koje uključuju stavke X i Y iz D.
Podrška (sup) = (broj transakcija koje sadrže X i Y) / (ukupan broj transakcija)
Poverenje (confidence, conf, c) pravila je udeo transakcija koje sadrže stavke skupa među transakcijama koje sadrže stavke skupa
Poverenje(conf) = (broj koji sadrži X i Y ) / (broj transakcija koje sadrže X)
32. Šta je klasterizacija?
Klasterizacija je jedan od oblika nenadgledanog mašinskog učenja. Kod ove metode ne postoje podaci o poželjnoj / ispravnoj grupi (klasi) za date instance. Potrebno je izvršiti grupisanje podataka na osnovu raspoloživih podataka.
33. Na koji način se vrši procena sličnosti instanci?
 Sličnost instanci se procenjuje primenom neke od mera za računanje: sličnosti (npr. Kosinusna sličnost ili koeficijent korelacije) ili udaljenosti dve instance (npr. Euklidska ili Manhattan udaljenost).
34. Navesti glavne komponenete Hadoop ekosistema
HDFS - Hadoop Distributed File System – distribuirani fajl system; MapReduce - programski zasnovana obrada podataka; YARN - Yet Another Resource Negotiator - upravljač resursima; Hadoop Common – osnovne biblioteke

35. Navesti elemente HDFS arhitekture
HDFS arhitektura se sastoji od glavnog čvora (NameNode), sekundarnog čvora (Secondary Name Node), skladišnih čvorova (DataNodes).
36. Koja je uloga glavnog čvora u HDFS arhitekturi?
Glavni čvor (NameNode) je centralni čvor koji upravlja metapodacima HDFS-a. Čuva informacije o rasporedu podataka, kao i o tome gde se podaci fizički nalaze u klasteru. Odgovoran je za vođenje evidencije o podacima raspoređenim preko DataNode-ova, upravlja metapodacima celokupnog datotečnog sistema i vrši balansiranje opterećenja.
37. Koja je uloga sekundarnog čvora u HDFS arhitekturi?
Sekundarni čvor (Secondary NameNode) je pomoćni čvor koji podržava NameNode u održavanju I arhiviranju metapodataka HDFS-a. Vodi evidenciju promena i redovno pravi snimke (snapshot) kako bi omogućio brzo pokretanje sistema. Periodično sinhronizuje metapodatke sa NameNode-om i
pomaže u obnavljanju metapodataka u slučaju pada NameNode-a. Nije rezervna kopija NameNode-a, već pomaže u održavanju i podršci.
38. Koja je uloga skladišnih čvora u HDFS arhitekturi?
DataNode čvorovi čine glavne skladišne čvorove u Hadoop klasteru. Zaduženi su za fizičko skladištenje podataka i pružaju usluge čitanja i pisanja podataka u skladu sa uputstvima NameNode-a. DataNode čvorovi održavaju kopije podataka, izvršavaju replikaciju ili kodiranje za brisanje grešaka (erasure coding) kako bi obezbedili redundanciju podataka i otpornost na greške.
39. Navesti faze MapReduce programskog modela
Faza mapiranja (map); faza grupisanja (shuffle); faza smanjenja (reduce)
40. Objasniti map funkciju
Map() funkcija se posebno primenjuje na svaku stavku ulaznih podataka. Ulaz je jedna stavka podataka iz datoteke sa podacima. Izlaz je nula ili više (ključ, vrednost) parova.
41. Šta je rezultat faze grupisanja?
Vrednosti konsolidovane u jednu listu (ključ, lista). Obavlja se automatski u MapReduce okruženju. Realizuje se funkcijom shuffle.
42. Šta je ulaz u reduce fazu MapReduce modela?
Ulaz je lista vrednosti koji sadrži sve vrednosti generisane za zadati ključ u Map fazi.
43. Šta je izlaz iz reduce faze MapReduce modela? Izlaz je lista vrednosti, po jedna za svaki ključ


prvi



Drugi kolokvijum – pitanja za prvih pet predavanja
1. Kako se može definisati pojam Big data?
Big Data se može definisati kao bilo koja vrsta izvora podataka koja ima sledeće karakteristike : Volume- Variety-Veracity-Velocity-Value-Verification-Visibility (Količina – Raznovrstnost – Tačnost – Brzina – Korisnost – Verifikacija – Vidljivost).
2. Koje su najvažnije Big Data karakteristike?
Volume- Velocity - Variety (Količina, Brzina, Raznovrsnost)
3. Koje vrednosti se smatraju količinom velikih podataka.
Količine podataka koje prevazilaze terabajte.
4. Šta predstavlja heterogenost podataka?
Raznovrsnost podataka
5. U koju kategoriju podataka spadaju slike, tekst, zvuk? Navesti osnovne karakteristike istih.
Slike, tekst, zvuk spade u nestruktuirane podatke koji nemaju unapred definisan model.
6. Koje su karakteristike struktuiranih podataka?
Imaju jasno definisan format i strukturu i najčešće se nalaze u bazama podataka ili skladištima podataka. Mogu se svrstati u kategoriju metričkih ili numeričkih tipova čija je obrada, analiza i interpretacija veoma precizno definisana i relativno jednostavna. Mogu se upotrebljavati više puta i pogodni su za automatsku obradu.
7. Kako se dele izvori struktuiranih podataka?
Izvori strukturiranih podataka se dele na mašinske (uređaji koji sami generišu podatke) i ljudske (izvori koje se odnose na interakcijiu čoveka i uređaja).
8. Koji podaci spadaju u kategoriju kvazi struktuiranih podataka?
To su tekstualni podaci koji su dati u nestandardnom formatu tako da se mogu formatirati, ali je za to potrebno dosta vremena, alata i znanja.
9. Navedi kategoriju podataka kod kojih pojedini elementi ne moraju da imaju zajedničku strukturu Polustrukturirani podaci se mogu definisati kao strukturirani podaci koji se ne uklapaju u formalnu strukturu modela podataka. Najčešće ne sadrže oznake koje razdvajaju semantičke elemente i nemaju zajedničku strukturu.
10. Navedi modela podataka i njihove osnovne karakteristike. Stablo: denormalizovani podaci strukture stabla koji se nalaze u formatima kao što su XML i JSON Nestruktuirani: mnogo podataka se jednostavno akumulira u sirovom obliku kao što su tekst, slike (pikseli), audio, video itd. Kocka: 1990.-ih, ovaj oblik podataka je bio veoma popularan u oblasti poslovne analitike, sa primarnim slučajem upotrebe analize podataka prodaje i izradu izveštaja za najviše rukovodstvo i strateško odlučivanje. Grafovi: sistemi baza podataka (Neo4j, Oracle PGX, itd.) koji prikazuju podatke kao graf sa čvorovima i vrhovima. Graf oblici su posebno korisni kada je slučaj upotrebe fokusiran na efikasno obilaženje podataka (ekvivalentno spojevima u tabelama, koji su prilično spori i skupi u poređenju sa drugim operacijama).
11. Navedi faktore koje utiču na brzinu generisanja podataka i objasni ih. Tri najvažnija faktora koja označavaju karakteristiku brzine generisanja podataka su: Kapacitet: koliko podataka možemo da uskladištimo po jedinici zapremine? Propusnost: koliko brzo možemo da pročitati u jedinici vremena? Latencija: koliko vremena treba da sačekamo dok bajtovi ne počnu da stižu - kada počinjemo da primamo podatke?
 12. Objasni Big Data karaketristiku tačnosti
Tačnost (Veracity) predstavlja kontrolisanje pouzdanosti i verodostojnosti podataka koji se prikupljaju iz širokog spektra različitih izvora i mogu biti u različitim formatima.

 13. Na šta se odnosi karakteristika Value?
Odnosi se na mogućnost pretvaranja podataka u dobit.
14. Na kojim konceptima se zasniva Big Data?
Infrastruktura, Skladištenje (čuvanje) velikih skupova podataka, Pronalaženje podataka, Tehnologije i analitički softveri koji se primenjuju na Big Data za obradu podataka, eliminaciju duplikata i strukturisanje informacija radi mogućnosti budućih analiza uz korišćenje BI (engl. Business Intelligence) i AI (engl. Artificial Intelligence) sistema, u cilju donošenja pametnih odluka koje počivaju da podacima.
15. Šta predstavlja Big Data infrastrukturu?
Izvori podataka, sistemi za prikupljanje podataka, fizički mediji za skladištenje podataka (servere), mreža za prenos podataka, softverski alati za analizu podataka, infrastruktura za rezervne kopije podataka, prateći softver i rezultate obrade.
16. Na koji način kompanije skladište velike količine podataka? U skladištima podataka, jezerima
 podataka, oblaku, kompanijskim serverima.
17. Koje način omogućava čuvanja podataka u izvornom formatu?
Jezera podataka
18. Šta je model podataka?
Model podataka je skup pravila koja određuju logičku strukturu unutar baze podatka. Model čini
osnovu za koncipiranje, projektovanje i implementaciju baze.
19. Na čemu je zasnovan relacioni model podataka?
Zasnovan je na matematičkom pojmu relacije. Podaci i veze među podacima prikazani su u
tabelarnom obliku.
20. Na čemu je zasnovan mrežni model podataka?
Mrežni model je zasnovan na usmerenim grafovima. Čvorovi su tipovi zapisa, a grane definišu veze
među tipovima zapisa.
21. Na čemu je zasnovan hijerarhijski model podataka?
Hijerarhijski model je specijalni slučaj mrežnog. Baza je predstavljena jednim stablom ili skupom stabala. Čvorovi su tipovi zapisa, a hijerarhijski odnos “nadređeni-podređeni” izražava veze među tipovima zapisa.
22. Na čemu je zasnovan objektni model podataka?
Objektni model je zasnovan na principima objektno-orijentisanih programskih jezicika. Baza je skup objekata koji se sastoje od svojih internih podataka i “metoda” (operacija) za rukovanje s tim podacima. Svaki objekat pripada nekoj klasi. Između klasa se uspostavljaju veze nasleđivanja, agregacije, odnosno međusobnog korišćenja operacija.
23. Kada kažemo da je relacija u prvoj normalnoj formi?
Relacija se nalazi u prvoj normalnoj formi (1NF) ako je svaki njen atribut atomičan – to znači da sadrži samo jednu vrednost. Svi neključni atributi su funkcionalno zavisni od primarnog ključa. Ovo pravilo je jednostavno i proizilazi iz definicije primarnog ključa. Baza podataka je u 1NF ako sve tabele ispunjavaju uslove prve normalne forme.
 24. Kada kažemo da je relacija u drugoj normalnoj formi?
Relacija se nalazi u drugoj normalnoj formi ako se nalazi u prvoj normalnoj formi i ako je svaki neključni atribut u potpunosti funkcionalno zavisan od celog primarnog ključa. Svaki neključni atribut mora da bude definisan i određen celim, a ne delom primarnog ključa. Svi atributi koji delimično zavise od primarnog ključa se izdvajaju u novu relaciju.
25. Kada kažemo da je relacija u trećoj normalnoj formi?
Relacija se nalazi u trećoj normalnoj formi ako se nalazi u prvoj i u drugoj normalnoj formi i ako ne

 postoji tranzitivna zavisnost izemeđu atributa. Tranzitivna zavisnost predstavlja funkcionalnu
zavisnost atributa od bilo kog drugog neključnog atributa u tabeli. 26. Šta predstavlja BASE svojstvo?
BASE svojstvo u NoSQL bazama podataka predstavlja alternativni pristup doslednosti podataka u odnosu na tradicionalne SQL baze podataka. Umesto stroge doslednosti koje zastupa ACID model u relacionima sistemima, naglasak je na visokoj dostupnosti i skalabilnosti.
27. Za BASE svojstvo, šta predstavlja komponenta Basically Available?
Ova karakteristika znači da će baza podataka uvek biti dostupna, čak i u prisustvu mrežnih problema, prekida u radu ili drugih smetnji. Umesto potpune doslednosti, baza podataka može pružiti privremene ili delimične odgovore na zahteve korisnika.
28. Za BASE svojstvo, šta predstavlja komponenta Soft state?
Ova karakteristika se odnosi na fleksibilnost i promenljivost stanja podataka u bazi. Podaci mogu prolaziti kroz različite faze, a baza podataka može biti u privremenom ili nestabilnom stanju. Sistem
 može dozvoliti prolazno stanje dok se baza podataka oporavlja ili rekonfiguriše.
29. Za BASE svojstvo, šta predstavlja komponenta Eventually Consistent?
Ova karakteristika ukazuje da će, nakon izvesnog vremenskog perioda, svi podaci u bazi podataka biti usklađeni i postati dosledni. Međutim, u trenutku upisa ili izmene, podaci mogu biti privremeno nesklađeni između replika ili čvorova baze podataka. Doslednost se postiže sinhronizacijom replika podataka tokom vremena.
30. Šta su jezera podataka? Objasniti osnovne principe i karaketristike.
Jezera podataka predstavljaju centralizovana skladišta podataka namenjena za skladištenje, obradu i čuvanje velike količine strukturiranih, polustrukturiranih i nestrukturiranih podataka. Podaci se mogu skladištiti u svojim izvornim formatima i obrađivati nezavisno od formata u kojem se nalaze, a bez ograničenja koje se odnosi na veličinu podataka. Jezera podataka pružaju skalabilnu i bezbednu platformu koja omogućava unošenje bilo kakvih podataka iz bilo kog sistema bilo kojom brzinom. U poređenju sa hijerarhijskom strukturom skladišta podataka, gde se podaci čuvaju u datotekama ili direktorijumima, jezera podataka koriste ravnu arhitekturu i skladište objekata za skladištenje podataka.
31. Objasniti osnovni princip vertikalnog skaliranja.
Vertikalno skaliranje podrazumeva nadogradnju hardverske strukture mašina sa ciljem poboljšanja performasi računarskog sistema. Postiže se ugradnjom bržih procesora, procesora sa više jezgara, proširanjem operativne memorije.
32. Objasniti osnovni princip horizontalnog skaliranja.
Horizontalno skaliranje podrazumeva prebacivanje obrade s jednog na više procesora. Više procesora zajedno može obraditi više podataka, ako rade paralelno.
33. Na koji način rade distribuirani sistemi?
 Distribuirani sistemi predstavljaju sisteme koji se sastoje od više procesora i komuniciraju razmenom poruka preko mreže. Svaka pojedina procesorska jednica, u kontekstu mreže, zove se čvor. Grupa čvorova koji su povezani fizičkim vezama predstavlja rek. Rekovi koji međusobno blisko sarađuju i povezani su vrlo brzim vezama predstavljaju klaster.
34. Šta je računarski klaster?
Računarski klaster se sastoji od više povezanih računara koji rade zajedno (na bliskoj lokaciji) tako da se mogu posmatrati kao jedinstveni sistem. Kod klastera svaki čvor sistema izvršava isti zadatak, kontrolisan i raspoređen od strane softvera. Klasteri se formiraju da bi se unapredile performanse rada

 u odnosu na pojedinačni računar. Rad računarskog klastera se zasniva na obradi procesa paralalno na svakom čvoru, po rasporedu koji definiše softver.
35. Šta je data centar?
Data centar predstavlja lokaciju gde su smešteni računarski sistemi, sistemi za čuvanje i skladištenje podataka i telekomunikaciona oprema. Obezbeđuju kompanijama smeštaj i funkcionisanje njihove IT infrastrukture po prihvatljivim cenama i na prihvatljiv način. Popularno se nazivaju i ,,farme servera’’.
36. Koje su osnovne karakteristike distribuiranih baza podataka?
Distribuirane baze podataka predstavljaju kolekciju više logički povezanih baza podataka raspoređenih na različitim mašinama koje su povezani u računarsku mrežu. Mogu se definisati i kao klasteri koje čine pojedinačne mašine logički povezani putem računarske mreže. U zavisnosti od karakteristika čvora u mreži, distriburane baze se dele na homogene, heterogene i klijent/server baze.
 Distribuirane baze omogućavaju implementaciju principa horizontalno skaliranja u relacionim sistemima, nezavisnost lokacije, hardvera, mreže,operativnog sistema i sistema za upravljanje (DBMS), distribuiranu obradu podataka, distribuirano upravljanje transakcijama, transparentnost transakcija, pristup podacima u slučaju kvara jedne mašine ili pada jednog DBMS sistema.
37. Koji su osnovni modeli distribucije podataka? Replikacija i fragmentacija
38. Šta je replikacija podataka?
Replikacija podataka predstavlja kopiranje istih podataka na više čvorova. Postoje dve vrste replikacije: master – slave i peer- to- peer
39. Opisati princip master - slave replikacije
Kod replikacije master – slave sve zahteve za dodavanjem i ažuriranjem podataka izvršava jedan čvor – master. Ostali čvorovi (slaves), sinhronizuju podatke sa master čvorom i odrađuju zahteve čitanja. Ovakva raspodela posla znatno ubrzava odgovaranje na zahteve čitanja. Čitanje se može ubrzati dodavanjem dodatnih slaves čvorova. čitanjem sa slaves čvorova mogu se dobiti i neažurni podaci, jer treba vremena da se ažuriranje od master čvora propagira na sve slaves čvorove.
40. Koje metode postoje za rešavanje problema neažurnosti podataka u slučaju master – slave replikacije?
Metoda ispravak kod čitanja i metoda odgođenog ispravka.
41. Šta je metoda ispravak kod čitanja?
Metoda koja rešava problem neažurnosti podataka u slučaju master – slave replikacije. Ako se kod čitanja utvrdi da je vrednost podataka zastarela, ažurira se i vraća se nova vrednost. Zastarelost se utvrđuje na osnovu vremenske oznake poslednjeg sprovedenog ažuuriranja. Proces ažuriranja usporava generisanje rezultata, ali zato korisnik dobija tačnu vrednost.
42. Šta je metoda odgođenog ispravka?
 Metoda koja rešava problem neažurnosti podataka u slučaju master – slave replikacije. Ako se kod čitanja utvrdi da je vrednost neažurna, vraća se klijentu kao rezultat, ali se označava kao zastarela. Master čvor će u nekom trenutku ažurirati sve vrednosti označene kao zastarele. Ovakav pristup pruža brz odgovor, ali uz mogućnost pojave neažurnosti podataka. Greška na nekom od slave čvorova neće ugroziti funkcionisanje sistema, a ukoliko dođe do greške u radu trenutnog mastera, bilo koja njegova replika može preuzeti ulogu mastera i sistem nastavlja sa radom.
43. Opisati princip peer -peer replikacije
U peer- to- peer replikaciji svi su čvorovi ravnopravni, što znači da svaki od njih može obraditi bilo koju vrstu zahteva. Time se rešava problem uskog grla kod ažuriranja i dodavanja podataka. Ovakav

 sistem nastavlja sa radom i nakon kvara nekog čvora. Njegova zaduženja se raspoređuju na preostale čvorove i funkcionalnost ostaje neugrožena. Ukoliko je potrebno poboljšati performanse, lako se mogu dodati novi, ravnopravni, čvorovi. Problem konflikta se javlja kada se zapis istovremeno ažurira na više čvorova. Postoji nekoliko metoda za rešavanje ovakvog konflikta, ali svaka od njih dodatno opterećuje sistem.
44. Šta je transakcija?
Transakcija predstavlja niz operacija nad bazom podataka koji odgovara jednoj logičkoj jedinici posla u realnom vremenu.
45. Šta predstavlja ACID model?
ACID model predstavlja princip realizacije i izvršavanja transakcija u relacionim bazama podataka.
46. Šta je atomarnost transakcije?
Atomatnost transakcije podrazumeva obavljanje svih operacija nad bazom podataka u celini. Definišu se dve specifične operacije nad bazom podataka: COMMIT: označava uspešan kraj transakcije kojim
 se potvrđuju sve promene u bazi koje je posmatrana transkacija proizvela; ROLLBACK: označava poništavanje efekta svih prethodnih operacija nad bazom podataka u jednoj transakciji, ako posmatrana transkacija zbog predviđene ili nepredviđene greške može da dovede bazu u nekonzistentno stanje.
47. Šta je konzistentnost transakcije?
Konzistentnost transkacije podrzumeva podrazumeva uspešno izvršavanje svih operacija transakcije ili poništavanje dejstva transakcije do prethodnog konzistentnog stanja baze podataka. Pre početka i posle okončanja transakcije baza podataka mora da zadovolji uslove konzistentnosti. Za vreme obavljanja transakcije konzistentnost baze podataka može da bude narušena.
48. Šta je izolacija transakcije?
Izolacija transakcije predstavlja izolovano izvršavanje pojedinačnih transakcija. Jedna transakcija ne utiče na rad ostalih transakcija koje se “paralelno” izvršavaju nad bazom podataka. Transakcija svoje promene ne čini vidljivim drugim transakcijama pre nego što se završi, odnosno što se potvrde promene. Ova osobina obezbeđuje uslove kojima se omogućava da se svaka transakcija samostalno izvršava nad bazom podataka. Efekti koje izazovu transakcije koje se obavljaju istovremeno moraju biti jednaki efektima njihovog serijskog izvršavanja.
49. Šta je trajnost transakcije?
Trajnost transakcije obezbeđuje da potvrđeni rezultati ili efekti transakcije budu trajni. Kada se transkacija završi njeni efekti ne mogu biti izgubljeni, čak i ako se neposredno po njenom okončanju desi pad sistema.
50. Objasniti CAP teoremu
CAP teorema se zasniva na tvrdnji da u distribuiranom sistemu je nemoguće da istovremeno budu ispunjena sva tri uslova: Konzistentnost, Raspoloživost; Tolerancija na razdvojenost.
51. Šta predstavlja uslov konzistentnosti u CAP teoremi?
Konzistentnost podrazumeva da sve akcije koje se vrše nad bazom podataka, bilo da su uspešno ili
 neuspešno izvršene, ostavljaju bazu podataka u konzistentnom stanju. Svaka operacija čitanja iz baze podataka kao rezultat ima najnoviju verziju podataka.
52. Šta predstavlja uslov raspoloživosti u CAP teoremi?
Raspoloživost podrazumeva prihvatljiv vremenski odziv sistema baza podataka. Svakoj operaciji čitanja je dostupna bar jedna kopija traženog podatka bez obzira na celokupnu funkcionalnost sistema. Dostupnost se povećava replikacijom i povećanjem broja serverskih sistema.

 53. Šta predstavlja uslov tolerancije na raspoloživost u CAP teoremi?
Tolerancija na razdvojenost podrzumeva funkcionisanje sistema bez obzira na skup otkaza. Nijedan skup otkaza, osim potpunog otkazivanja, ne sme da proizvede neispravan odziv sistema baze podataka (u slučaju delimičnog otkaza sistem nastavlja da radi kao da do otkaza nije ni došlo).
54. Šta obezbeđuju CA uslovi zasnovani na CAP teoremi?
CA uslovi obezbeđuju konzistentnost i raspoloživost, ali nema tolerancije na razdvojenost. Podaci moraju biti konzistentni za sve čvorove i u svakom trenutku moraju biti raspoloživi za izvršenje neke operacije, ali ne prihvataju particionisanje čvorova. Realizacija ovih uslova je moguća u slučaju kada je kompletan sistem na jednom računaru ili kada je realizovano višestruko umrežavanje primenom redudantne veze. Sistemi koji su zasnovani na ispunjenosti CA uslova su: RDBM, PostgreSQL, Greenplum
55. Šta obezbeđuju CP uslovi zasnovani na CAP teoremi?
CP uslovi obezbeđuju konzistentnost i toleranciju na razdvojenost, ali se ne garantuje vreme odziva. Podaci moraju biti konzistentni za sve čvorove i ukoliko dođe do particionisanja čvorova, čvor koji je
 i dalje dostupan odbija da primi zahtev da ne bi došlo do narušavanja konzistentnosti. Realizacija je moguća u slučaju uspostavljanja niže sprege između čvorova. Primeri sistema koji su zasnovani na ispunjenosti CP uslova: BigTable, Hypertable, Hbase, MongoDB...
56. Šta obezbeđuju AP uslovi zasnovani na CAP teoremi?
AP uslovi obezbeđuju raspoloživost i tolerancije na razdvojenost, ali se ne ne garantuje čitanje poslednje verzije podataka (konzistentsnost). Čvorovi ostaju dostupni i kada ne mogu da komuniciraju međusobno, a tada će podaci biti sinhronizovani samo onda kada je particionisanje eliminisano. U tom slučaju nije sigurno da će svi čvorovi imati iste podatke.Primeri sistema koji su zasnovani na ispunjenosti AP uslova: Dynamo, Voldemort, Cassandra ...
57. Koje su karekteristike nerelacionih baza podataka?
Ekonomičnost, fleksibilnost, lake za održavanje, otvorenog koda, podržavaju horizontalno skaliranje i distribuiranu obradu podataka, ne insistiraju na integritetu podataka, skladište veliku količinu heterogenih podataka, ne postoji standardni upitni jezik, nemaju uanpred definisanu šemu modela podataka, imaju brz odziv.
58. Kako su organizovane document orjentisane baze podataka?
Dokumenti su organizovani u kolekcije koje se mogu posmatrati kao tabele u relacionim bazama
podataka. Za svaku kolekciju definiše se tip dokumenata koje čuva. Velika prednost kolekcija je što nemaju definisanu šemu, svaki dokument, čak i unutar iste kolekcije, može imati proizvoljnu strukturu. Dokumenti unutar jedne kolekcije mogu sadržavati druge dokumente primenom ugnježdavanja objekata. Ugnježdenje omogućava čuvanje povezanih podataka u okviru jednog dokumenta odnosno njihovo zajedničko skladištenje u memoriji. Prednost ovog pristupa se ogleda u brzini pristupa i eliminiše se potreba za operacijama spajanja upita kroz više kolekcija.
59. Šta je model referenciranja dokumenata?
Model referenciranja dokumenata predstavlja normalizovani model podataka i zasnovan je na vezi 1:M koja se u sistemu relacionih baza podataka relaizuje preko stranog ključa. Povezivanje dokumenata, veze između podataka, se ostvaruju uključivanjem referenci iz jednog dokumenta u
 drugi. Primenjuje u slučaju kada ugnježdenje dokumenata rezultuje pojavu velike količine dupliciranih podataka; treba realizovati tip veze M:N; potrebno izvršiti modelovanje velikih hijerarhijskih skupova podataka.
60. Šta je model podataka zasnovan na ugnježdenim dokumentima? Model podataka zasnovan na ugnježdenim dokumentima se smatra denormalizovanim modelom podataka. Koristi se kada je potrebno struktuirati podatke tako da se na jednom mestu nalaze svi podaci koji se odnosi na jedan koncept posmatranja i modelovanja. Ugrađivanje povezanih podataka u jedan dokument smanjuje broj pristupa bazi i ubrzava operacije čitanja. Izbegava se spajanje više kolekcija i dobija brži odziv sistema kao i brže ažuriranja podataka sa jednim upitom. Mana ovog modela je kreiranje velikih

 dokumenti čija veličina može da dostigne i maksimalne vrednosti koje zavise od sistema (za
MongoDB maksimalana veličina dokumenta je 16 MB) .
61. Šta predstavljaju kante u ključ-vrednost bazama podataka?
Kante predstavljaju grupisane parove ključ – vrednost. Omogućavaju da logički povezani podaci budu fizički grupisani zajedno. Kreiranjem nove kante dodeljuje se jedinstveno ime. Ključevi moraju biti jedinstveni samo unutar kante u kojoj se nalaze. Kante se mogu logički grupisati po tipovima.
62. Navesti karakteristike ključ- vrednost baza podataka.
Jednostavnost ( minimalna struktura podataka, jednostavan model); Skalabilnost; Master – slave
replikacija; Brzina odziva
63. Koje su osnovne operacije u ključ- vrednost bazama podataka?
PUT (key, value); GET (key) ; DELETE (key)
64. Navesti najznačajnije sisteme baza podataka zasnovane na ključ-vrednost modelu. DynamoDB , Riak, Redis
