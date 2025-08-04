# MemeWatcherBotV3-master-ultimate

🤖 Автоматический бот для поиска и торговли мемкоинами на Solana.

## 📦 Структура

- `main.py` — запуск бота
- `config.py` — настройки (ключи, лимиты, RPC)
- `watcher.py` — мониторинг токенов
- `trader.py` — логика входа/выхода
- `wallet_manager.py` — контроль лимита и авто-вывод
- `notifier.py` — уведомления (Telegram + Push)
- `scheduler.py` — ежедневный отчёт в 21:00
- `model_trainer.py` — обучающий фильтр
- `utils.py` — утилиты (например, новые токены)
- `powershell_push.ps1` — скрипт для загрузки на GitHub

## 🚀 Запуск

1. Установи зависимости:
   ```bash
   pip install -r requirements.txt
   ```

2. Запусти:
   ```bash
   python main.py
   ```

## ✅ Уведомления

Бот отправляет сообщения:
- В Telegram: `@MainWatcherBot`
- Через Push (Pushover)

## 📌 Требования

- Python 3.10+
- Рабочий RPC QuickNode
- Созданный Telegram-бот
