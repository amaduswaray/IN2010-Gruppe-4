# Uke 5 - Grafer: Hva grafer er, hvordan de representeres, hvordan traversere de, hvordan de kan ordnes.

Denne uka gikk vi gjennom litt basoics om grafer. Se mer på ukas [slides]

### Algorithms of the week
Ukas algoritmer handler primært om å traversere grafer!
* Dybde først søk
* Bredde først søk
* Topologisk sortering


NB: Veldig viktig at du forstår hvordan algoritmene fungerer! Hvis du er etter en utfordring, så andbefaler jeg å forstå ukens algoritmer intuitivt, og deretter implementere det, uten bruk av pseudokoden!


# Ukes og Gruppe Oppgaver:

**Implementer Algoritmene fra forelesninger**

### Gruppeopppgaver for grafer:

4 Typer grafer(eksamen 2020)
Side 14 og hedover

https://www.uio.no/studier/emner/matnat/ifi/IN2010/h21/eksamens-ressurser/in2010-h2020-eksamen.pdf

#### Eulerkrets
En Eulerkrets i en graf G er en vei som starter og slutter i samme node og er innom alle kantene i G nøyaktig en gang. Lag en algoritme som finner ut om G inneholder en Eulerkrets. Output skal være true/false. Kjører algoritmen i polynomiell tid? Begrunn svaret. Hint: Det finnes en egenskap som har med graden til nodene i G å gjøre, som nøyaktig bestemmer om G har en Eulerkrets eller ikke.


#### Hamiltonsykel
En Hamiltonsykel i en en graf G er en sykel som inneholder hver node nøyaktig en gang. Lag en algoritme som løser Hamiltonsykel. Output skal være true/false. Hint: Enn så lenge har ingen klart å finne en algoritme som løser dette problemet i polynomiell tid, så ikke ta det så tungt om også din algoritme bruker eksponensiell tid.





#### Prøv deg på Kattis!

* Grafer!(DFS/BFS)
    * [weak vertices](https://open.kattis.com/problems/weakvertices)
    * [horror](https://open.kattis.com/problems/horror)
    * [torn to pieces](https://open.kattis.com/problems/torn2pieces)
    
* Topologisk Sorering
  * [pick up sticks](https://open.kattis.com/problems/pickupsticks)
  * [build dependencies](https://open.kattis.com/problems/builddeps) - Ganske krevende
