# Webscraping_Dataanalysis
Overview
This project looks at full web-scraping and data analysis project. After identifying the HTML elements on a page, their id and class attributes, this knowledge is used to extract
information via both automated browsing with Splinter and HTML parsing with beautiful soup.
Table of Contents

Required Libraries
The project requires the following Python libraries:

BeautifulSoup
pandas
matplotlib
Splinter

Installation
Steps include import libraries, from splinter import browser, bs4 import BeautifulSoup


Usage
Create a Beautiful Soup object and use it to extract text elements from the website.


Data
Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to scrape the data in the HTML table.
Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

Analysis
Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

Results
Summary of the findings from the analysis is included in part_2_mars_weather(1).ipynb


Contributing
Individual contributer- Nick Nath


License
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
