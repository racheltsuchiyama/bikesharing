# bikesharing

## Overview
The bike sharing business has proved to be very successful in New York City. In order to determine if the bike sharing business would also be successful in Des Moines, I performed analysis of the bike sharing data from NYC. Bike sharing programs are popular among tourists, as a way to get around a new city and explore it in a more in depth manner. Bike sharing programs are also popular among locals because they provide a convenient method of transportation for commuting to and from work. Therefore, there is the potential for a large customer base for the bike sharing program in Des Moines.

## Results

* **Checkout Times**

![avg_duration](https://user-images.githubusercontent.com/83552696/127792083-8e24f80b-eb24-4165-813d-6fc211d98736.jpg)
As the age of the rider decreases, the average trip duration increases. Therefore, younger people take longer bike rides than older people. The working aged riders rent more bikes than the elder riders, but there are some anomalies within the data. For example, the peak in average trip duration for riders born in 1890 is strange.


![Checkout_users](https://user-images.githubusercontent.com/83552696/127792031-d7faa2e8-1a4f-4b91-8cbc-3f61d2915ab0.jpg)
This graph shows the trip durations of the bikes for each rider. The majority of the riders checkout the bike for less than an hour, with a peak at five minutes. However, there are riders that check out the bikes for 1 to 23 hours.

![6](https://user-images.githubusercontent.com/83552696/127792075-9f661db7-a60e-43f9-8162-62230eac02d5.jpg)

To analyze the customer base, I looked at the breakdown of the genders of each rider. The majority of the riders are men and about a quater of the riders are female. Therefore, men are more likely to rent bikes in NYC.

![2](https://user-images.githubusercontent.com/83552696/127792035-d54d475f-1230-4c34-8ca9-d8e1bc510323.jpg)
I further investigated the checkout times and gender by filtering the first graph by gender. The men checkout times peak at five minutes while the women checkout times peak at six minutes. The majority of men and women checkout bikes for less than an hour. This further shows that people find the bikes quick and convinient. 

* **Trips**

![3](https://user-images.githubusercontent.com/83552696/127792039-4f12639f-9988-4df8-a084-0d6e55fa3f33.jpg)

This graph shows the hours of the days of the week that have the most rides. The darker the square, the more bikes were rented on that hour on that day. A lot of the bikes are rented at 8am and 5pm, which is the time people commute to and from work. There are also riders that rent from 9am to 5pm on the weekends. 

![4](https://user-images.githubusercontent.com/83552696/127792041-cefdf794-4b9b-4d3d-b1eb-e18149a98bdf.jpg)
I filtered the graph above by gender. The male riders use the most bikes at 8am and 5pm on weekdays. They also use the bikes for weekend transportation. The women ride the bikes at the some hours, but to a lesser degree. Therefore, the riders in NYC rent the bikes to commute and for recreational activities.

![5](https://user-images.githubusercontent.com/83552696/127792046-e9a6a797-c518-40a1-8ad3-6b40c7fed619.jpg) ![5_legend](https://user-images.githubusercontent.com/83552696/127792063-c44a3183-4c35-4d4e-a007-34d02669358d.jpg)
This graph shows the user trips by gender by weekday and filtered by usertype. There are more subscribers than customers renting the bikes. The men subscribers rent the most bikes on Thursday, followed by the other weekdays. They rent the bikes on the weekends, but at a lower frequency.The women data follows a similar pattern to the men's rider data.

## Summary
The graphs demonstrates the high usage of rental bikes during commuting hours. There are a large number of men in NYC that rent city bikes on the weekdays at 8am and 5pm for short trip durations. Therefore the bike rentals are popular among the male working class, and some of the female working class, for commuting. The riders also use the bikes for recreational activities on the weekends.

Another useful visualization would be the activitiy of each bike. It would be useful to know the total trip miles of each bike because it would provide insight into the bike's performance. The bike sharing program would not be profitable if the bikes were breaking down after short time periods. Another useful visualization would be comparing all the commuting methods of the working population. If a majority of the working population are subscribers to bike rental programs to commute, it would indicate that rental bikes are a popular form of commute transportation.

## Tableau Story
[link to dashboard]  https://public.tableau.com/app/profile/rachel.tsuchiyama/viz/Challenge_16277058175350/BikeSharingStory?publish=yes
