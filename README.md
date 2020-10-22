# input-output
De `input()` en output (`print()`) functies zorgen 
voor communicatie tussen de computer en de gebruiker.


## input
De `input()` functie wordt als volgt gebruikt:
```python
input('Wat is je naam? ')
```

Als je dit script uitvoert krijg je dit te zien:
```md
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
```md
Hallo
```

Je kan ook variabelen printen:
```python
tekst = 'Hallo'
print(tekst)
```
```md
Hallo
```
Wanneer je meerdere dingen wilt printen op 1 regel, kan je gebruik maken van 2 methodes

- Methode 1: een `+` tussen elk apart element
```python
tekst =  'Hallo'
print(text+' wereld')
```
```md
Hallo wereld
```
- Methode 2: een `,` tussen elk apart element
```python
print(text,' world')
```
```md
Hallo wereld
```

## input-output
