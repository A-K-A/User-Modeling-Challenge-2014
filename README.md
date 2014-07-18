User-Modeling-Challenge-2014
============================

https://www.ideatory.co/challenges/8/1/


The objective of this challenge is to build an effective data-driven recommendation system for predicting the rating a user is likely to give an event.


Problem Statement

The challenge is to model users based on their location and past activities. We have given a list of users who are represented by unique User IDs along with their home location. Also given are a list of events each represented by unique Event IDs along with their location. Users can attend events and sometimes give ratings to events. Given this data, you have to predict the ratings which users are likely to give certain events.

STAGE 1:
Analyze the given data set and find a data model to predict the ratings users will give to events.

STAGE 2:
Present the vision on how predictive data analytics can make our day-to-day life easier.


DATASETS:

D1: https://www.dropbox.com/s/2opz5e7pro6pfol/UserData.csv
user ID <-> the geospatial location (latitude and longitude) of each user 


D2: https://www.dropbox.com/s/ofdvx7c703l005v/EventData.csv
Event ID <-> the geospatial location (latitude and longitude) of each event

D3: https://www.dropbox.com/s/9dz513i4i55qx97/AttendanceData.csv
The information of a user attending an event.

D4: https://www.dropbox.com/s/qerik0pue5m8ejk/UserRatings(for%20training).csv
The ratings users have given to specific events.


FINAL TASK:
for all thr users in the following data:
https://www.dropbox.com/s/4arx3qtvhb4kczw/UserRatings(for%20evaluation).csv

Predict the rating the user is likely to give the corresponding event.


OUTPUT: The CSV file, in which the first column should contain the User ID, the second should contain the Event ID and the third should contain the rating that you predict the user will give to that event.


USER_ID, EVENT_ID, RATINGS


