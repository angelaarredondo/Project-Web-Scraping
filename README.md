# Project Web Scraping: Laptop and Screen Price Recommendator

## Overview:
For this project, data for laptops and screens were scraped from three different online retailers (Amazon, segundamanopc and Mediamarkt). This data will allow the users to compare the prices of different models and brands, both new and second hand, in order to find the best deal based on the user's budget and needs.

## Procedure:
This project aims to help individuals starting a new Bootcamp find the perfect laptop and screen set that meets their budget and needs, with both new and second-hand options available.

### 1. Webpage Selection and Scraping
For the initial phase of the project, we identified three websites as sources of data:

New laptops and screens:

- Amazon
- MediaMarkt

Second-hand laptops and screens:

- Segunda Mano PC

The Python library Beautiful Soup was used to extract the content from the websites.

### 2. Product building - Comparison, Criteria Choice & Output
A Python notebook was developed to provide users with two main capabilities:

1. Get an overview of the products, organized by brand
2. Find the best value products, based on the criteria of RAM for laptops and screen size for screens

The methodology for ranking products by value was:

Laptop: GB RAM / Price Screen: Screen size / Price

### 3. Extra Feature - Send info by email
The user can choose to have the requested information sent to their email address through the use of the Python library yagmail.
