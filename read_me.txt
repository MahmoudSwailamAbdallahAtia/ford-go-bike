# Fordgobike-Tripdata Exploration


## What is the structure of dataset?
	there are 183,412 rows of 3 types of data:
	duration_sec and start/end_time are quantitative continues,
	member_birth_year is quantitative descrite the rest of data are categorical nominal.

## What is/are the main feature(s) of interest in dataset?
	I'm most interested in figuring out which features are predicting which age is more productive and help us to be the best?

## What features in the dataset do you think will help support your investigation into your feature(s) of interest?
	member_birth_year and our known the data for Feb 2019 will determine the age,
	duration_sec will determine the productivity
	rest of data will determine which best age for us or range of ages


## the main key insight is which age or ages more productive?

### it extract alot of questions but we interested in some as our questions:

	which age or ages more frequent?
	when we count ages we find that age 31 is the most frequent with 10236 user,
	and then 26 years old with 9325 user and then 30 with 8972 , 29 with 8658 
	31, 26, 30 is more frequent than others 
	
	which age or ages we need to care about in frequent or which less frequent?
	alot of ages we need to care about if it more productive than others in another side.
	ages counts less than 100 people  18 years old which is more productive in another side ,and
	76, 77, 86, 73, 117, 80, 78, 118, 81, 99, 85, 75, 91, 109, 89, 92, 141, 70, 88, 119, 71 years old
	
	which ages counts of it between mean and median ?
	counts between mean and median in this ages 19 , range ages 46:52 and range ages 54:56
	
	is ages between mean and median far away from the top heighst ages?
	the top heighst counts more than 3 times
	the counts between mean and median
	that explain that we focus only in range ages 26 to 31 years old
	but we dont care about alot of data we need to care about
	
	what is the shape of count of ages in all data sorted by ages?
	the shape of data is right skewd from age 18 to 141 the average of ages is 34 years old.
	count of age increase from 18 to 31 and then decrease
	
	what ages counts of it above mean ?
	and what ages counts of it above median?
	range ages above mean from 20 to 45 years old.
	range ages above median from 19 to 56 where the destribution is right skewd more than mean.
	
	which range of ages is compine most the data ?
	approxemately all the data compined above age 17 years old and under age 41 years old.
	
	what is the proportion of Top 5 ages count people?
	approxemately 25% of this data in only 5 ages which are 26 years old and range from 28 years old to 31 years old.
	
	we know now 25% of counts what about 50%, 75%, 90% ?
	proportions of data 24.9%, 50.8%, 75.8%, and 90.3%
	range ages of this proportions respectivly:

		25% of data in this ages {26, [28 : 31]}
		50% of data between 24 years old and 34 years old.
		75% of data between 22 years old and 40 years old.
		90% of data between 20 years old and 51 years old.
		90% of data from 20 to 48 years old and 51 years old.
		
	if there any groups of ages seems to be like each other?
	count 11 people for ages 117, 80 and count 807 people for ages 59, 62 years old.
	
	counts people whats the shape of it when we talk about range ages in this data?
	when the age increase the count of people in this age decrease
	
	what range of ages in this data when we talk about counts?
	approxemately range of counts people between 20 and 80 years old.
	
	which ages more productive in duration seconds?
	when we talk about duration second in this data approxemately more people between 18 and 65 years old
	
	what is the mean of duration second of every age? 
	and why age 18 is more productive less count ?
	average of age 18 years old is greater than others when we talk about duration sec.
	when we want more duration second its important to focus on age 18 years old in our marketing.
	because of average more productive in duration of second and now there only 34 person in this data
	
	what count of duration second of every age? and what is the shape of it?
	the shape determine the counts of duration second of every age the shape is right skewd from fewest range ages to largest.
	count duration second is more between 19 and 48 years old from 48 to 63 years old decrease and then be few above 63 years old.
	
	what is porportion of top count duration for ages ?
	and what count duration more productive?
	sum of duration better in this range of ages 26:31 years old which its porporthion of count duration_sec is 31.6% .
	30 and 31 ages is more productive when we talk to duration second; but it is not surprise
	because approxemately this 2 ages come to ride more than others especialy 31 years old with 10236 person.
	
	what range of ages counts duration second is above or equal mean?
	from 21 to 45 years old greater than or equal to the mean of duration second.
	
	what size of half data as type customers ?
	and what size of half data as type supscribers when we talk about ages?
	aproxemetly all of data combined between 20 and 40 years old
	half of customers between 28 and 36 years old
	half of subscribers between 27 and 39 years old
	
	
	what type is more productive?
	we see now that customers are more productivity when we talk about duration second than subscribers.
	


# summary:
	average of ages is 34 with count 8265 but when we talk to average of count for all years will be 2413 user.
	the shape of data is right skewd from age 18 to 141 the average of ages is 34 years old
	count of age increase from 18 to 31 and then decrease.
	range ages above mean from 20 to 45 years old.
	range ages above median from 19 to 56 where the destribution is right skewd more than mean.
	approxemately all the data compined under age 40 years old.
	26 years old and range from 28 years old to 31 years old is more than others.
	approxemately 25% of this data in only 5 ages which are 26 years old and range from 28 years old to 31 years old.
	proportions of data 24.9%, 50.8%, 75.8%, and 90.3%
	range ages of this proportions respectivly.
	25% of data in this ages {26, [28 : 31]}
	50% of data between 24 years old and 34 years old.
	75% of data between 22 years old and 40 years old.
	90% of data between 20 years old and 51 years old.
	90% of data from 20 to 48 years old and 51 years old.
	ages 75, 80, 81, 85, 89, 91, 92, 99, 109, 117, 141 is less than others
	group of ages count people less than 100 person
	 is{18, 70, 71, 73, [75:78], 80, 81, 85, 86, 88, 89, 91, 92, 99, 109, 117, 118, 119, 141}
	when the age increase the count of people in this age decrease.

	18, 70, 71, 73, 75, 78, 80, 81, 85, 86, 88, 89, 91, 92, 99, 109, 117, 118, 119, 141
	this ages compined is 468 user only as a porportion of people who come to ride bike is 0.25%

	approxemately range of counts people between 20 and 80 years old.
	when we talk about duration second in this data approxemately more people between 18 and 65 years old.
	average of age 18 years old is greater than others when we talk about duration sec

	when we want more duration second its important to focus on age 18 years old in our marketing
	because of average more productive in duration of second and now there only 34 person in this data.

	count duration second is more between 19 and 48 years old from 48 to 63 years old decrease 
	and then be few above 63 years old.
	sum of duration better in this range of ages 26:31 years old which its porporthion of duration_sec is 31.6% 

	30 and 31 ages is more productive when we talk to duration second; 
	but it is not surprise because approxemately this 2 ages come to ride more than others 
	especialy 31 years old with 10236 person.

	from 21 to 45 years old greater than or equal to the mean of duration second.

	aproxemetly all of data combined between 20 and 40 years old
	half of customers between 28 and 36 years old
	half of subscribers between 27 and 39 years old

	customers are more productivity when we talk about duration second than subscribers.
