# City Bike Analysis

## Summary 

After traveling to New York City and exploring historic landmarks such as Central Park, the Statue of Liberty, and the Empire State Building, an interest has been peaked in Citi Bikes. The Citi Bikes allowed for not only easier travel, but a more in-depth experience of the city. 

A Citi Bike Proposal has been made to propose a similar bikesharing business in Des Moines, Iowa. 

Since August is the most beautiful time of the year to rent a bike, August Citi Bike data has been analyzed to better understand how biksharing works in New York City. The following questions will be answered throughout in order to bring insight into a Des Moines bikesharing business. 

QUESTIONS:

(1) How many bike trips were recorded during the month of August?

(2) What is the breakdown of annual subscribers vs. short-term customers?

(3) What is the breakdown of male vs. female users?

(4) What are the highest traffic locations? 

(5) How many trips per bike were taken during the month of August?

(6) How much is each bike being utilized based on cumulative trip duration?

(7) What are the peak hours for bike rentals?

### Citi Bike User Information

To determine bikesharing expectations, Citi Bike User information has been analyzed for the month of August. 

A total number of 2,344,224 trips (rides) were recorded during the month of August; for each of these rides, the proportion of short-term customers versus annual subscribers to the Citi Bike Service has been determined. As illustrated by the "Customers" pie chart, about 81% of the customers are "subscribers", while only about 19% are "customers" (short-term riders).

The demographics of the users have also been take into consideration. The "Average Trip Duration" displays the average trip time in seconds versus the birth year of the user. In general, the later the birth year (older the user), the longer the ride duration. However, it is important to note that some of the user data is incorrect. There are user birth years dating back to 1885, which would make the user 135 years old. Although this user input has most likely been entered in correctly, the trend maintains consistent. Looking at the "Gender Breakdown", it can also be observed that the majority of the users are male. 

### Top Starting and Ending Locations

To help find the most popular Citi Bike stations in the city, the starting and ending latitude and longitudes for each bike ride has been plotted on a map of New York City. The more popular locations are marked by a larger and darker symbol. 

The most popular station for starting and ending trips is the Pershing Square North Citi Bike Station. The popularity of this station is most likely due to the fact that it is located directly across from Grand Central Terminal, a world-famous landmark in Midtown Manhattan also known as a shopping, dining, and cultural destination. 

### Bike Maintenance Considerations

Beyond the initial setup of the bikesharing business, bike maintenance will most likely be one of the largest expenses. The bikes used to most frequently will probably be the ones that require the most maintenance. To determine which bikes are being used the most frequently, each Bike Id in reference to its total number of records and total trip duration has been illustrated. 

The "Bike Repairs" treemap displays each Bike Id, and the larger and darker tiles correlate to a higher sum of "Number of Records". The "Bike Utilization" packed bubble chart illustrates the utilization level of each Bike Id. If a bike has a higher utilization level (higher cumulative trip duration), it will be a larger and darker bubble. When comparing the two charts, it can be observed that the Bike Id with the highest number of records does not also have the longest cumulative trip duration. This is an important observation since total trip duration for a certain bike may be skewed if one or more users took the bike on a very long ride. 

The best time to complete the maintenance on the bikes needs to be considered as well. Looking at the "August Peak Hours", it can be observed that 2:00 am to 5:00 am would be a good time for bike maintenance since the number of trips recorded during this time frame is much lower compared to others. For example, 5:00 pm to 7:00 pm are top riding hours during August in NYC, therefore it would negatively impact the business to prevent trips by performing maintenance at these hours. 

### Des Moines and New York City Demographics

Now that the original questions for understanding how bikesharing works in New York City have been reviewed, let's take a look at how this will apply to Des Moines. 

The gender diversity of Des Moines needs to be considered since the majority of Citi Bike users in New York are male. Comparing the gender breakdown of Des Moines and New York City, New York city actually has a larger percentage of females compared to Des Moines. This is positive news for Des Moines bikesharing. Even though there are a percentage of users during August that maintained an anonymous gender, the number of male users still exceeds the unknown and female users combined. 

Additional metrics have also been considered when comparing New York City and Des Moines as well, particularly age groups. Des Moines has a similar age breakdown compared to New York City, in that the majority of the population are between the ages of 18 and 64. Refering again to the "Average Trip Duration", the average trip duration steadily increases, in general, from having a birth year in 1965 to 2003. This trend falls within the range for people from 17 to 65 years of age, which is similar to the city's largest age group. 

### Additional Considerations

Overall, there is a lot of potential for a successful bikesharing business in Des Moines. I still, however, recommend performing additional research on the following questions:

QUESTIONS:

(1) What are the top attractions in Des Moines and where are they located? 
- Based on the top starting and ending locations, the most popular stations are located either near a popular public transportation hub or tourist attraction. The wide variety of popular destinations in Des Moines make it a good candidate for a bikesharing service. Specifically, there is a large emphasis on outdoor activities such as popular trails and parks. There may be a potential market in providing bike services not only in the main city for historical, food/ drink, art, and event related activities, but also near trailheads as well. 

(2) How many square miles will the bike stations cover? And, how many bike stations will there be?
- Keeping in mind that the average bike trip duration in New York City is about 18 minutes, it is important to start considering how for apart each bike station will be located from one another. Also, based on popular attractions and where the bike will be most utilized, the area where the bikesharing service will be provided within needs consideration as well.

### Tableau Public link
<https://public.tableau.com/profile/shayna2477#!/vizhome/bikesharing_15996439905750/CitiBikeProposal>











