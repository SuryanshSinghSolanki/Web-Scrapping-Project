# Web-Scrapping-Project
Overview
This project collects box office data for movies from Box Office Mojo using web scraping techniques. The data is fetched using Python libraries such as requests to handle HTTP requests, and BeautifulSoup to parse the HTML content of web pages.

How to Use
Import Required Libraries
The project uses popular Python libraries including NumPy, Pandas, Matplotlib, Seaborn, BeautifulSoup, and Requests.

Set the Target URL
The URL containing the yearly box office data is defined as:

python
url = "https://www.boxofficemojo.com/year/?ref_=bo_nb_di_secondarytab"
Fetch the Web Page Content
Using requests.get(), the HTML content of the page is downloaded:

python
content = requests.get(url)
data = content.text
Next Steps
With the HTML content available, you can parse and extract specific data such as movie rankings, grosses, release dates, and more by using BeautifulSoup.

Requirements
Make sure you have Python 3 installed along with the following libraries:
numpy, pandas, matplotlib, seaborn, beautifulsoup4, and requests.

You can install these dependencies via pip:

bash
pip install numpy pandas matplotlib seaborn beautifulsoup4 requests
Notes
This project currently fetches and stores the webpage content. You can further enhance it by implementing data extraction and analysis.

Remember to respect the website’s terms of use and avoid sending too many requests to prevent being blocked.
