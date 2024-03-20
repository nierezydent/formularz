# [formularz ](formularz.nierezydent.pl)


## Formaty plików

korzyści i wady lokalizacji
```csv
COUNTRY, PROS, CONS

```


Podatki
```csv
COUNTRY, VAT, CIT, limits, levels of tax

```


Jezyki, populacja, ...
```csv
COUNTRY, Language, Population

```


## USER data


+ select: one person OR with wife
+ option: with children
+ list of countries, how long you plan stay there
+ salaries


Scenariusz pobytu
```csv
partner, kraj pobytu, ilosc dni pobytu dzieci, zarobki, waluta, uslugi
1,PL,100,2, 5000, PLN, Consulting
1,UK,165,2, 2000, GBP, Consulting
1,DE,65,2, 1000, EUR, Consulting
2,DE,200, 50000, EUR, Consulting
2,EE,10, 60000, EUR, Consulting
2,PL,155, 15000, PLN, Consulting

```


## input

```csv
if COUNTRY.language

```


## Output

table with countries and benefits, comparasion, many variants, simulations as matrix


Variables:
+ COUNTRIES
  + tax
  + for how long
  + 


## działanie

+ załadowanie danych do tablicy COUNTRY, USER i przeprowadzenie na nich warunków i zapisanie dozmiennych wyjśćiowych




## definicje

```yml
country:
  - pros
  - cons

```
