# Elektron

**Polski open-source elektryczny quad**

Projekt koncepcyjny oparty na tych samych zasadach co ex-polonez:
- **Maintainability First**
- **Circular DIY + Low-Cost**
- Maksymalny upcycling / recycling / reuse
- Jak najwięcej elementów do samodzielnego wydrukowania (3D) lub pospawania
- Otwartość (open source hardware + dokumentacja)

---

## Wizja

Prosty, solidny, tani w budowie i naprawie elektryczny quad użytkowy / rekreacyjny.  
Ma dać się zbudować w garażu z dużą ilością części ze złomu, rozbitek EV i druku 3D.  
Ma być naprawialny przez jedną osobę z podstawowymi narzędziami.

Nazwa „Elektron” – nawiązanie do polskiej tradycji technicznej i czystej energii.

---

## Zasady docelowe (niezmienne)

1. Metal (spawany lub solidnie skręcany) tylko tam, gdzie są duże siły i bezpieczeństwo.
2. Wszystko inne – druk 3D, złom, upcycling, improwizacja.
3. Modularność agresywna: baterie w kasetach, napęd jako wymienny blok, łatwy dostęp serwisowy.
4. Bezpieczeństwo HV nie podlega negocjacjom (izolacja, interlocki, wyłączniki awaryjne).
5. Pełna dokumentacja + pliki do druku + instrukcje spawania w repo.
6. Koszt materiałów docelowy: jak najniższy rozsądny (cel orientacyjny pierwszej wersji: poniżej 15–25k PLN przy agresywnym upcyclingu).

---

## Wstępna koncepcja techniczna

### Rama
- Rurowa / kątownikowa, spawana z profili stalowych ze złomu lub hurtowni.
- Prosta geometria (łatwa do skopiowania i spawania).
- Punkty mocowania zawieszenia, silników/napędu i kaset baterii zaprojektowane z myślą o serwisie.

### Napęd
- Opcja A (najtańsza na start): jeden silnik centralny + dyferencjał / wałki (reuse z quada / samochodu / przemysłowy).
- Opcja B: silniki piastowe (hub motors) – prostsze, ale droższe i trudniejsze w serwisie.
- Preferowane źródła: używane silniki z skuterów EV, małych aut, przemysłowe, Leaf EM57 w wersji zredukowanej jeśli pasuje.

### Bateria
- System kasetowy (1–4 kasety).
- Moduły z rozbitek (Tesla, Leaf, inne).
- Na start możliwe chłodzenie powietrzne.
- Napięcie systemowe: 48–96 V na początek (łatwiejsze i tańsze komponenty) lub 300+ V jeśli używamy gotowych napędów EV.

### Zawieszenie i koła
- Proste wahacze lub sztywne mosty (reuse + spawanie).
- Koła i opony z rynku wtórnego / quadowego.

### Nadwozie / osłony
- Maksymalnie druk 3D lub blacha + sklejka + kompozyt z recyklingu.
- Łatwe do demontażu panele serwisowe.

### Elektronika
- Open-source kontroler (VESC / OpenInverter / podobne).
- Prosty wyświetlacz + podstawowa telemetria.
- Service Box z łatwym dostępem.

---

## Plan rozwoju (wstępny)

1. Zdefiniowanie dokładnych wymiarów ramy i rozstawu osi.
2. Wybór napięcia systemowego i pierwszego silnika.
3. Projekt kaset baterii (współdzielony z doświadczeniami z ex-polonez).
4. Prototyp ramy (spawany).
5. Integracja napędu i baterii.
6. Testy, dokumentacja, pliki STL.

---

## Status

Projekt w fazie koncepcyjnej.  
Wszystkie pliki będą otwarte. Zachęcamy do forków, poprawek i współtworzenia.

---

*Nova / EXÆE – 2026*
