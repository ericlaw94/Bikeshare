# Citi Bike NYC System Dataset - How does Covid19 affect Citi Bike Ride Trend?
## by Eric Law Yuwei


## Dataset

Introduction
Citi Bike is New York City’s bike share system, and the largest in the nation. Citi Bike launched in May 2013 and has become an essential part of our transportation network. It's fun, efficient and affordable – not to mention healthy and good for the environment.


Citi Bike consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. People use bike share to commute to work or school, run errands, get to appointments or social engagements, and more. Citi Bike is available anytime, anyday, and riders have access to thousands of bikes at hundreds of stations across Manhattan, Brooklyn, Queens and Jersey City.

In this project, I will be investigating the year 2020 Citi Bike dataset by using Python to perform steps of the data analysis.


Note:The dataset can be obtain from here: https://www.citibikenyc.com/system-data which include

Trip Duration (seconds)
Start Time and Date
Stop Time and Date
Start Station Name
End Station Name
Station ID
Station Lat/Long
Bike ID
User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
Gender (Zero=unknown; 1=male; 2=female)
Year of Birth


## Summary of Findings

- By comparing with previous dataset, year 2020 obviously has less bike users compare with any other years due to Covid 19 Pandemic
- There are two type of users which are Subscriber and Customer. Subscriber which majority are male gender representing 74.1% and customer holds 25.9%.
- The average age bike user is between 30-35
- The most popular place to rent bike is Grove St Path , and least popular place is JCBS Depot.
- Subscribers are mainly commuters. Bike usage peaks at 8am and 5-6pm daily on the weekdays.
- Both user ride behavior are show similar pattern in the weekend
- Saturday is the most popular day for bike usage in 2020 which more than 40k trip made by users
- April has the lowest bike usage as the government in New York City responsed to the Covid 19 pandemic with a full lockdown from March 2020 to April 2020, followed by a four-phase reopening plan by region from April 2020 to July 2020.


## Key Insights for Presentation

> Citibike Gender & User Types ratio are shared
> Citibike monthly usage based on user types figure is provided
> Bike hourly usage based on user type are shared to show the important time
> Multivariate Exploration with Heatmap is provided 
