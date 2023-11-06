# **DareIT Challenge**

## **TASK 1**

### **Subtask 1**

9

### **Subtask 3**

Witam, mam na imię Baśka. Biorę udział w DareIT Challenge żeby zdobyć praktyczne umiejętności z zakresu testowania manualnego. 
W zeszłym roku przypadkowo trafiłam na materiały dotyczące testowania i przepadłam. Od tej pory ciągle się uczę, odkrywając, że wraz z postępami w nauce rośnie ilość wiedzy, którą muszę i chcę przyswoić.
Jednak nie samą teorią człowiek żyje i potrzebuję nieco praktyki, która sprawi, że suche fakty wskoczą na swoje miejsce i ułożą się w ciągi logiczne.

**_Baśka_**

### **Subtask 4**

1. Aplikacja dla skautów piłki nożnej, która umożliwia przeglądanie wskaźników, umiejętności i pozycji zawodników.
  Dzięki aplikaji użytownik powinien móc określić cechy danego piłkarza i jego potencjlną przydatność dla zespołu.

2. W aplikacji użytkownik może przeglądać bazę zawodników. Bazę można sortować po punktacji zawodnika, imieniu lub nazwisku w kolejności alfabetycznej, wieku, pozycji, klubie, recenzji.
  Po wybraniu zawodnika użytkownik widzi podstawowe dane, może wyświetlić mecze w których zawodnik wystąpił, stracone i strzelone gole w danym meczu oraz raport gracza.
  Użytkownik ma możliwość edycji wszystkich powyższych danych.
  Użytkownik ma możliwość dodania zawodnika.
  Użytkownik ma możliwość zapisywania danych do pliku csv oraz drukowania zestawień. 
  Funkconalności są dosyć mało intuicyjne. "Rozrzucone" w różnych miejscach, mało logiczne. Niektóre się powtarzają.
  Nie do końca udało mi się dojść na czym polega funkcja "rozpocznij mecz" i kolejno dodawane akcje. Nie widzę korelacji z raportem czy rankingiem gracza.

4. Interfejs jest dosyć oszczędny, mało intuicyjny. Nie męczy oczu. Strona główna niestandardowa pod kątem rozmieszczenia elementów. Logo umieszczone z boku, mało widoczne. Linki pomocnicze umieszczone centralnie. Nie widać też z poziomu strony głównej, znajdujących się po lewej stronie, meczy i raportów. Koncepcja mało logiczna, nietypowa - co utrudnia kożystanie.

5. Jeśli chodzi o tworzenie i edycję to niedoświadczony użytkownik jest w stanie się połapać, natomiast pojawiają się obszary, które dobrze byłoby dopracować:
Lupka w wyszukiwarce nie jest aktywna. Wyłącznie enter powoduje zatwierdzenie wyszukiwanej frazy. Dobrze by było, gdyby można było wykorzystać ją do wyszukiwania oraz przedatne byłoby wyszukiwanie dynamiszne tzn. wyniki wyszukiwania były wyświetlane już w trakcie wpisywania tekstu w wyszukiwarkę. Niektóre funkcjonalności "proszą się" o podpowiedź/objaśnienie.

   

6. W sesji testowania eksploracyjnego skupiłam się na przetestowaniu możliwości edycji profilu zawodnika.
   
   
   Błędem z założenia wydaje mi się możliwość dowolnej edycji profilu gracza, co może prowadzić do spekulacji. Uprawnienia do edycji powinien mieć jeden użytkownik zarządzający profilem np. menager zawodnika lub drużyny/trener/PR-owiec.
  
      * W profilu gracza pole "waga" pzyjmuje wartość ujemną - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "data urodzenia" przyjmuje datę przyszłą oraz datę sprzed wynalezinia piłki nożnej ;) - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "wzrost" przyjmuje wartości nieprawdopodobne - należy wprowadzić wartości brzegowe
  
      * W profilu gracza pole "poziom rozgrywek" przyjmuje dowolny ciąg cyfr lub liter - proponuję rozwijaną listę z wyborem poziomu
  
      * W profilu gracza pole "pozycja główna" przyjmuje dowolny ciąg cyfr lub liter - proponuję jak wyżej
  
      * W profilu gracza pole "pozycja alternatywna" przyjmuje dowolny ciąg cyfr lub liter - proponuję jak wyżej
  
      * Nie rozumiem co ma na celu pole "Łączy nas piłka" - sugeruję wyszarzoną podpowiedź w oknie np. krótki opis kariery
  
      * Nie rozumiem co ma na celu pole "90 minut" - proponuję jak wyżej
  

## **TASK 2**

 ## **Subtask 1**

[Przypadki testowe w oparciu o User Story](https://docs.google.com/spreadsheets/d/1cJdgKOohFKX-LAvIPEd7_Vse6Cfx7HyT/edit?usp=sharing&ouid=113890725788163755679&rtpof=true&sd=true)

### **Subtask 2**

[Przypadki testowe na podstawie doświadczenia](https://docs.google.com/spreadsheets/d/1-a9cfQO4mb6n4rqtnMebCNdCA5_44QsHkxkJyuEzlGY/edit#gid=0)

### **Subtask 3**

We write test cases to ensure that software or systems perform as expected and meet their functional requirements. Test cases provide a systematic and documented approach to verifying that each aspect of the software functions correctly and that potential issues are identified and addressed. They serve as a guide for testers to execute specific scenarios and help maintain the quality and reliability of the software throughout its development and maintenance lifecycle.

Test cases clarify what needs to be done to test a system. It gives us the steps which we execute in a system, the input data values which we enter in the system along with the expected results when we execute a particular test case.

## **TASK 3**

### ** Subtask 1 i 2**

[Zgłoszenia błędów](https://docs.google.com/spreadsheets/d/1htyuzVqItWh8yE92ktEhn92GnH8HS9ysbGRo0EyD-o0/edit?usp=sharing)


## **TASK 4**

### **Subtask 1 i 2**

[Zgłoszenia błędów aplikacji mobilnej](https://docs.google.com/spreadsheets/d/1St6qdEFl7r6by0NS6X8u0wtX9QR8_QMf80mT9zHiXAk/edit#gid=0)

### **Subtask 3**

1. What is the application for? What is the purpose of the application?
The OLX app is an online marketplace that facilitates buying and selling of various products and services. Users can browse listings in different categories, from electronics to real estate, and connect with sellers locally or globally. The app offers tools for creating user profiles, messaging, and managing listings. It's a platform that enables easy, convenient, and secure transactions between individuals looking to sell items they no longer need and those in search of specific goods or services.

2. Who is the end user of the application?
The end users of the OLX application are individuals or consumers who use the platform to buy and sell various products and services. OLX is an online marketplace where people can list items they want to sell and browse listings for items they want to buy. Users can be both buyers and sellers, and they use the OLX application to connect with each other and facilitate transactions. The application caters to a wide range of users who are interested in buying or selling used or new items, such as electronics, furniture, vehicles, clothing, and more.

3. Is the application user friendly?
In my opinion, the application is very user-friendly.  Good design, navigation, ease of use, and the quality of the user interface. 

4. How would you improve the application? Do you have any idea for additional functionality?
The application meets all my requirements. The only improvement that I think is worth considering is adapting the application for blind or visually impaired people and enabling the use of the application in English.
Even if it is a local application, allowing non-Polish speakers to use it could expand the audience.

5. What differences do you see between testing a web application and a native one?
The basic difference in testing a native application and a web application is that web applications can run on a platform with any operating system, while a mobile application is dedicated to a specific platform, which makes testing mobile applications more advanced than web applications. The web application can be used by a web browser, while the mobile application must be downloaded to the device and installed. In addition, mobile applications look different from web applications.


## **TASK 5**
### **Subtask 3**


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

## **TASK 6**
### **Subtask 1**
11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd

UPDATE customers set surname = 'Miler' where customer_id = 3;
SELECT * FROM customers
obraz

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

SELECT customers.name,customers.surname,customers.email FROM sale INNER JOIN customers on sale.customer_id = customers.customer_id where sale.movie_id = 4;
obraz

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

UPDATE customers set email = 'pati@mail.com' where customer_id = 4;
SELECT * FROM customers
obraz

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

SELECT customers.name, customers.surname , movies.title FROM sale INNER JOIN customers on sale.customer_id = customers.customer_id INNER JOIN movies on sale.movie_id = movies.movie_id;
obraz

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

ALTER TABLE customers ADD pseudonym VARCHAR(15) NOT NULL;
UPDATE customers set pseudonym =CONCAT(LEFT(name,2),RIGHT(surname,1))
obraz

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

SELECT DISTINCT movies.title FROM sale INNER JOIN movies on sale.movie_id = movies.movie_id
obraz

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

SELECT actors.name, actors.surname FROM actors UNION SELECT customers.name,customers.surname FROM customers ORDER by 1 ASC;
obraz

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

UPDATE movies set price = price + 2.5 where year_of_production > '2000'
SELECT * FROM movies where year_of_production > '2000'
obraz

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

SELECT actors.name, actors.surname, movies.title FROM cast INNER JOIN actors on cast.actor_id = actors.actor_id INNER JOIN movies on cast.movie_id - movies.movie_id where actors.actor_id = 4
obraz

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

INSERT INTO customers (customer_id, name, surname, email, pseudonym) VALUES ('7', 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')



