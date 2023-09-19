Mars Web Scraping and Data Analysis

Part 1:

Step 1: Automated Browsing and Data Extraction
I will start by using automated browsing to visit the Mars News website. I will inspect the page to identify the HTML elements that contain the information I need.

Step 2: Data Storage
Once I identify the necessary elements, I will create a Beautiful Soup object to extract the text elements from the website. I will then store the scraped data in Python data structures as follows:

Step 3: Data Presentation
I will print the list of scraped data in my Jupyter Notebook for review.



Part 2: Scrape and Analyze Mars Weather Data

In this part, I will use automated browsing to visit the Mars Temperature Data Site and scrape weather data. I will then analyze the data.

Step 1: Automated Browsing and Data Extraction
 
I will visit the Mars Temperature Data Site and inspect the page to identify the elements that contain the   weather data. I will create a Beautiful Soup object to scrape the data from the HTML table.

Step 2: Data Assembly

I will assemble the scraped data into a Pandas DataFrame with the following columns:

    id: Identification number of a transmission from the Curiosity rover.
    terrestrial_date: The date on Earth.
    sol: The number of elapsed sols (Martian days) since Curiosity landed on Mars.
    ls: The solar longitude.
    month: The Martian month.
    min_temp: The minimum temperature (in Celsius) of a single Martian day (sol).
    pressure: The atmospheric pressure at Curiosity's location.



Data Analysis

I will analyze the data using Pandas functions to answer the following questions:

    How many months exist on Mars?
    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this     question, I will find the average minimum daily temperature for all months and plot the results as a bar chart.
    Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question, I will   find the average daily atmospheric pressure of all months and plot the results as a bar chart.
    About how many terrestrial (Earth) days exist in a Martian year? To answer this question, I will consider   how many days elapse on Earth in the time that Mars circles the Sun once. I will also visually estimate the   result by plotting the daily minimum temperature.



Data Export

Finally, I will export the DataFrame to a CSV file for further analysis or sharing.
This project will showcase my skills in web scraping, data extraction, data analysis, and data presentation.
