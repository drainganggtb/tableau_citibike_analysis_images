# Citi Bike Analysis NYC
I tasked myself to create a set of Tableau visualizations to be combined in dashboards and stories for [Citi bike data](https://www.citibikenyc.com/system-data) provided by NYC Bike Share.
![alt text](citibike.jpg)

## Task
Data needed to be aggregated, so I chose to make visualizations on data from **July to December 2019**. Next, unique phenomena were identified and visualized. In order to fully categorize trends from the six month time period, I chose to make separate dashboards for summary statistics and maps, rider data/demographics, and ride distance/length themes. 

![union](union.png)

Additionally, each dashboard is complimented by analysis describing the trends that were identified. 

## Other notes
Given that the dataset was divided between Customers and Subscribers to the Citi Bike service, it could be assumed that not all data was accurate for those who are not subscribed in the system. 
The following image shows what I describe as the **"69 effect"**, where I propose that customers providing information in a hurry, or knowing that they are not taking many rides in the future, are prone to providing fake information, which although anonymizing, does not provide accurate data. This is all to communicate that way too many people chose **1969** as their birth year. The oldest birth year and the coordinates 0,0 also produced unintended outliers. 

![69](69effect.png)

Becuase the dataset that was created is composed of over 11,000,000 records -- a union of 6 month datasets -- it is fair to say that Tableau Public would not host my visualizations. Fewer records, I feel, would not convey the same information about Citi Bikes in NYC due to seasonal effects and the need to make broader forecasts and support for identified trends. For this reason, screnshots of my visualizations are provided in this repo.

The original gender data is binary, so when representing it on visualizations, aliases corresponding to male, female, and unknown were utilized. 

## Visualizations

The city required a visualization of all of the stations on a map with an indication of popularity, along with zip codes. Using the map layer function in Tableau, I was able to add more detail in streets and zip codes.
![required](required.png)

Next, I mapped the top 10 locations by number of records and added custom icons. The map layer in this map shows important landmarks, in order to give context to the popularity of each station.

![top10landmarks](top10_withlandmarks.png)

## Dashboards
I made three dashboards to describe the most popular stations, rider demographics, and trip data.
![maps](db_maps.png)
![demo](db_demographic_analysis.png)
![rider](db_rider_analysis.png)

## Extra context
The following images provide context for how the visualizations were constructed. 
![viz1](viz1.png)
![viz2](viz2.png)
