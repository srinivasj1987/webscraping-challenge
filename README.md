# Mars News and Weather Analysis
This project is focused on web-scraping and data analysis of information related to Mars. The project consists of two parts: Part 1 is a Jupyter notebook containing code that scrapes the Mars news titles and preview text. Part 2 is a Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data.

# Technical Skills
- Webscraping 
- Splinter
- Beautiful Soup
- Data analysis using Pandas
- Plotting charts using Matplotlib

# Weather Analysis
## #1. How many months exist on Mars?
<img width="811" alt="no of months on mars" src="https://github.com/srinivasj1987/webscraping-challenge/assets/132161799/20b46424-2832-4975-a609-07d5384b05d2">
<hr>
### 12 months exist on Mars

## #2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
<img width="808" alt="No of days of data" src="https://github.com/srinivasj1987/webscraping-challenge/assets/132161799/1460462d-6d08-4401-9281-a61022a3b896">

### 1867 days worth of data
<hr>

## #3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
![temperature_vs_month](https://github.com/srinivasj1987/webscraping-challenge/assets/132161799/bb73c2b8-fc0f-4e82-9684-2ed1e7540c70)

### On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the "warmest". But it is always very cold there in human terms!
<hr>

## #4. Which months have the lowest and the highest atmospheric pressure on Mars?
![atm_vs_month](https://github.com/srinivasj1987/webscraping-challenge/assets/132161799/242837cb-5246-41c7-95fb-562027fdf0a8)


### Month 6 has the lowest atmospheric pressure, while month 9 has the highest
<hr>

## #5. About how many terrestrial (Earth) days exist in a Martian year?
![No_of_days_on_mars](https://github.com/srinivasj1987/webscraping-challenge/assets/132161799/e3cabf05-d6bc-47f9-8006-6843f756d9f8)


### There are 687 Earth days in a Martian year. As visualized by the chart, the distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
<hr>

# Project Parameters
- Deliverable 1: Scrape Titles and Preview Text from Mars News (40 points)
    - Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup)
    - The titles and preview text of the news articles were scraped and extracted
    - The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries

- Deliverable 2: Scrape and Analyze Mars Weather Data
    - The HTML table was extracted into a Pandas DataFrame. Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types
    - The data was analyzed to answer all five listed questions, with data visualizations provided when specified
    - The DataFrame was exported into a CSV file 
