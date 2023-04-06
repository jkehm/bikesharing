# Module 15 Challenge - Bikesharing

## Overview
In this Module we have been learning about Tableau and it's many uses. In this challenge we will create a Story for one of the investors, who would like to see the following. 
* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.
* Some additional analysis will be required

#### The link to the created dashboard can be found [here](https://public.tableau.com/app/profile/justin.kehm/viz/Module_15bikesharing/Story#1)
## Results
In this section we will take a look at each deliverable, and explain what the images mean. 


![link to Checkout Times](https://github.com/jkehm/bikesharing/blob/main/images/Checkout%20Times%20for%20Users.png)
This line graph indicates that the majority of people rent their bikes for less than 10 minutes or so. From time 0, there is a steady increase until the 5 minute mark, where we see a steady decrease until the 40 minute mark or so. At that point the graph starts to flatten out. From this graph, it is clear that most people are using these bikes for short rides. 

![link to Checkout Times by Gender](https://github.com/jkehm/bikesharing/blob/main/images/Checkout%20Times%20for%20Users%20by%20Gender.png)
This graph was built very similarly to the one above. However, here we also filter by Gender. It is clear that the vast majority of users are male. Overall, the same general trend is seen as in the graph where we did not filter by gender, which makes sense. 

![link to Trips by weekday per hour](https://github.com/jkehm/bikesharing/blob/main/images/Trips%20by%20Weekday%20Per%20Hour.png)
In this Heatmap we are taking a look at when the bikes are the most popular, based on the hour of the day, and which day of the week. There is a clear increase in usage on Monday-Friday in the morning and afternoon. These times are consistent with when people would be commuting to and from work. On the weekends, we see an increase in usage from 10 AM until 9 PM. Which is consistent with people going out and enjoying their weekend. 

![link to Trips by Gender Weekday per Hour](https://github.com/jkehm/bikesharing/blob/main/images/Trips%20by%20Gender%20weeday%20per%20hour.png)
This heatmap was again constructed very similarily to the one above. However, we also filtered by Gender. The same general pattern can be seen when comparing the Female and Male graphs. However, the colors are darker for the Males. Which again supports our second graph "Checkout Times by Gender," indicating that Males are predominantly using these bikes.

![link to User Trips by gender by weekday](https://github.com/jkehm/bikesharing/blob/main/images/User%20Trips%20by%20Gender%20by%20Weekday.png)
This heatmap shows who is using the the Citibikes the most. We have filtered by Gender, Usertype, and Day of the Week. 

Based on our graph, it is clear that Subscribers are more likely to use these bikes on average than a general customer. And certainly, males use these bikes the most, with Males that are subscribers using them the most by far. In general these bikes are getting use mostly during the week. Which supports our idea that these bikes are being used to commute to and from work primarily.

![link to Top Starting Locations](https://github.com/jkehm/bikesharing/blob/main/images/Top%20Starting%20Locations.png)
![link to Top Ending Locations](https://github.com/jkehm/bikesharing/blob/main/images/Top%20Ending%20Locations.png)
Here we are comparing the Top starting and Ending locations for our Citibike data. The most populated area by far in this data is Manhattan. Which is a business center of New York City. 

Interestingly it seems that these two maps are  very similar. Which supports the idea that people are taking a trip into the city to work, and then riding back home at the end of the day.

## Summary
From the analysis that we have conducted it is clear that the predominate user of the Citibikes are Males. Additionally, it is a very good sign that most of the users are already subscribed to the App. Also, there is not an issue where bikes are being scattered across New York City. Based off of the Top Starting and Ending Locations graphs, we know that in general people are picking up a bike near their home, riding to work, picking up a different bike in the evening, and riding back home. So, this system seems self-regulating and no company interference must occur. 

In an effort to dig further into the data, some more visualizations could be performed. One example would be looking into which bikes are being used the most, and are in need of servicing. We could also add a gender filter to the Starting/Ending locations and see if there is any good information to be pulled from that.

I would also be curious to look into some data in Des Moines (the area that the investors are looking to expand to) and see if biking is a viable option there. Are bike lanes available? Is the population density dense enough to allow for people to live close enough to their work to bike, or would that just be a small amount of people?
