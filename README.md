# PyBer Analysis
# Overview of Analysis

The goal of this analysis was to learn about the connection between the type of city (urban, suburban, rural), and the fares and drivers through the ride sharing app "PyBer". The analysis was performed through the use of pandas, matplotlib, and pyplot in order to build and work with dataframes, and analyze the outputs through the use of data visualization. 

## Results
In order to start understanding the data related to the different types of cities we will look at a summary dataframe created using pandas. 
To confirm that the information from this dataframe is understood we will discuss all columns in order.


<img src="https://github.com/sparrishmatt/PyBer_Analysis/blob/main/Resources/type%20summary.png" width="500">


#### Total Rides
As would be expected, urban cities had the most rides taken and rural cities had the least, with suburban cities landing right in the middle. Less population density leads to less business for a company like PyBer. The difference between the total number of rides for rural and urban cities is 1500.

#### Total Drivers
Continuing off of the information from above, the total number of drivers per city type is 78 for rural, 490 for suburban, and 2,405 for urban. The difference between urban and rural cities is 2,327.

#### Total Fares
Rural cities once again have the smallest total for fares with $4,327.93, suburban cities with $19,356.33, and urban cities have the largest total with $39,854.38. Urban cities have 9.21x the total fares of rural cities. 

#### Average Fare per Ride
The lowest average fare per ride is urban cities at $24.53, followed by suburban at $30.97, with rural cities having the highest average fare per ride at $34.62. 

#### Average Fare per Driver
The average fare per driver follows the same smallest to largest order as the average fare per drive with urban cities at $16.57, suburban at $39.50, and rural at $55.49. 

### Interpretation
The high fare averages for both suburban and rural cities compared to urban cities can be explained by the company doing less business in those cities. since there are less drivers and rides that means that more must be charged per ride to make it worth it for PyBer. Urban cities have so many drivers and rides that the company does not need to charge higher fares for a worthwhile payout. One strange thing to look at however is that urban cities have more drivers than total rides. What could the explanation for this be?

### Visualization

<img src="https://github.com/sparrishmatt/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png" width="800">

Since this is a time based visual we are able to see at what points the company perfomed better than average. One important note for the company is that it seems that the total fare per month increased over time for urban cities. This is important because urban cities are the prime market for PyBer. Suburban and rural cities both seem to stay pretty consistent in terms of average total fares however. All three city types had a peak (or almost the peak for rural cities) late in February before a gradual decline. 

Notice that at the end of the chart that urban and rural cities are taking a small dip, while suburban city fares are heading up faster than any other point on any other city. 

## Summary 
With all of the information we have, what suggestions can be made to the CEO? 

* First of all, it seems that the company might have expanded too quickly in the urban market as there are more drivers than total rides. It would make more sense for the company to have less drivers in the urban market at this point so that the remaining drivers can work more consistently. 

* Future expansion into the suburban market should be considered. These cities make much more than rural cities and seem as though the total fares could eventually get closer to urban cities if current trends continue. 

* Continue finding business trends through analysis to learn more about what drives demand based on city types, and then push the business in those directions.
