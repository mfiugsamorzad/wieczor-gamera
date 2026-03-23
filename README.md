# Wieczór Gamera: MFI x Kinguin 🎮 - Landing Page

Repozytorium zawiera kod źródłowy strony docelowej (tzw. *Landing Page*) stworzonej specjalnie na e-sportowe wydarzenie integracyjne **Wieczór Gamera**, organizowane przez Radę Samorządu Studentów Wydziału Matematyki, Fizyki i Informatyki UG we współpracy z Kinguin Esports Lounge.

## 🎨 Design i Technologia
Strona została napisana w czystym HTML i CSS (bez użycia zewnętrznych frameworków). Jej układ opiera się na strukturze *One-Page* z płynnym przewijaniem (Smooth Scroll) do poszczególnych sekcji.

Szata graficzna została dopasowana do tematyki e-sportowej i plakatów promujących wydarzenie:
* **Tło:** Głęboki, fioletowo-czarny gradient (`#28003f` - `#000000`).
* **Akcenty:** Neonowy róż (`#EE3E8B`) oraz cyjan (`#01AEFF`).
* **Detale:** Złoto nawiązujące do League of Legends (`#E0B35B`).
* **Styl kart:** *Glassmorphism* (półprzezroczyste, rozmyte tła sekcji), idealnie wpisujące się w nowoczesny, gamingowy klimat.

## 📌 Struktura Strony
Strona podzielona jest na 4 główne sekcje informacyjne:
1. 🏆 **Turniej:** Informacje o głównym turnieju League of Legends (format 5v5, limit 8 drużyn).
2. 🕹️ **Integracja:** Strefa free-to-play (FIFA, Just Dance) oraz strefa kibica.
3. 📝 **Zapisy:** Szczegóły dotyczące wpisowego (15 zł/os.) oraz przycisk przekierowujący do oficjalnego formularza zapisów (Microsoft Forms).
4. 📍 **Informacje:** Czas (16.04.2026, 17:00), miejsce (Kinguin Esports Lounge, Galeria Metropolia) i benefity (bony na bar).

## 📁 Wymagane Pliki
Aby strona działała poprawnie, w głównym folderze repozytorium muszą znajdować się:
* `index.html` — główny plik z kodem strony.
* **Logotypy w formacie PNG z przezroczystym tłem (najlepiej białe):**
  * `UG_logo_RGB_pionowy_negatyw_bialy_achromatyczny_PL.png` (Uniwersytet Gdański)
  * `Logo MFI.png` (Wydział)
  * `logo-rss-biale.PNG` (RSS MFI)
  * `logo-kinguin.png` (Kinguin)

## ⚙️ Instrukcja Obsługi (Edycja Linków)

### Jak zaktualizować link do zapisów (w razie potrzeby)?
1. Otwórz plik `index.html` i kliknij ikonę ołówka.
2. Zjedź do sekcji `<div id="zapisy" ...>`.
3. Znajdź przycisk z aktualnym linkiem: 
   `<a href="https://forms.cloud.microsoft/e/032xZ6KUAk" target="_blank" class="cta-button">`
4. Jeśli w przyszłości zajdzie potrzeba zmiany formularza, podmień ten link w atrybucie `href` na nowy.
5. Zapisz zmiany (*Commit changes*).

### Jak zmienić link powrotny do głównej strony Samorządu?
1. W sekcji `<nav>` na samej górze kodu znajdź przycisk `class="back-link"`.
2. Zaktualizuj adres w atrybucie `href` na poprawny link Waszego repozytorium głównego.

## 🚀 Hosting
Strona jest hostowana całkowicie za darmo przy użyciu usługi **GitHub Pages**. Zmiany w kodzie są automatycznie publikowane pod przypisanym adresem URL w ciągu około minuty.

---
**Główny Organizator:** Rada Samorządu Studentów Wydziału Matematyki, Fizyki i Informatyki UG
**Kontakt:** samorzad.mfi@studms.ug.edu.pl | IG: [@mfiugsamorzad](https://instagram.com/mfiugsamorzad)
