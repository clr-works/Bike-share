# Bay Area Bike Share System

## Preliminary Comments

### Geographic distribution of stations in the network

![heatmatp_sanfrancisco](https://user-images.githubusercontent.com/37026778/85060763-0d0f1080-b1a6-11ea-9038-effb5b2f9190.png)

### Geographic distribution of trips per station where they start

![mountain view heatmap](https://user-images.githubusercontent.com/37026778/85060755-097b8980-b1a6-11ea-9fb6-f8b2942317aa.png)

### 1.1 Distribution of the duration in minutes of all trips in the network

As we can see from the distribution graph, the majority of trips take a duration of around 10 minutes; the distribution is
highly skewed to the right with very few trips lasting around one hour. 

![dist_duration](https://user-images.githubusercontent.com/37026778/85017944-9a357380-b16c-11ea-9acd-c33e83affaf6.png)

### 1.2 Distribution of the distances in km for all trips.

These distances are approximated by the distance between start station and end station,resulting in no estimation for the cases where the end and start station are the same. The purpuse is not to examine the km the riders ride, but to understand if the different cities in the network act as separate clusters.

![distance of trips dist](https://user-images.githubusercontent.com/37026778/85047062-9d8f2600-b191-11ea-89eb-94261a7bf885.png)

### 1.1 Total Trips by Day of the Week

As noted in the previous section, day of the week is a very relevant variable to take into account.The majority of the trips
occur during the week, where there is a marked difference in behaviour between customers and subscribers. The following graph confirms the relevance of the week vs weekend analysis
 
![trips_days](https://user-images.githubusercontent.com/37026778/85037176-4a16db00-b185-11ea-8aee-3c3ead73d163.png)

### 1.2 Total Trips by Month 

If we look at the impact of the month, we see the major impact is comparing July performance to December. Subscribers are impacted with a reduction of 40% whereas customers reduction in activity is around 30%. They show similar behaviour over the weekend for the whole year.

![trips per month](https://user-images.githubusercontent.com/37026778/85033556-5ef16f80-b181-11ea-8cc9-50363cc1139d.png)

### 1.3 Total Trips per Hour

Trips per hour sheds further light over the difference between customers and subscribers. Subscribers show a marked behaviour over the week, linked to working hours (conmuting from work), while customers have a more equally distributed behaviour over the day.

![trips per hour](https://user-images.githubusercontent.com/37026778/85033520-54cf7100-b181-11ea-97a1-90b19c71ea31.png)


### 2.1 Not equal start and end stations. 

It can be argued that the customers that take a bike in one station to end the trip in a different station may show different behaviour from those that end the trip in the same station as it was started. An additional separation between subscribers and occasional customers shows interesting patters to take into consideration. Over the week, we can hypothesize that the subscribers that start and end in a different station are those that go to work on a defined schedule. They show a marked difference from occasional customers, difference that is less strong over the weekend.

![duration_nestat_log](https://user-images.githubusercontent.com/37026778/85043551-c6f98300-b18c-11ea-8de1-768311b6214f.png)

### 2.2 Equal start and end stations

With regards to the customers that start and end in the same station, it can be noticed that, on the first place, they constitute only a % of those who end in a different station. Futhermore, the difference between customers and subscribers is less marked than in the previous case. We could potentially explain this assuming that these are customers that are most probably not working on a fixed schedule. Both customers and subscriber get more likely distributions over the weekend.

![duration_equalst_log](https://user-images.githubusercontent.com/37026778/85042974-24d99b00-b18c-11ea-8363-037437193548.png)

### 3.1 Number of Trips started por city, showed in logarithmic scale

![cities](https://user-images.githubusercontent.com/37026778/85045936-fcec3680-b18f-11ea-8c1e-8491c52a45dd.png)

### 3.2 Heatmap San Francisco

![heatmatp_sanfrancisco](https://user-images.githubusercontent.com/37026778/85045926-f8c01900-b18f-11ea-871c-b1d2b163a338.png)

### 3.3 Heatmap Mountain View

![mountain view heatmap](https://user-images.githubusercontent.com/37026778/85045911-f362ce80-b18f-11ea-9509-3bc50ef5d7e4.png)

### 4.1 Impact of Weather on activity

![weather_impact](https://user-images.githubusercontent.com/37026778/85047694-7d139b80-b192-11ea-8625-62b2bae6433e.png)
