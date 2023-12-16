# Web Crawling and Web Scraping 
## Overview

This project focuses on web crawling and web scraping to extract information from a given website. It includes a web crawler that identifies internal and external URLs, and a web scraper that extracts specific content from a web page. The goal is to provide a basic framework that can be extended for various purposes.

## Contributors

- Nilavini B.M (21PD22)
- Varsha S (21PD39)
- PSG COLLEGE OF TECHNOLOGY

## Technologies Used

- Python
- Requests library
- BeautifulSoup library

## Project Structure

The project is structured into two main components:

1. **Web Crawler (`web_crawler`):**
    - The web crawler explores a given URL and identifies internal and external links.
    - It uses BFS (breadth-first search) to crawl multiple levels deep.
    - Internal links are stored in the `links_intern` list, and external links are stored in the `links_extern` list.

2. **Web Scraper (`web_scraper`):**
    - The web scraper focuses on extracting information from a specified web page.
    - It extracts the title, subtitles (h2), and main content (h3) of the web page.

## Usage

1. Run `web_crawler` to crawl the web pages. Enter the starting URL and the depth of crawling when prompted.
2. The program will display internal and external URLs along with suggested web pages from the same domain.

3. Run `web_scraper` and provide the URL of the web page you want to scrape.
4. The program will display the title, subtitles, and main contents of the specified web page.

## Dependencies

-Python
