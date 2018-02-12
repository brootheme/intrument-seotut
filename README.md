# Набор инструментов и ссылок
Документация по markdown [docs.modx.pro](https://docs.modx.pro/) и офф вариант [DaringFireBall](https://daringfireball.net/projects/markdown/)

Навигация по файлу:

1. JQuery
2. [Хорошие решения](https://github.com/seotut/intrument-seotut/blob/master/README.md#%D0%A5%D0%BE%D1%80%D0%BE%D1%88%D0%B8%D0%B5-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F)
> 2.1. Полезные сервисы
# JQuery
### Библиотеки и решения
* [niceSelect](http://hernansartorio.com/jquery-nice-select/) - делает красивый селект (выпадающий список)
* [searchable select](https://www.jqueryscript.net/form/jQuery-Plugin-For-Custom-Searchable-Select-List-Customselect.html) - поиск в селекте (выпадающем списке) 
* [slick-slide](http://kenwheeler.github.io/slick/) - адаптивный слайдер с множеством функций
* [magnific-popup](http://dimsemenov.com/plugins/magnific-popup/) - всплывающие окна
* [smartmenus](https://www.smartmenus.org/about/themes/) - адаптивное меню с удобной мобильной реализацией
* [sweetalert](https://github.com/t4t5/sweetalert) и [DEMO](https://sweetalert.js.org/) - красивые всплывающие уведомления
* [rangeslider](http://ionden.com/a/plugins/ion.rangeslider/) - и [DEMO](http://ionden.com/a/plugins/ion.rangeSlider/demo.html) красивый слайдер диапозонов
* [customScrollBar](https://github.com/malihu/malihu-custom-scrollbar-plugin) и [DEMO](http://manos.malihu.gr/repository/custom-scrollbar/demo/examples/complete_examples.html) - множество скролл баров
* [animateCSS](https://github.com/daneden/animate.css) - Анимации элементов сайта, лучше использовать с WOW (ниже)
* [WOW](https://github.com/matthieua/WOW) - запуск после попадания в область видимости
* [SPIN](http://spin.js.org/) - Создает SPIN (прелоадер круговой)
## Обжимание изображений
#### Онлайн сервисы
* [TinyJpg](https://tinyjpg.com/) - для jpg изображений
* [TinyPng](https://tinypng.com/) - для png изображений
## Полезные сервисы
* [CodePen.io](https://codepen.io/) - наборы pen'ов с готовыми примерами
* [FlatIcon.com](https://www.flaticon.com/) - наборы готовых иконок, в том числе и с svg
* [w3school](https://www.w3schools.com/howto/default.asp) - набор готовых элементов
* [301 редирект](https://web-optimizator.com/301-redirekt-htaccess/) - набор редиректов на все случаи жизни
* [phx](https://gaserge.ru/blog/modx-revolution/filtryi-phx-(-modifikatoryi-)-v-modx-revo.html) - примеры phx модификаторов
* [тестирование производительности хостинга](https://tools.lite.company/performance/) - скачать файл и поместить в корень сайта, при запуске вывдет информацию о железе хостинга
## Дополнения к MODX
#### Базовый репозиторий
* [Ace](https://modstore.pro/packages/content/ace) - редактор кода с подсветкой
* Translite - ЧПУ для страниц сайта
* pdoTools [Doc](https://docs.modx.pro/components/pdotools/) - набор инструментов на все случаи жизни
* MIGX [Рус Doc](https://webstool.ru/documentation-migx-russian.html)- Создание контента по статичной форме (идеален для слайдера)
* [deBugParser](https://docs.modx.pro/components/debugparser) - вывод информации о работе страницы (все вызова и время их обработки) нужен для отлова тормозящих элементов 
* ClientConfig - управление статичными элементами сайта для обновления (удобно для номеров телефонов, контактов)
* Collections - вывод дочерних ресурсов в табличном представлении (ресурсы не отображаются в дереве) - удобно для новостей, но так же можно использовать и для услуг - в таком виде удобно кастомизировать таблицу и обновлять часть полей, не заходя в ресурс (цены, сроки)
* ControlErrorLog [Doc](https://modzone.ru/documentation/controlerrorlog.html)- вывод лога ошибок в верхнем меню с просмотром в всплывающем окне
* image+ - компонент для обрезания изображения по выделенной области (как аватарки в вк)
* [admintools](https://modstore.pro/packages/utilities/admintools) [docs](https://modzone.ru/documentation/admintools.html) - компонент для улучшения админ панели - вывод ссылку на шаблон при редактировании ресурса, позволяет добавить в избранное часто редактируемые чанки, заметки, авторизация в админке через e-mail, цветовая схема админки
* modDevTools - компонент для ввода хлебнх крошек + выводит чанки, которые использутся в шаблоне (ВНИМАНИЕ - есть конфликт с admintools)
* pThumb - более удобный компонент для вывода обрезанных или уменьшенных изображений (содержит параметры для указания угла обрезки) и водяного знака, альтернативные phpthumb(of) ([on](https://modstore.pro/packages/photos-and-files/phpthumbon) чуть поновее)
#### Российский репозиторий [modstore.pro](https://modstore.pro/)
* [AdminPanel](https://modstore.pro/packages/utilities/adminpanel) - редактирование страницы после авторизации в админке
* DateAgo - вывод даты используя форматы "5 минут назад", "час назад" и д.р.
* [ms2Gallery](https://modstore.pro/packages/photos-and-files/ms2gallery) [Doc](https://docs.modx.pro/components/ms2gallery/) - для создания 1 галереи на странице
* [minifyX](https://modstore.pro/packages/utilities/minifyx) - сжатие css и js в 1 файл много параметров
* [ajaxSnippet](https://modstore.pro/packages/utilities/ajaxsnippet) - запуск любых сниппетов через ajax
### Хорошие решения
* [Контроль кэша css и js](https://webstool.ru/kak-kontrolirovat-kesh-css-i-skriptov.html) - через сниппет проверяем хеш-файла (так делают многие гиганты интернета, чтобы не заставлять юзеров жать ctrl + f5)
* Формы обратной связи (чтоы использовать отдельные компоненты системы) [webstool](https://webstool.ru/feedbackform.html) - пока не рассмотрел :-), [itChief](https://itchief.ru/lessons/php/pop-up-feedback-form#comment-5306) - выгрузка форм из одного файла, [WebDesignMaster](https://webdesign-master.ru/blog/tools/578.html) - любое кол-во полей
### Расширения для Google Chrome
* 
* [Топвизор](Топвизор) - нумерация позиий сайтов в поисковой выдаче, бытрый переход к проектам, апометру и API
