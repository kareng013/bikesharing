# Citibike Analysis

## Overview

The purpose of this analysis is to research and explore the data from Citibike in NYC and utilize the information to convince investors that a bike sharing program in Des Moines is a solid business proposal. One of the key stakeholders requested a bike trip analysis in order to back up the proposal and final decision. 

For this analysis, we'll start by using Pandas to convert the data from an integer to datatime datatype. 
Using the converted datatype, we'll create a set of visualizations shown in the results below. 

The data provided is for the month of August, which is the busiest month of the year.

Visualizations:
1) Checkout Times for Users
2) Checkout Times by Gender
3) Trips by Weekday
4) Trips by Gender (Weekday per hour)
5) User Trips by Gender by Weekday
6) Toal Trips by Gender
7) Top Starting Locations by Users

## Results

### Checkout Times for Users

![User_Checkouts](https://github.com/kareng013/bikesharing/blob/main/Images/Checkout%20Times.png)

The graph above shows the length of time that bikes are checked out for all riders. 
From this data we can see most bikes are checked ou under the 20 minutes range.

### Checkout Times by Gender

![Gender_Checkout](https://github.com/kareng013/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png)

This graph showcases the length of time that bikes are checked out for each gender. 

### Trips by Weekday for Each Hour

![Trips_Weekday](https://github.com/kareng013/bikesharing/blob/main/Images/Trips%20by%20Weekday.png)

This heatmap displays the number of bike trips by each weekday and every hour. 
As the number of users per hour increases, the color of each box gets darker.
From the graph we can see that Thursday between 5:00pm until 7:00pm had the highest number of bikes checked out. 

### Trips by Gender (Weekday per Hour)

![Trips_Gender_Weekday](https://github.com/kareng013/bikesharing/blob/main/Images/Trips%20by%20Gender(Weekday%20per%20hour).png)

This heatmap displays total data by each Gender for each hour of each day of the week. As the quantity per gender gets darker, it indicates the number of riders in that hour has increased. From this we can see that the Male gender saw he highest number of riders on Thursday at 6:00pm, a total of 30,749 rides which is the max from the data in August. 

### User Trips by Gender by Weekday

![User_Trips_Gender](https://github.com/kareng013/bikesharing/blob/main/Images/User%20Trips%20by%20Gender%20by%20Weekday.png)

This data showcases the number of users that are customers and subscribers by gender. 
We can distinguish that a majority of the Male Users are subscribers at the maximum count of 259,316 users checking out bikes on Thursdays.

### Total Trips by Gender

![Total_trips_Gender](https://github.com/kareng013/bikesharing/blob/main/Images/Total%20Trips%20by%20Gender.png)

This data shows the total amount of trips taken by users and catergorized by Gender. From the pie chart to the left we can see a large perentage of Users are Male.
There are 1,530,272 Male users; 588,431 Female users; 225,521 Unknown users. The male population is double the sum of females and unknown categories. 

### Top Starting Locations by User Type

![Top_Starting_Locations_Usertype](https://github.com/kareng013/bikesharing/blob/main/Images/Top%20Starting%20Locations%20by%20User%20Type.png)

In this map, the user type is show cased via starting locations. This map shows a majority of the user types are subscribers and where they tend to start. Regular customers may be tourists that start around the park and outter edges of the city. 

This map utilizes size which increases as number of users per starting point increases. It also gets darker as the number of users surpasses to a higher amount.


## Summary

In summary, the story presents visualizations of NYC Citibike data in different maps to showcase a few key points:

1) A majority of the users in the city are Male
2) The peak hours for trips are between 5:00pm to 7:00pm with Monday,Tuesday, and Thursday having the busiest hours. 
3) The subscriber population is much larger than regular customers, and by gender Males have the most number of subscriptions

In order to further enhance this report, we can also take a look at the number of subsribers by gender to show the ratio of males, females, and unknown.
Another good chart would be to show on a map where most users end their trip by user type and gender. 

Overall, the data may not represent similar data in Des Moines, however with more information from this town we can determine how data would differ when planning a Citibike company here.


