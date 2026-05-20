# Bookstore-Web-Scraper
Bookstore Web Scraper 📚

📌 Project Overview

This project is a Python-based web scraper that automatically extracts product information from a fictional online bookstore (books.toscrape.com). The goal of this project was to practice web scraping techniques and build a custom dataset from scratch.

🛠️ Tools & Libraries Used

Python: The core programming language.

Requests: Used to send HTTP requests to the website and download the raw HTML content.

BeautifulSoup (bs4): Used to parse the HTML and extract specific data points (tags, classes).

Pandas: Used to structure the scraped data into a clean, readable DataFrame and export it as a CSV file.

📊 Data Extracted

The scraper successfully extracts the following details for the books on the webpage:

Book Title

Price (in £)

Star Rating (One to Five stars)

🚀 How to Run the Code

Open the book_scraper.ipynb notebook in Google Colab or Jupyter Notebook.

Run the cells sequentially.

The final cell will generate and download a scraped_books.csv file containing the clean dataset.
