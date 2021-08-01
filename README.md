# PyBer_Analysis
Module 5

## Overview

We are reviewing ride-shareing data based on city type of Urban, Suburban and Rural.  Additional information in this dataset includes City name, date of ride, fare, ride ID and driver count.

We have been asked to find total weekly fares for each city type.  The date ranges will be for January 1 to April 29, 2019.

## Results

 ### DataFrame Summary Results

Our summary results include data for rides, drivers, fares, average fare per ride and average fare per driver.

1. Total rides by city type:

!["rides"](https://github.com/ckbauman/PyBer_Analysis/blob/main/rides.png)

2. Total drivers by city type:

!["drivers"](https://github.com/ckbauman/PyBer_Analysis/blob/main/drivers.png)

3. Total fares by city type:

!["fares"](https://github.com/ckbauman/PyBer_Analysis/blob/main/fares.png)

4. Average fare per ride:

!["avg_fare_ride"](https://github.com/ckbauman/PyBer_Analysis/blob/main/avg_fare_ride.png)

5. Average fare per driver:

!["avg fare driver"](https://github.com/ckbauman/PyBer_Analysis/blob/main/avg_fare_driver.png)

6. Summary

INSERT: summary

We can see that most rides come from the Urbaan areas with very few rural rides.  Rides fares are generallly more expensive in rural areas because it isn't as cost effective to drive to rural areas.  Drivers don't make as much in Urban areas as they do in Rural areas either.

### Total Weekly Fares Results

Weekly results were calculated with date, fare and city type.

1. Create DataFrame for type, date and fare

INSERT: dataframe fares

2. Reset index  and create a pivot table with date as index, column type and value fare

INSERT: pivot type

3. Create DataFrame for date range

INSERT: dataframe date

4. Change date index to datetime and check it

INSERT: index date

5. Create DataFrame by week

INSERT:  dataframe week

6. Create chart with weekly data

INSERT: chart code

7. Total Fares by City Type 

INSERT:  fig8

As you can see, Urban fares are higher then Surburban and Rural Fares.  They stay this way month over month.  Rural fares always remain low and consistently stay this way.


## Summary

1. The vast majority or rides occurs in Urban areas.  It is wise to invest in Urban drivers

2. Rural areas have the lowest fares, but drivers make the most.

3. It may be good to invest in more Rural drivers to bring up total rides, which would increase total fares in this area.

4. Suburban fares also make more then Urban fareas, so may be able to invest in more drivers.
