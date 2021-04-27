# Udacity-Project-5
Ford GoBike System Data Wrangling and Analysis


# Ford GoBike System Data

##Intro

Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

## Dataset

Dataset includes individual riders in San Fransisco who used bike-sharing system. All data is taken in Feb,2019.

## Summary of Findings

In this project, I gathered, assessed and cleaned data at wrangling phase and prepared for analysis.Later I started analysis data step by step. 

Quality issues were mostly incorrect data types and there were missing values for station name and member gender. I decided to delete rows of missing information. Also there was participants who were older than 75, I accepted this information wrong and deleted these rows as well. 
Also I created trip year, month, day, time, period of time, age columns.
Finally I started to analysis data.

Firtly I did univariate exploration. Here is my question to ask myself.

- Gender Distribution (bar chart): Male gender participated more than females. (%74.6 male)
- User Types Distribution (pie chart): %90.5 of participants is subscribers.
- Bike Share Distribution (pie chart): %90.1 of participants did not share their bike.
- Member Birth Year Distribution (histogram): Most of participants' birth year is between 1985 and 1995.
- Duration of Trip Distribution (histogram): Participants mostly used bikes between 200-500 seconds. 

Secondly I did bivariate exploration. Here is my question to ask myself.

- What is relationship between birth year vs duration of trip?: Participants who has birth year between 1985-1995 have higher duration of trip.
- What is relationship between gender distribution regarding to user type?: Females and males have higher participants who are subscribers.There are approx. 120.000 subscriber as male, approx. 4.000 subscribers 
- What is relationship between gender and duration trip?: Female has higher duration of trip than males.
- What is relationship between user type and duration trip?: Customer has higher duration of trip than subscribers.
- How is the distribution for duration of trip per day?: Weekends have higher duration of distribution than weekdays.
- How is the distribution for duration of trip per day period?: Duration of trip has higher value at evening and morning.
- What is relationship between gender and day period?: Both male and females used system on evening or morning more than other periods of day.
- What is relationship between gender and birth year?: Most of femaes and males were born at 1990-1980. 
- What is relationship between most popular stations and user type?: Customers Market St at 10th St is most popular start station for subcribers and costumers.

Finally I did multivariate exploration. Here is my question to ask myself.

- What is distribution duration of trip regarding to week days for subscribers and costumers?: Subscribers have less duration of trip than costumers for every day. Weekend is more popular than weekdays for both category.
- What is distribution duration of trip regarding to week days for males, females and others?: Others have higher duration of trip than males and females every day, females have higher duration of trip than males every day.
- What is distribution duration of trip regarding to genders for diffirent start stations?: There are 4 women who had over than 2.000 second duration of trip and their start station was Berry St at 4th St.
- What is the distribution duration of trip regarding to genders for diffirent ages?: Person who has highest duration of trip and is 19 years old is female.


As a result, some of my findings were really interesting and I added them to my explanatory analysis result as slide.
Here is some of them:

- It is obvious that male participants have important percentage than women.
- Although subscribers are more than customers, customers have higher duration of trip than subscribers. 
- People have more duration of trip at weekends.
- Mean Duration of trip is quite close for every period of day.
- Most Popular start station is Market St at 10th St for subcribers.
- Male gender has higher duration of trip than females every day, yet others have higher than males.
- Most of participants are younger than 40s. 


These are important results of analysis.
