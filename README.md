# Banks Market Capitalization ETL Project

## 📌 Overview
This project extracts data of the largest banks by market capitalization from Wikipedia, transforms it to multiple currencies using provided exchange rates, and loads it into a CSV and SQLite database for querying and analysis.

## 🚀 Features
- Web scraping with BeautifulSoup
- Currency conversion to GBP, EUR, INR
- Data storage in CSV and SQLite
- SQL queries for global office reports
- Data visualization (Top banks barplot)

## ⚙️ Requirements
- Python 3.8+
- pandas
- numpy
- requests
- beautifulsoup4
- matplotlib
- seaborn
- sqlite3

Install via:
```bash
pip install pandas numpy requests beautifulsoup4 matplotlib seaborn
