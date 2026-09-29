CodSoft Task 5 – Web Scraping & Data Analysis
📌 Project Overview

This project is part of the CodSoft Data Analytics Internship – Task 5. The objective is to collect publicly available data from a website using Python, clean and organize the scraped information, perform exploratory data analysis, identify trends and patterns, and export the final dataset.

🎯 Objectives
Collect data from a publicly available website
Use Requests and BeautifulSoup for web scraping
Extract structured product information
Clean and preprocess the collected data
Perform exploratory data analysis
Identify trends and patterns
Create meaningful visualizations
Export the results to CSV and Excel
Automate the scraping process for multiple pages
🛠️ Technologies Used
Python
Requests
BeautifulSoup
Pandas
NumPy
Matplotlib
Seaborn
Google Colab
CSV
Excel
🌐 Data Source

The project uses Books to Scrape, a publicly available website designed for web-scraping practice.

Website: https://books.toscrape.com/

📊 Data Collected

The scraper collects information such as:

Product/Book Title
Price
Rating
Availability
🔄 Project Workflow
Public Website
      ↓
Requests
      ↓
BeautifulSoup
      ↓
Web Scraping
      ↓
Raw Data
      ↓
Data Cleaning
      ↓
Pandas DataFrame
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
CSV / Excel Export
🧹 Data Cleaning

The collected data is cleaned by:

Removing currency symbols and unwanted characters
Converting prices into numeric values
Converting ratings into numerical values
Cleaning availability text
Checking missing values
Removing duplicate records
Resetting the DataFrame index
📈 Exploratory Data Analysis

The project analyzes:

Average product price
Minimum and maximum price
Rating distribution
Most expensive products
Cheapest products
Price distribution
Relationship between price and rating
Product availability
📊 Visualizations

The project includes visualizations such as:

Price Distribution Histogram
Rating Distribution Bar Chart
Average Price by Rating
Top 10 Most Expensive Products
Price vs Rating Scatter Plot
Product Availability Chart
Price Box Plot
Correlation Heatmap
🤖 Automation

The scraper can automatically process multiple website pages using a Python loop. This allows the dataset to be collected and updated without manually scraping each page.

📁 Project Files
CodSoft-Task-5/
│
├── CodSoft_Task-5.ipynb
├── codsoft_task5_scraped_data.csv
├── codsoft_task5_scraped_data.xlsx
└── README.md
🚀 How to Run
Open the .ipynb file in Google Colab.
Install the required libraries.
Run the scraping cells.
Create the Pandas DataFrame.
Clean the data.
Perform exploratory analysis.
Generate visualizations.
Export the cleaned dataset to CSV and Excel.
💡 Key Outcome

This project demonstrates the complete data analytics workflow from web data collection to data cleaning, exploratory analysis, visualization, and automated export, providing practical experience with Python-based web scraping and data analysis.
