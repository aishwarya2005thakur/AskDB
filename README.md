# 🧠 AskDB – Query Your Data with AI, No SQL Needed

**AskDB** is an AI-powered web app that lets you upload database-like PDFs and interact with the data using plain English — no SQL skills required. Ask a question, and the app converts it into a SQL query using OpenAI's GPT model, executes it on your structured data, and shows you the results instantly.

Whether you're a student, analyst, or just someone dealing with data, AskDB simplifies the way you interact with databases.

---

## ⚙️ How It Works

1. 📤 **Upload a PDF** – Upload your database (tables) in PDF format.
2. 🧾 **PDF Extraction** – `pdfplumber` extracts and converts the tables into a usable SQL format.
3. 💬 **Ask Questions** – Type a question like _"Show me all students with marks above 90"_.
4. 🧠 **AI Translation** – FastAPI backend sends your query to OpenAI, which translates it into SQL.
5. 📊 **Get Results** – The query runs on your database, and the matching results are returned.

---

## 🧰 Tech Stack

- **Frontend**: React Native (TypeScript)
- **Backend**: FastAPI (Python)
- **AI/NLP**: OpenAI API (text-davinci or gpt-3.5-turbo)
- **Database**: MySQL / SQLite (configurable)
- **PDF Extraction**: pdfplumber

---

## 📦 Installation

### Prerequisites

- Node.js & npm
- Python 3.9+
- OpenAI API key
- Expo CLI (for React Native)

---

### Step 1: Clone the Repo

```bash
git clone https://github.com/your-username/AskDB_V2.git
cd AskDB_V2
