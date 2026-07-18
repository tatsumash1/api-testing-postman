# API Endpoints

## Base URL

```text
https://reqres.in
```

## Список эндпоинтов для проверки

| ID | Метод | Endpoint | Описание | Ожидается |
| ---| ----- | ---| --- |
| API-001 | GET | `/api/users?page=2` | Получение списка пользователей | 200 OK |
| API-002 | GET | `/api/users/2` | Получение одного пользователя | 200 OK |
| API-003 | GET | `/api/users/23` | Пользователь не найден | 404 Not Found |
| API-004 | POST | `/api/users` | Создание пользователя | 201 Created |
| API-005 | PUT | `/api/users/2` | Полное обновление пользователя | 200 OK |
| API-006 | PATCH | `/api/users/2` | Частичное обновление пользователя | 200 OK |
| API-007 | DELETE | `/api/users/2` | Удаление пользователя | 204 No Content |
| API-008 | POST | `/api/register` | Успешная регистрация | 200 OK |
| API-009 | POST | `/api/register` | Неуспешная регистрация | 400 Bad Request |
| API-010 | POST | `/api/login` | Успешный логин | 200 OK |
| API-011 | POST | `/api/login` | Неуспешный логин | 400 Bad Request |

## Что проверять для каждого запроса

- HTTP-метод;
- URL;
- query parameters;
- request body;
- status code;
- response body;
- обязательные поля в JSON;
- типы данных;
- время ответа;
- поведение при некорректных данных.

## Авторизация

Для запросов ReqRes используется API key в заголовке:

```text
x-api-key: {{api_key}}

