# PyBer with Matplotlib Analysis
## Overview
V. Isualize works for PyBer, a Python based ride-sharing app company, who has assigned myself to analyze data from the app for each city type: Urban, Rural, Suburban. I calculated the following five metrics for each city type: Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. Also, I calculated the weekly total fare amount for each city type over the duration of four months. With these analyses, I will be able to address any disparities and recommend solutions for them to PyBer.
### Purpose
The purpose of this new analysis is to create the two following deliverables: a summary DataFrame of the five calculated metrics listed above and a multiple-line graph that presents the total weekly fares for each city type, which will help me in suggesting resolutions to disparities in PyBer.
## Resources
* Data Sources: city_data.csv, ride_data.csv
* Softwares: Jupyter Notebook, Pandas, Matplotlib
## Results
The following dataframe, pyber_summary_df, holds the five calculated metrics. ![image](https://user-images.githubusercontent.com/107401667/201246554-5b559423-72db-48c6-a8fd-c0ce4b7e3e3b.png) Compared to Suburban and Urban, Rural had the smallest amount for total rides, total drivers, and total fares. Urban had the largest amounts for these three. Rural had the highest average fare per ride and average fare per driver. The average fare per driver in Rural is about 12 times larger than Urban. There is about 111 times more drivers in Urban compared to Rural.
## Summary
Because there is such a large difference between total Urban drivers and total Rural drivers, PyBer can put a max cap on the amount of drivers allowed for Urban cities. Drivers can then go work local rural cities close to the urban ones. A second recommendation is to do promotions for drivers pay during peak hours in rural city types to help increase their toal drivers. A third recommendation is to give discounts to customers in rural cities when using PyBer during peak hours to help increase total rides in rural cities.
