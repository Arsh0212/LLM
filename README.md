# 📰 Moneycontrol News Scraper & Semantic Search Engine

This project fetches financial news from [Moneycontrol](https://www.moneycontrol.com/news/), stores it in a local **PostgreSQL** database, and provides a powerful **semantic search interface** using **Google Gemini embeddings** + **FAISS** for similarity retrieval.

---

## 📌 Features

- ✅ Scrape latest articles from Moneycontrol (all categories)
- ✅ Store article `title` and `content` in PostgreSQL
- ✅ Multithreaded article scraping for performance
- ✅ Semantic search powered by Gemini Embeddings and FAISS
- ✅ Ask questions and receive AI-generated answers

---

## 🧱 Project Structure

.  
├── main.py # Main entry to fetch articles  
├── Para_Processing.py # Gemini + FAISS Semantic Search  
├── DB_CRUD.py # PostgreSQL CRUD operations  
├── requirements.txt # Required libraries  
└── README.md # Project documentation  


---

## 🧰 Technologies Used

- `Python 3.8+`
- `BeautifulSoup` + `requests`
- `SQLAlchemy`
- `PostgreSQL`
- `FAISS`
- `LangChain`
- `Google Generative AI (Gemini)`

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/yourusername/moneycontrol-news-scraper.git
cd moneycontrol-news-scraper
```
### Install Dependencies
```bash
pip install -r requirements.txt
```

💬 Example Output

Write any keyword you want to search about: RBI
Type your question: What did RBI announce?
RBI has announced several monetary changes...