# Analysis of Ford Bike Sharing Data In Francisco Bay Area
## by Odimegwu David


## Dataset

> This project was carried out to satisfy the requirements for an Udacity Nanodegree in the Udacity Nanodegree for Data Analysis program. The dataset in the file `fordgobike.csv` was provided by Udacity and used as-is. 

> The data was wrangled and cleaned after collection. Initially, there were 183,412 samples and 16 features in the data but this increased after cleaning and data exploratory analysis was done. 

> I used all the features of the dataset to answer the 15 questions that were the focus of the exploratory analysis and more features like trip_distance, duration_minutes were also added. A major part of the cleaning exercise was focused on converting between datatypes since there were no duplicates. There were some nulls in the dataset but I decided they should not be removed. 

## Summary of Findings

> This is a brief summary of my findings after exploring the dataset:

> 1. Market St at 10th St, San Francisco Caltrain Station 2 (Townsend St at 4th St), and Berry St at 4th St were the stations with highest starting points for bike trips. 

> 2. The top 20 stations that served as starting points for bike trips were also noticed as ending stations. Notably, Market St at 10th St and San Francisco Caltrain Station 2 (Townsend St at 4th St) were the most preferred stations by members for both start and end stations. 

> 3. It was observed that bike ID 4794 had the highest frequency of rides and was 
followed by bike ID 4814. 

> 4. It was observed that bike renters are mostly young people between 25 and 40, 
with the most frequent age been 35. It was also observed that senior citizens 
at their sixties and seventies are still bike renters.

> 5. It was observed that males are 3 times (75%) as likely as females (23%) to rent a bike at the San Francisco Bay Area. The members whose gender are unlabeled, seen as "Other", make a tiny fraction of the whole (2%).

> 6. Generally, only a small proportion of members engage in bike sharing for all 
their trips.

> 7. It was observed that members were more likely to take a bike on Thursday, followed by Tuesday. The midweek comes third. There were less rides during theweekend. The low turnout on weekends could be because schools and offices are closed during this time.

> 8. We see that the days for bike returns follows the same trend as that for bike rental days. That means most members usually return their bikes on the same 
day. 

> 9. We notice that there are two time-peaks for bike rentals. The first peak is in the morning between 7-9 am and the second peak is in the evening between 4-6 pm. This follows the morning and evening shift for workers who use bikes to commute to work.

> 10. It was observed that the trend for return hours follows that for the rent hours. 

> 11. It was observed that the bike durations that are above 60 minutes are very rare. Most of the trip durations are below 30 minutes.

> 12. To confirm the time duration above in trips, most of the distances traveled were short distances. Distances above 4 kilometers are rare while a major part of 
the distances fell within 1 kilometer.

> 13. Although it was seen that males are 3 times more than females in riding bikes, females have a higher average travel distance between stations. Therefore, 
one can conclude the female bikers rent bikes for longer distances than males 
although they rent lesser number of times.

> 14. It was observed that the highest average distances were traveled on thursdays, fridays, and tuesdays. On weekends, there was less average distance traveled by bike members.

> 15. We can see that for females, the highest mean distances traveled were recorded on thursdays and Tuesdays, while for men, it was thursdays and fridays.  

> 16. Bike sharing is a factor that limits the distance a biker can go. This is evident from the fact that male and female bikers who do not bike share have a significantly higher average distance traveled than bikers of both gender who bike share. 

> 17. Non-bike sharing bikers travel more distances generally than bike sharing bikers. Bike sharing bikers prefer going further during the weekends compared to non-bike sharing bikers who prefer weekdays. 

## Key Insights for Presentation

> It was observed that bikers are creatures of habit. They tend to use the same station when renting and returning bikes. The most notable are Market St at 10th St and San Francisco Caltrain Station 2 (Townsend St at 4th St). 

> It was also noticed that most bikers are very young people. The modal age for bikers is 35 with a majority of them falling between 25 and 40 years. But senior citizens also use bikes for commuting. From these young bikers, men form a larger proportion of the number. 

> The best days for renting and returning bikes were Thursdays, Tuesdays, and Fridays. It was observed that rented bikes are usually returned on the same day. This is because most biking distances are short distances. Most distances are within the 1 kilometers mark and rarely do you find something exceeding 4 kilometers in distance. 

> Women make up a smaller number than men but they use bikes for longer distances than men and their preferred days also varies. While women prefer using bikes on Thursdays and Tuesdays, men prefer using bikes on Thursdays and Fridays for short commutes in the morning and evenings. 
