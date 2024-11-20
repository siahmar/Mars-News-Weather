# Mars-News-Weather

### Module 11 Challenge

### Background

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their `id` and `class` attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

### What You're Creating

This new assignment consists of two technical products. You will submit the following deliverables:

* Deliverable 1: Scrape titles and preview text from Mars news articles.
* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


## Part 1: Scrape Titles and Preview Text From Mars News

**See part_1_mars_news.ipynb for code and outputs**

## Part 2: Scrape and Analyze Mars Weather Data

**See part_2_mars_weather.ipynb for code and outputs**


Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?

   * **12**
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?

   * **1867**
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? :

   * **Data indicates that the minimum temperatures on Mars reach their lowest average in the third month, while the eighth month records the highest.**
4. Which months have the lowest and the highest atmospheric pressure on Mars?

   * **The average atmospheric pressure reaches its lowest point in the sixth month and its highest point in the ninth month.**
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

* Consider how many days elapse on Earth in the time that Mars circles the Sun once.
* Visually estimate the result by plotting the daily minimum temperature.
* **Based on the Minimum Temperature vs. Number of Terrestrial Days plot, the interval between peaks, approximately from day 130 to day 800, spans about 670 days. This suggests that a year on Mars is approximately 670 days long.**
