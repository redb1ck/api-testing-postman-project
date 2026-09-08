API Test Cases — JSONPlaceholder API Testing


Проект:
API Testing Project


Инструмент:
Postman


Окружение:
REST API


Тестовые сценарии:


TC-001 Проверка получения списка постов

Метод:
GET

URL:
https://jsonplaceholder.typicode.com/posts

Шаги:
1. Отправить GET запрос.
2. Проверить статус ответа.

Ожидаемый результат:
Статус ответа 200 OK.
Ответ содержит список постов.

Результат:
Passed


TC-002 Проверка получения пользователя по ID

Метод:
GET

URL:
https://jsonplaceholder.typicode.com/users/1

Шаги:
1. Отправить GET запрос.
2. Проверить наличие данных пользователя.

Ожидаемый результат:
Статус ответа 200 OK.
Ответ содержит ID пользователя и email.

Результат:
Passed


TC-003 Создание нового поста

Метод:
POST

URL:
https://jsonplaceholder.typicode.com/posts

Шаги:
1. Отправить POST запрос с JSON Body.
2. Проверить ответ сервера.

Ожидаемый результат:
Статус ответа 201 Created.
Созданный объект содержит заголовок.

Результат:
Passed


TC-004 Обновление поста

Метод:
PUT

URL:
https://jsonplaceholder.typicode.com/posts/1

Ожидаемый результат:
Статус ответа 200 OK.
Данные успешно обновлены.

Результат:
Passed


TC-005 Удаление поста

Метод:
DELETE

URL:
https://jsonplaceholder.typicode.com/posts/1

Ожидаемый результат:
Статус ответа 200 OK.
Объект удалён.

Результат:
Passed
