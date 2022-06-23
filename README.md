# ni-apricot
## Uvod
Projekat za kurs Naucno izracunavanje http://ni.matf.bg.ac.rs/ 2021/2022 godine.
Tema projekta je upoznavanje sa paketom Apricot (https://github.com/jmschrei/apricot) kroz primere.

Apricot paket pruza nacin da se iz (potencijalno velikog) skupa podataka uzme njegov reprezentativni podskup, koristeci tehnike submodularne optimizacije.
Primena je mnogostruka: na primer, za vizualizaciju i razumevanje podataka, kao i za generisanje skupa podataka za treniranje modela u masinskom ucenju (kada  zbog velicine skupa podataka nije moguce trenirati model u realnom vremenu, ili je to skupo).
Detaljniji opis funkcionalnosti paketa se nalazi u svesci main.ipynb , a dodatni primeri upotrebe paketa u direktorijumu ./examples.

## Potrebni paketi
Jupyter sveska 00_hello_apricot sadrzi informacije o potrebnim paketima za funkcionisanje apricot bibiloteke i kako ih instalirati.
Potrebni paketi su:
1. numpy
2. scipy
3. numba
4. tqdm
5. sklearn
6. nltk
7. apricot-select

## Korisni linkovi
1. Detaljna zvanicna dokumentacija je dostupna na adresi https://apricot-select.readthedocs.io/en/latest/index.html
