# 📰 NST News Scraper & Processor (100K+ Articles)

This project is a high-performance web scraper that extracts over **100,000 national news articles** from the [New Straits Times (NST)](https://www.nst.com.my/news/nation) website. It uses **Playwright** for asynchronous browser automation and **BeautifulSoup** for HTML parsing. The collected data is saved into a CSV file and can be further processed using multithreading, multiprocessing, or distributed computing techniques.

---

## 🚀 Features

- ⚡ Fast asynchronous scraping using Playwright
- 🔄 Handles dynamic page content and retries on failure
- 📄 Extracts title, teaser, category, and article URL
- 💾 Outputs clean CSV format
- 🔧 Built for scalability and large-scale crawling
- 🧠 Ready for post-processing using parallel computing

---

## 📦 Requirements

Install dependencies:

```bash
pip install playwright beautifulsoup4 lxml
playwright install
