# 🗺️ Gemini Travel Guide Chatbot (Paris) – Jupyter Notebook

This project is a Jupyter Notebook that uses Google’s **Gemini 1.5 Flash** model to simulate a travel guide chatbot focused on **Paris**. The bot answers common tourist questions about landmarks, directions, and must-see attractions in a concise and helpful manner.

---

## 📓 Notebook Overview

The notebook performs the following steps:

- Configures access to the Gemini API
- Sets a system prompt for the bot to act as a Paris travel guide
- Initializes a chat with history to establish context
- Sends a series of questions and prints model responses

---

## 📁 Files

.

├── paris_travel_guide.ipynb # Jupyter Notebook implementing the chatbot

├── README.md # Project documentation

---

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook or JupyterLab
- `google-generativeai` package

Install required packages:

```bash
pip install google-generativeai
```

## 🔑 Setup

Get your API key from [Google AI Studio](https://makersuite.google.com/app).

Set the API key as an environment variable before running the notebook:

import os
os.environ["GOOGLE_API_KEY"] = "your-api-key-here"

## 💬 How It Works

The chatbot is designed to answer travel-related questions such as:

- "How far away is the Louvre from the Eiffel Tower (in miles) if you are driving?"
- "Where is the Arc de Triomphe?"
- "What are the must-see artworks at the Louvre Museum?"

Responses are concise and context-aware, based on the chat's initialization parameters.

---

## 🤖 Model Used

- **Model**: `gemini-1.5-flash`
- **API**: Google Generative AI for Python
- **Mode**: Multi-turn chat with history

---

## 📌 Notes

- You can fully customize the system prompt and supported question types.
- Easily expand the chatbot to include other cities, integrate maps, or build it into a web app.

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/license/mit).
