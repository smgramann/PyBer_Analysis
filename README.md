# Ride Sharing Analysis

### Purpose

Starter code was provided to kick off the analysis.  Utilizing Python and Pandas a summary dataframe of ride-sharing data by city type was created, which was then leveraged via Pandas and Matplotlib to create a multiple-line graph showing the total weekly fares for each city type.  This data and visual helped summarize trends for decision-makers at Pyber.

## Analysis

### Results

There are clear differences in the ride sharing summary stats when comparing the three city types:  Rural, Suburban, and Urban.  The Rural type had the lowest total rides, drivers, and fares, but had the highest average fare per ride and driver.  The Urban type had the highest total rides, drivers, and fares, but had the lowest average far per ride and driver


![summary_df](https://user-images.githubusercontent.com/80165223/115962215-df8aa600-a4df-11eb-8121-14795748ccb6.png)



Total Fare by City Type when plotted on a time series multi-line chart to represent change by week over a four-month period demonstrates disparities in fares across the city types.  Fares by Urban and Suburban city type always trended significantly higher than the Rural city type



![Pyber_fare_summary](https://user-images.githubusercontent.com/80165223/115962231-ec0efe80-a4df-11eb-9a20-3db8c243a185.png)




## Summary

### Recommendations

The trends identified in this analysis are likely driven by population and geography, which influence the number of rides and drivers as well as distance of each ride thus influencing fare.  To better understand the underlying reasons of these trends to inform decision-making, the following is recommended:

1)	Conduct an analysis on population size or average population size for each city or city type to identify the appropriate number of drivers per city type.  Average rides per 100K residents in each city may allow for a better comparison and analysis.

2)	Collect more data on distance traveled for each ride to better understand average fare for each city type.  Average miles traveled per dollar spent by city type may reveal that individuals are spending more in Urban settings, but without more data this is unknown.

3)	Pilot a program or campaign in a couple of Rural city types to see if average fare and total rides can be increased through specific targeted efforts.
