# SensorMonitor

getFromCOM - сервер. Слушает СОМ порт, записывает в базу, а так же держит ServerSocket и отвечает пока на один запрос(средние данные за последние 7 дней для данного пользователя)

SensorMonitor - клиент. Отображает список датчиков и их показатели. Ведётся работа над общением с сервером и заполнением главной страницы.
