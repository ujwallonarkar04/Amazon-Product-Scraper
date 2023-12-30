# Amazon-Product-Scraper
Python script for Amazon India's bags fetches product data using requests, BeautifulSoup, pandas. It extracts URLs, names, prices, ratings, reviews across pages. 'scrape_product_info' function fetches descriptions, ASINs, manufacturers from product page

This repository contains a Python script designed to scrape Amazon India for bag-related product information. The scraper uses Python libraries like requests, BeautifulSoup, and pandas.

# Instructions
Install the required libraries mentioned in the requirements.txt file.
Run the main script (amazon_product_scraper.py) after configuring the base URL and specifying the range of pages to scrape.
The script outputs a CSV file (amazon_products.csv) containing the scraped data, including product URL, name, price, rating, and number of reviews.
Additionally, it provides a function to extract further details (description, ASIN, product description, manufacturer) from individual product pages.

# Usage

Ensure Python is installed on your system.
Install the necessary libraries using pip install -r requirements.txt.
Run the script and specify the page range to scrape.
The script generates a CSV file with the collected data.
Utilize the function to extract detailed product information from individual URLs.
