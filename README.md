# Legal Advisor ChatBot - Telegram

This project is a **Legal Advisor ChatBot** built using **Groq Llama3-70b-8192** and integrated with **Telegram**. It allows users to get legal advice by interacting with the chatbot via Telegram.

## Prerequisites
- Python 3.7 or higher
- A Telegram account with the app installed on your smartphone
- A Groq account and API key

## Telegram Setup
1. Open Telegram and search for **BotFather**.
2. Start a conversation with BotFather and type `/newbot`.
3. Choose a name for your bot (e.g., `<mybot>`).
4. Set a username for your bot (e.g., `<mybot_bot>`).
5. BotFather will provide a URL for your bot — click on it to start chatting with your bot.

## AIogram Documentation
For more details on the AIogram framework used in this project, check out the official documentation:  
[AIogram Documentation](https://docs.aiogram.dev/en/latest/)

## How to Run the Code
1. Clone this repository or download the ZIP file.
   ```bash
   git clone <repository-url>
2. Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install the required dependencies:
   pip install -r requirements.txt
4. Create a .env file in the root directory and add your Groq API key and Telegram BOT TOKEN as follows:
      GROQ_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TELEGRAM_BOT_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
6. Open Telegram, search for your bot’s username, and start interacting!

