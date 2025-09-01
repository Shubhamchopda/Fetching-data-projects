# Fetching-data-projects

### 1. Web Scraping Books.toscrape.com 📚

This project demonstrates a simple web scraping script written in Python. It's designed to extract book information from the `books.toscrape.com` website, which is a great site for practicing web scraping.

The script uses the **`requests`** library to send an HTTP request to the website and the **`BeautifulSoup`** library to parse the HTML content.

---

### Key Features ✨

* **Data Extraction**: The script iterates through 50 pages of the website to collect data for a total of 1000 books.
* **Information Scraped**: It extracts the following details for each book:
    * **Book Name** 📖
    * **Price** 💰
    * **Stock Availability** ✅
    * **Star Rating** ⭐
* **Data Structuring**: The collected data is stored in lists, which are then used to create a **Pandas DataFrame** for easy viewing and analysis.
* **Output**: The final DataFrame contains organized columns for each piece of information, as shown in the output of the `df.head()` command.

### ✨ 2. Fake Store API Data Analysis: A Python Project

This project is a simple yet effective demonstration of how to leverage Python libraries like **requests** and **pandas** to interact with a RESTful API, specifically the **Fake Store API**, and transform the retrieved data into a structured format for analysis.

-----

### 🛠️ Key Features

  * **API Connection**: The notebook starts by using the `requests` library to fetch product data from the Fake Store API endpoint. This is the first step in any web-based data acquisition.
  * **Data Wrangling**: The raw JSON data received from the API is then parsed and converted into a highly versatile **pandas DataFrame**. This makes it easy to organize and manipulate the data.
  * **Targeted Data Selection**: We focus on what's important\! The code creates a clean DataFrame that includes only the essential product details: **'title'**, **'category'**, and **'price'**.
  * **Feature Engineering**: The project goes a step further by extracting the product **'rating'** from the nested JSON response and adding it as a new **'rate'** column. This enriches the dataset, making it more useful for analysis.

-----



-----
