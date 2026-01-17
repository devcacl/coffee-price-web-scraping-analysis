# ☕ Coffee Price Web Scraping and Analysis

This project implements a **web scraping pipeline** to collect **coffee price quotations** from multiple Brazilian sources and analyze their **price evolution over time**.

The system automatically extracts data from static websites, stores historical prices, and generates visual insights using time series and comparison charts.

---

## 📌 Project Objectives

- Scrape coffee price data from different Brazilian market sources
- Normalize and consolidate prices into a single dataset
- Store historical data for longitudinal analysis
- Visualize price trends and compare average prices across sources

---

## 🌐 Data Sources

The project scrapes coffee prices from the following public sources:

- **B3** – Brazilian Stock Exchange (via Cooxupé Hub)
- **CEPEA / ESALQ-USP**
- **Coopama**
- **Coopercam**
- **CCMG** – Coffee Trade Center of Minas Gerais
- **Cooxupé**
- **Café Poços**
- **Cooabriel**

Each source requires a custom scraper due to differences in HTML structure.

---

## 🧠 Key Features

- Randomized User-Agent headers to reduce blocking
- Modular scraper functions per data source
- Automatic date and time handling with timezone support
- Data cleaning and normalization (Brazilian number formats)
- Historical CSV storage (append mode)
- Line charts for price evolution
- Bar charts for average price comparison

---

## 🛠️ Technologies Used

- **Python**
- **Requests** – HTTP requests
- **BeautifulSoup** – HTML parsing
- **Pandas** – data manipulation
- **Matplotlib & Seaborn** – data visualization
- **pytz** – timezone handling

---

## 📊 Data Visualization

### ✔ Time Series Analysis
- Line charts showing coffee price evolution per source
- Focus on recent observations (last 30–60 entries)

### ✔ Comparative Analysis
- Bar chart comparing **average prices per source**
- Highlights price differences between market entities

---

##👤 Author

Camilo Coronado

Systems Engineering & Data Science 

