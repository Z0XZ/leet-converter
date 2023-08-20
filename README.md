# 1337-programmet  

Du skal nå skrive et program som tar en tekst som input og lager om teksten til 1337-tekst. Et eksempel på hvordan programmet kan fungere ser du under:

![Alt Text](assets/1337-program.gif)

  ## 1. Input
Lag deg en variabel som skal ta en input fra brukeren. Variabelen skal ha et fornuftig navn, f.eks.:
```python
original_tekst = input("Tekst som skal oversettes:\n")
```
<p style="font-size:12px">I eksempelet over ser du at teksten inne i input slutter med \n. Dette betyr det samme som å trykke enter på tastaturet (altså å lage en ny linje). Dette betyr at brukeren som skal skrive inn en tekst skriver inn denne i linjen under.</p>

## 2. Replace
Du skal nå erstatte den originale teksten med andre tegn for å oversette den originale teksten til 1337-tekst. Dette kan vi enkelt gjøre ved å bytte ut bestemte bokstaver med tall.

Først lager vi en ny variabel hvor vi henter inputen fra brukeren:
```Python
oversatt_tekst = original_tekst
```
Deretter erstatter vi ulike tegn med .replace-metoden:
```Python
oversatt_tekst = oversatt_tekst.replace("t", "7")
```
I eksempelet over byttes alle t-ene ut med 7-tall. Teksten "tall" ville altså blitt til "7all". For å sjekke at teksten faktisk har blitt byttet ut kan man bruke print-funksjonen til å skrive ut verdien til variabelen.

Du skal nå fortsette med å bruke .replace-metoden slik at du fåt byttet ut alle bokstavene som skal byttes ut. En oversikt over bokstavene som skal byttes ut med tall finner du i tabellen under:

|Originalsymbol |1337-symbol |
|:---:|:---:|
|a|4|
|b|8|
|e|3|
|l|1|
|o|0|
|s|5|
|t|7|

## 3. Printing
Når du har laget et program som konverterer alle symbolene i tabellen over til 1337-symboler skal programmet skrive ut den nye teksten. Prøv å bruke f-strenger slik at programmet forklarer hva som kommer ut, f.eks. "1337-tekst:" slik som i eksempelprogrammet under.
![Alt Text](assets/1337-program.gif)

Sjekk at programmet stemmer med noen eksempeltekster. Ordet "tall" skal eksempelvis bli oversatt til "7411", og "LEET" bli til "1337".

Oversetter programmet også de store bokstavene?

Når du er fornøyd med programmet kjører du testene i menyen til venstre og ser om programmet er godkjent. Om du ikke får godkjent på testen, forsøk å rette opp i programmet slik at det blir riktig.

For å kjøre en test kan du navigere deg hit i menyen:
![Alt Text](assets/Tests.png)
