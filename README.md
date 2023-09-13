# **Task 1**

## **Subtask 1**

9

## **Subtask 3**

Witam, mam na imię Baśka. Biorę udział w DareIT Challenge żeby zdobyć praktyczne umiejętności z zakresu testowania manualnego. 
W zeszłym roku przypadkowo trafiłam na materiały dotyczące testowania i przepadłam. Od tej pory ciągle się uczę, odkrywając, że wraz z postępami w nauce rośnie ilość wiedzy, którą muszę i chcę przyswoić.
Jednak nie samą teorią człowiek żyje i potrzebuję nieco praktyki, która sprawi, że suche fakty wskoczą na swoje miejsce i ułożą się w ciągi logiczne.

**_Baśka_**

## **Subtask 4**

1. Aplikacja dla skautów piłki nożnej, która umożliwia przeglądanie wskaźników, umiejętności i pozycji zawodników.
  Dzięki aplikaji użytownik powinien móc określić cechy danego piłkarza i jego potencjlną przydatność dla zespołu.

2. W aplikacji użytkownik może przeglądać bazę zawodników. Bazę można sortować po punktacji zawodnika, imieniu lub nazwisku w kolejności alfabetycznej, wieku, pozycji, klubie, recenzji.
  Po wybraniu zawodnika użytkownik widzi podstawowe dane, może wyświetlić mecze w których zawodnik wystąpił, stracone i strzelone gole w danym meczu oraz raport gracza.
  Użytkownik ma możliwość edycji wszystkich powyższych danych.
  Użytkownik ma możliwość dodania zawodnika.
  Funkconalności są dosyć mało intuicyjne. "Rozrzucone" w różnych miejscach, mało logiczne. Niektóre się powtarzają.
  Nie do końca udało mi się dojść na czym polega funkcja "rozpocznij mecz" i kolejno dodawane akcje. Nie widzę korelacji z raportem czy rankingiem gracza.

3. Interfejs jest dosyć przyjemny, przejrzysty, nie męczy oczu.

4. W sesji testowania eksploracyjnego skupiłam się na przetestowaniu możliwości edycji profilu zawodnika.
   
   
   Błędem z założenia wydaje mi się możliwość dowolnej edycji profilu gracza. Uprawnienia do edycji powinien mieć jeden użytkownik zarządzający profilem.
  
      * W profilu gracza pole "waga" pzyjmuje wartość ujemną - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "data urodzenia" przyjmuje datę przyszłą oraz datę sprzed wynalezinia piłki nożnej ;) - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "wzrost" przyjmuje wartości nieprawdopodobne - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "poziom rozgrywek" przyjmuje dowolny ciąg cyfr lub liter - proponuję rozwijaną listę z wyborem poziomu
  
      * W profilu gracza pole "pozycja główna" przyjmuje dowolny ciąg cyfr lub liter - proponuję jak wyżej
  
      * W profilu gracza pole "pozycja alternatywna" przyjmuje dowolny ciąg cyfr lub liter - proponuję jak wyżej
  
      * Nie rozumiem co ma na celu pole "Łączy nas piłka" - sugeruję wyszarzoną podpowiedź w oknie np. krótki opis kariery
  
      * Nie rozumiem co ma na celu pole "90 minut" - proponuję jak wyżej
  

