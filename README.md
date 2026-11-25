# Ultimate 11 Draft

Gra przeglądarkowa: losujesz kraj, rok i pięć kart, składasz jedenastkę i wygrywasz turniej albo ligę.
Działa jak aplikacja na telefonie (PWA), także bez internetu.

## Jak to wrzucić na GitHub Pages

1. Zaloguj się na github.com i kliknij **New repository**. Nazwa np. `ultimate11`, widoczność **Public**.
2. Na stronie nowego repozytorium kliknij **uploading an existing file** i przeciągnij **wszystkie pliki z tego folderu**
   (`index.html`, `manifest.webmanifest`, `sw.js`, pliki `.png`, `.nojekyll`, `README.md`). Zatwierdź przyciskiem **Commit changes**.
3. Wejdź w **Settings, Pages**. W sekcji *Build and deployment* wybierz **Deploy from a branch**, gałąź **main**, folder **/ (root)**, i kliknij **Save**.
4. Po minucie lub dwóch strona będzie pod adresem `https://TWOJA-NAZWA.github.io/ultimate11/`.

## Instalacja na telefonie

- **Android (Chrome):** otwórz adres gry, menu z trzema kropkami, **Zainstaluj aplikację** (albo *Dodaj do ekranu głównego*).
  Aplikacja uruchomi się pełnoekranowo, w poziomie.
- **iPhone (Safari):** otwórz adres, przycisk Udostępnij, **Do ekranu początkowego**. Safari nie blokuje orientacji,
  więc obróć telefon ręcznie i wyłącz blokadę obrotu ekranu.

## Aktualizacja gry

Podmień `index.html` w repozytorium (**Add file, Upload files**) i w `sw.js` zmień wartość `VERSION`
(np. `u11-v10`). Telefon pobierze nową wersję przy następnym uruchomieniu z internetem.

## Uwagi

- Zapis gry (monety, ulepszenia, historia) jest w pamięci przeglądarki dla danego adresu. Zapis z innego adresu
  (np. z claude.ai) się nie przeniesie. Wyczyszczenie danych witryny w przeglądarce kasuje postęp.
- Czcionki ładują się z Google Fonts przy pierwszym uruchomieniu z internetem i są potem zapamiętane.
  Bez nich gra używa czcionek systemowych.
