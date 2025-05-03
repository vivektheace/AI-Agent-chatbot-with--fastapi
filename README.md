#  AI-Agent-Chatbot-with-FastAPI

A full-stack, modular AI chatbot system built using **LangGraph**, **FastAPI**, and **Streamlit**. This project lets you interact with powerful LLMs like **OpenAI GPT-4o-mini** and **Groq LLaMA/Mixtral** through a responsive UI, supporting dynamic prompt customization and optional web search capabilities.

---

## Features

* Multiple LLM provider support (OpenAI, Groq)
* FastAPI backend with LangGraph agent orchestration
* Intelligent response generation with optional search (Tavily)
* Streamlit frontend for interactive querying
* Environment-based API key management (`.env`)

---

##  How to Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/your-username/AI-Agent-Chatbot-with-FastAPI.git
cd AI-Agent-Chatbot-with-FastAPI
```

### 2. Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Create a `.env` file

```env
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
TAVILY_API_KEY=your_tavily_key
```

### 5. Run the FastAPI backend

```bash
python backend.py
```

### 6. Run the Streamlit frontend

```bash
streamlit run frontend.py
```

---

## Example Use Case

Define your custom AI agent (e.g., helpful assistant, research bot), choose the provider and model, enable web search if needed, and ask any question — all in a few clicks.

---

##  Tech Stack

* [LangGraph](https://github.com/langchain-ai/langgraph)
* [FastAPI](https://fastapi.tiangolo.com/)
* [Streamlit](https://streamlit.io/)
* [LangChain](https://python.langchain.com/)
* [Tavily Search](https://www.tavily.com/)
* [Groq](https://groq.com/) & [OpenAI](https://openai.com/)

---

## License

MIT – feel free to use, modify, and share.

--
