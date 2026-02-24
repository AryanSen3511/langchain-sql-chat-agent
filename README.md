# 🦜 Gen AI Project - LangChain SQL Chat Application
---

## 📌 Project Overview

**This is a Generative AI-powered application that enables users to interact with SQL databases using natural language. Instead of writing complex SQL queries, users can simply ask questions in plain English and receive accurate, real-time answers from the database.**

**Built using LangChain's SQL Toolkit, Groq's LLaMA 3 model, and Streamlit, this project demonstrates the power of combining Large Language Models (LLMs) with structured data retrieval — a key capability in modern enterprise AI solutions.**

🔹 Chat with a SQLite or MySQL database using natural language

🔹 Automatically generate SQL queries using LangChain Agents


---
<img width="1669" height="704" alt="image" src="https://github.com/user-attachments/assets/dbe893c3-b209-4e7a-bdb6-f5933ddd0150" />

<img width="1688" height="821" alt="image" src="https://github.com/user-attachments/assets/9167a825-fc94-427c-8102-6ed7c8359032" />


---



## 🎯 Key Features

1. Natural Language to SQL — **Ask questions in plain English; the AI automatically generates and runs SQL queries.**

2. Dual Database Support — **Connect to either a local SQLite database or a remote MySQL database.**
 
3. Powered by Groq + LLaMA 3 — Ultra-fast inference using llama-3.1-8b-instant model
 
4. LangChain SQL Agent — Uses ZERO_SHOT_REACT_DESCRIPTION agent type for autonomous reasoning
  
5. Interactive Streamlit UI — Clean, user-friendly interface with real-time streaming responses
  
6.  Secure Credential Handling — Passwords and API keys handled securely via Streamlit input masking
  
7. Agent Reasoning Visibility — View the AI's step-by-step thought process via StreamlitCallbackHandler

---



## 🛠️ Tech Stack

1. LangChain – Framework for building LLM-powered applications and SQL agents.

2. Groq – High-speed LLM inference provider.

3. Llama 3.1 8B Instant – Large Language Model used for natural language to SQL generation.

4. Streamlit – Frontend framework for building interactive web applications.

5. Python 3.10+ – Core programming language used for backend logic.

6. SQLite / MySQL – Relational databases for data storage and querying.

7. SQLAlchemy – Database engine and abstraction layer for handling connections.

8. MySQL Connector – Driver for connecting to MySQL databases.

9. SQLite3 – Lightweight local database module for SQLite integration.

---

## 📂 Project Structure

```

LangChain SQL Chat Application
|
├── app.py            # Main Streamlit application
├── sqlite.py         # Script to create and populate student database
├── student.db        # SQLite database
├── requirements.txt  # Dependencies
└── README.md


```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/langchain-sql-chat.git
cd langchain-sql-chat
```

### 2️⃣ Create Virtual Environment

```
conda create -p venv python==3.10 -y
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Create Database (Optional)

```
python sqlite.py
```

### 5️⃣ Run Application

```
streamlit run app.py
```


---

## 🛡️ Author ⚔️

### Aryan Sen

---

## 📬 Contact

📧 Email: [yourEmail@gmail.com](mailto:senaryan973@gmail.com)
🔗 LinkedIn: [https://linkedin.com/in/yourProfile](https://linkedin.com/in/aryansen1212)

---

## 📄 License

This project is licensed under the GPL.


