# TASK 1
### Subtask 1
Ilość punktów: 9/10 :blush:
### Subtask 3
Cześć! Jestem Jowita, mam 29 lat i trójkę małych dzieci, którym całkowicie się poświęciłam. Teraz przyszedł czas na mnie, znalazłam swoją drogę, którą chcę podążać i liczę na to, że niedługo pójdę do swojej pierwszej, wymarzonej pracy (Dokładnie tak, pierwszej w życiu. Wcześniej studiowałam, trochę błądziłam słuchając sugestii innych bardziej niż siebie, następnie założyłam rodzinę). Swoją naukę rozpoczęłam od rozmów z koleżanką, opowiadała mi dużo o swojej pracy jako testerka, wysłała mi Sylabusa od którego zaczęłam, następnie przeczytałam parę książek dotyczących tego zawodu, korzystałam i korzystam nadal z przeróżnych materiałów dostępnych na internecie i się "wkręciłam". Dlaczego wybrałam ten kurs? Przede wszystkim po to, by _poszerzyć_ swoją wiedzę i _nauczyć się dobrych praktyk_, nie chcę wyrabiać w sobie złych nawyków. Wierzę, że wyjdę z tego kursu pewniejsza siebie i gotowa na dalszą naukę i rozwój. Jestem bardzo podekscytowana 😄
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
- Sprawdziłam działanie aplikacji zmieniając sieć na wolną 3G oraz szybką 3G, na tej wolniejszej sieci oczekiwanie na otwarcie strony jest dość długie.
- W emulatorze urządzeń na IPhonie 12 Pro, Samsungach funkcja przewijania informacji o zawodniku nie działa jak powinna. Po obróceniu ekranu już lepiej to wygląda.



 

