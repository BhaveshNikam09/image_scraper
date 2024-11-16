## Image Scraper
### Description
The Image Scraper is a Python-based web scraping tool that allows users to download images from a given URL or a set of URLs.
This tool leverages the requests, BeautifulSoup, and os libraries to extract image URLs from web pages and save them locally on your machine.

### Features:

    1.Scrapes images from any webpage URL.
    2.Allows users to download images to a specified directory.
    3.Supports downloading images from multiple URLs.
    4.Handles errors gracefully, ensuring a smooth scraping experience


### Script Overview
#### 1.app.py

  his script does the following:

  1.Extracts image URLs from a webpage using BeautifulSoup.
  
  2.Downloads images from the extracted URLs and saves them locally.
  
  3.Handles errors such as missing images or connection issues.
