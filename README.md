# Metal Scraper

## Brief description

This is a simple scraper made with Scrapy to get information about Metal bands (scraping data from metal-archives.com).

Run `scrapy crawl steelspider -o items.json` in main folder and you will get every band listed in metal-archives.com in your items.json file.
Scrapy provides automagically other exporting formats, so you can do `scrapy crawl steelspider -o items.csv` and get the output in csv.

## Requirements:

* Python
* Scrapy
