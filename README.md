# PyBer_Analysis

This analysis aims to identify patterns and trends in the PyBer data to aid decision makers in improving access to ride sharing services and determine affordability for underserved neighborhoods. The following analysis uses visualizations to showcase the relationship between the type of city—urban, suburban, and rural—and the follow metrics:

-	the total number of rides
-	the total number of drivers
-	the total fares 
-	the average fare per ride
-	the average fare per driver
-	total weekly fares from January to April 2019

## Resources:

-	Jupiter Notebook
-	Python
-	city_data.csv, ride_data.csv

### Results:

### Differences by City:

The following overall differences among cities was observed:

- Rural cities had the lowest number of total rides: 125, total drivers: 78, and total fares: $4,327.93. Rural cities also had the highest average fare per ride: $55.49, and average fare per driver: $55.49.
-	Suburban cities had the second largest number of total rides: 625, total drivers: 490, and total fares: $19,854.33.  Suburban cities had the second lowest average fare per ride and per driver, both of which are $39.50.
-	Urban cities had the largest number of total rides: 1625, total drivers: 2405 and total fares: $39,854.38. Urban cities had the lowest average fares per ride: $16.57, and average fare per driver: $16.57.

### Total Fare by City Type from January to April

Further analysis was conducted on the total weekly fares for rural, suburban and urban cities to get a closer look at how the data compares among each city type. The disparities presented in the Pyber summary dataframe are also seen in multi-line chart “Total Fare by City Type and the January to April weekly fares by city type dataframe. The weekly fares for each city. Rural cities had the lowest total fares per week, suburban cities retained the second greatest total fares per week, and urban cities held the greatest total fares per week.

The following are recommendations to address these disparities:

1.	Increase the number of drivers in suburban. In suburban cities the number of total rides, 625, exceeds the number of drivers, 490. Whereas in urban cities the total number of drivers, 2,405, exceeds the number of rides, 1,625. Increasing the number of drivers in suburban cities can prompt a decrease in fare prices and encourage people to choose ridesharing for travel.

2.	Increase marketing for reduced price car-pooling in suburban and rural cities. The reduced prices offered by car-pooling—where multiple individuals to be pick up and dropped on during one trip—can incentivize people to choose ridesharing for travel.

3. Offer passengers rewards for the miles they ride. In rural and suburban cities, where topography in more spread out, trips are longer, and more expensive, people are discouraged by the hefty price of the ride-share option. With a miles reward program, riders can collect points for the miles they ride with PyBer, and receive discounts on fares when riders reach a certain number of miles. This offer favors suburban and rural riders—who have a longer ride—and can encourage them to choose ridesharing for travel.  

