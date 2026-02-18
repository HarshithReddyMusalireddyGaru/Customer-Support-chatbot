# Retailia 🤖 – AI Customer Support Chatbot

Retailia is an AI-powered conversational customer service chatbot built using Llama3, Agentic RAG architecture, and Streamlit.  
It intelligently routes user queries to either a FAQ retrieval system or an SQL database agent to provide accurate, context-aware responses.

---

##  Features

- 🔎 FAQ Retrieval using FAISS Vector Store
- 🗄️ SQL Agent for order, product, cart, and rating queries
- 🧠 Agentic Routing (FAQ Agent + SQL Agent)
- 💬 Conversational and human-like responses
- 🔐 User Login Authentication
- 🖥️ Streamlit-based Web Interface

---

## Architecture

- **LLM:** Llama3 (via Groq)
- **Vector Database:** FAISS
- **Database:** SQLite (ecommerce database)
- **Frameworks:** LangChain, LangGraph
- **Frontend:** Streamlit

The system routes user queries dynamically:
- Product/order-related questions → SQL Agent
- General FAQs → Vector Store Agent



