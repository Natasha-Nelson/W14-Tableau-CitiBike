# W14-Tableau-CitiBike

## Overview
The purpose of this project is to explore CitiBike ride data from August 2019 to draw conclusions about best practices for operating a bike rideshare company. This analysis can be used as part of a broader project to pitch similar companies/business models in other areas outside of New York City. In this analysis, I will be drawing conclusions from visualizations in Tableau to answer the following questions:
  1. Who are the customers for bike shares?
  2. How long are bikes checked out and when? 
  3. Where should bikes be placed and where do they end up?
  4. When should bikes be maintained?

## Resources
Data: https://www.citibikenyc.com/system-data, 201908-citibike-tripdata
Python, PANDAS, Jupyter Notebook for data manupulation
Tableau Public for visualization 

## Results

### Customer Profiles
In this first section we examined the breakdown between subscribers and one time customers, female/male/'gender unknown' riders and the age of riders. From these figures we can conclude the majority of riders in August are male. We can also observe that in both the female and male demographic, trips from subscribers outweight those of single customers. We can also see a trend in rider age that peaks between 20-35. 

### Checkout Times
In the second section, we can review the trip duration of rides in August. It is immediately clear that the vast majority of rides last less than hour, peaking well below the 20 minute mark. This pattern holds true across all genders and ages (with the noteable of 1969). 

From our breakdown of checkout times by weekday, we can see that peak hours across the week are between 7-10am and 4-7pm ET each day. Ridership is more consistent throughout the day on the weekends. The lowest ridership day is Wednesday, whereas the highest use day is Thursday. We can observe that subscribers ride more frequently during the week, whereas one time customers are more frequent users on weekends. This pattern seems to hold across genders.

## Conclusions 
From the customer profile, we observed that the majority of rides were made by subscribers to the ridership service, suggesting that regular use of bikes by commuters may outweight usage by tourists. This means we can rely on high traffic commuting areas to gain traction in new cities. We can also see an unusual spike of riders with a birth year of 1969 with a high number of 'gender unknown' records. It would be worth exploring this segment further to ensure a clean data set. 

From the checkout times we can conclude that the best times to perform bike maintenance is in the early morning hours between 2-4am. We can also conclude that Wednesdays might prove the best days to transport bikes between locations or perform station cleanings. Our visualizations also support the hypothesis that bikes are being used by regular commuters, as the daily peaks line up with working hours during the week and normalize on the weekends. 

### Further Visualizations and Exploration
There is evidence to suggest that the data set we've been working with contains anomalies (especially for those records associated with 1969) so it would be worthwile to perform more robust statistical analysis on this subset of datapoints. Other visualizations that might prove helpful are:
  1. Breakdown of trip duration for different customer types



