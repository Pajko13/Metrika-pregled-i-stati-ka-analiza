# Metrika-pregled-i-stati-ka-analiza

Lines of Code (LOC):
Ukupan broj linija koda za ceo projekat: 106 linija.

Ciklomatska i kognitivna složenost fajl Calculator.java:

Ciklomatska složenost: 9
Kognitivna složenost: 8

Izveštaj o statičkoj analizi Fajl Calculator.java:

Linija 18: Metoda ToString bi trebalo da bude toString u skladu s konvencijom nazivanja metoda.
Linija 31: Nepotrebno dodavanje praznog stringa u metodi ToString. Može se koristiti String.valueOf umesto konkatenacije.
Linija 47: Nepotrebna upotreba catch bloka ako se hvata bilo kakav Exception. Preporučuje se hvatanje specifičnih izuzetaka.
Linije 79-155: Metoda Calculate ima visoku ciklomatsku složenost i sadrži dosta ponavljanja koda. Ovo može dovesti do poteškoća u održavanju i razumevanju koda.

Start.java:nema zapažanja

Zaključak:
Projekat ima relativno nisku složenost i sadrži osnovnu funkcionalnost kalkulatora. Međutim, postoje neke prakse koje bi se mogle poboljšati radi bolje čitljivosti i održavanja koda. Takođe, Calculate metoda u Calculator.java fajlu je složena i sadrži ponavljanja koda, što bi se moglo optimizovati radi bolje strukture i performansi.

Lines of Code (LOC):
Ukupan broj linija koda za fajl Start.java: 15 linija.

Ciklomatska i kognitivna složenost fajl Start.java:

Ciklomatska složenost: 2
Kognitivna složenost: 2

Izveštaj o statičkoj analizi Start.java:nema zapažanja

Zaključak:
Fajl Start.java sadrži osnovnu funkcionalnost za pokretanje kalkulatora. Nema primetnih nedoslednosti ili propusta, a složenost je relativno niska.











