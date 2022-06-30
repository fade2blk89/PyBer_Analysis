# PyBer Ridesharing Analysis

## Overview of the Analysis
Within the data sets provided, we were tasked with creating a summary DataFrame of the ride-sharing data by city type. To better illustrate this data, we then consructed a multiple-line graph showing the total weekly fares for each of the 3 city types from January to April 2019. 

## Source
Data Source: city_data.csv, ride_data.csv

Software: Python 3.7.9, Jupyter Notebook 6.4.8

## Results
After analyzing the data from almost 2,400 rides, we found that rides taken in urban areas accounted for over two-thirds of the dataset, as shown below: 

![Percentage of Rides Per City Type](https://github.com/fade2blk89/PyBer_Analysis/blob/main/analysis/Fig6.png)

This number becomes even larger as we shift our focus to the total number of drivers per city type in the dataset. When viewing the total city fare types by drivers, 80% of them completed rides in urban cities. 

![Percentage of Total Drivers by City Type](https://github.com/fade2blk89/PyBer_Analysis/blob/main/analysis/Fig7.png)

Although the percentage of drivers and rides in urban cities remains high when viewing the total fares, the suburban cities end up accounting for approximately 30% of the total fares. 

After determining the total number of rides, drivers and fares per city type, we also calculated the average fare per ride and driver into the below dataframe. 

![Summary Dataframe](https://github.com/fade2blk89/PyBer_Analysis/blob/main/analysis/Fig9.png)

Using the information from this datafme, we were able to resample the information and convert the information into a line graph showing the weekly fares over time from January to April 2019 for each of the city types. 

![Line Graph Summary](https://github.com/fade2blk89/PyBer_Analysis/blob/main/analysis/Fig8.png)

## Summary
The above dataframe shows that the average fare price seems to increase as less drivers are available and more fares are requested, whereas the multiple-line graph demonstrates the total amount of fares being completed in urban cities completely overshadows the amounts taken in from the suburban and rural cities. Even though rural fares and drivers accounted for the smallest amount of total fares, we recommend increasing the availability radius of rideshare drivers to include more of this city type. Alternatively, we may want to provide a first time ride incentive to those in rural or suburban areas to increase overall total fares. Finally, we may want to consider partnering with local transit to help transport clients between a central pick up/drop off location in a suburban city and their rural location. 
