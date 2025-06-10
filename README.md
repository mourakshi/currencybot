# Multi-Platform Currency Converter Bot

A dual-purpose currency converter that works with both **Dialogflow** and **Telegram**, powered by FreeCurrencyAPI.

## 🌟 Features

- **Dual integration**: Works with Dialogflow AND Telegram
- 💱 Real-time currency conversions for 150+ currencies
- 🤖 Natural language processing (via Dialogflow)
- 🔄 Fallback to direct Telegram commands
- 📊 Usage analytics logging

## 🛠 Setup

### Prerequisites
- Python 3.8+
- [FreeCurrencyAPI](https://freecurrencyapi.com) key
- Telegram Bot Token ([@BotFather](https://t.me/BotFather))
- (Optional) Ngrok for local testing

### Installation
```bash
git clone https://github.com/yourusername/currency-bot.git
cd currency-bot
pip install -r requirements.txt

#🔧 Configuration
1. Create .env file:
TELEGRAM_TOKEN=your_telegram_bot_token
CURRENCY_API_KEY=your_freecurrencyapi_key
2. Dialogflow:
DIALOGFLOW_PROJECT_ID=your-project-id

   
