# 🌐 API Документация для Скрэбл.by  
📌 (TW, SA)

Эта документация описывает предполагаемое API для мобильного приложения **Скрэбл.by**, ориентированного на PvP-игру, синхронизацию данных и игровую логику.

---

## 🔐 Аутентификация (опционально)

📌 (SA)

Если будет реализована регистрация:
- `POST /api/auth/signup`
- `POST /api/auth/login`
- токен доступа: JWT (в заголовке `Authorization: Bearer <token>`)

---

## 🎮 Игра

### `POST /api/game`
📌 (SA) Создание новой игры (режим по сети)