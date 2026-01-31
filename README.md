# Translator Bot

Telegram bot for translating messages into the selected language using `deep-translator`.

## Features

- Commands `/start` and `/change`
- Translates incoming messages
- Supported languages: `kk`, `ru`, `en`, `de`, `uz`, `zh-CN`, `ko`, `es`

## Quick start

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Set the bot token:
   ```bash
   export BOT_TOKEN="your_telegram_token"
   ```
3. Run the bot:
   ```bash
   python bot.py
   ```

## Usage

- `/start` — greeting and instructions
- `/change` — choose the translation language

By default, translations are done in English (`en`) until the user selects a language.
