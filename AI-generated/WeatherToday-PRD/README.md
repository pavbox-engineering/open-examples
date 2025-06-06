# Weather Today Telegram Bot

Быстрый и удобный Telegram-бот для получения прогноза погоды на выбранный период. Поддержка поиска по альтернативным названиям городов, ручной ввод координат, интеграция с Open-Meteo API и OpenStreetMap.

- Все ответы и интерфейс на русском языке
- Валидация данных пользователя
- Кэширование популярных запросов
- Документация по запуску и смене API-ключа

**Требования и подробности см. в [WeatherToday-PRD.md](WeatherToday-PRD.md)**

## Запуск

1. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```
2. Создайте файл `.env` в каталоге проекта и укажите токен Telegram:
   ```
   TELEGRAM_BOT_TOKEN=ваш_токен_бота
   ```
3. Запустите бота:
   ```
   python bot_main.py
   ```

## Переменные окружения
- `TELEGRAM_BOT_TOKEN` — токен Telegram-бота

Open-Meteo и OpenStreetMap не требуют API-ключей для базового использования. 