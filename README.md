# Bikesharing
## Tableau practice / Bike share data

## Project Overview
The objective of this project was to determine the viability of a proposed bike-sharing app program in Iowa. In order to establish facts about how bike shares normally operate, data from New York's Citibike program was downloaded to Tableau. After some transformation to make the dates and times of the rides readable for trip duration, several visualizations were created to represent the user demographics and frequency of rides on the shared bicycles.

## Results
The analysis produced the following visualizations:

![Gender breakdown](Images/Gender_breakdown.png)

Of the users whose genders were shared, a sizable majority were male.

![Subscription breakdown](Images/Subscription_status.png)

Over 75% of the trips were made by subscribers. This is a positive sign that once users subscribe, they often continue to use the bicycles.

![Trip durations](Images/Trip_durations.png)

Nearly all trips were under an hour in length, with the highest frequencies occurring for trips under 20 minutes in length.

![Gender-split durations](Images/Gender_durations.png)

Riders of unknown gender, who tend to be unsubscribed customers, were not as strong in their tendency toward shorter trips

![Ride dates and times](Images/Dates_times.png)

Weekday rides tended to cluster around the morning and evening commute hours. Weekend rides were more broadly spread throughout the day.

![Trip times by gender](Images/Gender_trip_times.png)

Gender does not appear to have much affect on the dates and times people prefer to ride, except that the user base skews toward males in general.

![Trip days by user type](Images/Type_gender_day.png)

Unsubscribed users were more prevalent on weekends, while subscribers tended to use the bikes more often on weekdays.


## Summary
### Generalizations
Overall, it appears that the riders in New York fall into two distinct categories: subscribers who ride mostly at weekday commute hours, and non-subscribed customers who ride on weekends during the day. The latter group are possibly tourists in New York, which is much less likely to be reliable in Iowa. The weekday rides by subscribers are often less than 30 minutes long, and the concentration of times would allow for maintenance on the bikes at midday, or overnight. A commuter-focused program, deployed in densely populated neighborhoods, would have the best chance of success. 

### Recommendations for additional visualization
Two likely visualizations of important things to consider here would be:

- A side-by-side map of bike lanes and bike-friendly infrastructure in New York compared to Des Moines, which would help establish whether it is currently viable to travel by bicycle in Iowa for the types of trips that were most common in the New York dataset

- A colored map of the population of Des Moines by neighborhood would be useful in determining the most likely scale and location for initial deployment of shared bikes.


## Tableau Public Link
The Tableau workbook used for this submission can be found here:
[link to dashboard](https://public.tableau.com/app/profile/stephen.ours/viz/Bikeshare_Challenge_16647421988270/UserAnalysis?publish=yes "link to dashboard")