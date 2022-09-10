# (Ford GoBike Dataset Exploration )
## by (Ozigis Mutalib)


##Go Bike Dataset

    1.This data set was provided by Udacity data analytics course in the communicate your data finding projectincludes information about individual rides made in a bike-sharing system(Ford GoBike) covering the greater San Francisco Bay area for the month of February,2017.The data set contains information about 183412 bike trips.This information spread across 16 columns whose names are intuitive- duration_sec,start_time,end_time,start_station_id,start_station_name,start_station_latitude,start_station_longitude,end_station_id end_station_name,end_station_latitude,end_station_longitude,bike_id user_type,member_birth_year member_gender,bike_share_for_all_trip.
    
    2.To be able to do analysis of the hours , days of the week variations in number of trips, extra(day,hours) columns were created and filled by extracting their values from the start_time column
    
    3.To get the age distribution, a new column was created and filled by subtracting the date of birth from 2022.
    the age was divided in to categories with the bin function, to provide more context to the ages


## Summary of Findings
     1.majority of the trips made lasted between 500-600 seconds,with very few trips lasting 2000 seconds and above.More trips were made as the duration of the trip was increased until it reached the maximum of 500-600 seconds from which fewer people could go beyond that length of trip
     
    2.the weekends had least amount of trips. This is logical as weekends are mostly off days
    
    3.There are two times of the day, 8am and 5pm, where the number of trips is the highest. This corresponds to the peak hours(resumption and closing time of businesses)
    
    4.Males carried out triple of the number of trips carried out by the females and other gender
    
    5.From the chart above, it can be seen that people btween the ages of 25-64 used the bike system the most, with very few seniors and young adults. this further corroborates the time distribution which seem to suggegst the users are working population or people involved in business
    
    6.It can be seen that majority of the users were between ages 20-40 years and a lot of them used the bike for less than 2000 seconds with subscribers more than customers.
    
    7,As adults use the bike rides most, their average length of ride is not significantly different from the few adults and seniors who eventually use the ride
    
    



## Key Insights for Presentation

    1.some of the variables, gave an insight as to the type of people who use the bike to be working population(24-64)years.
    2.the Duration of trips is not really affected by gender but might be affected by the user type
