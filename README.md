# langchain-ollama-streamlit-app
# LangChain DeepSeek Chat App 🧠💬

This is a simple Streamlit-based chatbot that integrates [LangChain](https://www.langchain.com/), [Ollama](https://ollama.com), and [DeepSeek](https://deepseek.com) to run local LLM-powered Q&A with an easy-to-use interface.

---

## Features

- ✅ Runs completely **locally** using Ollama (no API keys needed for LLM)
- ✅ Uses **LangChain** to structure the prompt and response
- ✅ Interactive **Streamlit UI** for user input
- ✅ Pluggable with any Ollama-supported model (e.g. `llama3`, `mistral`, `deepseek-coder`, etc.)

---

##Tech Stack

- Python 🐍
- Streamlit 📺
- LangChain 🔗
- Ollama 🧠 (LLM backend)
- DeepSeek Model via Ollama

---

## 📦 Installation

1. **Install Ollama**  
   [Download Ollama](https://ollama.com/download) and install it for your OS.

2. **Pull the DeepSeek model** (or any model you want to use):

   ```bash
   ollama pull deepseek-coder:1.3b
