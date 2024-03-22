# [formularz](https://nierezydent.github.io/formularz/)


Formularz służy kalkulacji korzyści i wad różnych rezydencji, będzie dostepny do testowania na dniach, to będzie prosty formularz z kilkoma opcjami do zaznaczenia i jako wynik będzie widoczna tabela z podsumowaniem aktualnego kosztu na aktualny rok oraz propozycja zmiany na najkorzystniejszą w obrębie Europy, z czasem będę dodawał kolejne kontynenty.


To projekt otwarty więc każdy może pomóc uwagami oraz propozycjami, dlatego też powstała ta grupa byśmy sobie pomogli w odpowiedzi na różne pytania.


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


### USER data


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


### Variables



### Conditions in python


```python
if COUNTRY.name == 'PL' and 

```



## Output

table with countries and benefits, comparasion, many variants, simulations as matrix


Variables:
+ COUNTRIES
  + tax
  + for how long
  + 


### Actions

+ country code as array
+ załadowanie danych do tablicy COUNTRY, USER i przeprowadzenie na nich warunków i zapisanie dozmiennych wyjśćiowych




### Definitions

```yml
country:
  - pros
  - cons
```



## techstack

[Full Stack FastAPI + VanillaJS Tutorial - YouTube](https://www.youtube.com/watch?v=p9YTVAq472E)

