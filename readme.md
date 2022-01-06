# about the used Dataset
the dataset fordgobike-tripdata that contain data about trips in 2019-february of 16 columns and 183412 rows of data most of them are clean with no dublicated rows and less 5% of the data only 8460 rows having nan values 

## wrangling steps:
- import the data from the CSV file to be a datafram
- change the data type of start_time , end_time from object to time 
- create new columns: age, start_day, start_month, start_hour 
- remove the outliers for ages, durations

## findings summary (conclutions) :
-  most of the users or members are males
-  most of the users are subscribers 
-  most of bike share for all trip are NO
-  most of the user use the bike for about 5 minutes
-  thursday is the most day and 5PM is the most hour 
-  most of the users are between 30 and 35 years old for all the gender types
-  there is no significant differant between them 
-  the average trip duration for users of user type Customer are more than Subscriber
-  as the age increase the duration decrease
-  no signficante differance between the days, while the customer is always larger the customers
-  the duration of the trip for the user type: subscriber is always lower than the user type: customer over the week days
-  the duration of the trip for the males is always larger than the females over the week days while the others are in between.


