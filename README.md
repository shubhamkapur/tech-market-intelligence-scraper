# tech-market-intelligence-scraper

Status: Work In Progress 

Description
This project is a web scraper designed to extract each brand hardware products from Flipkart. Currently, the scraper is in its alpha phase. It successfully navigates the target site and extracts raw data into a CSV format for initial analysis.

Current State
The scraper is functional but "unrefined". At present the output we get is a .csv file which do have information about laptop brands available on flipkart along with their customer reviews and specifications  

Success: It generates a raw_output.csv containing Brand, Model, Selling price, original price, Customer ratings, Specifications.

WIP: Data cleaning, error handling for pagination, and rate-limiting features are still under development.

Libraries: [e.g., BeautifulSoup4, Selenium, Playwright, Pandas]

Storage: CSV (Local)

Usage: To run the scraper and generate the rough CSV:

Known Issues / Rough Edges
Since this is a WIP, please note the following:

Data Consistency: Some fields in the CSV may contain HTML tags or whitespace that require manual cleaning.80% data available is now clean.
