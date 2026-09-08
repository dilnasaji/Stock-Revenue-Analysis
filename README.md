## Tesla vs GameStop: Stock Price and Revenue Analysis

# Project Overview
This project analyzes historical stock prices and company revenue for Tesla and GameStop using Python.

The analysis combines financial market data retrieved using yfinance with quarterly revenue data collected through web scraping.

The goal of the project is to demonstrate an end-to-end data analysis workflow involving data collection, web scraping, data cleaning, exploratory analysis, and visualization.

# Tools & Technologies
- Python
- Pandas
- yfinance
- Requests
- BeautifulSoup
- Matplotlib
- Jupyter Notebook
  
# Project Workflow
1. Extract Tesla historical stock data using yfinance
2. Scrape Tesla quarterly revenue data
3. Clean and transform Tesla revenue data
4. Extract GameStop historical stock data
5. Scrape GameStop quarterly revenue data
6. Clean and transform GameStop revenue data
7. Compare stock-price and revenue trends
8. Visualize the results
9. Summarize key observations

## Data Collection

# Stock Data
Historical stock-price data was retrieved using the yfinance library.

Ticker symbols used:
- Tesla = TSLA
- GameStop = GME

# Revenue Data
Quarterly revenue data was collected from HTML webpages using:
- requests to retrieve webpage content
- BeautifulSoup to parse the HTML
- Pandas to structure the extracted information into DataFrames

## Data Cleaning
The scraped revenue data required additional preparation before the analysis.

The cleaning process included:
- Removing dollar signs
- Removing commas from revenue values
- Removing blank values
- Handling missing values
- Converting revenue values to numeric format
- Converting date values to datetime format

## Results
# Tesla: Stock Price and Revenue
Tesla showed strong long-term growth in both stock price and revenue during the period analyzed. Revenue increased steadily overall, while the stock price accelerated much more sharply toward 2020–2021.

# GameStop: Stock Price and Revenue
GameStop showed a different pattern.Revenue fluctuated and generally weakened toward the later years, while the stock price experienced an unusually large spike around 2021.

## Key Observations
- Tesla showed strong long-term growth in both stock price and revenue during the period analyzed.
- Tesla's revenue increased steadily overall, while its share price accelerated much more sharply toward 2020–2021.
- GameStop's revenue fluctuated and generally weakened toward the later years, while its stock price experienced an unusually large spike around 2021.
- The comparison highlights that stock-market performance and company revenue do not always move together, so multiple indicators should be considered when evaluating company performance.

## Repository Structure

stock-revenue-analysis/
│
├── README.md
├── stock_revenue_analysis.ipynb
├── requirements.txt
└── images/
    ├── tesla_stock_revenue.png
    └── gamestop_stock_revenue.png

## How to Run

Install the required Python libraries:
pip install -r requirements.txt
Then open stock_revenue_analysis.ipynb in Jupyter Notebook or JupyterLab and run the cells in order.

## Key Learning

This project helped me understand how multiple parts of a Python data-analysis workflow connect together.
I practiced:
- Extracting stock-market data
- Sending HTTP requests
- Parsing HTML
- Web scraping
- Building Pandas DataFrames
- Cleaning raw data
- Working with dates and numeric values
- Creating visualizations with Matplotlib

## Acknowledgment

This project was developed while completing the IBM Data Analyst learning program and was reorganized into a personal portfolio project to demonstrate the Python, web-scraping, data-cleaning, and visualization techniques I practiced.
