Домашнее задание к занятию 12.3 "Реляционные базы данных: SQL. Часть 1"
Домашнее задание нужно выполнить на Dataset из презентации.

Решение нужно прислать одним SQL файлом, содержащим запросы по всем заданиям.

Задание можно выполнить как в любом IDE, так и в командной строке.

# Задание 1.
Получите уникальные названия районов из таблицы с адресами, которые начинаются на “K” и заканчиваются на “a”, и не содержат пробелов.
___
**Ответ:**

![Снимок экрана от 2022-10-20 21-38-23](https://user-images.githubusercontent.com/94833070/197266500-e7d1d9a9-2f45-4b64-a40a-4a3621596262.png)


# Задание 2.
Получите из таблицы платежей за прокат фильмов информацию по платежам, которые выполнялись в промежуток с 15 июня 2005 года по 18 июня 2005 года включительно, и стоимость которых превышает 10.00.
___
**Ответ:**

![Снимок экрана от 2022-10-20 22-57-50](https://user-images.githubusercontent.com/94833070/197266685-3b3d621e-48f0-4921-a933-f382ea496493.png)


# Задание 3.
Получите последние 5 аренд фильмов.
___
**Ответ:**

![Снимок экрана от 2022-10-20 23-26-20](https://user-images.githubusercontent.com/94833070/197267075-9cd3ab96-3908-4398-8f81-c88854f1d889.png)


# Задание 4.
Одним запросом получите активных покупателей, имена которых Kelly или Willie.

Сформируйте вывод в результат таким образом:

все буквы в фамилии и имени из верхнего регистра переведите в нижний регистр,
замените буквы 'll' в именах на 'pp'
___
**Ответ:**

![Снимок экрана от 2022-10-22 00-48-37](https://user-images.githubusercontent.com/94833070/197267199-92f83d4b-80b2-44a6-93fd-d409732dc574.png)



# Дополнительные задания (со звездочкой*)
Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

# Задание 5*.
Выведите Email каждого покупателя, разделив значение Email на 2 отдельных колонки: в первой колонке должно быть значение, указанное до @, во второй значение, указанное после @.

# Задание 6.*
Доработайте запрос из предыдущего задания, скорректируйте значения в новых колонках: первая буква должна быть заглавной, остальные строчными.