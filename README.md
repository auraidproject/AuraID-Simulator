Evo kompletnog, uređenog teksta za tvoj README.md. Sada sadrži tvoje ime i službeni email, što projektu daje puni legitimitet.

Samo kopiraj sve ispod ove linije:

AuraID: Digitalna Aura za hiper-lokalno povezivanje

"Vaš mobitel zna što trebate. Vaša okolina ima što tražite. AuraID ih spaja."

🌟 Vizija

AuraID je konceptualni sustav "pasivne telepatije" koji rješava problem propuštenih prilika u neposrednoj blizini (do 50 metara). Dok klasične društvene mreže fokusiraju vašu pažnju na globalnu razinu, AuraID vam omogućuje da "osjetite" digitalnu auru informacija ljudi i objekata koji se nalaze neposredno pored vas — u kafiću, tramvaju, studentskoj menzi ili trgovini.

🚀 Problem koji rješavamo

Svaki dan se mimoilazimo s ljudima koji nude upravo ono što nam treba (posao, uslugu, informaciju ili socijalni kontakt), ali toga nismo svjesni jer nemamo način za pasivnu razmjenu tih informacija bez narušavanja privatnosti. AuraID premošćuje taj jaz bez potrebe za aktivnim pretraživanjem.

🛠 Tehnički stupovi sustava

AuraID nije samo još jedna aplikacija; to je optimizirani komunikacijski protokol dizajniran za rad u pozadini:

Hex-Hash Handshake (BLE): Sustav koristi Bluetooth Low Energy za emitiranje ultra-kratkih heksadecimalnih kodova. Umjesto slanja cijelih profila, uređaji razmjenjuju samo ID i Smart Hash (vrsta ponude/potražnje + kontrolni zbroj). To osigurava minimalnu potrošnju baterije i maksimalnu brzinu obrade.

Acoustic ToF Radar (Ultrazvuk): Za razliku od nepreciznog Bluetootha, AuraID koristi nečujne ultrazvučne signale (Time-of-Flight) za mjerenje udaljenosti u centimetrima, omogućujući korisniku iskustvo "digitalnog detektora metala" pri lociranju prilike.

Privacy-First: Podaci se uspoređuju lokalno na uređaju. Sustav ne zahtijeva centralno praćenje lokacije korisnika, čime se štiti anonimnost do trenutka obostranog pristanka (Match).

📱 Primjeri upotrebe

Studentski domovi i menze: Pronalaženje skripti, instrukcija ili partnera za učenje u krugu od 20 metara tijekom ručka.

Hiper-lokalni marketing: Trgovina u kojoj se nalazite vas obavještava da imaju točno onaj artikl koji ste upisali na listu želja prije tri dana.

Networking: Diskretno povezivanje stručnjaka na konferencijama ili u velikim poslovnim zgradama.

Socijalizacija: "Digitalni ledolomac" za upoznavanje ljudi sličnih interesa u istom fizičkom prostoru.

📊 Trenutni status: Proof of Concept (PoC)

Ovaj repozitorij sadrži AuraID Simulator, web-bazirani prototip koji koristi Google Sheets kao "virtualni eter" za simulaciju BLE komunikacije i logike uparivanja.

Frontend: HTML5 / JavaScript (GitHub Pages)

Backend: Google Apps Script (Simulacija logike procesora mobitela)

Database: Google Sheets (Simulacija lokalne log liste uređaja)

👤 Autor

Darko Banović
Idejni začetnik i autor koncepta AuraID.
📧 Kontakt: auraid.project@gmail.com

🔒 Licenca i prava

© 2026 Darko Banović / AuraID Project. Sva prava pridržana.
Ovaj projekt je intelektualno vlasništvo autora. Trenutno je u fazi razvoja prototipa. Svako neovlašteno kopiranje koda ili metodologije (posebno Hex-Hash protokola i Acoustic ToF metode mjerenja udaljenosti) podliježe zaštiti autorskih prava.

