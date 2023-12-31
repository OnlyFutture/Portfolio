# SQL – Анализ базы данных сервиса для чтения книг по подписке

## Данные
### Таблица books
Содержит данные о книгах:
- book_id — идентификатор книги;
- author_id — идентификатор автора;
- title — название книги;
- num_pages — количество страниц;
- publication_date — дата публикации книги;
- publisher_id — идентификатор издателя.
### Таблица authors
Содержит данные об авторах:
- author_id — идентификатор автора;
- author — имя автора.
### Таблица publishers
Содержит данные об издательствах:
- publisher_id — идентификатор издательства;
- publisher — название издательства;
### Таблица ratings
Содержит данные о пользовательских оценках книг:
- rating_id — идентификатор оценки;
- book_id — идентификатор книги;
- username — имя пользователя, оставившего оценку;
- rating — оценка книги.
### Таблица reviews
Содержит данные о пользовательских обзорах на книги:
- review_id — идентификатор обзора;
- book_id — идентификатор книги;
- username — имя пользователя, написавшего обзор;
- text — текст обзора.
## Задачи
- проанализировать базу данных крупного сервиса для чтения книг по подписке, чтобы сформулировать ценностное предложение для нового продукта.
## Выводы

Статус проекта: завершен.

- открыли все датафреймы- пропусков нет.

Итоги по исследованиям:
- После 1 января 2000 года вышло 819 книга.
- Максимально количество обзоров набрала книга Memoirs of a Geisha- 8 шт со средним рейтингом 4.14.
- Издательство, которое выпустило наибольшее число книг -Penguin Books
- Автор книги J.K. Rowling/Mary GrandPré	имеет самую высокую среднюю оценку
- Среднее количество обзоров от пользователей - 24.

## Навыки и инструменты
*SQL, PostgreSQL, Pandas*
