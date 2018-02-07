# Набор инструментов и ссылок
Документация по markdown [docs.modx.pro](https://docs.modx.pro/) и офф вариант [DaringFireBall](https://daringfireball.net/projects/markdown/)

Навигация по файлу:
[Хорошие решения](https://github.com/seotut/intrument-seotut/blob/master/README.md#%D0%A5%D0%BE%D1%80%D0%BE%D1%88%D0%B8%D0%B5-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F)


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
