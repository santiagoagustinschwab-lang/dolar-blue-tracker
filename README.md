# Dólar Blue Tracker

Python script that scrapes the current Dólar Blue exchange rate 
(buy and sell price) from dolarhoy.com and saves it to an Excel file, 
building a historical record over time.

Every time the script runs, it appends a new row with the current 
date, time, buy price, and sell price — without overwriting previous data.

## Technologies
- Python
- requests
- BeautifulSoup4
- openpyxl
- datetime

## How to run it
1. Install dependencies: `pip install requests beautifulsoup4 openpyxl`
2. Run: `python dolar_tracker.py`
3. This creates (or updates) `Dolar Tracker.xlsx` with a new row 
   each time you run it

## Use case
Useful for businesses or individuals who need to track exchange 
rate fluctuations over time without checking manually every day.