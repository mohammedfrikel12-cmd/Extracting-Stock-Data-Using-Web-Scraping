# Extracting Stock Data Using Web Scraping

This project demonstrates how to extract historical stock market data from a web page using Python web scraping techniques. The notebook focuses on downloading HTML content, parsing it with BeautifulSoup, extracting table data, and converting the results into a Pandas DataFrame.

The main goal of this project is to practice collecting structured financial data from websites when the data is not directly available through an API.

## What I Learned

Through this project, I practiced:

* Sending HTTP requests using the `requests` library
* Downloading HTML content from a web page
* Parsing HTML using `BeautifulSoup`
* Understanding basic HTML table tags such as `<table>`, `<tbody>`, `<tr>`, `<td>`, and `<th>`
* Extracting rows and columns from an HTML table
* Creating and filling a Pandas DataFrame
* Using `pandas.read_html()` to extract tables more easily
* Working with historical stock price data
* Understanding financial columns such as Date, Open, High, Low, Close, Adj Close, and Volume

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* HTML
* Jupyter Notebook

## Project Overview

The notebook includes two main approaches:

1. Manual web scraping using `requests` and `BeautifulSoup`
2. Table extraction using `pandas.read_html()`

The project first demonstrates the process using Netflix stock data, then applies the same method to Amazon stock data as an exercise.

## Note

This notebook was completed as part of a learning/course lab. I added it to my GitHub portfolio to show my understanding of how Python can be used to collect, clean, and structure data from web pages. The project helped me practice important beginner-level data analytics and web scraping skills.
