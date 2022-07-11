# PyBer_Analysis

## Overview
### Data
The following data was collected for 2,375 Pyber Rides in 120 cities from January 1, 2019 through May 8, 2019:
- City --Name and type (urban, suburban, or rural)
- Date and time of ride
- Fare collected
- A count of drivers available in each city (total drivers: 2,973)
- Ride ID number

### Project
The purpose of this project is to analyze the data collected in order to increase access to ride shares in underserved neighborhoods and to determine the affordability of rides for that population.

## Results
![Total_Fare_by_City](https://user-images.githubusercontent.com/102555125/178305401-42ff307b-b62e-467f-bf51-03e4d4f6a74d.png)

#### Summary Data
![Pyber Summary chart](https://user-images.githubusercontent.com/102555125/178305350-dda56baa-6c73-48f1-a449-79ded0ac9d7c.png)


### Urban
#### Drivers vs. Rides
Urban data shows 780 more drivers than total rides.  This tells me that there is either a very high turn-over rate for urban drivers or that there are a large number of inactive drivers.  This throws off the average fare per driver making it seem like it is much less than it actually should be.  A much more accurate portrayal would be to count the *active* drivers instead of total drivers.

#### Rides and Fares
Even though the average fare per driver is low, urban areas out-perform other city types in total rides and total fares. Urban city types complete 2.6 times the rides of Suburban city types and 13 times the number of rides of Rural city types.  This brings in twice as much revenue as Suburban and 9 times the revenue of Rural.

#### Fares Over Time
Fares start out lower in the winter months and show a steady increase until peaking in early spring. On this small of a time scale, fares are inconsistent through March untilmid April where they level out a bit on a downward slope.

### Suburban
#### Fares
Suburban Average Fare per Ride is between the more expensive Rural rides and the least expensive Urban rides, costing on average $30.97 per ride.


#### Fares Over Time
Suburban fares stay pretty consistently in the middle when compared to Urban and Rural Fares.  Revenue spikes, as the rest of them do, going into March, but the up-and-down that the other two city types experience is less severe.

### Rural
#### Rides and Fares
Rural rides are the most expensive, coming in at an average of $34.62 per ride: $10 more per ride than in Urban communities. It would be interesting to see the data on the distance of the average ride to see if this cost increase is due to that or another factor.  

#### Representation
Rural, by far, has the least representation of the city categories.  This tracks with National Census Bureau data that states that in 2010, [19% of the country's population lived in rural communities.](https://mtgis-portal.geo.census.gov/arcgis/apps/MapSeries/index.html?appid=49cd4bc9c8eb444ab51218c1d5001ef6) This number has been slowly declining since then as more and more people move to urban areas and the suburbs. There are significantly less rides, drivers, and total fare collected for rural communities




## Summary
Data analysis often raises more questions to explore than provides answers.

Driver count is higher than the ride count signifying that there are many drivers who did not accept rides during a 4 month period. How many drivers are inactive?  I wonder how the stats would change if we just counted active drivers.  What areas do these inactive drivers drive for?  

Why is there less representation in rural areas?  Less driver interest in 

Cost per ride could be attributed to the distance the rider needs to travel.  Urban distances are generally less as people travel from point to point in a city.  On the other hand, Rural residents need to travel much farther to get to destinations outside of small towns.  That leaves Suburban in the middle, as they are generally closer to larger cities that have services they might not find in their smaller cities.

If the goal is to increase revenue, Urban areas are the money-makers for ride share.  However, the goal of this study was to find the underserved communities, and that title belongs to the Rural community.  With 30 times less drivers than Urban, rural residents have less opportunity to use rideshare services.  My next suggestion would be a study on the demand for these services in rural communities to see if this is even something that is needed before increasing outreach.
