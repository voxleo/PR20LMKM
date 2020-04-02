# Tehnčini pregledi motornih vozil v Sloveniji 2019

## Skupina
* Leon Macur - 63180190
* Kevin Mohar - 63180209

## Podatki in analiza
### Opis
Za projetkno nalogo sva se odločila analizirati podatke o tehnčinih pregledih motornih vozil, ki so potekali v Sloveniji leta 2019. Z uporabo metod podatkovnega rudarjenja želiva ugotoviti, kako so se opravljeni pregledi čez leto razlikovali. Predvsem naju zanima, katere znamke, starost motornega vozila, gorivo, prevoženi kilometri in ostale specifikacije vpilavajo na uspešnost opravljenega tehničnega pregleda.

### Podatki
Podatke sva pridobila iz strani "OPSI: odprti podatki" -> [rezultati tehničnega pregleda](https://podatki.gov.si/dataset/rezultati-tehnicnih-pregledov-motornih-vozil). Natančneje bova podatke črpala iz tekstovne datoteke "Uspešnost TP 2019". Datoteka ima 25 atributov in vsebuje podatke o vozilu, regestraciji, lastniku ter rezultate o nepravilnostih, obremenitvah in ugotovitvah pregleda vozil v Sloveniji za leto 2019.

### Analiza
#### Problem 1:
Pri tej nalogi sva želela ugotovite katera znamka vozil je najmanj zanesljiva pri opravljanju tehničnega pregleda, pri vozilih ki so bila prvič registrirana vsaj 25 let nazaj. To sva storila tako da sva najprej poiskala znamke vozil ki so imele vsaj 1000 zapisov v tabeli. Nato sva za vsako posamezno znamko izračunala verjetnost uspeha pri opravljanju tehničnega pregleda. Na koncu 10 znamk z najmanjšo verjetnostjo uspeha ter jih prikazala z ustrezno vizualizacijo.

![Graf1](slike/graf1.png)



#### Problem 2:
Pri tej nalogi sva želela ugotoviti v kateri enoti je opravljanje tehničnega pregleda najuspešnejše. To sva storila tako da sva za vsako posamezno enoto, v kateri je vsaj 100 vozil opravljalo tehnični pregled, preštela število vozil, ki so tam uspešno opravila tehnični pregled in ga delila s številom vseh vozil, ki so tam opravila tehnični pregled. Tako sva za vsako enoto dobila verjetnost uspešno opravljenega tehničnega pregleda v teh enoti. Iz dobljenih rezultatov sva izbrala 3 najbolj uspešne enote in 3 najmanj, ter jih ustrezno vizualizirala.

![Graf2](slike/graf2.png)

Kot lahko razvidimo iz grafa imajo najboljše 3 enote praktično enako verjetnost opravljenega tehničnega pregleda. Pravtako so te verjetnosti zelo visoke. Pri najslabših treh pa lahko opazimo večjo razliko med verjetnostmi. Opravljanje tehničnega pregleda v katerikoli enoti razen najslabši, bi imelo zelo visoko verjetnost uspeha.


#### Problem 3:
Pri tem problemu naju je zanimalo kako se spreminja uspešnost opravljenega pregleda skozi leto glede na tip goriva. Podatke sva najprej razdelila po mesecih, nato pa za vsak mesec podatke razdelila na 2 skupini. V eni skupini so bila tista vozila ki uporabljajo bencin, v drugi pa tista ki uporabljajo dizel. Za vsako od teh skupin sva za pripadajoč mesec nato izračunala verjetnost uspešnega opravljanja tehničnega pregleda. Podatke sva nato prikazal z ustrezno vizalizacijo.

![Graf3](slike/graf3)

Iz grafa lahko razberemo da imajo vozila z dizelskim motorjem večjo verjetnost da opravijo tehnični pregled. Ugotovila sva tudi da je najboljši čas za opravljanje pregleda z vozilom na dizelski pogon spomladi, za vozila z bencinskim pogono pa v začetku poletja. Najslabši čas za oba pa je pozimi.
## Ugotovitve
