App created during MegaK course. 
Its all about creating your tasty cookie using base, and adding additional ingredients.

Written in JS, express.js, handlebars and of course some html and css styling included.
Main focus was to be more familiar with backend operations and how everything works together.

Views, paths, partials, routers, data storage and cookies(files). All those topics was in this
project, so it was a lot of new things to lear and broaden my knowlegde.

Pretty happy with the result in general, and last but not least its going to be more and more uderstandable.
Cant wait to dive deeper in backends world.





******************************************************************
npm i express-handlebars@5.3.4 == gdyby handelbarsy nie dzialaly
to instalujemy
******************************************************************
pseudo kodzik
konfiguracja expressa
    -json nie jest konieczny poki nie uzywam fetcha
    -pliki ststyczne sie przydadza
    -cookie parser koniecznie
    - urlencoded /tradycyjny ormularz/ zbedny
    hbs'y potrzebne

sciezki statyczne
    -usuwamy index.html
    -css sie przyda
    -potrzebne grafiki

routes i moduly
    -configurator
    -home
    -order

widoki/sciezki
    -strona glowna
    -podziekowanie za dodanie dodatku
    -podziekowanie za usuniecie dodatku
    -podziekowanie za wybor spodu
    -strona bledu
    -podsumowanie koszyka
    -podziekowanie za zakupy

partiale
    -lista wybranych dodatkow i ich cen
    -podglad ciastka
    -powrot do str glownej

przechowywanie informacji o aktualnym zamóieniu
    -ciastko ze spodem== string
    -ciastko z dodatkami == tablica stringow=JSON

przechowywanie danyh o spodach, dodatkach
    -w pliku js beda 2 obiekty 1 ze spodami i 2 z dodatkami
    - w obiektach kluczem beda jeden ze spodami a drugim z dodatkami, a wartoscia beda ceny

sposob wyswietlania ciastka
    -div ze stala szer i wys ze wsawionymi wieloma obrazkami nalozonymi na siebie przez background
