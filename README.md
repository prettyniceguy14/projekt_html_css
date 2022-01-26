# Projekt zaliczeniowy HTML i CSS

Projekt na zaliczenie części **HTML i CSS** z laboratorium **Technologie Internetowe**.

Uniwersytet Rzeszowski, Informatyka I st. II rok sem. zimowy

Wykonał: **Karol Bobowski**

Link do działającej wersji strony: https://prettyniceguy14.github.io/projekt_html_css/index.html

> **Tworząc wygląd strony wzorowałem się na: https://www.behance.net/gallery/70471695/iMediaLab-Tech-Blog-Magazine**

---

## Opis projektu

Projekt przedstawia przykładową reprezentację dla strony typu blog o tematyce technologicznej. Na stronie głównej omawianej witryny przedstawiane są nowinki z branży tech wraz ze zdjęciami, nagłówkami i krótkimi opisami jako posty w trzech kolumnach jeden pod drugim. Z każdego postu po kliknięciu nagłówek zostajemy przeniesieni na podstronę, gdzie znajduje się rozwinięcie danego postu/tematu/dyskusji. Strona zawiera również panel logowania, jak i rejestracji na kolejnych podstronach.

## Struktura projektu

Strona składa się z czystego HTML i CSS bez użycia jakichkolwiek bibliotek czy też gotowych komponentów.

Zawartość plików i katalogów:

> `index.html` - strona główna z listą najnowszych postów.

> `article.html` - podstrona z rozwinięciem danego tematu postu.

> `login.html` - podstrona z logowaniem.

> `register.html` - podstrona z rejestracją.

> `../css/` - katalog zawierający plik/pliki **.css**

> `../img/` - katalog zawierający wszystkie grafiki umieszczone na stronie.


- Strona główna (`index.html`) składa się z:
    - Nawigacji z logiem, wyszukiwarką i odnośnikiem do panelu logowania. Oraz karuzeli z odnośnikami do ostatnich newsów/postów w formie nagłówka.
    - Sekcję głównej zawierającej poszczególne posty posortowane wg. kategorii 'najpopularniejsze' i 'najnowsze' wraz z możliwością wybrania konkretnego roku i dodania nowego postu.
    - Stopkę, która zawiera przycisk do kontaktu, sitemapę oraz sekcje z informacjami o samej stronie.
<br /><br />
- Podstrona artykułu/postu (`article.html`) składa się z:
    - Nawigacji z logiem, wyszukiwarką i odnośnikiem do panelu logowania.
    - Zdjęcia związanego z danym postem w większej rozdzielczości.
    - Sekcji z nagłówkiem i dokładnym opisem postu.
<br /><br />
- Podstrona z logowaniem (`login.html`) składa się z:
    - Nawigacji z logiem.
    - Formularza z polem tekstowym na login i hasło oraz przycisku submit.
<br /><br />
- Podstrona z rejestracją (`register.html`) składa się z:
    - Nawigacji z logiem.
    - Formularza z polem tekstowym na login, hasło, weryfikacje hasła i email oraz przycisku submit.    
<br /><br />

Strona kodowana zgodnie ze standardem `UTF-8` z użyciem semantycznych znaczników z `HTML5`.

### Strona jest w pełni zgodna ze standardami W3C:

> https://validator.w3.org/nu/?doc=https%3A%2F%2Fprettyniceguy14.github.io%2Fprojekt_html_css%2Findex.html

> https://validator.w3.org/nu/?doc=https://prettyniceguy14.github.io/projekt_html_css/article.html

> https://validator.w3.org/nu/?doc=https://prettyniceguy14.github.io/projekt_html_css/login.html

> https://validator.w3.org/nu/?doc=https://prettyniceguy14.github.io/projekt_html_css/register.html


## Prawa autorskie do zdjęć:
Zdjęcia pochodzą ze strony https://unsplash.com/

Na podstawie licencji: https://unsplash.com/license

- All photos can be downloaded and used for free

- Commercial and non-commercial purposes

- No permission needed (though attribution is appreciated!)

Linki do zdjęć:
> **bg.jpg** - https://unsplash.com/photos/mP7aPSUm7aE

> **cactus.jpg** - https://unsplash.com/photos/UzPbvwqvKNE

> **camera.jpg** - https://unsplash.com/photos/rBY_CjoyItM

> **headphones.jpg** - https://unsplash.com/photos/cZWZjymwI9o

## UI / Wygląd Desktop

![prettyniceguy14 github io_projekt_html_css_index html](https://user-images.githubusercontent.com/84191672/149358525-92fe2913-1744-4d15-888d-43bd8eedf5b2.png)

![prettyniceguy14 github io_projekt_html_css_article html](https://user-images.githubusercontent.com/84191672/149358717-1434743e-30fc-4875-923b-272981bab3ea.png)

![prettyniceguy14 github io_projekt_html_css_login html](https://user-images.githubusercontent.com/84191672/149359027-24e3f14b-358f-42e6-8c78-06316219f954.png)

![prettyniceguy14 github io_projekt_html_css_register html](https://user-images.githubusercontent.com/84191672/149359174-1d4b96d9-56a3-4094-90cf-481f2318e524.png)


## UI / Wygląd Mobile

![Screen Shot 2022-01-13 at 17 54 16-fullpage](https://user-images.githubusercontent.com/84191672/149373956-a7305def-439b-4c35-b489-3ffae02f846d.png)

![Screen Shot 2022-01-13 at 17 55 05-fullpage](https://user-images.githubusercontent.com/84191672/149374057-9f598f0b-2cb1-4630-be35-3e0e942e1ee2.png)

![Screen Shot 2022-01-13 at 17 55 27-fullpage](https://user-images.githubusercontent.com/84191672/149374111-40202487-d675-40cc-9396-6da3517231c4.png)

![Screen Shot 2022-01-13 at 17 55 50-fullpage](https://user-images.githubusercontent.com/84191672/149374228-4ebc7db5-f86e-4be1-95c0-9e94ad36e82a.png)
