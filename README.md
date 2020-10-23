# input/output
De `input()` en output (`print()`) functies zorgen 
voor communicatie tussen de computer en de gebruiker.


## input
De `input()` functie wordt als volgt gebruikt:
```python
input('Wat is je naam? ')
```

Als je dit script uitvoert krijg je dit te zien:
```Markdown
Wat is je naam? 
```

>TIP: zorg dat er op het einde van je vraag een spatie staat.
Dit zorgt ervoor dat er ruimte is tussen je vraag en je antwoord.

Je kan ook je antwoorden opslaan in een variabel. Hierdoor kan je ze later terug gebruiken.
```python
antwoord1 = input('Wat is je naam? ')
```

Wanneer je een getal wilt vragen, moet je de `int()`functie gebruiken als volgt:
```python
antwoord2 = int(input('Wat is je leeftijd?'))
```

## output
De `print()` functie wordt als volgt gebruikt:
```python
print('Hallo')
```

Als je dit script uitvoert krijg je dit te zien:
```Markdown
Hallo
```

Je kan ook variabelen printen:
```python
tekst = 'Hallo'
print(tekst)
```
```Markdown
Hallo
```
Wanneer je meerdere dingen wilt printen op 1 regel, kan je gebruik maken van 2 methodes

- Methode 1: een `+` tussen elk apart element
```python
tekst =  'Hallo'
print(text + ' wereld')
```
```Markdown
Hallo wereld
```
- Methode 2: een `,` tussen elk apart element
```python
print(text , ' world')
```
```Markdown
Hallo wereld
```

## input-output
Om de computer te laten comunniseren met de gebruiker heb je zowel een `input()` als een `print()` functie nodig.
De code zit als volgt in elkaar:
```python
antwoord = input('Wat is je naam? ')
print('Hallo ', antwoord)
```
De gebruiker kan nu een antwoord ingeven waarop wordt geantwoord. (De input staat tussen [])
```Markdown
INPUT

Wat is je naam? [Robbe bruynweels]
```
```Markdown
OUTPUT

Hallo Robbe Bruynweels
```

## opdracht
Schrijf een script dat kan berekenen hoe oud je bent a.d.h.v. de volgende formule: `2020-geboortejaar`. Laat de computer dit weergeven in de volgende zin: `NAAM is LEEFTIJD oud.`


Maak gebruik van de volgende functies:

- input()
- print()
- variabelen
- int()

Veel succes!
