# Evidencija aktivnosti

## 23.06.2022.
Pocetak | Kraj
------- | ----
19:00   | 00:05
### Kratki opis promjena
Dodana početna struktura aplikacije i početni razmještaj, spoj na bazu, model za event, kontroler za event (get-svih, get-jednog, post, put i delete), dodani testovi za prethodno navedene rute, napravljen rest requests na postojeće stanje na evente i dodan model za korisnika, dodan kontroler za korisnika (post metoda), rest request za tu metodu i odgovarajući test. 

## 24.06.2022.
Pocetak | Kraj
------- | ----
12:45   | 16:00
### Kratki opis promjena
Dodani get (svih), get (jednog), put i delete u kontroler za korisnika, testirani i napravljeni rest requests, dodan login na backend, middleware za JsonWebTokenError te testovi za login, izmijenjen get u kontroleru za korisnike (zahtjeva se token) te pripadajući testovi

Pocetak | Kraj
------- | ----
18:45   | 23:50
### Kratki opis promjena
Izmijenjene rute za get jednog, put i delete u kontroleru za korisnika te napravljeni pripadajući testovi, izmijenjene rute get, post, put i delete u kontroleru za evente, izmijenjeni pripadajući testovi te dodani testovi koji za put i delete bez pripadajućeg tokena vraćaju da je nemoguća izmjena. Dodani servisi na frontendu za evente, korisnike i login. Dodani login, forma za login i forma za registraciju u components te dodano rutiranje u app.js s rutom prema login. Dodana komponenta za ispis svih dogadaja(eventa) i putanja do nje u app.js

## 25.06.2022.
Pocetak | Kraj
------- | ----
11:50   | 16:00
### Kratki opis promjena
Dodana komponenta za ispis svih korisnika i putanja do nje u app.js. Dodane forme za uređivanje i kreiranje eventa. Dodan logout, ograničen pregled korisnika. Dodane rute za prijavu korisnika na event, brisanje te iste prijave te uređivanje dopuštenja korisniku na event.

Pocetak | Kraj
------- | ----
18:20   | 00:35
### Kratki opis promjena
Dodan kontroler za prijave u kojeg je premješteno prijava korisnika na event, brisanje i dopuštanje korisnika na event. Dodano dohvaćanje (get) svih eventa gdje je korisnik prijavljen, svih prijava na jedan event, jedne prijave korisnika u određenom eventu te pripadajući testovi. Dodano postavljanje ocjene prijavljenog korisnika na event, brisanje svih eventa jednog korisnika te brisanje svih prijava na evente jednog korisnika uz pripadajuće testove. Prilikom brisanja eventa, dodano i brisanje reference kod korisnika na event. Dodan servis za prijave i u servisu za evente dodane metode koje su nedostajale. Dodana komponenta za prikaz eventa čiji je vlasnik prijavljeni korisnik. Dodana komponenta koja sadržava pomoćne funkcije koje se pojavljuju u više komponenti.

## 26.06.2022.
Pocetak | Kraj
------- | ----
13:00   | 16:10
### Kratki opis promjena
Dodana mogućnost prijave i odjave s eventa na frontendu kod prijavljenog korisnika, brisanje eventa kad je prijavljen vlasnik eventa, ispravljene greške u servisu za prijave te u pomocnoj komponenti dodane provjere za vrstu prijave korisnika.

Pocetak | Kraj
------- | ----
18:30   | 00:15
### Kratki opis promjena
Dodana metoda za promjenu uloge korisnika na backend i odgovarajući test. Dodana jedna više razina od admina, dodana mogućnost ocjenjivanja, dodana mogućnost pregleda prijavljenih na event te dopuštanje na event korisniku od strane vlasnika eventa, dodane mojePrijave na kojima možemo vidjeti evente na koje smo prijavljeni, popravljene greške koje su se pojavljivale u prijašnjim dodavanjima.

## 27.06.2022.
Pocetak | Kraj
------- | ----
13:15   | 15:10
### Kratki opis promjena
Napravljen razmještaj frontenda, dodana biblioteka react-bootstrap i bootstrap ikone, dodana navigacijska traka, dodan izgled početne stranice, dodan css, djelomično primjenjen.

Pocetak | Kraj
------- | ----
17:50   | 00:40
### Kratki opis promjena
Primjenjeno uređenje te dodan profil. Dodani detalji o korisniku s ispisom svih njegovih eventa prilikom pregleda korisnika od strane admina. Detalji o eventima nadograđeni samim ispisom o eventu te postavljeni da su dostupni na više elemenata. Kod sređen.

## 28.06.2022.
Pocetak | Kraj
------- | ----
18:25   | 01:32
### Kratki opis promjena
Dodani frontend testovi za dogadaj.js, formFields.js, testovi u gotovDogadaj.js, korisnik.js, ocjena.js, pomocne.js, formEvent.js, korisnik.js, loginForm.js, prijave.js, registerForm.js 

## 29.06.2022.
Pocetak | Kraj
------- | ----
11:50   | 01:15
### Kratki opis promjena
Dodani frontend testovi za kreirajEvent.js, detalji.js, detaljiKorisnik.js, dogadaji.js, korisnici.js, login.js, mojePrijave.js, mojiEventi.js, render pocetna.js, i profil.js te ispravljeni bugovi. Dodan cypress i E2E test koji simulira otvaranje početne stranice, pronalazak i pregled detalja nekog eventa, promjenu uloge korisnika od strane masteradmina te registraciju korisnika.