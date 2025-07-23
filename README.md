# 🦜 LangChain: Chat with SQL DB

A conversational AI interface built using [LangChain](https://www.langchain.com/) and LLMs (such as Groq, OpenAI, etc.) that allows you to chat directly with your SQL database using natural language.

## 🚀 Features

- 💬 Natural language to SQL conversion
- 🧠 LLM-powered responses using Groq (LLaMA3), OpenAI, or any other provider
- 🔍 Automatically runs and returns SQL query results
- 📊 Query any connected SQL database (PostgreSQL, MySQL, SQLite, etc.)
- 🖥️ Streamlit frontend for interactive usage
- 🔒 Secure API key management

---

## 🛠️ Tech Stack

- **LangChain** – LLM integration & chain management
- **Groq / OpenAI** – LLM provider (configurable)
- **SQLAlchemy** – Database connection and interaction
- **Streamlit** – UI for the chatbot interface
- **Pydantic** – Model validation

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/langchain-sql-chat.git
cd langchain-sql-chat

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
