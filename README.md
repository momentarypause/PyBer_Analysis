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
Urban data shows 780 more drivers than total rides.  This tells me that there was either a very high turn-over rate for urban drivers or that there were a large number of inactive drivers.  This throws off the average fare per driver making it seem like it is much less than it actually should be.  A much more accurate portrayal would be to count the *active* drivers instead of total drivers.

#### Rides and Fares
Even though the average fare per driver was low, urban areas out-performed other city types in total rides and total fares. Urban city types completed 2.6 times the rides of Suburban city types and 13 times the number of rides of Rural city types.  This brought in twice as much revenue as Suburban and 9 times the revenue of Rural.

#### Fares Over Time
Fares started out lower in the winter months and showed a steady increase until peaking in early spring. On this small of a time scale, fares were inconsistent through March until mid April where they leveled out a bit on a downward slope.

### Suburban
#### Fares
Suburban Average Fare per Ride was between the more expensive Rural rides and the least expensive Urban rides, costing on average $30.97 per ride.


#### Fares Over Time
Suburban fares stayed consistently in the middle when compared to Urban and Rural Fares.  Revenue spiked, as the rest of them did, going into March, but the up-and-down that the other two city types experience is less severe.

### Rural
#### Rides and Fares
Rural rides were the most expensive, coming in at an average of $34.62 per ride: $10 more per ride than in Urban communities. It would be interesting to see the data on the distance of the average ride to see if this cost increase is due to that or another factor.  

#### Representation
Rural, by far, has the least representation of the city categories in respect to number of available drivers.  This tracks with National Census Bureau data that states that in 2010, [19% of the country's population lived in rural communities.](https://mtgis-portal.geo.census.gov/arcgis/apps/MapSeries/index.html?appid=49cd4bc9c8eb444ab51218c1d5001ef6) This number has been slowly declining since then as more and more people move to urban areas and the suburbs. There are significantly less rides, drivers, and total fare collected for rural communities.




## Summary
### Final Thoughts
Data analysis often raises more questions to explore than provides answers. The following are questions raised while analyzing the available data:
1. How many of these total drivers took 0 rides during this time period?  How does that affect the average fare per driver?
2. What are the distances for each of these rides? Cost per ride could be attributed to the distance the rider needs to travel.  Urban distances are generally less as people travel from point to point within a city.  On the other hand, Rural residents need to travel much farther to get to destinations outside of small towns.  That leaves Suburban in the middle, as they are generally closer to larger cities that have services they might not find in their smaller cities. 
3. Why are there so many fewer drivers available in rural areas? Does this contribute to the low number of rides or is there another reason?
4. If the goal is to increase revenue, Urban areas are the money-makers for ride share.  However, the goal of this study was to find the underserved communities, and that title belongs to the Rural community.  With 30 times less drivers than Urban, rural residents have less opportunity to use rideshare services.  

### Next Steps
- Locate data that includes distance of each ride to get a more accurate picture of Fare per Driver.
- Conduct a study on the demand for rideshare services in rural communities to see if this is even something that is needed before increasing outreach.  Include inquiries about reasons why rural community members use or do not use rideshare services.
  -   If it is needed, tailor advertising to recruit more rural drivers and offer incentives to draw more in.  Tailor consumer advertising to reach those reasons someone in a rural community might want to use a rideshare.
  -   If it is not something the rural community is interested in, continue building Urban and Suburban business and when revenue increases, pass that onto the customer in the form of reduced rates.
