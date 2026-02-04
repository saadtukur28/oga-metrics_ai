# OgaMetrics

**Be the oga of your numbers.**

OgaMetrics is an AI-powered web application that helps small businesses understand their operational data and make better decisions using natural language.

“Oga” means **boss** in Nigerian Pidgin — OgaMetrics helps business owners become the boss of their data.

---

## 🚩 The Problem

Small businesses generate sales, expense, and customer data every day, but most of this data is never analyzed.

Why?
- Business intelligence tools are expensive
- Dashboards are complex and time-consuming
- Hiring analysts is not affordable

As a result, many business decisions are made based on guesswork instead of evidence.

---

## 💡 The Solution

OgaMetrics acts as a **virtual operations analyst**.

Instead of learning complex tools, business owners can:
1. Upload their business data (CSV files)
2. Ask questions in plain English
3. Receive clear, data-backed insights and explanations

No dashboards to learn.  
No technical skills required.

---

## ✨ Core Features (MVP)

- Secure authentication
- CSV data ingestion and validation
- Automated business summaries
- Natural-language AI chat over uploaded data
- Trend analysis and anomaly detection
- Interactive visual dashboards

---

## 🧠 How It Works (High Level)

1. Business data is uploaded and cleaned
2. Key metrics and trends are extracted
3. Data is embedded into a vector store
4. Relevant data is retrieved per user question
5. An AI model generates grounded, explainable responses

This ensures answers are based on **real data**, not assumptions.

---

## 🏗️ System Architecture

**Frontend**
- Next.js
- Tailwind CSS
- Recharts / Chart.js

**Backend**
- FastAPI
- Python analytics services

**Database**
- PostgreSQL (Supabase free tier)

**AI Layer**
- Open-source LLaMA models
- FAISS vector database
- Retrieval-Augmented Generation (RAG)

---

## 📈 Scalability Vision

**Today**
- Spreadsheet-based analysis

**Tomorrow**
- POS and payment integrations
- Inventory management
- Automated alerts and recommendations

The system is designed to scale without rewriting core components.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-----|-----------|
| Frontend | Next.js, Tailwind CSS |
| Backend | FastAPI |
| Database | PostgreSQL (Supabase) |
| AI | LLaMA |
| Vector Store | FAISS |
| Hosting | Vercel, Render / Fly.io |
| Auth | Supabase Auth |

---

## 🚧 Project Status

This project is currently **in active development** as a final AI web application project.

---

## 👤 Author

**Tukur Saad Gbolahan**  
AI & Full-Stack Developer  

---

## 📄 License

This project is licensed under the MIT License.
