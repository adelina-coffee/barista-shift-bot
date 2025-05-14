# Barista Shift Bot

## 📦 Установка

1. Скачай архив и распакуй
2. Создай новый репозиторий на GitHub и загрузи туда содержимое
3. Зайди на [render.com](https://render.com), создай новый Web Service:
   - Укажи свой репозиторий
   - В `Build Command` поставь: `pip install -r requirements.txt`
   - В `Start Command`: `python barista_shift_bot.py`

4. Добавь переменные окружения на Render:
   - `TOKEN` — токен бота от @BotFather
   - `SPREADSHEET_ID` — ID Google Таблицы

5. Загрузите `creds.json` в корень проекта (замени мой шаблон на свой файл)

✅ Готово!
