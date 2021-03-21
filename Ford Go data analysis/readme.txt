__Dataset used__:

-the fordgo bikes dataset

Data Cleaning part:

1- removing null values 
2-changing the __start_time__ and __end_time__ columns' datatype to 'timestamp'
3-creating a duration in minutes column
4-droppin the duration in seconds column
5-creating a member age category column including ['>=18', '>=40', '>=60']
6-creating three new columns for the year , month and day of the week of the dataset

__Main Data Findings__:

 1-number of unique stations in the dataset is about 330 stations, 
this may be useful in determinig whether we would need to increase
 or decrease the number of stations, to increase revenue.

2-It looks like the number of 'subscribers' in this data set is way above the number of 'customers', 
which may mean that people enjoy their experience with the service in general that they subscribe.

3-removing points where the age is more than 100 years because they act as outliers

4- The most duration points are between 2.23 and 84 minutes__, so I will remove the values which are more than 100 minutes as they act as outliers.

5-  The majority of users are between the age 18 - 60, this maybe due to the fact that the stations do not rent bikes to users whose ages less than 18 users
 maybe because they do not have personal ids

6-The highest amount of rentals was in thursday, then tuesday

7-The age category that spends the most riding the bikes are the '>=18' group which is kinda legitimate

8- The most time spent was in Sunday and Saturday with the average time is 14 mins

9- The most amount of time spe riding bikes is from the customers type, which is kinda __surprising__ because the amount of customer users compared to the subscriber users is __too small__,
 maybe this is telling us that the subscriber type users are using the bikes to do some __usual chores__ that do not span that __big amount of distance__ 
compared to the customer type users who might use the bikes for more far distened locations.Or maybe this is due to some __outliers__ in the customer user type. 

10-Actually the most amount of points are in the male and female genders but, the other gender has a lot of outliers which caused the confusion in the previous plot

11- It seems like that the customer type is dominant through out the week ,which means that customer type users use the bikes for longer distances in general but not as frequent as the subscriber type users.

12- The predominant user type is subscriber across all genders. And the >=18 age category is the predominant across all days of the week except Monday, maybe because monday is the start of the week so, people go to schools, colleges and work and most of the people who go to these places are between 18 and 40 

List of Resources:

kaggle

stackoverflow

tutorials point

seaborn document

matplotlib document