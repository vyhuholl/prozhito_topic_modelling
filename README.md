Работа с хакатона центра Digital Humanities НИУ ВШЭ 17 января 2021 г.
### Авторы:
**Ольга Жукова** (гуманитарная экспертиза, таймлайн)<br>
*1 курс магистратуры Digital Humanities, НИУ ВШЭ*<br>
<br>
**Ольга Пичужкина** (обработка и визуализация данных)<br>
*4 курс бакалавриата "Фундаментальная и компьютерная лингвистика", НИУ ВШЭ*
<br>
# Цель исследования
Тематическое моделирование корпуса текстов: связь тем дневниковых записей с периодом времени написания.
# Данные
**Meet your dataset: дневниковые записи** [(источник)](https://t.me/c/1358367494/782)<br>
<br>
**Откуда у нас дневники?**<br>
Наши данные - это причёсанный дамп [сайта "Прожито"](https://prozhito.org) от апреля 2019 года. Таблицы содержит несколько сотен тысяч записей за большой отрезок времени (от XVIII до XXI века, преимущественно — XX век), так что вам будет, где развернуться ;).<br>
<br>
**Как устроен датасет?**<br>
У нас есть две таблицы, `whole_table.csv` и `whole_table_with_lemm.csv`. Вторая отличается наличием колонки c лемматизированными (т.е. с приведенными в начальную форму словами) mystem записями.<br>
В обеих таблицах есть колонки:
*   `notes` - содержит сами дневниковые записи
*   `dates` - дата записи в формате год/месяц/день
*   `id`  -  айдишник автора (не записи!)
*   `author` - имя автора записи
<br>

Практически все поля заполнены, у некоторых отсутствует дата (так как таблица отсортирована по датам, они в самом начале).<br>
*От авторов исследования: даты отформатированы как YYYY/(M)M/(D)D, отсутствовать могут день, месяц или год, отсутствующие элементы даты заменены нулями.*
# Результаты
[Таймлайн "Живые души XX века"](https://www.sutori.com/story/zhivyie-dushi-xx-vieka--LVLEntAwko13P3cmo1Chy9D8)<br>
Для просмотра нажмите на **Present**.
