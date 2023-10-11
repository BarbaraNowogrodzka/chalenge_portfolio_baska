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
  

# **Task 2**

 ## **Subtask 1**

[Sutask 1](https://docs.google.com/spreadsheets/d/1cJdgKOohFKX-LAvIPEd7_Vse6Cfx7HyT/edit#gid=541246506)

## **Subtask 2**

[Subtask 2](https://docs.google.com/spreadsheets/d/1-a9cfQO4mb6n4rqtnMebCNdCA5_44QsHkxkJyuEzlGY/edit#gid=0)

## **Subtask 3**

We write test cases to ensure that software or systems perform as expected and meet their functional requirements. Test cases provide a systematic and documented approach to verifying that each aspect of the software functions correctly and that potential issues are identified and addressed. They serve as a guide for testers to execute specific scenarios and help maintain the quality and reliability of the software throughout its development and maintenance lifecycle.

# **Task 4**

## **Subtask 1 i 2**

[Zgłoszenia błędów aplikacji mobilnej](https://docs.google.com/spreadsheets/d/1St6qdEFl7r6by0NS6X8u0wtX9QR8_QMf80mT9zHiXAk/edit#gid=0)

## **Subtask 3**

The OLX app is an online marketplace that facilitates buying and selling of various products and services. Users can browse listings in different categories, from electronics to real estate, and connect with sellers locally or globally. The app offers tools for creating user profiles, messaging, and managing listings. It's a platform that enables easy, convenient, and secure transactions between individuals looking to sell items they no longer need and those in search of specific goods or services.


# **Task 5****
## **Subtask 3


1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

SELECT * FROM actors ORDER BY surname ASC; 

2. Wyświetl film, który powstał w 2019 roku.

SELECT * FROM movies where year_of_production = '2019';

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT * FROM movies where year_of_production BETWEEN '1999' and '2019';

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 

SELECT title, price FROM movies where price < '7'; 

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM actors where actor_id >= '4' and actor_id <= '7'; 

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 

SELECT * FROM actors where actor_id = '2' or actor_id = '4' or actor_id = '6'; 

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

SELECT * FROM actors where actor_id in ('1','3','5');

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

SELECT * FROM actors where name like 'An%';

9. Wyświetl dane klienta, który nie ma podanego adresu email.

SELECT * FROM customers where email IS NULL;

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

SELECT * FROM movies where price > '9' and movie_id BETWEEN '2' and '8';



