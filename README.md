# Data_collection

This challenge was a full web-scraping and data analysis project. This new assignment consists of two technical products. Submited are the following deliverables:

* Deliverable 1: Scrape titles and preview text from Mars news articles.

* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News

> ### Results (Python dictionary of each title and preview text):

![alt text](https://github.com/AnitaGj1/Data_collection-challenge/blob/main/Images/mars_news.png)

## Part 2: Scrape and Analyze Mars Weather Data

1. Use automated browsing to visit the Mars Temperature Data Site [link](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Inspect the page to identify which elements to scrape. 

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. 

3. Assemble the scraped data into a Pandas DataFrame. 

![alt text](https://github.com/AnitaGj1/Data_collection-challenge/blob/main/Images/mars_facts_df.png)

4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyze the dataset by using Pandas functions to answer the following questions:

* How many months exist on Mars?

* How many Martian (and not Earth) days worth of data exist in the scraped dataset?

* What are the coldest and the warmest months on Mars (at the location of Curiosity)?

![alt text](https://github.com/AnitaGj1/Data_collection-challenge/blob/main/Images/AverageTempByMonthDesc.png)

> On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

* Which months have the lowest and the highest atmospheric pressure on Mars?

![alt text](https://github.com/AnitaGj1/Data_collection-challenge/blob/main/Images/AveragePressureByMonth.png)

> Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

* About how many terrestrial (Earth) days exist in a Martian year? 

![Alt text](https://github.com/AnitaGj1/Data_collection-challenge/blob/main/Images/MartianYear.png)

> The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year  > is equivalent to 687 earth days.

6. Export the DataFrame to a CSV file.

