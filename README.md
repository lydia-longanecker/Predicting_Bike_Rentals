# Predicting_Bike_Rentals
Washington, D.C. has a bike rental program.
The District collects detailed data on the number of bicycles people rent by the hour and day.
The CSV file contains 17380 rows, with each row representing the number of bike rentals for a single hour of a single day.
You can download the data from the University of California, Irvine's website. 

Here are the descriptions for the relevant columns:

instant - A unique sequential ID number for each row
dteday - The date of the rentals
season - The season in which the rentals occurred
yr - The year the rentals occurred
mnth - The month the rentals occurred
hr - The hour the rentals occurred
holiday - Whether or not the day was a holiday
weekday - The day of the week (as a number, 0 to 7)
workingday - Whether or not the day was a working day
weathersit - The weather (as a categorical variable)
temp - The temperature, on a 0-1 scale
atemp - The adjusted temperature
hum - The humidity, on a 0-1 scale
windspeed - The wind speed, on a 0-1 scale
casual - The number of casual riders (people who hadn't previously signed up with the bike sharing program)
registered - The number of registered riders (people who had already signed up)
cnt - The total number of bike rentals (casual + registered)

In this project, the goal of this project is to predict the total number of bikes people rented in a given hour. 
A few different machine learning models were created and evaluated in this project.
