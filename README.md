# Fetching-data-projects
Different ways to collect data using python <br>
**ALL PROJECTS INFO**<br>

Web Scraping Books.toscrape.com 📚
This project demonstrates a simple web scraping script written in Python. It's designed to extract book information from the books.toscrape.com website, which is a great site for practicing web scraping.

The script uses the requests library to send an HTTP request to the website and the BeautifulSoup library to parse the HTML content.

Key Features ✨
Data Extraction: The script iterates through 50 pages of the website to collect data for a total of 1000 books.

Information Scraped: It extracts the following details for each book:

Book Name 📖

Price 💰

Stock Availability ✅

Star Rating ⭐

Data Structuring: The collected data is stored in lists, which are then used to create a Pandas DataFrame for easy viewing and analysis.

Output: The final DataFrame contains organized columns for each piece of information, as shown in the output of the df.head() command.
