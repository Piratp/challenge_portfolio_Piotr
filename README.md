# Task 1
<h2>Subtask 1</h2>
<i> 9/10 punktów :) </i>

## Subtask 2

Myślę o zmianie branży na IT. Nie wiedziałem na co się zdecydować przez ogrom dostępnych opcji, dlatego chcę zacząć od teoretycznie najłatwiejszej opcji wejścia do nowej branży. <br> Dodatkowo wydaje mi się, że jestem osobą szczegółową oraz drobnostkową, co jest porządane na tym stanowisku. <br>
Mam nadzieję, że dzięki kursowi podtrzymam tę chęć do zmiany branży i w przyszłości uda mi się wejść do świata IT :)

## Subtask 3

* Na czym polega ta aplikacja? Do czego służy? <br>
Aplikacja służy do zbierania przez skautów informacji na temat zawodników piłkarskich.


* Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? <br>

  * Logowanie do systemu
  * Wylogowanie z systemu
  * Zmiana języka
  * Rozwijalna lista województw
  * Możliwość wklejania linków z youtube
  * Możliwość ściągnięcia danych w formacie CSV
  * Możliwość wydruku
  * Możliwość wyboru kolumn
  * Możliwość filtrowawnia tabeli
  * Możliwość sortowania kolumn
  * Możwliwość powrotu na stronę główną
  * Dodawanie nowych oraz edycja istniejących raportów meczowych
  * Podgląd ostatich aktywnośc


* Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie? <br><br>
Jest prosta, w miarę przejrzysta. Myślę, że spełnia swoje zadanie.

* Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).<br><br>
Dodałbym jeszcze "klikalne" zakładki na stronie głównej, czyli "ilość graczy", "ilość meczy" itp.<br>
Natomiast tak, od razu rzuca się w oczy możliwość dodania gracza.

* Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)<br>
  * Można wpisać ujemny wzrost
  * Można podać ujemny wiek
  * W telefonie można wpisać litery
  * Czy przycisk "clear" nie powinien czyścić też pozostałych komórek?
  
# Task 2
<h2> Subtask 3</h2>

* Po co piszemy test case’y? <br>
  * sprawdzenie danego oprogramowania
  * sprawdzenie czy w oprogramowaniu znajdują się wszystkie wymagane fukncjonalności
  * sprawdzenie czy aplikacja działa zgodnie z wcześniej założonymi oczekiwaniami
  * sprawdzenie czy podane linki działają oraz przenoszą nas do odpowiedniej zawartości
  
<h1> Task 3 </h1>

https://drive.google.com/drive/folders/1mkIPSn0hzK9n5sDDZoJ5_GwDy3Cgwry4?usp=sharing

<h1> Task 4 </h1>

<h2> Subtask 1 </h2>

https://docs.google.com/spreadsheets/d/1hAifpGW5oRbkTJNaqD8NBT2tYIjGNixMpxtnXWeofNQ/edit?usp=share_link

<h2> Subtask 2 </h2>
https://docs.google.com/spreadsheets/d/1hAifpGW5oRbkTJNaqD8NBT2tYIjGNixMpxtnXWeofNQ/edit?usp=share_link

<h2> Subtask 3 </h2>
<ol>
 <li> <i> Do czego służy ta aplikacja? Jaki jest cel tej aplikacji? </i> </li> <br>
Głównym celem aplikacji jest chęć zarobienia na niej. <br>
Dodatkowo, jest to aplikacja handlowa, służąca do tworzenia i wystawiania ogłoszeń na całą Polskę. Możemy tutaj wystawić ogłoszenie sprzedaży, chęci kupna, wymiany czy wynajmu określonych towarów i usług. Pojawiają się tutaj także ofety pracy.
 <br><br>
 
 <li> <i> Kto ma być użytkownikiem końcowym aplikacji? </i> </li><br>
 Kupujący, sprzedający, wynajmujący oraz potencjalni najemcy, a także poszukujący i oferujący pracę.<br><br>
 
 <li> <i> Czy według Ciebie aplikacja jest user friendly? </i> </li><br>
 Tak, jest user friendly. <br><br>
 
 <li> <i> Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? </i></li><br>
 Dodałbym opcję zmiany języka, min. j. angielski.<br>
 Przydatną fukncją byłaby tzw. karuzela, czyli przesuwające się co jakiś określony czas ogłoszenia np. w obserwowanych w celu poprawy dynakimi aplikacji.
 Fajną rzeczą byłby też wyskakujący czat, jeśli apliakacja "zauważy", że użytkownik nie może znaleźć poszukiwanej funkcji aplikacji, np. przy tworzeniu profilu        kandydata.<br><br>
 
 
 <li><i>  Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej? </i></li><br>
 Na pewno w przypadku aplikacji natywnej trzeba zwrócić uwagę na wygodę aplikacji, tzn. czy przyciski funkcjonalne (wstesz, zapisz itp.) są w zasięgu palca użytkownika.


# Task 5
 
## Subtask 1
 
<ol>
<li> SELECT </li>
 <li> USE </li>
 <li> GO </li>
 <li> CREATE TABLE </li>
 <li> ORDER BY </li>
 <li> WHERE </li>
 <li> AS </li>
 <li> LIKE </li>
 <li> BETWEEN </li>
 <li> IN </li>
 
<h2> Subtask 3 </h2>
 
 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname. <br><br>
 
 SELECT * FROM actors ORDER BY surname <br><br>
 
 ![image](https://user-images.githubusercontent.com/121132379/218864438-6a95de31-493f-47e9-9255-7915fba67734.png) <br>

 
 2. Wyświetl film, który powstał w 2019 roku.<br><br>
 
 SELECT * FROM `movies` WHERE year_of_production = 2019 <br><br>
 
 ![image](https://user-images.githubusercontent.com/121132379/218865645-f16b9034-509a-4bd5-9cb0-79180e7467bb.png) <br>

 
 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.<br><br>
 
 <br><br>

 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.<br><br>
 
 <br><br>
 
 
 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.<br><br>
 
<br><br> 
 
 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.<br><br>
 
 <br><br>
 
 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.<br><br>
 
 <br><br>
 
 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.<br><br>
 
 <br><br>
 
 9. Wyświetl dane klienta, który nie ma podanego adresu email.<br><br>
 
 <br><br>
 
 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.<br><br>
 
 <br><br>
 
 
    
 
