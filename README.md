# PyBer_Analysis
Module 5

## Overview

We are reviewing ride-sharing data based on city type of Urban, Suburban and Rural.  Additional information in this dataset includes City name, date of ride, fare, ride ID and driver count.

We have been asked to find total weekly fares for each city type.  The date ranges will be for January 1 to April 29, 2019.  We will be using our original dataset from a .csv file.

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

!["summary"](https://github.com/ckbauman/PyBer_Analysis/blob/main/Summary.png)

We can see that most rides come from the Urban areas with very few Rural rides.  Ride fares are generally more expensive in rural areas because it isn't as cost effective to drive to rural areas.  Drivers don't make as much in Urban areas as they do in Rural areas either.

### Total Weekly Fares Results

Weekly results were calculated with date, fare and city type.

1. Create DataFrame for type, date and fare

!["dataframe fares"](https://github.com/ckbauman/PyBer_Analysis/blob/main/dataframe_fares.png)

2. Reset index  and create a pivot table with date as index, column type and value fare

!["pivot type"](https://github.com/ckbauman/PyBer_Analysis/blob/main/pivot_type.png)

3. Create DataFrame for date range

!["dataframe date"](https://github.com/ckbauman/PyBer_Analysis/blob/main/dataframe_date.png)

4. Change date index to datetime and check it

!["index date"](https://github.com/ckbauman/PyBer_Analysis/blob/main/index_date.png)

5. Create DataFrame by week

!["dataframe week"](https://github.com/ckbauman/PyBer_Analysis/blob/main/dataframe_week.png)

6. Create chart with weekly data

!["chart code"](https://github.com/ckbauman/PyBer_Analysis/blob/main/chart_code.png)

7. Total Fares by City Type 

!["chart image"](https://github.com/ckbauman/PyBer_Analysis/blob/main/analysis/Fig8.png)

As you can see, Urban fares are higher then Surburban and Rural Fares.  They stay this way month over month.  Rural fares always remain low and consistently stay this way.


## Summary

1. The vast majority or rides occurs in Urban areas.  It is wise to invest in Urban drivers

2. Rural areas have the lowest fares, but drivers make the most.

3. It may be good to invest in more Rural drivers to bring up total rides, which would increase total fares in this area.

4. Suburban fares also make more then Urban fareas, so may be able to invest in more drivers.
