# Bay Area Bike Share System

## Preliminary Comments


### 1. Distribution of the duration in minutes of all trips in the network

As we can see from the distribution graph, the majority of trips take a duration of around 10 minutes; the distribution is
highly skewed to the right with very few trips lasting around one hour. 

![dist_duration](https://user-images.githubusercontent.com/37026778/85017944-9a357380-b16c-11ea-9acd-c33e83affaf6.png)

### 1.2 Not equal start and end stations. 

It can be argued that the customers that take a bike in one station to end the trip in a different station may show different behaviour from those that end the trip in the same station as it was started. An additional separation between subscribers and occasional customers shows interesting patters to take into consideration. Over the week, we can hypothesize that the subscribers that start and end in a different station are those that go to work on a defined schedule. They show a marked difference from occasional customers, difference that is less strong over the weekend.

![duration_nestat_log](https://user-images.githubusercontent.com/37026778/85033500-500abd00-b181-11ea-941e-ad1304a40d96.png)

### 1.3 Equal start and end stations

With regards to the customers that start and end in the same station, it can be noticed that, on the first place, they constitute only a % of those who end in a different station. Futhermore, the difference between customers and subscribers is less marked than in the previous case. We could potentially explain this assuming that these are customers that are most probably not working on a fixed schedule. Both customers and subscriber get more likely distributions over the weekend.

![duration_equalst_log](https://user-images.githubusercontent.com/37026778/85033495-4da86300-b181-11ea-8c88-7f1319d991cb.png)

## 2.1 Total Trips by Day of the Week
 

## 2.2 Total Trips by Month 

![trips per month](https://user-images.githubusercontent.com/37026778/85033556-5ef16f80-b181-11ea-8cc9-50363cc1139d.png)

## Total Trips per hour

![trips per hour](https://user-images.githubusercontent.com/37026778/85033520-54cf7100-b181-11ea-97a1-90b19c71ea31.png)




