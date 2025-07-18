# 📚 Book Price Scraper and Visualizer

This project is a simple web scraping and data visualization tool that extracts book titles and prices from [Books to Scrape](http://books.toscrape.com/), converts prices from GBP to INR, saves the data to a CSV file, and visualizes the book prices using a bar chart.

## 🚀 Features

- Scrapes book titles and prices from the first page of [books.toscrape.com](http://books.toscrape.com/)
- Converts prices from GBP to INR (using a custom conversion rate)
- Stores the data in a structured format using Pandas
- Saves data to a CSV file
- Visualizes book prices in INR using Seaborn bar plot

## 🧰 Technologies Used

- Python
- BeautifulSoup (for web scraping)
- Requests (for HTTP requests)
- Pandas (for data manipulation)
- Matplotlib & Seaborn (for visualization)

## 📦 Requirements

Install the required libraries using:

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn
