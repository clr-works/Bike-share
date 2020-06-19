# Bay Area Bike Share System

## Preliminary Comments

### Geographic distribution of stations in the network

![newplot (14)](https://user-images.githubusercontent.com/37026778/85102706-7bcf8680-b205-11ea-84f7-e94512f3e815.png)

### Geographic distribution of trips per station where they start

![newplot (15)](https://user-images.githubusercontent.com/37026778/85102635-5c385e00-b205-11ea-8b46-7be9324bd7cd.png)

### 1.1 Distribution of the duration in minutes of all trips in the network

As we can see from the distribution graph, the majority of trips take a duration of around 10 minutes; the distribution is
highly skewed to the right with very few trips lasting around one hour. 

### 1.2 Distribution of the distances in km for all trips.

These distances are approximated by the distance between start station and end station,resulting in no estimation for the cases where the end and start station are the same. The purpuse is not to examine the km the riders ride, but to understand if the different cities in the network act as separate clusters.


### 1.1 Total Trips by Day of the Week

As noted in the previous section, day of the week is a very relevant variable to take into account.The majority of the trips
occur during the week, where there is a marked difference in behaviour between customers and subscribers. The following graph confirms the relevance of the week vs weekend analysis
 
<img src="Images/trips_days.png">
 

### 1.2 Total Trips by Month 

If we look at the impact of the month, we see the major impact is comparing July performance to December. Subscribers are impacted with a reduction of 40% whereas customers reduction in activity is around 30%. They show similar behaviour over the weekend for the whole year.


<img src="Images/trips%20per%20month.png">


### 1.3 Total Trips per Hour

Trips per hour sheds further light over the difference between customers and subscribers. Subscribers show a marked behaviour over the week, linked to working hours (conmuting from work), while customers have a more equally distributed behaviour over the day.

<img src="Images/trips%20per%20hour.png">



### 2.1 Not equal start and end stations. 

It can be argued that the customers that take a bike in one station to end the trip in a different station may show different behaviour from those that end the trip in the same station as it was started. An additional separation between subscribers and occasional customers shows interesting patters to take into consideration. Over the week, we can hypothesize that the subscribers that start and end in a different station are those that go to work on a defined schedule. They show a marked difference from occasional customers, difference that is less strong over the weekend.


### 2.2 Equal start and end stations

With regards to the customers that start and end in the same station, it can be noticed that, on the first place, they constitute only a % of those who end in a different station. Futhermore, the difference between customers and subscribers is less marked than in the previous case. We could potentially explain this assuming that these are customers that are most probably not working on a fixed schedule. Both customers and subscriber get more likely distributions over the weekend.


### 3.1 Number of Trips started por city, showed in logarithmic scale


### 3.2 Heatmap San Francisco

![heatmatp_sanfrancisco](https://user-images.githubusercontent.com/37026778/85104797-8db32880-b209-11ea-89c2-69fa6db7595a.png)

### 3.3 Heatmap Mountain View

![mountain view heatmap](https://user-images.githubusercontent.com/37026778/85104950-d79c0e80-b209-11ea-80e2-cbc3875d9510.png)

### 4.1 Impact of Weather on activity during the Week

<img src="Images/weather_impact_week.png">

### 4.2 Impact of Weather on activity during the weekend

<img src="Images/weather_impact_weekend.png">

### 4.3 Hour impact by month, December

<img src="Images/December.png">

### 4.4 June

<img src="Images/june.png">

