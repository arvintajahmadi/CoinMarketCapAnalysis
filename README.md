# CoinMarketCapAnalysis

This project was consisted of 4 main parts:
+ Data gathering (web scraping)
+ Storing the data in a database
+ Insight extracting with statistical methods
+ Turning insights into visuals using Microsoft PowerBI

This project was done by a group of 4 in 2 weeks.
The project was presented to the project owner (Quera IT Consulting and Education) and was scored 99.5/100 by the respective company auditing team. 

## Data Gathering
In this phase we used both bs4 abd selenium in python to scrape the data from CoinMarketCap.com. We used data from August 23rd in a 365 days period based on websites' options.

## Database Design and Data Entry
Using SQL Alchemy python ORM, we entered the scraped data into the exclusively designed database.

## Statistics
Based on the project needs, implemented different hypothesis testing models on normal and exponential data groups using T-tests and U-tests. We even tried to go further and used Box-Cox Transformation and later Yeo-Johnson transformation to test the data in different distributions. Finally we were able to help the project owner via accurate results in the statistics part.

## Visualization
Using the same data stored in our database, we used Microsoft PowerBI to visualize and present our statistical and non-statistical implications of the data and it future trends. 