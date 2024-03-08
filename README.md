# Web Scraping Libraries
This document provides an overview of the key libraries commonly used for web scraping in Python. These libraries offer a variety of functionalities to extract data from websites efficiently.

Table of Contents
Requests
Beautiful Soup
Selenium
Scrapy
LXML

Requests
Requests is a simple and straightforward HTTP library for sending HTTP requests. It allows you to make HTTP requests and handle responses easily. While it is not a scraping library itself, it is often used in combination with other libraries for making HTTP requests to fetch web pages.
Command to install
pip install requests


Beautiful Soup
Beautiful Soup is a powerful library for pulling data out of HTML and XML files. It provides Pythonic idioms for iterating, searching, and modifying the parse tree. Beautiful Soup sits on top of popular Python parsers like lxml and html5lib, allowing you to choose the parsing method.
Command to install 
pip install beautifulsoup4

Selenium
Selenium is a browser automation tool that is often used for scraping dynamic websites where content is loaded using JavaScript. It allows you to control a browser programmatically, interact with web elements, and handle AJAX requests.
Command to install
pip install selenium


Scrapy
Scrapy is an open-source web crawling framework for Python. It provides an integrated way to follow links and extract data from websites. Scrapy is designed for efficiency and allows you to define the data extraction process through spiders.
Coomand to install 
pip install scrapy


LXML
LXML is a high-performance, production-quality XML and HTML parsing library. It provides a Pythonic API for working with XML and HTML documents. LXML is often used in combination with Beautiful Soup for parsing and navigating HTML content.
pip install lxml




