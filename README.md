# PyBer_Analysis

## Purpose
The purpose of this analysis is to create a summary dataframe of the ride sharing dataframe of the ride sharing data by city type. I'll create a multi-line graph that shows the total weekly fares for each city type using Pandas as Matplotlib. In conclusion, this report summarizes how the data differs by city type and how those differences can be used by decision makers at PyBer. 

The data I worked with included city_data.csv, which included a list of cities, their driver count, and city type (urban, suburban, rural); and ride_data.csv, which included city, date, fare, and ride_id. These datasets were merged into one dataframe for ease of analysis:

![Screen Shot 2021-11-17 at 1 29 11 PM](https://user-images.githubusercontent.com/89936913/142285420-148e4baa-4bbd-4169-b0de-41d293c66741.png)


## Deliverable 1
Deliverable 1 is a ride-sharing summary Dataframe by city type

![Screen Shot 2021-11-18 at 10 57 03 PM](https://user-images.githubusercontent.com/89936913/142579159-e48ae335-caeb-4bfd-a984-c327c627c0a8.png)

Rural cities have the highest average fare per ride and lowest number of total drivers, while urban cities have the lowest average fare and the biggest number of total drivers. This makes sense, as rural cities have drivers few and far inbetween, while it's much easier to find work as a driver in larger cities like New York or San Francisco. Urban cities also have more drivers (2,405) than rides (1,625), which means many drivers spend time waiting for the next customer. 

## Deliverable 2
Deliverable 2 is a multiple-line chart of total fares for each city type

<img width="605" alt="Screen Shot 2021-11-21 at 4 06 56 PM" src="https://user-images.githubusercontent.com/89936913/142784609-2f1cd224-5807-47b6-86d0-3417dd8654c0.png">

Urban cities have the highest total fares in USD, meaning more rides happen here overall, as evidenced by the fact that urban cities see over 10x the number of rides than rural cities. 

## Deliverable 3
Deliverable 3 is a written report for the Pyber analysis in the form of a ReadMe.md file

# Overview of the anaysis:
This analysis was conducted in order to analyze trends amongst the rides, drivers, fares and city types so as to give Pyber recommendations as to how best strategize in the future. I merged datasets and produced visualizations so that all three city types (urban, rural and suburban) could be compared easily. 

# Results
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

Rural cities have the lowest number of rides and drivers, but have the highest average fare per driver at $55.49, meaning that most of the drivers should have good opportunity and pay. The total fares in rural cities in $4,327.93 with an average fare per ride of $34.62. This fare per ride is the highest of the three city types, which makes sense as rural destinations are farther apart than they are usually in cities where buildings are packed close together. 

Suburban cities have a similar ratio of rides to drivers available, with a second highest average fare per driver of $39.50, so suburban drivers should have good opportunity and high demand, though not as good pay as in rural cities. The total fares in suburban cities are at $19,356.33 with an an average fare per ride at $30.97. 

Urban cities have a ratio of rides to drivers that is problematic for drivers, as there are too many of them and average wages are low ($16.57) per driver. Urban cities see a total fare of $39,854.38 with the average fare per ride at $16.57, which again makes sense because there are lots of drivers to choose from and destinations can be closer together. 

<img width="231" alt="Screen Shot 2021-11-21 at 5 31 44 PM" src="https://user-images.githubusercontent.com/89936913/142788360-e775c5d7-5eee-479e-a4ff-fcf5d6802559.png">



# Summarizing statement and business recommendations
Overall, the disparities between the city types come down to the number of drivers available and the number of rides being requested. 

As for what business recommendations this analysis can support:
1. Attaining more drivers in rural cities and more riders in urban cities, all through better advertising directed at both customers and workers. This would bring the ratios of rides to available drivers of rural and urban cities closer together, and raise overall wages. 
2. Reducing the number of active drivers in urban cities so that there aren't so many waiting on giving a ride, which would raise the incomes of drivers that are working consistently. 
3. Investigate whether rural average fares per night are partially due to longer distances between destinations by collecting mileage data on every ride so I could incorporate it in a future analysis. 

