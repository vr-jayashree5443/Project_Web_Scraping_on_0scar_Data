# Project_Web_Scraping_on_0scar_Data

This project aims to demonstrate web scraping techniques using Python libraries such as BeautifulSoup and conducting data analysis on the scraped data. The primary focus is on extracting information from various websites and preparing a dataset for further analysis.

## Contents

### Part 1: Web Scraping
- **Libraries Used:** 
    - BeautifulSoup (Beginner Level)
    - Scrapy (Advanced Level)
- **Library Documentation:** [BeautifulSoup Documentation](https://pypi.org/project/beautifulsoup4/)
- **Sections Covered:**
    1. Import Libraries
    2. Web Scraping
    
### Detailed Steps

1. **Import Libraries:** The necessary Python libraries are imported, including numpy, pandas, matplotlib, seaborn, and BeautifulSoup from bs4.

2. **Web Scraping:** The notebook demonstrates web scraping by attempting to extract data from various websites. It includes:
    - Attempts to scrape data from Amazon, Flipkart, and Jiomart, showcasing responses received and encountered issues due to server restrictions.
    - Scraping data from Wikipedia to extract a list of Academy Award-winning films.
    - Cleaning the scraped data by identifying patterns in HTML tags and using regular expressions (regex) to extract relevant information.
    - Creating a dataset containing information about films, years, awards, and nominations.

### Dataset Creation

The dataset is created by scraping information about Academy Award-winning films from a Wikipedia page. The following columns are included:
- **Film:** Name of the film.
- **Year:** Year of the Academy Award.
- **Award:** Type of award won.
- **Nomination:** Number of nominations received.

The dataset is then cleaned to remove any unnecessary elements or discrepancies.

## Conclusion
The notebook provides an introductory demonstration of web scraping techniques using BeautifulSoup and showcases the process of extracting and cleaning data from various websites. This serves as a foundation for further data analysis and exploration.
