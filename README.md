# AmazPT

AmazPT is an Amazon web scraper/price tracker that scrapes data from Amazon.com based on search parameters set in the amazon_config.py file and presents the user with sorted results.

######@###.### V1.8.21.2021
Microsoft Visual Studio Community 2019
Version 16.10.4
Selenium
ChromeDriver 92.0.4515.107

Utilizes Selenium and ChromeDriver to open Amazon.com and search for products according to parameters set in "amazon_config.py". Products can be searched for and filtered using NAME, MIN/MAX PRICE, and CURRENCY type. Search results are automatically itereated through and the product, seller, price, asin, title, and link are all scraped from Amazon.com and saved to a json file in the "reports" folder. Unnecessary attributes and tracking info is removed from the URL during navigation. The lowest price offered in the result is displayed as the "Best Item" at the top of the results list.

