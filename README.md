# Izveštaj o neformalnom pregledu koda i statičkoj analizi

**Ukupan LOC za kompletan projekat:** 72 linije koda

### Zapžanja i pronađeni propusti (Code Smell):

* Calculator.java – linija 37 – Metoda za deljenje ne sadrži proveru deljenja nulom.
* Calculator.java – linije 11, 19, 27, 35 – Nazivi metoda 'Sabiranje', 'Oduzimanje', 'Mnozenje' i 'Deljenje' počinju velikim slovom. 
* Start.java – linija 14 – Kôd koristi fiksne magične brojeve umesto da koristi imenovane konstante ili promenljive unete od strane korisnika.
