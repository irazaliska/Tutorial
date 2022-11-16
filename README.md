# Tutorial

Cлайдер реалізується на дівах:
(div>div*4>img+p наприклад).

Заходимо на бібліотеку https://kenwheeler.github.io/slick/
Вибираємо вид слайдера.
Копіюємо скрипт, вставляємо у файл slider.js
Прописуємо клас для загального діву.
Підключаємо скрипт перед закриваючим тегом </body> <script src=
На сайті бібліотеки скролимо вниз до View on GitHub https://github.com/kenwheeler/slick/
Копіюємо два лінка для head перед стилями. 
Just add a link to the css file in your <head>:

<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>

Копіюємо ще один лінк і ставимо перед закриваючим тегом body та script  src
Then, before your closing <body> tag add:

<script type="text/javascript" src="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

Далі повертаємось на Slick, шукаємо вікно з jquery, копіюємо два посилання і ставимо перед закриваючим тегом боді та попередніми скриптами:

<script type="text/javascript" src="//code.jquery.com/jquery-1.11.0.min.js"></script>
 <script type="text/javascript" src="//code.jquery.com/jquery-migrate-1.2.1.min.js"></script>

Відкриваємо слайдер у браузері та через інструменти розрозбника дивимось стилізацію елементів. Копіюємо стилі у свій проект, змінюємо властивості.
