### Задача № 5
** Работа с python. **

Пишем простой сайт. Больше не будем использовать самописные серверы, а используем: https://docs.python.org/3/library/http.server.html

Верстка на сайте самая элементарная.

Бэкенд должен быть красивый, читаемый, простой и понятный.

Сайт должен умет делать CRUD для таблицы table_task1.

Это может быть одна страница на которой отображаются все записи из этой таблицы, а также элементы управления для удаления, вставки новых записей, и изменения существующих записей.

На сайте есть кнопка позволяющая загрузить файл. Загружать будем файл table_task1.csv

После загрузки файла, таблица ОТЧИЩАЕТСЯ полностью, затем в неё заново из файла записываются данные.

Конечно же URL routing который вы выберете для обработки действий на бэкенде должны быть адекватным, так если ваш сайт поднимается например на http://192.168.0.1/ то для удаления отправляется get запрос на http://192.168.0.1/delete/...., а например для редактирования POST запрос на http://192.168.0.1/update/

Результат складываем в day9/task5/

Удачи)