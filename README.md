# Mars Data Scraper and Analysis Project

## Overview
This project involves two main parts: scraping titles and preview text from Mars news, and scraping and analyzing Mars weather data. The goal is to extract, analyze, and visualize Martian data using Python tools like Splinter, BeautifulSoup, and Pandas.

## Part 1: Scrape Titles and Preview Text from Mars News (40 points)

### Objectives
- **Automated Browsing**: Utilize Splinter for automated browsing to visit the Mars news site and extract HTML code. (10 points)
- **Data Scraping**: Employ BeautifulSoup to scrape the titles and preview text of the news articles. (20 points)
- **Data Storage**: Store the scraped information in a Python data structure, specifically a list of dictionaries. (10 points)

## Part 2: Scrape and Analyze Mars Weather Data (60 points)

### Objectives
- **Data Extraction**: Extract the HTML table into a Pandas DataFrame using either Pandas or a combination of Splinter and BeautifulSoup. Ensure columns have correct headings and data types. (15 points)
- **Basic Data Analysis**: Analyze the data to answer:
  - How many months exist on Mars? (5 points)
  - How many Martian days' worth of data are there? (5 points)
- **Advanced Data Analysis and Visualization**: Further analyze the data and create visualizations to answer:
  - Which month, on average, has the lowest and highest temperature? (10 points)
  - Which month, on average, has the lowest and highest atmospheric pressure? (10 points)
  - Estimate how many terrestrial days exist in a Martian year, with a visual estimate within 25% accuracy. (10 points)
- **Data Export**: Export the DataFrame into a CSV file. (5 points)

## Tools and Technologies
- Python
- Splinter
- BeautifulSoup
- Pandas
- Data Visualization Libraries (Matplotlib)
