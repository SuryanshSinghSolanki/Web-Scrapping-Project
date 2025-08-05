# Web Scraping Project

## Overview

This project collects box office data for movies from [Box Office Mojo](https://www.boxofficemojo.com/year/) using web scraping techniques. Data is fetched with Python libraries such as `requests` (for web access) and `BeautifulSoup` (for parsing HTML).

## How to Use

### 1. Import Required Libraries

The project uses:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- BeautifulSoup
- Requests

### 2. Set the Target URL

url = "https://www.boxofficemojo.com/year/?ref_=bo_nb_di_secondarytab"


### 3. Fetch the Web Page Content

content = requests.get(url)
data = content.text


### 4. Next Steps

With the HTML content available (`data`), you can parse and extract details like movie rankings, gross earnings, release dates, and more using BeautifulSoup.

## Requirements

- Python 3.x

Install all dependencies with:

*pip install numpy pandas matplotlib seaborn beautifulsoup4 requests*


## Notes

- This project currently fetches and stores the webpage content. For full analysis, you can enhance it by implementing HTML parsing and data extraction.
- Remember to respect the website’s terms of use and avoid sending too many requests to prevent being blocked.
