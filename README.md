Тема домашней работы:	Выборка и агрегация данных в MongoDB.

Цель домашней работы:	Закрепить на практике основные приемы работы с СУБД MongoDB, включая выборку, сортировку, объединение, агрегацию данных и передачу результатов выборки в программу на Python в целях аналитики и дальнейшей обработки.

Формулировка задания	
В этом задании вам предстоит выполнить несколько запросов к базе данных для получения выборок по условиям, а также воспользоваться фреймворком агрегации MongoDB для построения конвейера обработки данных.

Что нужно использовать в работе над заданием	
MongoDB:
Зарегистрируйтесь в сервисе MongoDB Atlas.

Создайте кластер уровня M0 (это бесплатно).

Добавьте в кластер тестовую базу данных sample_mflix, используя опцию Load Sample Dataset.

В качестве альтернативы вы можете установить MongoDB на свой локальный компьютер и импортировать необходимые датасеты в свою СУБД, загрузив их по ссылке. Для этого подключитесь к своему серверу через Compass, создайте новую БД, создайте для каждого датасета коллекцию и щелкните «Add data» → «Import JSON or CSV file».

MongoDB Compass — в качестве вспомогательного инструмента для конструирования запросов и агрегаций.

Python и библиотека pymongo. Работа ведется в Jupyter Notebook или Google Colaboratory. Рекомендуется использовать версию Python 3.12.
