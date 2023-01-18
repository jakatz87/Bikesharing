# Bikesharing
## [Link to Tableau Dashboard](https://public.tableau.com/app/profile/joshua.a.katz/viz/BikeShareAnalysis_16739965582890/CitibikeStory?publish=yes)

## Overview
Using publicly available data from New York's Citibike, I created a visualization that can be used for general information for any other city thinking of replicating the service.

## Results
I was able to show that most bikes were used for rides that lasted between 4 and 12 minutes.

![Checkout Times for Users](https://github.com/jakatz87/bikesharing/blob/main/images/Checkout%20Times%20for%20Users.png)

This use of bike times was consistent by gender.

![Checkout Times by Gender](https://github.com/jakatz87/bikesharing/blob/main/images/Checkout%20Times%20by%20Gender.png)

I found that the most popular time for bike usage was for morning and evening commutes for work, as well as weekend afternoons for leisure.

![Trips by Weekday per Hour](https://github.com/jakatz87/bikesharing/blob/main/images/Trips%20by%20Weekday%20per%20Hour.png)

Bike usage times were also consistent by gender.

![Trips by Gender](https://github.com/jakatz87/bikesharing/blob/main/images/Trips%20by%20Gender.png)

Weekdays, especially Thursday and Friday, showed the most popular days of usage, with a lull on Wednesday.  In terms of times for analysis, reflection, and maintenance, Wednesdays would be ideal.

![User Trips](https://github.com/jakatz87/bikesharing/blob/main/images/User%20Trips.png)


With costs in mind, bike maintenance is worth investigating given this free data.

I can consider either the location of a shop, or a centralized area for a mobile bike mechanic given these points of starts and ends for rides:

![Top Starts](https://github.com/jakatz87/bikesharing/blob/main/images/Top%20Starting%20Locations.png)

![Top Stops](https://github.com/jakatz87/bikesharing/blob/main/images/Top%20Ending%20Locations.png)

To track which bikes would be in need of service, I can use this visualization to easily identify the bikes in potential need of service by their Bike ID.

![Bike Use](https://github.com/jakatz87/bikesharing/blob/main/images/Bike%20Utilization.png)

## Summary
With the free data provided by Citibike, I would suggest removing the category of gender since it seems to be redundant and shows no significant impact.  If gender was still a data point of interest, perhaps the number of reported maintenance issues by user would possibly reveal something.  

If a city is to replicate this type of service, this analysis shows that focusing on its use for transportation to and from work may be best.  

Further information for visualization should include maintenance costs per bike, overhead costs per month, city population data, and disaggregated data by neighborhood.  This information would help other cities or companies in their decisions to replicate this service.
