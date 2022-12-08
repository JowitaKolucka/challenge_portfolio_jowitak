# TASK 1
### Subtask 1
Ilość punktów: 9/10 :blush:
### Subtask 3
Cześć! Jestem Jowita, mam 29 lat i jestem mamą trójki dzieci. Marzy mi się pójscie do pracy, a marzenia są po to by je spełniać. Swoją naukę na testera rozpoczęłam od rozmów z koleżanką, opowiadała mi dużo o swojej pracy jako testerka, wysłała mi Sylabusa od którego zaczęłam, następnie przeczytałam parę książek dotyczących tego zawodu, korzystałam i korzystam nadal z przeróżnych materiałów dostępnych w internecie i się "wkręciłam", bardzo chcę się dalej rozwijać. Dlaczego wybrałam ten kurs? Przede wszystkim po to, by _poszerzyć_ swoją wiedzę i _nauczyć się dobrych praktyk_, nie chcę wyrabiać w sobie złych nawyków. Wierzę, że wyjdę z tego kursu pewniejsza siebie i gotowa na dalszą naukę i rozwój. Jestem bardzo podekscytowana 😄
### Subtask 4 
#### 1. Na czym polega aplikacja:
Testowana aplikacja jest bazą danych o piłkarzach oraz meczach. Pozwala na dodawanie nowych graczy, meczy i raportów z nich. Jest dostępna również w języku angielskim.
#### 2. Funkcjonalności:
- dodawanie nowego gracza
- dodawanie nowego meczu z poziomu danego gracza
- dodawanie raportu z meczu 
- spis graczy 
- możliwość wydrukowania listy graczy oraz wygenerowania pliku .csv
- intuicyjne jest dodanie nowego gracza, reszta niestety nie. W Linkach Pomocniczych powinno być więcej odnośników, np. do  dodania nowego meczu, czy raportu z niego. Ponadto brakuje ważnej funkcji usunięcia gracza oraz opcji usunięcia meczów i raportów z nich. Przez to robi się bałagan w aplikacji i jest dużo niepotrzebnych danych.
#### 3. Interfejs  
prosty, możnaby było wyodrębnić niektóre funkcjonalności, żeby była przyjemniejsza w odbiorze.
#### 4. Intuicyjność 
funkcja dodania nowego gracza jest intuicyjna, a reszta funkcjonalności nie. Aplikacja jest ogólnie mało czytelna, można się w niej pogubić. 
#### 5. Błędy:
- Błąd 01: Podczas otwierania strony w narzędziu Devtools pojawił się błąd z kodowaniem http 404. Link url: https://scouts-test.futbolkolektyw.pl/pl/favicon.ico
- Błąd 02: Po sprawdzeniu walidacji boxu do logowania poprzez kliknięcie w przycisk "Zaloguj", po odświeżeniu strony przycisk "Zaloguj" zmienił swoje położenie i znajduje się na granicy z boxem.
Załącznik: ![image](https://user-images.githubusercontent.com/115720724/198887923-9a17eef5-1009-4c20-bb5a-93beba36b0ab.png)

- Błąd 03: W polu "Wzrost gracza" można wpisać zbyt dużą ilość cyfr, nie można podać liczb po przecinku oraz akceptowane są liczby ujemne.
![image](https://user-images.githubusercontent.com/115720724/198887712-c6e7dfe9-4d7b-437e-87dc-9109a10cdede.png)

- Błąd 04: W polach "Imię" oraz "Nazwisko" możliwe jest wpisanie cyfr oraz znaków specjalnych. 
Załącznik: ![image](https://user-images.githubusercontent.com/115720724/198888589-1be343d4-a3ad-4b5b-ab1e-00d90edcdb42.png)

- Błąd 05: W polu "Waga" nie można wpisać innych liczb po przecinku niż "0". Ponadto aplikacja akceptuje wpisanie dużej ilośći cyfr oraz akceptuje wartości ujemne.
- Błąd 06: W polu z datą urodzenia można podać datę urodzenia z dużym wyprzedzeniem.
- Błąd 07: W polu "Klub" możliwe jest wpisanie dużej ilości cyfr, liczb oraz znaków specjalnych.
- Błąd 08: Podczas edycji danych gracza po kliknięciu przycisku "Clear" dane się nie wymazują, kliknięcie tego przycisku powoduje cofnięcie jednej czynności. 
- Błąd 09: Przy edycji meczu danego gracza po kliknięciu przycisku "Clear" wymazuje się część danych (bez gwiazdki), a w polu "Stracone gole" pojawia się nieprawidłowa wartość. W załączniku stan po naciśnięciu przycisku "Clear", przed nim wszystkie pola były wypełnione.
![image](https://user-images.githubusercontent.com/115720724/198889367-8b8e2e05-ec3e-4d0b-a52c-ecab8d59e1b6.png)

- Błąd 10: Podczas edycji meczu w polach z drużyną zawodnika i przeciwną można wpisać nieskończenie dużą ilość znaków specjalnych, cyfr oraz liter.
- Błąd 11: Po kliknięciu w menu "Raporty", następnie "Dodaj Raport" zostajemy przekierowani na stronę "Mecze". 
- Błąd 12: Na stronie "Mecze", po wybraniu Akcji "Rozpocznij mecz" możliwe jest wysłanie pustego raportu. 
- Błąd 13: Nie działające tłumaczenie na język angielski (Z konta user02@getnada.com)
Załącznik: ![image](https://user-images.githubusercontent.com/115720724/198888506-62a97d66-5a33-4b9d-a6d2-07d1c8da94fb.png)
- Błąd 14: W edycji meczu dla gracza w polach "Stracone gole" oraz "Zdobyte gole" można wpisać dużą ilość liczb.
Załącznik:
![image](https://user-images.githubusercontent.com/115720724/198888880-b69fbdad-850d-4cdb-9f34-871253cc2a91.png)
- Błąd 15: W formukarzu edycji Raportów meczowych nie ma walidacji dotyczącej limitu znaków.
- W konsoli w Devtoolsach pojawiają się komunikaty: "Nie udało się załadować elementu mapy źródeł" oraz "Params `start` and `limit` are deprecated. Use `_start` and `_limit`"
- Błąd 16: W polu "Imię" aplikacja zaakceptowała 239463 liter, więcej nie wpisywałam. Wydaje mi się, że reszta pól także nie posiada walidacji dotyczącej maksymalnej liczby znaków. Po wpisaniu w wyszukiwarce graczy tego "gracza", aplikacja się porzeszyła i żeby otworzyć więcej informacji o nim trzeba bardzo długo przewijać stronę w bok  ![image](https://user-images.githubusercontent.com/115720724/199312898-1c397bbe-9310-48e2-9814-d6a03e7315eb.png)
Podobna sytuacja jest po kliknięciu w tego zawodnika: ![image](https://user-images.githubusercontent.com/115720724/199313034-be9112b1-7806-465e-8f8c-a805de939b8d.png)
Po kliknięciu w homepage w dane tego zawodnika strona długo nie odpowiada, po czym się wyłącza: ![image](https://user-images.githubusercontent.com/115720724/199315509-535e8101-4e21-4842-8cad-a701b768babe.png)


- Sprawdziłam działanie aplikacji zmieniając sieć na wolną 3G oraz szybką 3G, na tej wolniejszej sieci oczekiwanie na otwarcie strony jest dość długie.
- W emulatorze urządzeń na IPhonie 12 Pro, Samsungach funkcja przewijania informacji o zawodniku nie działa jak powinna. Po obróceniu ekranu już lepiej to wygląda.

# TASK2
### Subtask1
:point_right:__[Subtask1](https://docs.google.com/spreadsheets/d/1WvgNeT7zoMLT_dVXP6OGcbG25ZfNrIn3Qoo_-KSdGgU/edit?usp=sharing)__

### Subtask2
:point_right:__[Subtask2](https://docs.google.com/spreadsheets/d/17aXryVwC_KJjK_7fEQuUaFH9VVKCezWeL1D1ATz1mZs/edit?usp=sharing)__

### Subtask 3

_Why should we write test cases?_
- writing test cases is important step to improve application quality
- writing test cases helps us to check if application meets the requirements of the user
- helps to check the behavior of the application
- helps us to keep consistency in testing
- test cases are a source of informations about application for employees

### Subtask 4
:point_right:__[Subtask4](https://docs.google.com/spreadsheets/d/1uEOFUuitIedHFeNPdvG4jfgqO08rtomRUYHuNR1Rowo/edit?usp=sharing)__

# TASK3
### Subtask1and2
:point_right:__[Subtask1and2](https://docs.google.com/spreadsheets/d/19OnQ9t3O9w3JdfsiuvQA0RNu8N6oGHDR3pL6XjfZ5iU/edit?usp=sharing)__
### Subtask3
:point_right:__[Subtask3](https://docs.google.com/document/d/1hhjrp0n0Ihc8Z-Ac1N18rPhC7kWsmeCB4l8BnpVBySc/edit?usp=sharing)__
### Subtask4
:point_right:__[Subtask4](https://docs.google.com/spreadsheets/d/1trzIb7EJdjzk6x9bkMN0su0mnncNOVoKCWpnPeS5vZI/edit?usp=sharing)__

# TASK4
### Subtask1and2
:point_right:__[Subtask1and2](https://docs.google.com/spreadsheets/d/17WN1m9REmA11eijGD58Y2FtpVVNW4LAXqQRk99-HvD0/edit?usp=sharing)__

### Subtask3 ☺️

This application has been created for stressed people, parents, kids and everyone who take care about his mental health. In addition, this application can be helpful for people with depression, eating disorders, anxiety, neurosis etc. I think that this application could be a good supplement for sports and a healthy lifestyle. In my opinion that application is friendly for the user and interface looks nice. I would like to add new function to this app, like antistress games. Mobile app testing is more advanced than web ones. There are several web browsers, and there are plenty of smartphones and their software versions. Mobile apps looks diffrent than web applications.

### Subtask4
:point_right:__[Jira](https://halas2022.atlassian.net/jira/people/635d61a2c97f5473af70ea8a)__

# TASK5
### Subtask1
__👉SQL__
- SELECT
- SELECT DISCINT
- WHERE, AND, NOT, NULL
- TOP
- MIN, MAX, COUNT, AVG, SUM
- LIKE, BETWEEN
- ORDER BY (DISC, ASC)
- WILDCARDS CHARACTERS, ALIASES
- IN 
- INSERT INTO, DELETE, UPDATE

### Subtask3
👉 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
![2022-11-24_21h35_14](https://user-images.githubusercontent.com/115720724/203860045-cbc01de1-14bb-4db3-8974-2acb0ac6908a.png)

👉 2. Wyświetl film, który powstał w 2019 roku.
![2022-11-24_21h40_28](https://user-images.githubusercontent.com/115720724/203860440-f7ac578c-da84-4fab-8e39-706cb4f01647.png)

👉 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
![2022-11-24_21h43_57](https://user-images.githubusercontent.com/115720724/203860657-c9ab9cdf-f23b-46fe-8674-f53a262be7d6.png)

👉 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 
![2022-11-24_21h48_02](https://user-images.githubusercontent.com/115720724/203860944-d57d889f-a920-44d8-a135-3e7843096f6b.png)

👉 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

![2022-11-24_21h52_29](https://user-images.githubusercontent.com/115720724/203861320-88c6b16e-c910-4f04-be13-d43f44deac87.png)

:point_right: 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 
![2022-11-24_22h21_15](https://user-images.githubusercontent.com/115720724/203864531-af666a9b-9cda-4f34-a1fe-f9d282a8ba43.png)

👉 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 

![2022-11-24_22h24_48](https://user-images.githubusercontent.com/115720724/203864970-fef30e59-1879-4b54-8fc3-ede8c7134ace.png)

👉 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![2022-11-24_22h26_06](https://user-images.githubusercontent.com/115720724/203865103-1ea49c34-ede1-4d27-83ad-d94f5d7cc36d.png)

👉 9. Wyświetl dane klienta, który nie ma podanego adresu email.

![2022-11-24_22h28_15](https://user-images.githubusercontent.com/115720724/203865221-095129b6-88a1-4d17-8034-14175b68fffd.png)

👉 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

![2022-11-24_22h31_26](https://user-images.githubusercontent.com/115720724/203865510-6ca865e9-bbb6-4dc8-b271-2cd700070946.png)

# TASK6
### Subtask1

:point_right: 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈

![2022-12-02_11h07_53](https://user-images.githubusercontent.com/115720724/205268561-7c7546ff-2eb2-4a47-844d-d8b98e33d851.png)

:point_right: 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
![2022-12-02_13h56_05](https://user-images.githubusercontent.com/115720724/205297863-82acae8d-4065-4d0f-8ad8-d7ca3ad3bd20.png)


👉 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
![2022-12-02_12h29_15](https://user-images.githubusercontent.com/115720724/205283199-df43a667-8b05-46bf-9341-d0434ea1ffd7.png)

👉 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
![2022-12-02_15h28_03](https://user-images.githubusercontent.com/115720724/205315329-8f7d95fb-42df-464e-a07c-e38f3e1de1b9.png)


👉 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag


![2022-12-08_11h50_27](https://user-images.githubusercontent.com/115720724/206428400-d276029e-8519-4f8c-8ebf-ed6bc63f06ae.png)
![2022-12-08_11h50_36](https://user-images.githubusercontent.com/115720724/206428406-1afb2df7-5979-4e10-97e2-b9c7b7ab7155.png)


👉 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

![2022-12-02_16h38_53](https://user-images.githubusercontent.com/115720724/205330003-ad23ad72-1db3-4223-9eac-f45df63cef2a.png)

👉 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

![2022-12-02_16h48_21](https://user-images.githubusercontent.com/115720724/205331736-c68f8db6-6d53-44c2-9ba7-ecd99ea1956a.png)

👉 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).
![2022-12-02_17h08_38](https://user-images.githubusercontent.com/115720724/205335612-88e6d974-ed78-4763-9fff-51e6941b18b6.png)
![2022-12-02_17h08_51](https://user-images.githubusercontent.com/115720724/205335618-8e95ec61-7945-4be2-a737-55c17b657b33.png)

👉 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał
![2022-12-03_16h27_25](https://user-images.githubusercontent.com/115720724/205448697-4fdf95f9-e16b-4d1b-9ecd-f6f02101ae30.png)




👉 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email= honia@mail.com oraz pseudonym = Hoa


![2022-12-02_17h39_32](https://user-images.githubusercontent.com/115720724/205341712-3f4d9a56-395d-4f5a-b16a-5b8869f3391c.png)

![2022-12-02_17h39_45](https://user-images.githubusercontent.com/115720724/205341720-61854419-b2b8-424d-9be6-0403a863fe44.png)

### Subtask 2 - Test
![2022-12-02_18h53_17](https://user-images.githubusercontent.com/115720724/205355173-6fca5b21-dae2-4885-9aab-943428da7b27.png)





