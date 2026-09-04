# 🔎 Python Job Listings Scraper

A Python web scraping project that automatically extracts job listings from a website and organizes the collected information into a structured dataset.

## 📌 About the Project

**Python Job Listings Scraper** is a web scraping application developed with Python.  
The main goal is to automate the collection of job offers and avoid manually browsing job websites.

The scraper retrieves useful information such as:

- 💼 Job title
- 🏢 Company name
- 📍 Location
- 🔗 Job offer URL

The extracted data can then be stored in a CSV file and analyzed using Python, Pandas, Excel, Power BI, or other data analysis tools.

## 🛠️ Technologies Used

- 🐍 **Python**
- 🌐 **Requests** — to send HTTP requests
- 🍲 **BeautifulSoup** — to parse and extract information from HTML pages
- 🐼 **Pandas** — to structure and manipulate the collected data
- 📄 **CSV** — to store the results

## 🏗️ Project Architecture

```text
Job Website
     │
     ▼
  Requests
     │
     ▼
  HTML Page
     │
     ▼
 BeautifulSoup
     │
     ▼
Extract Job Listings
     │
     ▼
    Pandas
     │
     ▼
  CSV Dataset
