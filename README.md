# StockPulse-Scraper
StockPulse Scraper is a Python tool that extracts real-time stock data from Groww using requests and BeautifulSoup. It fetches metrics like company names, stock prices, daily changes, and trading volumes, organizing them into a Pandas DataFrame and saving as an Excel file. It includes delays to minimize server load and avoid blocking.


# Stock Data Scraper

This Python script scrapes stock data (company name, price, daily change, and volume) from the Groww platform for a list of US and Indian stocks. It extracts the data using BeautifulSoup and stores the results in an Excel file.

## Features
- Scrapes stock data (company, price, daily change, volume) from Groww.
- Uses `requests` to retrieve web pages and `BeautifulSoup` to parse HTML.
- Stores the data in a Pandas DataFrame and exports it to an Excel file (`stocks.xlsx`).

## Requirements
- Python 3.x
- Required Libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `openpyxl` (for saving Excel files)

You can install the necessary libraries using the following command:

```bash
pip install requests beautifulsoup4 pandas openpyxl
```

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/stock-data-scraper.git
```

2. Navigate to the project directory:
```bash
cd stock-data-scraper
```

3. Run the script:
```bash
python stock_scraper.py
```

