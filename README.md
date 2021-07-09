# PyBer Analysis
*Matplotlib Analysis for PyBer Ride-Share company*

## Project Overview 
### Purpose & Background

The purpose of this analysis is to perform data analysis for Ride-Share company *PyBer* and to tell a compelling story with data visualization. This analysis showcases the relationship between the type of the city -- urban, suburban and rural -- and their correlation between rides, drivers and fares, and congregates data from January to early May of 2019 and focuses on the following: 

-	The total number of rides for each city type. 
-	The total number of drivers for each city type.
-	The sum of the fares for each city type.
-	The average fare per ride for each city type.
-	The average fare per driver for each city type.
-	The total fares for each week by city type. 

### Overview the methods and code
The data is gathered in two different CSV files (the city data and the ride data). We then utilize **Jupyter notebook** and **Pandas Library** to inspect data, merge datasets,
perform calculations and create new data series and data frames to work with.  We are also using Python’s plotting library **Matplotlib** to make the more effective charts. 

### Resources
- Data Source: 
  - [PyBer_ride_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/PyBer_ride_data.csv)
  - [city_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/city_data.csv)
  - [ride_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/ride_data.csv)

## Results 
The first exercise in this challenge was to create a DataFrame with our combined data.  The new Pyber Fare Summary looks like this: 

![Pyber datafame](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Graphics/PyBer%20Summary%20DataFrame.png)
 
The next exercise was to build a pivot table to display the comparitive results. From the pivot table we were able to  
prdouce and display more meaningful data.  This multi-line chart tells the story in detail and is pleasant to read. 

1. The total number of rides for each city type. 
   - Here we see that total ridership in Urban cities and higher that Suburban and most significantly higher than Rural cities - by 
3. The total number of drivers for each city type.
   - We also know that total drivers in Urban cities is much higher that in rural cities.
5. The sum of the fares for each city type.
   - The fares in Urban cities is much higher than Suburban and Rural. In some cases, 9 times higher.  
7. The average fare per ride for each city type.
   - The average fare per ride is lower in Urban cities and Suburban cities, than in Rural
9. The average fare per driver for each city type.
   - Average fares are also lower in Urban cities than in Rural cities.  
11. The total fares for each week by city type. 
   
   

 ![Multiple Line Chart Tot Fares by City Type](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Graphics/PyBer_fare_summary.png)

 
This data in the multi-line graph is from a period of time Jauary 2019 to May 2019.    
