# Exploratory Analysis of The Housing Market In Västra Götaland (Sweden)

As a potential first time buyer, you view a house that you like, it's within your budget and in the right location. You decide that YES, this is the house for you, only to see the bidding start and immediately soar... The closing price finishes 35% over starting price at which point you realise that you know next to nothing about this market!

This was the motivation for this project. The aim is to gain a better understanding of the local housing market and answer questions such as, what is the average expected price increase, which areas are most popular for our target house and is the variances within a kommun which would make certain areas more desirable.

Our dataset has been scraped from hemnet.se which is a popular listing website in Sweden and offers data on sale prices and percentage change between the list price and closing price.

The project was started to scrape, clean and analyze house price data for the region of Västra Götaland in Sweden for a specific criteria. The inspiration for this project was to get a greater understanding of the housing market and understand basic metrics such as mean and median price differences, mean sale prices in target locations, temporal and spacial trends.

The criteria for the house price data is as follows:

 - Västra Götalands Län
 - Villa
 - Rooms min 3,5
 - min final price 1,750,000kr
 - max final price 4,000,000kr
 - Last 12 months

The result of our webscraping algorithm was 2181 datapoints from June 2019, June 2020. Our analysis mainly focuses on a specific area in Västra Götaland as this is the area most interesting to us. There are many more possibilities for this dataset which may be returned to at a later date. 

Techniques

- Data cleaning
- Exploratory data analysis
- Matplotlib
- Python / Jupyter notebook
- Seaborn
- Web scraping - Beautiful Soup

Projects can be viewed using nbviewer (https://nbviewer.jupyter.org/) if Github's ipynb glitch continues.
