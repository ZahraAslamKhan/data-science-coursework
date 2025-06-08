# 📦 Dynamic Web Scraping Projects – Data Science Coursework

This repository contains three dynamic web scraping projects using **Selenium**, **BeautifulSoup**, and **pandas**. These assignments demonstrate the ability to extract structured data from websites that load content dynamically using JavaScript.

---

## 🧠 Covered Projects

### 🔹 1. Lamudi Property Listings – DHA Phase 6, Lahore
- **URL:** [Lamudi.pk](https://www.lamudi.pk/search/lahore/homes-for-sale-in-dha-phase-6-1448/?location_ids=1448,1450,1451)
- **Objective:** Scrape location, price, number of beds/baths, and area from property listings across the first five pages.
- **Tech:** Selenium for navigation, BeautifulSoup for parsing, pandas for formatting data.

📁 Notebook: `lamudi-property-listings.ipynb`

---

### 🔹 2. Bitcoin Historical Data – Yahoo Finance
- **URL:** [Yahoo Finance – BTC-USD](https://finance.yahoo.com/quote/BTC-USD/history/)
- **Objective:** Automatically search and scrape daily historical Bitcoin data (last 3 months).
- **Features Extracted:** Date, Open, High, Low, Close, Adjusted Close, Volume.
- **Tech:** Selenium-based search simulation via Google → Yahoo Finance → Table extraction with pandas.

📁 Notebook: `bitcoin-historical-data.ipynb`

---

### 🔹 3. YouTube Channel Scraping – Aima Baig
- **URL:** [Aima Baig’s YouTube Channel](https://www.youtube.com/@AimaBaig.official)
- **Objective:** Scrape:
  - Video titles
  - View counts
- **Tech:** Selenium for dynamic loading, interaction, scrolling; BeautifulSoup for data parsing.

📁 Notebook: `aima-baig-youtube-analysis.ipynb`

---

## 🛠️ Tools & Libraries
- Python 3.x  
- Jupyter Notebook  
- `selenium`  
- `bs4` (BeautifulSoup)  
- `pandas`  
- `time`, `re`, `warnings`, `webdriver-manager`


