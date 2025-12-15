# API Overview

Нижче наведено приклад вигаданого API для демонстрації технічної документації.

## GET /api/movies
Отримати список фільмів.

Запит:
GET /api/movies

Відповідь:
```json
{
  "status": 200,
  "movies": [
    { "id": 1, "title": "Inception", "rating": 8.8 },
    { "id": 2, "title": "Interstellar", "rating": 8.6 }
  ]
}
