# Zadanie egzaminacyjne

Wykonaj aplikację internetową salonu fryzjerskiego, wykorzystując pakiet XAMPP oraz edytor zaznaczający składnię.

Do zadania dołączono archiwum ZIP o nazwie pliki3 zabezpieczone hasłem: `XSaloon[Fryz]`

Archiwum należy rozpakować. Na pulpicie należy utworzyć folder. Jako nazwy folderu należy użyć numeru zdającego (jest to Twój numer PESEL). Rozpakowane pliki należy umieścić w tym folderze. Po skończonej pracy wszystkie wyniki należy zapisać w tym folderze.

## Operacje na bazie danych

Do wykonania operacji na bazie danych należy wykorzystać tabele `uslugi` i `kadra` przedstawione na `rysunku 1`
W tabeli `uslugi` znajduje się pole `rodzaj`, które przyjmuje wartości: `1 – usługi kosmetyczne`, `2 – usługi
fryzjerskie`, `3 – inne`.

**_Rys. 1: Baza danych_**\
![Baza danych](https://ckziu2.edu.pl/programista/arkusze/inf-03/praktyczny-03/baza-zadanie-3.jpg)

Wykonaj operacje na bazie danych:

1. Utwórz bazę danych o nazwie `fryzjer`
2. Do bazy `fryzjer` zaimportuj tabele z pliku `egzamin3.sql` z rozpakowanego archiwum
3. Wykonaj zrzut ekranu po imporcie. Zrzut zapisz w formacie `PNG` pod nazwą `import`. Nie kadruj zrzutu.
   Zrzut powinien obejmować cały ekran monitora, z widocznym paskiem zadań. Na zrzucie powinny być
   widoczne elementy wskazujące na poprawnie wykonany import tabel
4. Wykonaj zapytania SQL działające na bazie `fryzjer`. Zapytania zapisz w pliku `kwerendy.txt`. Wykonaj
   zrzuty ekranu przedstawiające wyniki działania kwerend. Zrzuty zapisz w formacie `JPEG` i nadaj im
   nazwy `kw1`, `kw2`, `kw3`, `kw4`. Zrzuty powinny obejmować cały ekran monitora, z widocznym paskiem
   zadań oraz zawierać wykonane zapytania

    - **Zapytanie 1**: wybierające jedynie pola `imie`, `nazwisko`, `stanowisko` z tabeli `kadra` dla pracowników
      na stanowisku `fryzjer` albo `stylista`
    - **Zapytanie 2**: liczące liczbę usług fryzjerskich oraz wskazujące najwyższą cenę usług fryzjerskich
    - **Zapytanie 3**: wybierające nazwy usług oraz przypisane do nich imiona osób z tabeli `kadra` dla rodzaju
      usług: `fryzjerskie` albo `inne`, należy posłużyć się relacją
    - **Zapytanie 4**: dodające kolumnę do tabeli usługi o nazwie `opinia` typu napisowego

## Witryna internetowa

**_Rys. 2: Strona index.html, kursor znajduje się nad wierszem tabeli_**\
![Witryna internetowa](https://ckziu2.edu.pl/programista/arkusze/inf-03/praktyczny-03/strona.jpg)

### Przygotowanie grafiki:

1. Plik `obraz1.jpg`, wypakowany z archiwum, należy przeskalować z zachowaniem proporcji tak, aby jego
   szerokość wynosiła dokładnie `250px`
2. Plik `obraz2.jpg`, wypakowany z archiwum, należy przeskalować z zachowaniem proporcji tak, aby jego
   szerokość wynosiła dokładnie `650px`

### Cechy witryny

1. Składa się ze stron o nazwach `index.html` oraz `fryzura.html`. Obie strony różnią się jedynie drugim
   blokiem lewym

### Cechy wspólne dla obu stron

1. Strony `index.html` i `fryzura.html` zapisane w języku `HTML 5`
2. Ustawiony język zawartości strony na polski
3. Jawnie zastosowany właściwy standard kodowania polskich znaków
4. Tytuł strony widoczny na karcie przeglądarki: `Fryzjerstwo`
5. Arkusz stylów w pliku o nazwie `styl.css` prawidłowo połączony z kodem strony
6. Podział strony na bloki: trzy bloki po lewej stronie i dwa po prawej, poniżej stopka. Podział zrealizowany
   za pomocą znaczników sekcji tak, aby po uruchomieniu w przeglądarce wygląd układu bloków był zgodny z rysunkiem 2
7. Zawartość pierwszego bloku po lewej stronie:
    - nagłówek pierwszego stopnia o treści `SALON FRYZJERSKI`, który jest odnośnikiem do strony `index.html`
8. Zawartość pierwszego bloku po prawej stronie:
    - nagłówek czwartego stopnia o treści `Ceny strzyżenia`, który jest odnośnikiem do strony `fryzura.html`
    - tabela o pięciu wierszach i dwóch kolumnach, w pierwszym wierszu znajdują się komórki nagłówkowe. Tabela jest zgodna z `Tabelą 1` arkusza egzaminacyjnego
9. Zawartość drugiego bloku po prawej stronie:
    - obraz o nazwie `obraz1.jpg` z tekstem alternatywnym `Fryzjerka`
10. Zawartość trzeciego bloku po lewej stronie:
    - akapit (paragraf) o treści: `Witaj! Miło nam, że odwiedziłeś nasz salon. Sprawdź promocje!`
    - nagłówek czwartego stopnia o treści `Kontakt: 444 555 666`
11. Zawartość stopki:
    - akapit (paragraf) o treści `Autor: `, dalej wstawiony numer zdającego
12. Zawartość drugiego bloku po lewej stronie dla strony `index.html`:
    - obraz o nazwie `obraz2.jpg` z tekstem alternatywnym `Strzyżenie`
13. Zawartość drugiego bloku po lewej stronie dla strony `fryzura.html` (rysunek 3):
    - nagłówek drugiego stopnia o treści `PROMOCJA!`
    - cztery pola `radio`, jedno pod drugim, z podpisami: `Krótkie`, `Średnie`, `Półdługie`, `Długie`. W danym
      momencie tylko jedno pole `radio` może być zaznaczone
    - Poniżej przycisk o treści „Odkryj promocję”, którego wciśnięcie powoduje wykonanie skryptu

**_Tabela 1:_**

| Długość włosów | Cena |
|:---------------|:-----|
| Krótkie        | 25   |
| Średnie        | 30   |
| Półdługie      | 40   |
| Długie         | 50   |

**_Rys. 3: Drugi blok lewy strony fryzura.html_**\
![Formularz](https://ckziu2.edu.pl/programista/arkusze/inf-03/praktyczny-03/formularz.jpg)

### Styl CSS witryny internetowej

Styl CSS zdefiniowany w całości w zewnętrznym pliku o nazwie `styl.css`. Arkusz CSS zawiera formatowanie:

1. Ustawione domyślne wartości dla wszystkich selektorów stylu CSS: krój czcionki `Garamond`, wyrównanie tekstu do środka
2. Wspólne dla wszystkich bloków lewych: szerokość `72%`
3. Dla pierwszego lewego bloku: kolor tła `#795548`, rozmiar czcionki `170%`
4. Dla drugiego lewego bloku: wysokość `400px`
5. Wspólne dla obu prawych bloków: kolor tła `#BCAAA4`, kolor czcionki `#795548`, wysokość `400px`, szerokość `28%`
6. Dla stopki: kolor tła `#795548`, biały kolor czcionki, marginesy wewnętrzne `20px`
7. Dla selektora tabeli: marginesy zewnętrzne wyliczane automatycznie przez przeglądarkę, szerokość `80%`, obramowanie linią ciągłą o szerokości `1px` i kolorze `#795548`
8. W momencie, gdy kursor znajduje się na wierszu tabeli, jego tło zmienia się na `Sienna`, a kolor czcionki na biały
9. Dla selektora nagłówka czwartego stopnia: rozmiar czcionki `200%`
10. Dla selektora obrazu: marginesy wewnętrzne `20px`, zaokrąglenie rogów `40px`
11. Dla selektora odnośnika: biały kolor czcionki
12. Dla pola radio: marginesy zewnętrzne `7px`

> _**UWAGA:** style CSS dla tabeli, nagłówka czwartego stopnia, obrazu oraz odnośnika należy zdefiniować wyłącznie przy pomocy selektora dla znaczników tabeli, nagłówka czwartego stopnia, obrazu oraz odnośnika. Jest to uwarunkowane projektem późniejszej rozbudowy witryny._

## Skrypt

Wymagania dotyczące skryptu:

1. Napisany w języku wykonywanym po stronie przeglądarki
2. Należy stosować znaczące nazewnictwo zmiennych i funkcji w języku polskim lub angielskim
3. Uruchamia się po wciśnięciu przycisku na stronie `fryzura.html`
4. Na podstawie wybranego przycisku radio wyświetla promocyjną cenę strzyżenia
5. Cena promocyjna jest o `10 zł` niższa od ceny strzyżenia zawartej w `Tabeli 1`
6. Wynik działania wyświetla się w akapicie pod przyciskiem według wzoru: `cena promocyjna: <wartość>`, gdzie `<wartość>` oznacza obliczoną cenę

> _**UWAGA:** po zakończeniu pracy utwórz w folderze z numerem zdającego plik tekstowy o nazwie `przeglądarka.txt`. Zapisz w nim nazwę przeglądarki internetowej, w której weryfikowana była poprawność działania witryny. Prześlij pliki z wynikami pracy. Przesłane powinny zostać następujące pliki: `fryzura.html`, `import.png`, `index.html`, `kw1.jpg`, `kw2.jpg`, `kw3.jpg`, `kw4.jpg`, `kwerendy.txt`, `obraz1.jpg`, `obraz2.jpg`, `przeglądarka.txt`, `styl.css`, ewentualnie inne przygotowane pliki._

## Ocenie będzie podlegać 5 rezultatów:

1. operacje na bazie danych
2. zawartość witryny internetowej
3. działanie witryny internetowej
4. styl CSS witryny internetowej
5. skrypt
