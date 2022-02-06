# PyBer_Analysis
Click here to view the analysis file: [PyBer_Analysis](https://github.com/vijaycse/pyber_analysis/blob/master/PyBer_Challenge.ipynb)

## Overview of Analysis
The goal of this analysis is to create a multiple-line graph that shows the total weekly fares for each city type. PyBer operates in three types of cities: urban, suburban, and rural. Previously, we analyzed the ride count, average fare per ride, and average number of drivers, all categorized by the type of city. Additionally, we compared each city's metrics and the average ride fare to the total number of rides per city. For this challenge, we took it a step further and created a summary data frame that organized total rides, total drivers, total fares, average fare per ride, and average fare per driver and the multiple line plot.

## Results
From the summary data frame, we can see that there is a trend between how populated a city is and the total number of rides, which directly affects the total number of drivers, total fare, and both averages. 

### Analysis1:

Although the total number of rides, drivers and fares decrease as the cities become farther from urbanized areas, the average fare per ride and per driver seems to increase. This can be explained by the accessibility of PyBer rides and drivers in rural areas. Less drivers in rural areas will may lead to a higher average fare per ride and driver, as prices increase when supply is low. 

![Summary Data](https://github.com/vijaycse/pyber_analysis/blob/master/Analysis/Summary_DataFrame.PNG)

### Analysis2:

With the multiple-line chart, we are able to compare total fares by city type over a period of five months. The number of rides seem peak at the end of February and fluctuates during the month of March. All the graphs tend to follow the same trend throughout these months, except for the trend in suburban cities, where we see a sharper increase during the month of April. 

![PyBer_fare_summary](https://github.com/vijaycse/pyber_analysis/blob/master/Analysis/PyBer_fare_summary.png)

## Summary & Recommendations:
1)  Since the total fare by city type seems to increase during the month of April in suburban cities, the company should research as to what causes this increase, especially because the total fare decreases for other types of cities. 

2) Additionally, we know that average fare per ride and driver is higher when there are less drivers. With this information, the company can influence ride-share prices by limiting or increasing the number of drivers during a certain time to achieve its profit goal. 

3) Lastly, the average fare per ride shows a gradual increase from more populated cites to less populated cities. However, the average fare per drive increases drastically when following the same trend. This indicates that the number of drivers may be exponentially lower than expected. The company may want to allocate more drivers to rural areas to optimize its profits. 
