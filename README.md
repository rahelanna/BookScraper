## Scrapy Project - Tutorial Based
### Overview

This project is a web scraping application built using the Scrapy framework, based on the [FreeCodeCamp Scrapy Beginner's Course](https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-1-overview/). The tutorial provides a comprehensive guide for beginners to understand and implement web scraping with Scrapy.

### Features
- **Tutorial-Based Implementation:** The project follows the step-by-step instructions provided in the tutorial.
- **Basic Spider Creation:** Learn how to create and customize spiders for web scraping.
- **Data Extraction:** Extract data such as titles, links, and other relevant information from web pages.
- **Export Options:** Export scraped data to JSON, CSV, and other formats.
- **Customizable and Extensible:** While the project starts simple, it can be expanded and modified for more complex scraping tasks.

### Installation

**1. Clone the repository**
```
git clone https://github.com/rahelanna/BookScraper
cd BookScraper
```

**2. Create a virtual environment**
```
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
**3. Install dependencies**
```
pip install -r requirements.txt
```

### Usage

**1. Run the spider**
```
scrapy crawl bookspider
```

**2. Export data**
```
scrapy crawl bookspider -o quotes.json
```
