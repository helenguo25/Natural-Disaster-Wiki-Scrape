# Natural-Disaster-Wiki-Scrape

This project uses R to web scrape the following Wikipedia page on natural disasters (https://en.wikipedia.org/wiki/List_of_natural_disasters_by_death_toll) and create an interactive plot for death toll for the deadliest natural disasters in each year during the 20th and 21st centuries, color-coded by type of disaster.

Download Natural_Disaster_Wiki_Scrape.html to view the interactive plot and R code used to scrape the Wikipedia tables/create the plot. Alternatively, to recreate the html file locally, download Natural_Disaster_Wiki_Scrape.Rmd and change the working directory to your local file before running/marking down.
   
The vertical (y-axis) of the interactive plot displays death toll (in thousands) while the horizontal (x-axis) shows the year of the natural disaster. Type of natural disaster is color-coded. Hover over each annual data point in the plot for a detailed breakdown (e.g. in 1900, the deadliest natural disaster was a tropical cyclone which resulted in an estimated death toll of 7,000). See code comments under 'Web Scrape and Clean' section for details on how death tolls were estimated.

Resources referenced in the creation of this project
1. https://www.r-bloggers.com/2021/07/politely-scraping-wikipedia-tables-2/
2. https://www.r-bloggers.com/2022/04/a-simple-introduction-to-ggplot2-for-plotting-your-data/
3. https://www.r-bloggers.com/2021/07/simplevis-interactive-plots-with-plotlyggplotly/
