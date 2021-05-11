# Bike-Sharing

## Project Overview
For this project, the goal is to analyze the Citbike usage data for New York City to determine whether a bike rental program would succeed in Des Moines, Iowa.

## Resources
201908-citibike-tripdata2.csv

## Results: 
[Link to dashboard](https://public.tableau.com/profile/kaitlin.rockway#!/vizhome/NYC_Citibike_Analysis_Challenge/Analysis)

After examining the NYC data, I was able to extract the following visualizations:

### Are men or women more likely to use the service?
![Gender](https://github.com/krockway/Bike-Sharing/blob/main/images/Gender.png)

Both men and women are equally likely to use the service, but men are more likely to be subscribers. 

### How long is each bike used for? Is gender a factor?
![TimeUsed](https://github.com/krockway/Bike-Sharing/blob/main/images/TimeUsed.png)

Most bikes are used for quick trips, less than 20 minutes. Although men are more likely to use the service, both men and women spend a similar amount of time per ride.

### What are the most popular days of the week to checkout bikes?
![DayPopularity](https://github.com/krockway/Bike-Sharing/blob/main/images/DayPopularity.png)

Popularity peaks during commuting hours (7-9am and 5-7pm) Monday through Friday. There is also increased usage on weekend afternoons (11am-5pm). Thursday evenings are the most common times bikes are used.

### Is gender a factor in the days or time of trips?
![DayPopularityGender](https://github.com/krockway/Bike-Sharing/blob/main/images/DayPopularityGender.png)

Gender does not appear to be a factor in the day of the week or time of day that bikes are used; similar patterns are seen for both genders. The unreported gender users do not have a distinct usage pattern, though weekends are slightly more popular.

### Where are the most common starting points?
![Map](https://github.com/krockway/Bike-Sharing/blob/main/images/Map.png)

Manhattan is by far the most common starting point for rides. This is likely because commuting hours are affiliated with the highest usage, one can also assume that riders work in Manhattan. In addition, there is a large tourist population in the area, which is likely increasing ridership compared to other neighborhoods.

### When is the best time to do repairs?
![Repairs](https://github.com/krockway/Bike-Sharing/blob/main/images/Repairs.png)

Luckily there is a small number of bicycles with extremely heavy (more than 384 rides) or heavy (more than 288 rides) usage (indicated in red). When compared with the least common number of rides, maintenance and repairs can easily be achieved between 11pm and 4am.

## Summary:

Overall, New York City (and Manhattan specifically) is a great place for a bike rental company like CitiBike. If Des Moines has a concentrated business center in which riders can commute via bike, they could also be a great place for this service. 

Before committing to this business, you and Kate should also examine the data more months of data. August is peak season in terms of weather and tourists, I presume that the winter months experience decreased ridership and this is important to know before committing. Will this be a seasonal business or year round?

Similar to the existing repair visualizations, I would add an additional view that adds the geo-location as another factor. This will help the maintenance crew pinpoint which neighborhoods are seeing the highest traffic and when they can do repairs with minimal impact on riders.

Lastly, it might be interesting to compare the length of each journey in miles. You could do so by comparing the starting and ending latitudes and longitudes.