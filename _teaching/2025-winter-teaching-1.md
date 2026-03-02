---
title: "Cyfrowe narzędzia w przekładoznawstwie"
collection: teaching
type: "Master's degree; 2nd year"
permalink: /teaching/2025-winter-teaching-1
venue: "ul. Grodzka 64, s. 202"
date: 2025-10-06
location: "Kraków, Poland"
---

This is an introductory course in stylometry. The students learn about the basics of stylometry with R, they get to know the basics of corpus building and finally they perform an analysis of their own collection of texts using stylo.

2025-10-06 Zajęcia organizacyjne, wprowadzenie do stylometrii
======
<a href="/files/0610_CyfroweNarzedzias.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

Warunki zaliczenia:
- obecność na zajęciach (do 2 nieusprawiedliwionych nieobecności)
- aktywność na zajęciach
- wykonanie projektu zaliczeniowego; [link do arkusza z zapisami na prezentacje](https://ujchmura-my.sharepoint.com/:x:/g/personal/aleksandra_rykowska_doctoral_uj_edu_pl/Eb3R3d05esdLqcCE6dTH7lQBGQkfvKdo6BzZ_mkZuEIVdQ?e=JSI3iy)

2025-10-13 Czym jest stylometria i na czym polega ta metoda?
======
<a href="/files/1310_CyfroweNarzedzia_compressed.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

2025-10-20 Przykładowe badania stylometryczne
======
<a href="/files/2010_CyfroweNarzedzia_compressed.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

<a href="/files/Rykowska_dramatfrancuski.pdf" target="_blank">Przykład prezentacji zaliczeniowej</a>

💻 Na następne zajęcia (27/10/2024) **proszę pamiętać o przyniesieniu swoich laptopów**, jeżeli ktoś chce instalować stylo na swoim sprzęcie. Jeśli ktoś nie chce instalować na swoim laptopie, dostępne będą komputery w sali, ale nie można ich zabrać do domu, żeby wykonać na nich projekt zaliczeniowy ☺️

2025-10-27 Instalowanie stylo i pierwsze własne analizy
======
<a href="/files/2710_CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

Linki do pobrania:
- [R dla Windowsa](https://cran.r-project.org/bin/windows/base/)
- [R dla macOs](https://cran.r-project.org/bin/macosx/)
- [XQuartz tylko jeśli jest błąd na Macu](http://www.xquartz.org)

2025-11-03 Bootstrap consensus - ćwiczenia
======
Przypominam o deklaracji terminu prezentacji projektu zaliczeniowego. Lista znajduje się [tutaj](https://ujchmura-my.sharepoint.com/:x:/g/personal/aleksandra_rykowska_doctoral_uj_edu_pl/Eb3R3d05esdLqcCE6dTH7lQBGQkfvKdo6BzZ_mkZuEIVdQ?e=JSI3iy).

<a href="/files/0311CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

Link do [dokumentu z ćwiczeniami](https://ujchmura-my.sharepoint.com/:w:/g/personal/aleksandra_rykowska_doctoral_uj_edu_pl/EaVqCc5gBkNMtSWc_6UHMxABSrkFFlV4eQmzNM9gHREvqg?e=cGN2q4). 

2025-11-24 Funkcja oppose(), wyrażenia regularne, instalowanie Gephi
=====
<a href="/files/2411CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

Link do [burzy mózgów](https://www.menti.com/alu8dhwzasg8).

Link do strony [Gephi](https://gephi.org/desktop/).

**Zadanie dla osób, które mają więcej niż 2 nieobecności:**

- Za pomocą funkcji `oppose()` wykonać ćwiczenie dot. różnic leksykalnych między powieściami napisanymi przez kobiety i powieściami napisanymi przez mężczyzn w korpusie `Klasyka polska`. (Dokładna instrukcja w prezentacji)
- Wykonać ćwiczenia dot. wyrażeń regularnych:
```
1. Jakim wyrażeniem regularnym wyszukamy wyrazy, które zaczynają się od prefiksów do-, po-, pod-?
2. Jakim wyrażeniem regularnym wyszukamy wyrazy, które kończą się na -ący, -ąca, -ące?
3. Jakim wyrażeniem regularnym wyszukamy wyrazy, które mają geminatę -tt-?
4. Jakim wyrażeniem regularnym wyszukamy pierwszy wyraz w nazwach plików, które zostały utworzone według wzoru: Autor_TytułPowieści_RokWydania?
5. Jakim wyrażeniem regularnym wyszukamy w nazwach plików utworzonych według schematu powyżej same lata wydania książek?
6. Jakim wyrażeniem regularnym wyszukamy w nazwach plików utworzonych według schematu powyżej tytuły książek?
```
- Wykonać [Regexle](https://regexle.com/) dla danego dnia i przesłać zrzut ekranu.

Odpowiedzi przesłać mailem :)

2025-12-01 Gephi
=====

<a href="/files/0112_CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

Link do strony [Gephi](https://gephi.org/desktop/).

Link do [dokumentu z zadaniem](https://ujchmura-my.sharepoint.com/:w:/g/personal/aleksandra_rykowska_doctoral_uj_edu_pl/IQBS7BxiWabGSYq461CQ6Cy5AcZWuN-EZWeOOJenQ3QMhEw?e=KkiLqa)

**Zadanie dla osób, które mają więcej niż 2 nieobecności:**

```
Proszę zainstalować Gephi i wykonać wykresy dla korpusów:
- Klasyka polska
- Francuzi po polsku
- Dramaty polskie (tutaj według dodatkowego polecenia z dokumentu podlinkowanego wyżej)
Wykresy proszę przesłać mailem :)
```

2025-12-04 Rolling stylometry
=====

<a href="/files/0412CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

**Zadanie dla osób, które mają więcej niż 2 nieobecności:**

```
Proszę wykonać analizy za pomocą funkcji `rolling.classify()` z użyciem `trzech różnych metod`. 
- Proszę mailowo przesłać trzy wykresy a analizy korpusu `Dickens and Collins`
- Proszę zaproponować inny tekst, który Państwo znają, który można zanalizować za pomocą wskazanej metody.
```

2025-12-08 Budowanie własnego korpusu
=====

<a href="/files/0812CyfroweNarzedzia.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

2026-01-08 Porady dot. prezentacji i hands-on session
=====

<a href="/files/0801Cyfrowe.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

**Zadanie dla osób, które mają więcej niż 2 nieobecności:**

```
Proszę poprawić 2 wykresy z Gephi, które robiliśmy w czasie zajęć tak, aby były w całości pokolorowane, bez szarych połączeń
```

2026-01-12 Prezentacje studenckie, inne narzędzia cyfrowe
=====
<a href="/files/1201Cyfrowe.pdf" target="_blank">Prezentacja z zajęć do przejrzenia/pobrania</a>

**Zadanie dla osób, które mają więcej niż 2 nieobecności:**

```
Proszę mailowo przesłać:
- link do strony korpusu diachronicznego języka polskiego
- link do strony słownika, w którym znajdziemy zarejestrowane i omówione wyrazy staropolskie
- nazwy 5 różnych narzędzi udostępnianych przez konsorcjum CLARIN-PL, które mogą być potrzebne w pracy przekładoznawcy i/lub tłumacza i podać wyjaśnienie
- wyjaśnienie, czym różnią się Korpusomat, Ant-conc oraz Sketch Enginec
```

**Przypominam też, że aby zaliczyć przedmiot należy:**
- nadrobić wszystkie ponadprogramowe nieobecności
- mieć >50% obecności na zajęciach
- proszę też sprawdzić, czy wrzucili Państwo wyniki swojej pracy w dokumentach, nad którymi pracowali Państwo w czasie zajęć

## Odrabianie zajęć z 17.11 i z 15.12

Umówiliśmy się na `czwartek 04.12` na godz. 15:00. 

W `czwartek 04.12` o godz. `15:00` widzimy się na `Gołębiej 16, w sali 52`.

Zajęcia z `15.12` odrobimy jednak po świętach - chciałabym, żeby mieli Państwo czas na zebranie korpusu. Na ostatnich zajęciach przed prezentowaniem projektów zrobimy **hands-on session** i każdy będzie miał całe zajęcia, żeby pracować nad projektem. Ja będę wtedy do Państwa dyspozycji i będę pomagać w razie wystąpienia jakichkolwiek problemów z analizami.

Odrabiane zajęcia z `15.12` odbędą się w `czwartek 08.01.2026` o godz. 15:00 na platformie MsTeams.



