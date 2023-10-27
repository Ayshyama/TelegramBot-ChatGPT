# Telegram Bot with ChatGPT

References to the documentation of the key libraries:

- [Telebot (pyTelegramBotAPI) Documentation](https://github.com/eternnoir/pyTelegramBotAPI)
- [OpenAI API Documentation](https://beta.openai.com/docs/)

## Library Recommendations

Alternative libraries and tools that might offer more features or better performance:

- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot): A more extensive Telegram bot framework that also supports asynchronous mode.
- [aiogram](https://github.com/aiogram/aiogram): A modern framework for building Telegram bots using Python with asynchronous mode (async/await).
- [Hugging Face's Transformers](https://github.com/huggingface/transformers): If you're looking to host GPT models locally without relying on the OpenAI API.

## How to Run the Telegram Bot

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ayshyama/TelegramBot-ChatGPT.git
   cd TelegramBot-ChatGPT
   ```

2. ** Install the Required Libraries**: 
The repository contains a requirements.txt file that lists all the necessary libraries. Install them using pip:

```bash
pip install -r requirements.txt
```

3. **Get the Telegram Bot Token**:

- Go to the Telegram App and search for the "BotFather" bot.
- Start a chat with BotFather and follow the instructions to create a new bot.
- Once the bot is created, BotFather will provide you with a token. This token is used to access the Telegram API.

4. Get the OpenAI API Key:

- Sign up on the OpenAI platform.
- Navigate to the API section to generate an API key.
  
5. **Update the Code**:
Open the singularity_bot.py file and set the following:

- Replace the empty string in bot = telebot.TeleBot("") with your Telegram bot token.
- Replace the empty string in openai.api_key = "" with your OpenAI API key.
  
6. **Run the Bot**:

```bash
python singularity_bot.py
```
7. **Interact with the Bot**:
- Go to the Telegram app, search for your bot's username, and start a chat.
- Send the /start command to initiate the conversation.
