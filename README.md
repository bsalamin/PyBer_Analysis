# PyBer Analysis Challenge

## Overview

The prescribed process for this analysis was to look at ride-sharing data by city-type (i.e., Urban, Suburban, and Rural rideshares). In order to do this, we had to:
* Use Python and of Pandas tocreate a summary DataFrame of the ride-sharing data by city type.
* Use Pandas and Matplotlib to create a multiple-line graph that shows the total weekly fares for each city type.
* Draft a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results

The ride share data differs notably across the 3 city types:
* There were barely more than 100 total rides in Rural cities, while there was 600 more in Suburban cities and a total of 1,625 rides in Urban cities.
* Total Urban drivers was over 2,400, while the Suburban and Rural driver count was less than 500 and less than 80, respectively.
* The Total Fares collected in Urban cities was 9 times more than that in Rural cities.
* The average fare per ride was most expensive in Rural cities and least expensive in Urban cities.
* The average fare per driver in Rural cities was more than 3 times that of the average fare in Urban cities.
![PyBer_df_summary](https://user-images.githubusercontent.com/100387078/161081721-d5c903f2-8466-4fbe-b492-bed8b8ccb296.png)
![PyBer_fare_summary](https://user-images.githubusercontent.com/100387078/161081784-33dc3464-25e6-43c5-a580-1451c058b6ce.png)

## Summary

There are several important takeaways from the analysis:
* Urban cities have more rides, more drivers, and more revenue overall. 
* But there were more drivers counted than rides taken, meaning not all drivers completed at least one ride. Reducing the number of drivers will increase average fare per driver. 
* Rural cities are much more profitable, however, there is no data on ride time, distance, or costs (e.g., fuel efficiency). Further data collection and analysis is necessary to determine the true cost-effectiveness of ridesharing in Rural and Suburban cities and how to augment profitability across city-types.
