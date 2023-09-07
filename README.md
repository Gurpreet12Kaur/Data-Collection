# Data-Collection
Challenge 11 background:
I'm now ready to take on a full web-scraping and data analysis project. I've learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. I've also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

Part 1: Mars News Scraping
In Part 1 of the challenge, I used automated browsing techniques and Beautiful Soup to scrape data from the Mars News website. I identified the elements containing titles and preview text of news articles, extracted this information, and stored it in a Python list. Each article was represented as a dictionary with two keys: 'title' and 'preview'. An example of the data structure looked like this:

Part 2: Mars Weather Data Scraping and Analysis
In Part 2, I continued with web scraping, this time focusing on Mars weather data. I visited the Mars Temperature Data Site and used Beautiful Soup to scrape data from the HTML table. After assembling the scraped data into a Pandas DataFrame, I analyzed the dataset by performing various tasks:
Determined the number of months on Mars.
Calculated the number of Martian days (sols) worth of data in the dataset.
Identified the coldest and warmest months on Mars by finding the average minimum daily temperature for all months and visualizing it in a bar chart.
Identified the months with the lowest and highest atmospheric pressure on Mars by finding the average daily atmospheric pressure for all months and plotting the results in a bar chart.
Estimated the number of terrestrial (Earth) days in a Martian year by considering how many Earth days it takes for Mars to orbit the Sun once. I also visualized this data using the daily minimum temperature.
Finally, I exported the DataFrame to a CSV file for further use.


Overall, these two parts of the project involved web scraping techniques, data extraction, data manipulation using Pandas, and data analysis to gain insights into Mars news articles and weather patterns. Part 2 was much more challenging compared to Part 1. A few things I struggled with were "# 3. What is the average low temperature by month?# Calculate average weather by month", "# Identify the coldest and hottest months in Curiosity's location", and # 5. How many terrestrial (Earth) days are there in a Martian year? I had to go back to the lecture and going over the task really helped. I also had to watch a few Youtube videos. 
