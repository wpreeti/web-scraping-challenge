# web-scraping-challenge

In this challenge we identify HTML elements on a page, identify their id and class attributes, and use them to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

Problem details




Part 1: Scrape Titles and Preview Text from Mars News

We start with the "part_1_mars_news.ipynb" Jupyter Notebook to scrape the Mars News website.
Use automated browsing to visit the Mars news site to an external site.. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to extract text elements from the website.
Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
Store all the dictionaries in a Python list.
Print the list in your notebook.
Store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.
Part 2: Scrape and Analyze Mars Weather Data

Open the Jupyter Notebook named "part_2_mars_weather.ipynb" to scrape and analyze Mars weather data.
Use automated browsing to visit the Mars Temperature Data Site Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to scrape the data in the HTML table.
Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column.
Analyze your dataset by using Pandas functions to answer the following questions:
How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.
Instructions to run

Part 1: Scrape Titles and Preview Text from Mars News

Activate conda dev enrivornment from the bash
Launch Jupter from Anaconda Navigator
Open "part_1_mars_news.ipynb"
Run all cells

Part 2: Scrape and Analyze Mars Weather Data

Activate conda dev enrivornment from the bash
Launch Jupter from Anaconda Navigator
Open "part_2_mars_weather.ipynb"
Run all cells
"mars_weather.csv" is located under output folder

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
