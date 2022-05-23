# PyBer_Analysis
Module 5 Challenge

## Overview
Explain the purpose
The purpose of this exercise was to use the matplotlib python library to create a multiple-line chart that displays the average fares by city type (suburban, urban, rural). 

Also, using pandas, Numpy, and Scipy, I determined the total number of rides, the total number of drivers, the sum of the fares, the average fare per ride, and the average fare per driver for each city type in each category. A dataframe was created to display the results. 

## Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### Summary Statistics Dataframe
<img width="444" alt="Screen Shot 2022-05-23 at 2 23 12 PM" src="https://user-images.githubusercontent.com/96043107/169891511-e77ede0d-5a6d-4a4f-88db-cee35959480f.png">

* As you can see in the image above, there is a decending order in average total rides, average total drivers, and average total fares between the rural, suburban, and urban cities, with urban cities being the highest and rural areas being the lowest. 
* For average fare per ride, rural cities charged the most, and urban areas charge the least on average. This is also the case for average fare per driver. 

### Total Fare By City Type Multiple-line Chart

![PyBer_fare_summary](https://user-images.githubusercontent.com/96043107/169891960-2ab8b978-36a0-445b-b57d-6b45f4266005.png)

* Rural, suburban, and urban areas all follow a similar pattern where near the end of February they reach close to their highest total fares. Urban areas oscillate that pattern through April. Suburban areas begin to climb near February-highs towards the end of April, while rural area total fares tend to decline during the month of April.  

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
1. Due to urban city types commonly resulting in overall shorter ride times, this results in lower average fares per ride. However, I would think that urban city drivers tend to have a higher volume of rides than rural cities, so they are likely making just as much if not more income than rural drivers. Collecting data on the different city types total monthly income would provide more insights on this.
2. Urban drivers may not have enough work to support themselves, given the lower average fares per ride. PyBer could invest in advertisement for their ride-sharing platform in urban city types to increase total rides to aid the lower average fares. 
3. If PyBer chooses to invest in advertisement for their ride-sharing platform, it would be wise for the CEO to consider when would be best to implement their advertisement program. While Feburary appears to be a good time for Urban areas to implement an ad program, a further analysis into the rest of the calendar year would be wise before investing capital. 
