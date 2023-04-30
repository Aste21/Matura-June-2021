# Matura-June-2021
Matura June 2021

Task:


    Zadanie 4. Schowane napisy
W pliku napisy.txt znajduje się 1000 wierszy po 50 znaków (dużych liter angielskiego
alfabetu oraz cyfr).
Napisz program(y), który(e) da(dzą) odpowiedzi do poniższych zadań. Odpowiedzi zapisz
w pliku wyniki4.txt, a każdą odpowiedź poprzedź numerem oznaczającym odpowiednie
zadanie.
Uwaga: Plik przyklad.txt zawiera dane przykładowe spełniające warunki zadania.
Odpowiedzi dla danych z pliku przyklad.txt są podane pod pytaniami.


    Zadanie 4.1. (0–2)
Podaj łączną liczbę cyfr we wszystkich napisach z pliku napisy.txt.
Dla danych z pliku przyklad.txt wynikiem jest: 46504


    Zadanie 4.2. (0–2)
W pliku napisy.txt ukryto pewne pięćdziesięcioznakowe hasło w następujący sposób:
– w co dwudziestym wierszu (w wierszach o numerach 20, 40, 60, …, 1000), ukryto dokładnie
jedną literę hasła;
– ukryta litera w kolejnych wierszach zawsze znajduje się na innej pozycji: w 20 wierszu na
pierwszej, w 40 wierszu na drugiej, w 60 wierszu na trzeciej, …, w 1000 na pięćdziesiątej.
Podaj to hasło.
Dla danych z pliku przyklad.txt wynikiem jest:
UDALOSIEIZDAJEMYEGZAMINYMATURALNEZWIELUPRZEDMIOTOW


    Zadanie 4.3. (0–4)
Palindromem nazywamy napis, który czytany od początku lub od końca jest taki sam (np.
KAJAK). Część napisów zapisanych w wierszach pliku (każdy ma 50 znaków) można w prosty
sposób – przez dodanie dokładnie jednego znaku na początku lub na końcu napisu – zamienić
na palindrom.
Podaj hasło utworzone przez środkowe litery tak utworzonych palindromów.
Dla danych z pliku przyklad.txt wynikiem jest: INFORMATYKA


    Zadanie 4.4. (0–4)
Ostatnie z haseł zostało ukryte w cyfrach zapisanych w pliku napisy.txt. Aby je odczytać,
należy cyfry z każdego wiersza pogrupować po dwie, pomijając ostatnią, jeśli w wierszu jest
nieparzysta liczba cyfr. Jeżeli liczba utworzona przez parę cyfr jest mniejsza od 65 lub większa
od 90, to ją pomijamy, w przeciwnym przypadku taką liczbę zamieniamy na znak o kodzie
ASCII odpowiadającym tej liczbie. Poszukiwanie hasła kończy się po otrzymaniu trzech
kolejnych znaków „X”. Odczytaj z pliku tak ukryte hasło.
Dla danych z pliku przyklad.txt wynikiem jest: NAPISANIEMATURYXXX
