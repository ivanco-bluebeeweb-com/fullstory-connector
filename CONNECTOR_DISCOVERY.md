# FullStory Connector — Connector Discovery

**Vendor API Baseline:** https://fullstory.com

## Архитектура API
- **Базовый адрес:** `https://api.fullstory.com/v2`
- **Протокол:** REST / HTTPS (JSON)
- **Аутентификация:** API Key (Authorization: Basic <key>)
- **Ключевые эндпоинты:**
  - сессии (/sessions)
  - сегменты (/segments)
  - кастомные события (/events)
  - события фрустрации
- **Тестовая точка проверки подключения:** `GET /v2/users`.
