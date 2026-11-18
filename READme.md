# Objective
Objective of this repo is to create a bare-bones web-crawler(scraper) to collect and analyze market
sentiments for a given organization, industry etc. 
1. Web-crawler should not use more than 1000 seed URLs and not more than Few GBs of storage for 
analytical database.
2. Web-crawler can get rid of data older than a month.
3. The market segment should be quantified e.g. bearish, bullish etc.

## Architecture
High-level Design of Web-crawler is as follows:
1. Core Crawler: URL Fetcher, Scheduler and Proxy Pool, Scraping layer
2. Parsing and NLP Pipeline
3. Storage & Messaging Infra
4. Observability and Monitoring
