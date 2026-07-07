# 🚀 Text2SQL Application

A modern full-stack **Text-to-SQL** application that transforms natural language questions into SQL queries using Large Language Models (LLMs).

This project provides an intuitive interface for interacting with PostgreSQL databases without writing SQL manually.

---

## ✨ Features

- Natural language to SQL conversion
- PostgreSQL database connectivity
- FastAPI REST API backend
- React + TypeScript frontend
- SQLAlchemy ORM integration
- Automatic database schema extraction
- Modular and scalable architecture
- Ready for LLM integration

---

## 🛠 Tech Stack

### Frontend
- React
- TypeScript
- Vite

### Backend
- FastAPI
- Python 3.12+
- SQLAlchemy
- Psycopg2

### Database
- PostgreSQL

### AI
- Qwen 2.5 (Planned)
- Prompt Engineering

---

## 📂 Project Structure

```text
text2sql-app/
│
├── backend/
│   ├── app/
│   ├── config/
│   ├── database/
│   ├── models/
│   ├── services/
│   └── main.py
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
git clone https://github.com/saurabh1802gupta-afk/text2sql-app.git
cd backend

python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt

cd text2sql-app
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=your_database
uvicorn main:app --reload
cd frontend

npm install

npm run dev
User
   │
   ▼
React Frontend
   │
   ▼
FastAPI Backend
   │
   ▼
Database Schema Extraction
   │
   ▼
LLM
   │
   ▼
SQL Generation
   │
   ▼
PostgreSQL
   │
   ▼
Query Results
Future Improvements
LLM integration
SQL validation
Query execution history
Docker support
Authentication
CI/CD pipeline
Multiple database support
