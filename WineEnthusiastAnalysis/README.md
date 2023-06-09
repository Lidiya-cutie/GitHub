# Знакомство с данными: винные обзоры

Дальнейший разбор инструментов и практические задания мы будем проводить на наборе данных из соревнования на *kaggle*.

Допустим, что после просмотра документального фильма о сомелье вы захотели создать прогностическую модель для оценки вин вслепую, как это делает сомелье.

Определив бизнес-задачу, вы перешли к сбору данных для обучения модели. После нескольких недель парсинга сайта [WineEnthusiast](https://www.wineenthusiast.com/) вам удалось собрать около 130 тысяч строк обзоров вин для анализа и обучения.
Вот какие признаки вам удалось собрать:

* **country** — страна-производитель вина.
* **description** — подробное описание.
* **designation** — название виноградника, где выращивают виноград для вина.
* **points** — баллы, которыми WineEnthusiast оценил вино по шкале от 1 до 100.
* **price** — стоимость бутылки вина.
* **province** — провинция или штат.
* **region_1** — винодельческий район в провинции или штате (например Напа).
* **region_2** — конкретный регион. Иногда в пределах винодельческой зоны указываются более конкретные регионы (например Резерфорд в долине Напа), но это значение может быть пустым.
* **taster_name** — имя сомелье.
* **taster_twitter_handle** — твиттер сомелье.
* **title** — название вина, которое часто содержит год и другую подробную информацию.
* **variety** — сорт винограда, из которого изготовлено вино (например Пино Нуар).
* **winery** — винодельня, которая производила вино.