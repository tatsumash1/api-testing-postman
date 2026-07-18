# API Endpoints

## Base URL

```text
https://reqres.in
```

## Список эндпоинтов для проверки

| ID | Метод | Endpoint | Описание |
| ---| ----- | ---| --- |
| API-001 | GET | `/api/users?page=2` | Получение списка пользователей |
| API-002 | GET | `/api/users/2` | Получение одного пользователя |
| API-003 | GET | `/api/users/23` | Пользователь не найден |
| API-004 | POST | `/api/users` | Создание пользователя |
| API-005 | PUT | `/api/users/2` | Полное обновление пользователя |
| API-006 | PATCH | `/api/users/2` | Частичное обновление пользователя |
| API-007 | DELETE | `/api/users/2` | Удаление пользователя |
| API-008 | POST | `/api/register` | Успешная регистрация |
| API-009 | POST | `/api/register` | Неуспешная регистрация |
| API-010 | POST | `/api/login` | Успешный логин |
| API-011 | POST | `/api/login` | Неуспешный логин |

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


