
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

git clone https://github.com/yourusername/currency-bot.git
cd currency-bot
pip install -r requirements.txt




## 🚀Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

- TELEGRAM_TOKEN=8157615530:AAHekARssFza4xQLRQWlA3fYwM0HtWeq8Js
- CURRENCY_API_KEY=https://api.freecurrencyapi.com/v1/latest?apikey




## 🏃Running the Bot

### Local Development
>python main.py

### With Ngrok (for webhook testing)
>ngrok http 5000
>>Then update your Telegram/Dialogflow webhook URLs

## 📝 Usage Examples

### Telegram Commands
- convert 100 USD EUR
- rates USD
- help

### Dialogflow/Natural Language
- "Convert 100 US dollars to Euros"
- "What's the exchange rate for GBP to JPY?"
- "100 Canadian dollars in Mexican pesos"
## 📊 Analytics

The bot logs conversion requests to conversions.log with:

- Timestamp

- Source platform (Telegram/Dialogflow)

- Currencies converted

- Amount
## 🛠 Development

### Project Structure

| File/Folder |	Description |
|-------------|-------------|
|bot|	Core bot implementation|
|├── telegram_handler.py|	Handles Telegram bot commands and responses|
|├── dialogflow_handler.py|	Processes natural language requests via Dialogflow|
|└── currency_api.py|	Manages currency conversion API calls|
|main.py|	Entry point that initializes all handlers|
|requirements.txt|	Python package dependencies|
|.env.example|	Template for environment configuration|
|conversions.log|	Logs all conversion requests for analytics|


### Dependencies
List key dependencies and their purpose:

- python-telegram-bot: Telegram bot framework

- dialogflow: Google's NLP service integration

- requests: API calls to FreeCurrencyAPI

- python-dotenv: Environment management
## 📄License

Distributed under the MIT License. See LICENSE for more information.


## 📧 Contact

Mourakshi Thakuria - mourakshithakuria@gmail.com

Project Link: https://github.com/mourakshi/currencybot
