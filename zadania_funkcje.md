# Zadania dla użytkowników i funkcje aplikacji

**Komentarz1:** Zadania podzielone na części - cały test będzie podzielony prawdopodobnie na 2 osobne części. Z technicznego punktu widzenia można rozważyć skonstruowanie nieco zmodyfikowanych aplikacji albo każdej części albo nawet do każdego z zadań lub grup zadań (to jeszcze zależy do tego, w jaki sposób realizowane będą testy przez firmę realizująca testy z użytkownikami).

**Komentarz2:** Trzeba też rozważyć czy na potrzeby testów nie zrobić osobnej instacji aplikacji dla każdego użytkownika (logi, możliwość separacji etc. )

## ZADANIA

### A. Zadania sprawdzające umiejętności posługiwania się informacją przestrzenną (*spatial cognition*) 

#### Wymagane:

1. **Wskaż miejsce Twojego zamieszkania** - użytkownik wskazuje za pomocą dowolnego narzędzia (poligon, punkt,linia) - sprawdzamy jakie narzędzie wybierze i jak dokładnie wskaże. Dane mamy z ankiety.  
2. **Wkaż OBIEKT na mapie** - umiejętność u czas potrzebny na znalezienie konkretnego, znanego wszystkim obiektu. Przy czy powinno być to powtórzone z różnymi typami geometrii (punkt, linia, poligon).
3. **Wskaż miejsca Twoim zdaniem najatrakcyjniejsze dla turystów** - rodzaj narzędzia, dokładność i ilość wskazań
4. **Wskaż Twoje ulubione miejsca w mieście** - rodzaj narzędzia, dokładność i ilość wskazań.

**Komentarz do 3&4** Tutaj trzeba się zastanowić czy w ankiecie podobne pytania jako weryfikacja i czy ankieta przed czy po czy oba warianty.


#### Opcjonalne:

### B. Zadania sprawdzające czytelność przekazu planistycznego

#### Wymagane:

1. **Zidentyfikuj i wskaż dany typ użytkowania (np. obszary pod zabudowę jednorodzinną) w planie miejscowym** lub jeszcze lepiej **Oceń jaki typ użytkowania ma największę znaczenie w danym rejonie (lub inne sformułowanie)** - ten test ma za zadanie sprawdzić czytelność planu miejscowego, umiejętność czytania legendy (np. korzustanie z popupów) i czytania mapy.
2. **Dodaj komentarz do plany miejscowego** - identyfikacja miejsca, wybór narzędzia, komentarz słowny. Trzeba sie  zastanowić czy dać konkretny komentarz może. 

#### Opcjonalne:



## Funkcje

#### Wymagane:

1. Możliwość dodawania punktów oraz jednego typu dodatkowo (linie, poligony) i zapisu w bazie z czasem dodania i identyfikatorem użytkownika.
2. Popupy z informacją na temat obiektów
3. Możliwość dodawania punktów z komentarzami poprzez okno dialogowe
4. Wyświetlanie komentarzy i punktów innych użytkowników
5. Warstwa z planem zagospodarowania i legendą.

#### Opcjonalne:

1. Możliwość dodawania wszystkich rodzajów obiektów (linia, poligon i punkt)

### Dodatek: Funkcje sprawdzające użyteczność interfejsu użytkownika

**Komentarz:** Poniższe elementy nie będę zmieniane przez użytkownika ale raczej pomiędzy grupami testowymi. Ma to za zadanie sprawdzić, czy uzyskiwane rezultaty są w jakiś sposób zależne od samego interfejsy, a nie od użytkownika 

#### Wymagane:

1. Zmiana podkładu mapowego
2. Różne formy legendy
3. Wyświetlanie na stałe lub na żądanie komentarzy i punktów innych użytkowników (wytworzone wcześniej na potrzeby testu). 

#### Opcjonalne:

1. Różne formy dodawania komentarzy i punktów (np. punkt -> komentarz lub komentarz -> punkt)
2. Dodatkowe warstwy informacyjne dla użytkownika

