Excel-Based Chatbot using Python, Flask, Pandas & NLTK

This project is a simple yet powerful Chatbot Application which is university chatbot built using Python, Flask, NLTK, and Pandas, designed to load Question–Answer pairs from an Excel file.
The chatbot processes user messages, finds the best matching question from the dataset, and returns the appropriate answer.

🚀 Features

📁 Excel-based Dataset (Q&A stored in .xlsx)

🤖 Chatbot with NLP using NLTK tokenization and filtering

🌐 Flask Web App with HTML/CSS frontend

🔍 Pandas-based searching & matching

⚡ Fast & lightweight

🎨 Frontend UI similar to ChatGPT (input box + send button)

📚 Easy to customize for universities, companies, or FAQ bots

🛠 Tech Stack
Component	Technology
Backend	Python, Flask
NLP	NLTK
Data Handling	Pandas, Excel (.xlsx)
Frontend	HTML, CSS, JavaScript
Templates	Flask Jinja2
📂 Project Structure
├── app.py
├── chatbot.xlsx
├── templates/
│   └── index.html
├── static/
│   └── style.css  (optional)
└── README.md

⚙️ How It Works

User sends a message in the web UI

Flask backend receives the message

NLTK preprocesses the input (tokenization, lowercasing, cleaning)

Pandas searches the Excel file for the best matching question

The matched answer is sent back and displayed
