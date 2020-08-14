# amazon-scraper

A simple amazon scraper to extract product details and prices from Amazon.com using Python Requests and Selectorlib.
Selectorlib is combination of two packages. A chrome extension that lets you markup data on websites and export a YAML file with it. A python library that reads this YAML file, and extracts the data you marked up on the page.

From a terminal 

1. Clone this project  `git clone https://github.com/anis-agwan/amazon-scraper.git` and cd into it `cd amazon-scraper`
1. Add a Virtual Environment `python3 -m venv .venv` (Optional)
1. Activate the Virtual Environment `source .venv/bin/activate` (Optional) 
1. Install Requirements `pip3 install -r requirements.txt`

## Scrape Products from Search Results

1. Add Amazon Product URLS to [search_results_urls.txt](search_results_urls.txt)
1. Run `python3 searching.py`
1. Get data from [search_results_output.jsonl](search_results_output.jsonl)
