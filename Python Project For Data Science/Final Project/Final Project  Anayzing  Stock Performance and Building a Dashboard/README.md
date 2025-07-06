#  Final Project: Web Scraping and Library-Based Data Extraction

This repository contains the final assignments for the IBM Data Science Professional Certificate. It includes two main components:

1. Library-based Data Extraction
2. Web Scraping with BeautifulSoup

Each notebook demonstrates essential data extraction techniques using Python.

## Tools and Libraries Used

- pandas – Data manipulation and cleaning
- requests – Sending HTTP requests
- BeautifulSoup – Parsing HTML content
- plotly – Interactive visualizations
- datetime – Handling date and time formats
- json – Processing API responses


## Notebook 1: Final_Assignment Library.ipynb

### Summary:
This notebook focuses on extracting and visualizing stock and revenue data using yfinance and pandas.

### Tasks Performed:
- Fetch stock data from Yahoo Finance using yfinance.
- Scrape quarterly revenue data from [Macrotrends](https://www.macrotrends.net).
- Clean and merge the datasets.
- Visualize data using plotly.

### Output:
- Line graph of historical stock prices
- Line graph of reported revenue

---

## Notebook 2: Final Assignment Webscraping.ipynb

### Summary:
This notebook demonstrates how to use web scraping techniques to collect and clean structured tabular data from HTML.

### Tasks Performed:
- Use requests to fetch an HTML page.
- Parse HTML using BeautifulSoup.
- Extract tabular data (such as tables with <tr> and <td> tags).
- Convert extracted data into a pandas DataFrame.
- Display and analyze the cleaned dataset.
