# Projektne faze
- [x] - Opis projekta
- [x] - Početna struktura aplikacije
- [x] - Prototip
- [x] - Konzultacije
- [x] - Finalna verzija
- [ ] - Obrana projekta

## Opis projekta
Potrebno je napisati kratki opis projekta.
Opis mora sadržavati popis funkcionalnosti koje će biti implementirane (npr. "prijava korisnika", "unos novih poruka", "pretraživanje poruka po autoru" itd...)
Napraviti ću aplikaciju za praćenje osobnih prihoda i rashoda. Kroz aplikaciju će se moći ...

## Početna struktura aplikacije
Potrebno je inicijalizirati početnu strukturu backend i frontend aplikacija.
Aplikacije moraju biti u odvojenim mapama koje su već inicijalizirane.
Ukoliko radite aplikaciju sa statičkim frontend sadržajem, onda u mapi mora biti izvorni kôd aplikacije

## Prototip
U ovoj fazi bi trebali imati "grubu" verziju svoje aplikacije. Ova verzija bi trebala imati implementirane osnovne funkcionalnosti koje su navedene u opisu projekta. Ne očekuje se da su implementirane SVE funkcionalnosti niti da su postojeće funkcionalnosti potpuno ispravne.

## Konzultacije
Nakon izrade prototipa potrebno se javiti nastavniku za termin konzultacija. Na konzultacijama ćete ukratko pokazati svoj prototip te će se po potrebi napraviti modifikacija početnih zahtjeva. Dovršeni projekti bez ove faze neće biti prihvaćeni.

## Finalna verzija
Nakon demonstracije prototipa možete nastaviti sa razvojem aplikacije i implementacijom svih funkcionalnosti. Prilikom razvoja potrebno je voditi dnevnik aktivnosti prema zadanim uputama.

## Obrana projekta
Zadnja faza je obrana projekta - nakon završetka finalne verzije svoje aplikacije javite se nastavniku za dogovor oko termina obrane projekta.

# Opis projekta
## Kratki opis
Napravit ću aplikaciju kojom možemo pratiti evente (događaje). Korisnik može kreirati svoj korisnički račun, a nakon toga i prijaviti preko svog korisničkog računa. Postoje 2 vrste prijave, jedna za „admina“, dok druga za običnog korisnika (u nastavku samo označen kao korisnik). Dok korisnik koji uopće nije prijavljen može samo vidjeti listu eventa, onaj korisnik koji je prijavljen može kreirati novi event kojemu, osim informacija o eventu, može odrediti je li event otvorenog tipa (može doći tko hoće) ili zatvorenog (potrebno je dopuštenje). Korisnik, osim dodavanja, može uređivati i brisati svoje evente. Prijavljeni korisnik može vidjeti svoju listu eventa (prošlih i nadolazećih), listu eventa na određenom mjestu i listu eventa na koje se prijavio te je li prijava odobrena. Opću listu eventa moguće je filtrirati po mjestu gdje se održavaju. Administrator može vidjeti cijelu listu korisničkih računa i eventa te ih po potrebi brisati. Kako prilikom registracije ne možemo birati ulogu, nego je automatski dodijeljena uloga korisnika, administrator može kreirati novi korisnički račun ili promijeniti ulogu nekog postojećeg u sustavu.
## Tehnologije
1. Frontend - React
2. Backend - Express
3. Baza - Mongo
## Popis funkcionalnosti
1. dodavanje, brisanje i uređivanje korisničkih računa
2. dodavanje, brisanje i uređivanje eventa
3. autentifikacija i autorizacija korisnika
4. filtriranje eventa
