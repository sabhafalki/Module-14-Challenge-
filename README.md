# Module-14-Challenge-Bikesharing
An analysis of NYC CitiBike bikesharing data from August, 2019, with Tableau

# Overview of Project #
The goal of this project is to use create visualtions, in order to help investors in hte bike-sharing program make a suitable decision. In order to accomplish this, analysis was carried out on the following:
1. The lenght of the time the bikes were checked out
2. THe number of bike trips for all riders
3. The number of bike trips for each type of user and gender

# Resources #
- Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
- Software: Tableau, Python, Jupyter Notebook, Pandas Library

# Results #
## Number of Bikes based on Duration ##
![initial](bikesharing/Image/Checout_times_users.png) <br><br>

This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

## Number of Bikes based on each Gender by Hour ##
![initial](bikesharing/Image/checkout_Gender.png) <br><br>

This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

## Number of Bike Trips on an Hourly Basis ##
![initial](bikesharing/Image/Trip_By_Weekday_hour.png) <br><br>


## Number Bike Trips by Gender on a Hourly Basis ##
![initial](bikesharing/Image/trip_weekday_by_Gender.png) <br><br>

A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.
## Number of Bike Trips based on Gender on a Daily Basis ##
![initial](bikesharing/Image/user_trip_by_gender_by_weekday.png) <br><br>
Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.
## Peak Hours of Usage ##
![initial](bikesharing/Image/Peak_Hours_of_Usage.png) <br><br>

This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.
## Gender Breakdown ##
![initial](bikesharing/Image/Gender.png) <br><br>

In the above image we can see that more than 3/4 of the users are Subscribers, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.
# Summary #
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

- Trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
- Average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.



