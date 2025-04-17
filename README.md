# 📰 News Category Web Scraper using Python & BeautifulSoup

This project is a Python-based web scraper that collects news articles from an online newspaper website. It organizes the data into a structured `dataspaper` object by category — making it ideal for real-time analysis, archiving, or feeding into NLP pipelines.

---

## 🌐 Overview

- Built with **Python** and **BeautifulSoup**
- Automatically fetches and parses news articles
- Categorizes articles into sections like:
  - Politics
  - Business
  - Sports
  - Entertainment
  - Technology
  - Health
  - Lifestyle
- Outputs a `dataspaper` dictionary object containing structured news data

---

## 🛠️ Technologies Used

- **Python 3.10**
- **BeautifulSoup** (`bs4`)
- **Requests**

---

## 🧠 How It Works

1. Scraper visits the main page of the newspaper
2. Extracts links to different **news categories**
3. For each category, it:
   - Fetches the page
   - Extracts article titles and links
   - Stores them in a `dataspaper[category]` list

---
