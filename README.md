# 🛒 E-Commerce AI Assistant (Multi-Route Conversational App)

An intelligent **AI-powered assistant** for e-commerce businesses that can answer FAQs, perform database queries, and engage in small talk — all within one unified Streamlit application.

This project demonstrates how to integrate **Groq LLaMA-3**, **Semantic Routing**, and **LangChain** to build a modular, context-aware conversational system capable of handling multiple query types.

---

## 🚀 Features

- 🧠 **Multi-Intent Understanding** — Detects whether a query is FAQ, SQL, or Small Talk  
- 🔀 **Semantic Routing** — Automatically routes each user message to the correct logic module  
- ⚡ **Groq LLaMA-3 Integration** — Uses Groq’s high-speed LLM for contextual responses  
- 🧮 **SQL Query Engine** — Converts natural language to SQL and queries a local SQLite database  
- 💬 **Small-Talk Module** — Handles conversational, human-like messages  
- 🌐 **Streamlit Frontend** — Simple, user-friendly chat interface


## 🧠 Architecture Overview

User Query → Semantic Router → Module (FAQ / SQL / SmallTalk)
↓
Groq LLaMA-3 Model
↓
Formatted Response
↓
Streamlit UI


## ⚙️ Modules Description

| Module | File | Functionality |
|--------|------|----------------|
| **Main App** | `main.py` | Streamlit frontend integrating all routes |
| **Router** | `router.py` | Detects query intent using Semantic Router |
| **FAQ** | `faq.py` | Handles static or knowledge-based FAQs |
| **SQL** | `sql.py` | Converts natural language to SQL and queries the e-commerce DB |
| **Small Talk** | `smalltalk.py` | Responds to casual user interactions like “How are you?” |
| **Database** | `db.sqlite` | Local e-commerce data storage |

---

## 🧩 Tech Stack

| Category | Tools |
|-----------|-------|
| **Frontend** | Streamlit |
| **LLM** | Groq LLaMA-3 |
| **Framework** | LangChain, Semantic-Router |
| **Database** | SQLite |
| **Data Handling** | Pandas, PandasQL |
| **Environment Management** | Python-dotenv |


<img width="1440" height="900" alt="Screenshot 2025-11-08 at 4 56 08 PM" src="https://github.com/user-attachments/assets/d6cd27b5-b9f2-499e-8453-3841b573ff74" />

<img width="1440" height="900" alt="Screenshot 2025-11-08 at 4 57 28 PM" src="https://github.com/user-attachments/assets/6878d231-2cca-4e5c-abec-2701afe25e3f" />
