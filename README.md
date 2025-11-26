# Scraping Data from a Real Website | Web Scraping in Python

This project demonstrates how to scrape structured data from a real website using Python.  
The notebook walks through each step of the process—from sending an HTTP request to parsing HTML and extracting useful information such as table headers and rows.  

The goal is to understand practical web scraping using Python, BeautifulSoup, and basic data handling.


## 📌 Features

- Fetching a webpage using `requests`
- Parsing HTML using `BeautifulSoup`
- Locating and extracting:
  - Tables
  - Headers (`<th>`)
  - Rows (`<tr>`, `<td>`)
- Converting scraped data into clean Python lists
- Printing and displaying results for further analysis


## 📦 Requirements / Installations

Before running the notebook, install the required Python libraries:

```bash
pip install requests
pip install beautifulsoup4
pip install lxml
