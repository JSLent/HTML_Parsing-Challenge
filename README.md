# HTML_Parsing-Challenge
Repo for Module 11 Challenge

# Mars Exploration Data Analysis

## Overview
This challenge for Module 11 involves two main deliverables.  The first is scraping titles and preview text from https://static.bc-edx.com/data/web/mars_news/index.html and the second is scraping and analyzing Mars Weather Data from https://static.bc-edx.com/data/web/mars_facts/temperature.html.  The goal is to automate the browsing process, identify required elements to scrape using BeautifulSoup, store the results in DataFrames, and perform data analysis.  

## Technology used
- Python
- Splinter
- BeautifulSoup
- Pandas
- Matplotlib

## Dependencies
To run these notebooks, you will need to have the following installed:
- Python 3
- Splinter
- BeautifulSoup4
- Pandas
- Matplotlib

## Installation
To set up the environment for this challenge follow these steps:
1. Install Python 3 if not already installed
2. Install the required packages

## Usage
To run the scripts, navigate to the directory containing the notebook and run: python -m notebook to open the mars_news_scraper.ipynb and mars_weather_analysis.ipynb files and run all cells to perform the scraping and analysis.  

### Part 1 Steps
1. **Visit the Mars News Site**: via automated browsing, visit https://static.bc-edx.com/data/web/mars_news/index.html to inspect the page and identify elements to scrape
2. **Scrape the Site**: A BeautifulSoup object is created to extract the text elements from the site
3. **Store the Results**: The titles and preview text of the news articles are extracted and stored in dictionaries which are added to a list

### Part 2 Steps
1. **Visit the Mars Temperature Site**: via automated browsing, visit https://static.bc-edx.com/data/web/mars_facts/temperature.html to inspect the page and identify elements to scrape
2. **Scrape the Table**: A BeautifulSoup object is created to scrape the data in the table
3. **Store the Data**: The data scraped is assembled into a Pandas DataFrame
4. **Prepare The Data For Analysis**: Display the data types of the table and set appropriate data types for analysis
5. **Analyze the Data**: Answer supplied questions about the Martian Data
6. **Save the Data**: Data is exported to a CSV stored in the Starter_Code Directory

