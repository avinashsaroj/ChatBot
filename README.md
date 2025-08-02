# 🧠 Enhanced Q&A Chatbot with Ollama + Streamlit

This repository contains a simple and interactive Q&A chatbot application built using **Streamlit** and powered by **Ollama's open-source LLMs** via **LangChain**. The chatbot takes user questions as input and responds intelligently using the selected open-source model (`mistral` by default).

---

## 🚀 Features

- Chatbot UI built with **Streamlit**
- Powered by **LangChain** and **Ollama**
- Prompt customization using `ChatPromptTemplate`
- Real-time interaction with Open Source LLMs
- Adjustable parameters: `temperature` and `max_tokens`
- LangSmith integration for tracing and debugging

---

## 📁 Project Structure

```
.
├── app.py                 # Main chatbot app
├── .env                  # Environment variables (API keys, etc.)
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

---

## ⚙️ Requirements

- Python 3.9+
- Streamlit
- LangChain
- Ollama
- dotenv
- openai (optional for hybrid usage)

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🌐 How to Run

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/chatbot-ollama.git
cd chatbot-ollama
```

2. **Set up environment variables**

Create a `.env` file and add your `LANGCHAIN_API_KEY`:

```bash
LANGCHAIN_API_KEY=your_langsmith_api_key
```

3. **Start the Streamlit app**

```bash
streamlit run app.py
```

---

## 🧠 Model Support

Currently supports:

- `mistral` (via Ollama)

More models can be added easily via LangChain’s `Ollama` interface.

---

## 📷 UI Preview

> ![Screenshot of Streamlit Chatbot](https://via.placeholder.com/600x350.png?text=Chatbot+UI+Preview)

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to add support for more models or features, feel free to open an issue first to discuss what you would like to change.

---

## 📝 License

MIT License © 2024

---
