# (Fordge Bike 2/2019 Data set)
## by (Kafayat Ibrahim)


## Dataset
  ### The 201902-fordgobike-tripdata is all about the information for  february 2019 fordge bike trip
>The data provided contain 16 columns with about 183412.two date time columns,which include start date and end date column. the data set has two location which are start_station, and end_station, user attributes. start and end latitude, longitute. the id's columns contain 197 null values,the member birth year and gender has 8265 null values. Most trip happens in same location so i decided to subset the data with the top 7 start station. Most trip started and ended in february except for some few trips so i did not actually consider the month in my analysis. i perform the following analysis in the subset data


## Summary of Findings
### Univariant Exploration:- 
>In this part of exploration, there are more trip in the early hour of day break, and evening period combining the hours to morning afternoon and night, there are more trip in the morning and afternoon and less trip in the night.Also there are more trip during the weekdays compare to weekend. it is claearly shown that the number of subscriber is higher than the number of customers with 90% and 9% respectively, this can be as a result of pricing. The  number of males is 3 times number of females with76% and 23% respectively. Most of the rider age falls between 30-40 years, The average duration of the trip is  around 650 seconds

### Bivariant Exploration:- 
>The relationship between member age and duration is slightly negative correllated, After creating a subset data with the  top 7 frequent station, in respect to the start station name, half of the station has more trips in the morning while the second half has more  trips in the afternoon. For the days of the week, there are more trip during the weekday while weekend has less trip across the top 7 stations. although i will investigate this further at the multivariant exploration

### Multivariant Exploration:- 
>After separating the user type, customers and sunscribers, exploring the two data set with time varible, with the period of the days half of thestations trips happen mostly in the morning while the other half trips occur mostly in the afternoon for both customers and subscribers. Investigating the two data set with days of the week, For customers user type most of the stations  trips has more freqency during the weekend e.g powell st bart station (market st at 4th st) and san francisco ferry building (harry bridges plaza) this might be due to the tourist center. For the subscribers most trip across the top 7  stations occur during the week days, althrough friday has a lesser trips compare to other weekdays this might be that most workers work from home on fridays. The subscribers in essence are workers who  go out in the morning and comes back in the evening period(majorly commuter) Also for the trip duration in secoond the average trip duration for customers is above 1000 seconds while for subscriber the average trip duration is around 650 seconds. This indicated that customers trip durations is always longer than that of subscribers


## Key Insights for Presentation
> Most trip happens during early hours of day break i.e aroun 8-9 hours in the morning, and 4-5pm in the evening, this can be as result of early hour rush to work and after close from work

> The stations with the higher trip is located in san fransisco, and connected to public transportation, including caltrain, Bart and ferry.

>the user type strongly influence the trip in terms of location and time group.

>customers trip has a longer duration to that of subscribers.


