# SelfProjects_WebScrap
How to Perform Web-Scraping using Node.js

Learn how to use Node.js and friends to perform a quick and effective web-scraping for single-page applications. This can help us gather and use valuable data which isn’t always available via APIs.

# What is web scraping?
Web scraping is a technique used to extract data from websites using a script. Web scraping is the way to automate the laborious work of copying data from various websites.

Web Scraping is generally performed in the cases when the desirable websites don’t expose the API for fetching the data.

# What will we need?
Getting started with web scraping is easy and it is divided into two simple parts-

1. Fetching data by making an HTTP request
2. Extracting important data by parsing the HTML DOM

We will be using Node.js for web-scraping.

We will also use two open-source npm modules:
1. axios - Promise based HTTP client for the browser and node.js.
2. cheerio - jQuery for Node.js. Cheerio makes it easy to select, edit, and view DOM elements.

In this study, we scrape the title and links of the news from the HackerNews website ('https://news.ycombinator.com').

We need some help of Chrome Developer Tools to search through the HTML of a web page and select the required data. 

