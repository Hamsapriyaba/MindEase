# 🧠 MindEase – Mental Health Support Chatbot

MindEase is an AI-powered mental health support chatbot that offers real-time, emotionally intelligent responses based on user input. By combining sentiment analysis, keyword extraction, and state-of-the-art language modeling, MindEase provides a comforting, interactive experience for individuals seeking mental health support.

---

## 💡 Features

- 🎯 **Sentiment Analysis** – Understands emotional tone using VADER.
- 🔑 **Keyword Extraction** – Uses TF-IDF to identify important terms from user input.
- 🤖 **Context-Aware Replies** – Generates therapeutic responses using LLaMA-3 via the Groq API.
- 🧪 **Interactive Interface** – Built with Gradio for an easy-to-use chatbot UI.
- 🛠️ **Modular Pipeline** – Easy to understand, extend, or retrain with your own data.

---

## 🛠️ Tech Stack

| Layer        | Tool/Library                        | Purpose                                              |
|--------------|-------------------------------------|------------------------------------------------------|
| Frontend     | [Gradio](https://gradio.app)        | Chat interface for user interaction                  |
| Backend      | Python                              | Core logic, integration of all components            |
| AI Model     | [LLaMA-3 via Groq API](https://groq.com) | Generates smart, therapeutic responses             |
| Sentiment    | VADER (NLTK)                        | Analyzes emotional tone of user input                |
| NLP Utility  | Scikit-learn (TF-IDF)               | Keyword extraction from input                        |

---


