# Diplom
Задача проекта - автоматизировать тесты из финального проекта
Для автоматизации было выбрано 5 UI и 5 API тестов, тестировался сайт "Кинопоиск"

# Структура проекта
test_API - Автоматизировалось 5 запросов Запрос на поиск фильмов по 2024 году, запрос на поиск фильмов по ID,
запрос на поиск фильмов по имени, запрос на поиск актера, запрос на поиск рецензии 

test_UI - Автоматизировалось 5 тестов: Поиск фильма по названию, по спецсимволам, по полному названию фильма, по цифре, по актеру
Была добавлена фикстура на открытие и закрытие браузера

UI тесты запускаются командой pytest test_UI.py
API тесты запускаются командой pytest test_API.py