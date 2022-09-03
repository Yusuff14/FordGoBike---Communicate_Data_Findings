# FordGoBike Exploratory Data Analysis
## by Yusuff Adebayo


## Dataset

This dataset is a compilation of the records of a bike hailing service known as FordGoBike. It contains information about individual rides made in a bike-sharing system. This dataset contains 183,412 observations with 16 variables which include: Ride duration (Secs), Start and end time, Start and end station id and Name, Start and end station Latitutude and Longitude, Bike Id, User type, Member birth year, Member gender, Bike share for all trip (Yes or No). Moreso, this dataset was provided by Udacity and it can be downloaded through this [link here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

After careful assessment and wrangling of the data, I discovered the need for feature engineering. Then, I created three more variables from the existing features to aid my analysis which were trip duration minutes, age and days of the week. This consequently increased my features to 19.


## Summary of Findings

From my data exploration, here are some of the findings made:

> Most of the trips are carried out on weekdays especially on Thursday with weekends recording the lowest.

> Also, the duration on riding is skewed to the right implying that most users spend short time on riding usually between 1 to 20 minutes.

> While 91% of users do not share their ride, only 9% do and the male gender happens to be the leading gender at saying NO to bike sharing.

> Also, while there are relatively fewer rides during the weekends, users actually spend more time riding during this period as against weekdays.

> On an average, female riders are younger than male riders but the male riders completed their trips faster than the female riders.

> Some users ride for 3 hours and beyond. However, it is only the youths around 30 years of age that fall in this category.

> There are more Subscribers than Customers.


## Key Insights for Presentation

The following amongst others are the Insights for the Presentation;

> The first insight involves age distribution as well as trip duration of the users of which both are skewed to the right.

> The distribution of those who share their ride against those who do not.

> Peak periods of the trips and the major users of the bike service.

> Lastly, the relationship between the numerical variables (duration and member age) was looked into as well as their relationship with other categorical data (such as gender, days of the week and user type).
