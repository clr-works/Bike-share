# Bay Area Bike Share System

## Preliminary Comments


### 1. Distribution of the duration in minutes of all trips in the network

As we can see from the distribution graph, the majority of trips take a duration of around 10 minutes; the distribution is
highly skewed to the right with very few trips lasting around one hour. 

![dist_duration](https://user-images.githubusercontent.com/37026778/85017944-9a357380-b16c-11ea-9acd-c33e83affaf6.png)

### 1.2 Not equal start and end stations. 

It can be argued that the customers that take a bike in one station to end the trip in a different station may show different behaviour from those that end the trip in the same station as it was started. An additional separation between subscribers and occasional customers shows interesting patters to take into consideration. Over the week, we can hypothesize that the subscribers that start and end in a different station are those that go to work on a defined schedule. They show a marked difference from occasional customers, difference that is less strong over the weekend.


### 1.3 Equal start and end stations

With regards to the customers that start and end in the same station, it can be noticed that, on the first place, they constitute only a % of those who end in a different station. Futhermore, the difference between customers and subscribers is less marked than in the previous case. We could potentially explain this assuming that these are customers that are most probably not working on a fixed schedule. Both customers and subscriber get more likely distributions over the weekend.


### 2.1 Total Trips by Day of the Week

As noted in the previous section, day of the week is a very relevant variable to take into account.The majority of the trips
occur during the week, where there is a marked difference in behaviour between customers and subscribers. The following graph confirms the relevance of the week vs weekend analysis
 
![trips_days](https://user-images.githubusercontent.com/37026778/85037176-4a16db00-b185-11ea-8aee-3c3ead73d163.png)

### 2.2 Total Trips by Month 

If we look at the impact of the month, we see the major impact is comparing July performance to December. Subscribers are impacted with a reduction of 40% whereas customers reduction in activity is around 30%. They show similar behaviour over the weekend for the whole year.

![trips per month](https://user-images.githubusercontent.com/37026778/85033556-5ef16f80-b181-11ea-8cc9-50363cc1139d.png)

### 2.3 Total Trips per Hour

Trips per hour sheds further light over the difference between customers and subscribers. Subscribers show a marked behaviour over the week, linked to working hours (conmuting from work), while customers have a more distributed behaviour over the day.

![trips per hour](https://user-images.githubusercontent.com/37026778/85033520-54cf7100-b181-11ea-97a1-90b19c71ea31.png)




