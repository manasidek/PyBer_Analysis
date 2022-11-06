# PyBer_Analysis

## Overview of the analysis

- Overview of the analysis is to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.

- The analysis and visualizations produced will help Pyber improve access to ridesharing services and determine affordability for underserved neighborhoods.

## Resources

-Data Source: 
[City Data]()
[Ride Data]()

- Software: Anaconda 22.9.0, Python 3.7.6, Jupyter Notebook 6.4.12

## Results:

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

### Step 1 of Analysis

- Creating a Series of data that has the type of city as the index for "ride_id","driver_count" and "fare" columns.

- Using the above data extration calculate the average fare per ride and average fare per driver by city type. Further, create a PyBer summary DataFrame with all the data gathered.

!(PyBer_join)[]

- Formating the above DataFrame to make it presentable

!(Ride_Sharing_Data)[]


### Step 2 of Analysis

- Creating a dataframe with multiple indices using the columns "type", "date"and"fare"to show total fare amount for each date. 

- The DataFrame is as follows:

!(Multi_Indices)[]

- Creating a resampled DataFrame, which looks like this:

!(Resampled_Data)[]

- Based on the above data a line chart is generated. 

- The line chart link is (PyBer_fare_summary)[]

## Summary

### Observations

After performing analysis of different data sets a final dataset was created (Ride_Sharing_Data) which gave the following conclusions:

1. Total no. of rides are 13 and 5 times higher in Urban and Suburban areas respectively as compared to Rural areas.

2. Total no. of drivers are 30 and 6 times higher in Urban and Suburban areas respectively as compared to Rural areas.

3. Total fare is 9 and 4 times higher in Urban and Suburban areas respectively as compared to Rural areas.

4. Average fare per ride and Average fare per driver is highest in Rural areas and lowest in the Urban area.

After analyzing the line chart showing fares by date, it can be observed that fares are maximum during the week of 02/11 - 02/17 across all city types.

### Business Recommendations

1. Increase no. of drivers in Rural areas as average fare per ride and fare per driver is highest in those areas.

2. Conduct market surveys in Urban areas to determine whether fare prices can be increased or no. of drivers can be decreased.

3. Explore ways to further increase fares during the week of 02/11 to 02/17.
