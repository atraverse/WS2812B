# WS2812B
Бібліотека для роботи з світлодіодами WS2812B за допомогою STM32F4xx

**WS2812B** – це RGB LED стрічка з піксельною адресацією. В основному світлодіоди з піксельною адресацією використовуються для різних динамічних світлоустановок, наприклад, динамічна підсвітка дисплеїв.
На модулі розташований один ультраяскравий RGB світлодіод NeoPixel. Модулі можна з’єднувати між собою - вихід одного просто з’єднується із входом наступного і для керування ланцюгом необхідно використати лише один пін контролера. У порівнянні з іншими схожими рішеннями, ці модулі надзвичайно компактні, за рахунок чого їх можна розмістити майже будь-де.

>**Технічні характеристики**
>* Вхідна напруга: DC 5 В;
>* Потужність: 9 Вт / м (30 світлодіодів / м), 18 Вт / м (60 світлодіодів / м);
>* Сіра шкала: 256;
>* FPC розмір: ширина - 10 мм, висота -  2,5 мм;
>* FPC колір: чорний / білий;
>* Ступінь захисту: IP30;

Проект був створений за допомогою CUBE MX. Процес підключення та створення проекту описанно у файлі "CUBE_MX.pdf" 
Опис самої реалізації знаходиться в "Realization.pdf"
Загальна документації на українській мові "Description.pdf"

**Офіційна документація** -  <https://cdn-shop.adafruit.com/datasheets/WS2812.pdf>
\\Проект виконали: Траверсе Анастасія, Гайда Анна, Штохман Юра.
