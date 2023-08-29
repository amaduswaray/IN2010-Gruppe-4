# Uke 4 - Sortering: Bubble, Selection, Insertion og Heap

Denne uka gikk vi gjennom de ulike trestrukturene, og hadde gjennomgang av rotasjoner Gjerne gå ukas [slides](https://github.com/amaduswaray/IN2010-Gruppe-5/blob/main/Uke%2004/IN2010%20Uke%204.pdf)

### Algorithms of the week
Ukas algoritmer handler primært om å implementere de ulike algoritmene!:
* Bubble Sort
* Selection Sort
* Insertion Sort
* Heap Sort


NB: Veldig viktig at du forstår hvordan algoritmene fungerer! Hvis du er etter en utfordring, så andbefaler jeg å forstå ukens algoritmer intuitivt, og deretter implementere det, uten bruk av pseudokoden!

Du kan vinne visualiseringer a de ulike algoritmene [her](https://visualgo.net/en/sorting)


#### Viktige Datastrukturer
* Max Heap
  * Her gjelder det å vite hvordan man bygger et maks heap!



## Oblig 1 Tips og tricks
I år har det blitt et fokus å gjøre obligene slik at programmene tar bruk i stdin og stdout
For å komme i gang jeg laget et enkelt skellett for et binært søketre [her](https://github.com/amaduswaray/IN2010-Gruppe-5/blob/main/Uke%2002/Kode/bs_skellet.py)
Filen inneholder også tips og triks på hvordan man kan bruke stdin, stdout og teste løsningen sin på kattis!

*NB! Husk at fristen er denne fredagen!*

# Ukes og Gruppe Oppgaver:

### Gruppeopppgaver for sortering:
Prøv deg på disse oppgavene!

For hver av påstandene nedenfor kan du anta at A er et array med n elementer, og at i er et heltall 0 ≤ i < n. 

Ta utgangspunkt i Bubble, Selection og Insertion sort:

(a) Etter x iterasjoner av den ytre loopen i ###### sort, er de x første elementene sortert.

(b) Etter x iterasjoner av den ytre loopen i ###### sort, er de x siste elementene sortert.

(c) ###### sort bytter kun elementer som står direkte ved siden av hverandre.

(d) ###### sort garanterer et minimalt antall bytter.

### Binære Heaps

For binære heaps anbefales det å implementere algoritmene fra timen! Om du ser etter en større utfordring så er det mange kattis oppgaver som tar bruk i prioritetskøer!


### Kjøretidsanalyse

Her limer jeg inn mine life hacks fra [Uke 1](https://github.com/amaduswaray/IN2010-Gruppe-5/tree/main/Uke%2001)

#### O-Notasjon(Big O)

Q: Hvor mange steg trenger man for å løse en algoritme? In worst case.

#### *Lifehack regler*
* Når det er ledd mellom plusstegn, så kan man ta hensyn til det leddet som vokser raskest:
  * Eksempel: O(n^3 + n^2 + n) = O(n^3) fordi n^3 vokser raskest når n øker :)
 

* Konstanter og koffesienter kan man se bort ifra, eller redusere ned til 1
  * Eksempel 1: O(50n) = O(1n) = O(n)
  * Eksempel 2: O(1000) = O(1)

* Variabler kan ganges sammen for å gjøre det enklere å se hva som vokser raskest
  * Eksempel: O( (n+15)*(n+20) ) = O(n^2 + 20n + 15n + 15*20) = O(n^2) ettersom at n^2 vokser raskest
  * Dette eksempelet kan også løses ved å se bort fra konstantene, ettersom at n vokser raskest i begge parantesene. Da ser løsningen slik ut:
    * O( (n+15) * (n+20) )= O(n * n) = O(n^2)


#### *Formulering*
* Konstant tid = O(1)
* Lineær tid = O(n)
* Logaritmisk tid = O(log(n))
* Lineærlogaritmisk tid = O(nlog(n))
* Kvadratisk tid = O(n^2)

Når man jobber flere inputs og inputsstørrelser som er uavhengig av hverandre, så får man flere variabler som m og n. Da kan man representere kjøretidskompleksiteten med hensyn til disse variablene
* Eskempel: O(m + n) og O(m * n)
* OBS! På oppgaver vil man ofte oppgi svar men kun én variabel, så ved bruk av Lifehack reglene så kan man komme i mål ;)





#### Prøv deg på Kattis!

* Denne uken kan det være fint å starte med dissse:
    * [height](https://open.kattis.com/problems/height)
    * [mjehuric](https://open.kattis.com/problems/mjehuric)
    * [sortofsorting](https://open.kattis.com/problems/sortofsorting)
    
* Deretter er dissse fine:
  * [DVDs](https://open.kattis.com/problems/dvds)
  * [DA-sort](https://open.kattis.com/problems/dasort)
  * [classy](https://open.kattis.com/problems/classy)
  * [Ultra-Quicksort](https://open.kattis.com/problems/ultraquicksort) - Vanskelig!
