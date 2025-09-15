# 📈 Extracting and Visualizing Stock Data

This project is part of the **IBM Course: Python for Data Science, AI and Development**.  
It focuses on **data extraction, cleaning, and visualization** using real-world stock and revenue data.

## 🗂️ Project Overview
For this project, I will assume the role of a Data Scientist / Data Analyst working for a new startup investment firm that helps customers invest their money in stocks. My job is to extract financial data like historical share price and quarterly revenue reportings from various sources using Python libraries and webscraping on popular stocks. After collecting this data you will visualize it in a dashboard to identify patterns or trends. The stocks we will work with are Tesla, Amazon, AMD, and GameStop.

## 🛠️ Tech Stack & Libraries  

- **Core**
  - ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
  - ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
  - ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)

- **Data Extraction**
  - ![yFinance](https://img.shields.io/badge/yFinance-000000?logo=yahoo&logoColor=white)
  - ![Requests](https://img.shields.io/badge/Requests-20232A?logo=python&logoColor=white)
  - ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?logo=python&logoColor=white)
  - ![lxml](https://img.shields.io/badge/lxml-0B4F6C?logo=python&logoColor=white)

- **Visualization**
  - ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
  - ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
## 📊 Key Steps
1. **Data Collection**
   - Stock data for Tesla, Amazon, AMD, and GameStop via `yfinance`.
   - Revenue data scraped from company financial pages with BeautifulSoup & `read_html`.

2. **Data Cleaning**
   - Removed commas, dollar signs, and missing values from revenue columns.
   - Converted date strings into datetime objects.

3. **Data Visualization**
   - Created subplots showing **stock price vs. revenue** for each company.
   - Used `plotly.graph_objects` with interactive features like hover tooltips and zoom.

## 🎯 Learning Outcomes
- Hands-on experience with data extraction APIs (yfinance)
- Practiced web scraping using BeautifulSoup and pandas.read_html
- Applied data cleaning techniques (regex, missing values handling)
- Built interactive dashboards with Plotly

## 📜 Certificate
<p align="center"> <img src="https://github.com/user-attachments/assets/c754701f-6999-4519-9a7e-c84e839581e5" alt="IBM Certificate" width="500"/> </p>

