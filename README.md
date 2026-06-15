# AmbitionBox Company Scraper 🏢

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4-green)
![Pandas](https://img.shields.io/badge/Pandas-latest-150458?logo=pandas)
![Requests](https://img.shields.io/badge/Requests-latest-orange?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A Python web scraper that extracts data on **top companies in India** from [AmbitionBox](https://www.ambitionbox.com), including ratings, reviews, company type, and location.

## 📊 Data Collected

| Column | Description |
|---|---|
| `name` | Company name |
| `rating` | Employee rating (out of 5) |
| `reviews` | Number of reviews |
| `CompanyType` | Industry/sector (e.g. IT Services, Banking) |
| `location` | Headquarters city |

## 🛠️ Tech Stack

- **Python 3**
- **requests** — HTTP requests to fetch web pages
- **BeautifulSoup (bs4)** — HTML parsing
- **pandas** — Data storage and manipulation

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/IITJodhpurcse28/ambitionbox-scraper.git
   cd ambitionbox-scraper
   ```

2. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 lxml pandas
   ```

3. Open the notebook:
   ```bash
   jupyter notebook ambitionbox_scraper.ipynb
   ```

4. Run all cells — the scraper loops through 10 pages and collects **200 companies**.

## 📁 Output

The final data is stored in a pandas DataFrame (`final`) with 200 rows (20 companies × 10 pages).

## 💡 Sample Output

| name | rating | reviews | CompanyType | location |
|---|---|---|---|---|
| TCS | 3.3 | (1.2L) | IT Services & Consulting | Bengaluru |
| Accenture | 3.7 | (74.5k) | IT Services & Consulting | Bengaluru |
| HDFC Bank | 3.8 | (53.3k) | Banking | Mumbai |
| Jio | 4.4 | (33.9k) | Telecom | Mumbai |

## ⚠️ Disclaimer

This project is for **educational purposes only**. Scraping websites should be done responsibly and in accordance with the website's terms of service.

---
Made with ❤️ by [Rahul Saxena](https://github.com/IITJodhpurcse28)
