# DeFi Llama Twitter Handle Scraper

## Overview:
This project involves scraping Twitter handles of various DeFi protocols listed on the DeFi Llama website using Selenium. The process includes first gathering the links of all the protocols and then extracting the Twitter handles from each protocol's page.

## Features:
- Utilizes Selenium for web scraping.
- Collects links of all DeFi protocols listed on the DeFi Llama website.
- Extracts Twitter handles of each protocol.
- Outputs a text file containing protocol links and a CSV file containing the Twitter handles.

## Dependencies:
- Python 3.x
- Selenium
- Webdriver (Chrome/Firefox)
- scrapeops.io API key (for rotating user agents)

## Usage:
1. Open the `script_defillama.ipynb` notebook file.
2. Make sure you have installed the necessary dependencies.
3. Execute the notebook cells to run the scraping process.
4. The output will be a text file containing protocol links (`protocols_links.txt`) and a CSV file containing the Twitter handles (`twitter_handles.csv`).

## Note:
- Ensure you have the appropriate webdriver installed and configured for Selenium (Chrome/Firefox).
- To ensure proper usage and prevent detection, consider providing an API key from scrapeops.io to rotate user agents. This can be done by making a request to scrapeops.io to get a list of different user agents, ensuring a more robust scraping process.
- Respect the website's terms of service and use the scraper responsibly.
- Ensure compliance with any legal or ethical guidelines regarding web scraping.
