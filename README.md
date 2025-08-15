Simple Rule-based Python Chatbot
📌 Overview

This project is a rule-based chatbot built in Python using if/elif/else conditions.
It responds to user inputs by matching specific keywords or phrases and returning predefined responses.
The bot can handle greetings, tell the current time/date, crack jokes, introduce itself, give help prompts, and end the conversation politely.

🚀 Features

Greetings → Responds to “hi”, “hello”, “hey”, and similar.

Bot Identity → Answers questions like “Who are you?” or “What’s your name?”.

Help Prompt → Displays available commands.

Time → Shows the current system time.

Date / Day → Displays today’s date and day of the week.

Jokes → Tells random programming jokes.

Thanks Response → Replies politely when thanked.

Farewell → Says goodbye and ends the chat when “bye” or similar is typed.

Fallback → Handles unknown inputs with a default message.

🛠 Technologies Used

Python 3

re → for text normalization and removing punctuation.

datetime → for fetching current time and date.

random → for selecting random greetings/jokes.

📂 File Structure
chatbot.py   # Main chatbot Python script
README.md    # Project description

💡 How It Works

normalize(text) → Converts input to lowercase, removes punctuation, and collapses extra spaces.

respond(user_message) → Checks normalized input against rule-based conditions and returns a response.

main() → Runs a loop to continuously chat with the user until they type “bye” or similar exit keywords.

▶️ How to Run

Make sure Python 3 is installed:

python --version


Save the script as chatbot.py.

Run the chatbot:

python chatbot.py


Type messages and interact with the bot.

Type bye to exit.
<img width="1234" height="558" alt="image" src="https://github.com/user-attachments/assets/1d467def-2231-4ee3-ad0c-f16b8d311e0f" />
