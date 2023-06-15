# mars_challenge
Module 11 Challenge

This repo consists of 2 Juypter Notebooks for analyzing the Mars News and Mars Temperature Data websites and an output_data folder for CSV and JSON exports:

Websites used: https://static.bc-edx.com/data/web/mars_news/index.html
              https://static.bc-edx.com/data/web/mars_facts/temperature.html

1. part_1_mars_news.ipynb - scrapes titles and preview text from the Mars News site and compiles them into a list of dictionaries. This list is also exported as a JSON file for future use.
   
2. part_2_mars_weather.ipynb - scrapes the weather data from the table to analize. A Pandas db is created and exported as CSV.
   Database is used to determine:
     - How many months exist on Mars?
     - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
     - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
     - What is the average minimum daily temperature for all of the months (plotted to bar chart)
     - Which months have the lowest and the highest atmospheric pressure on Mars? (plotted to bar chart)
     - About how many terrestrial (Earth) days exist in a Martian year?
  
  3. output_data - contains mars_articles.json from part 1 and mars_data.csv from part2
