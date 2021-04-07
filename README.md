# Citi Bike NYC

In this repository we have created a Tableau story based on Citi Bike bicycle rental data in New York City. The aim is to persuade investors to invest in a pilot location in Des Moines Iowa. The story can be seen at this link: 
![Citi Bike Challenge](
https://public.tableau.com/profile/thomas.k.stover#!/vizhome/CitiBikeChallenge_16177490156440/CitiBikeAnalysis?publish=yes)

## Results

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Checkout_Times_for_Users.png)

The first visual used in the Tableau story is the “Checkout Time for Users” graph. The peak rental time is 5 minutes which has 146,752 rentals. As time grows larger, rentals drop very quickly. There is a filter to the right of the graph which allows users to filter by hour.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Checkout_Times_for_Users_Gender.png)

The next visual is like the previous except it is based on gender. Males make up the majority of users and have a peak at 5 minutes with 108,087 rentals. Females peak with a slightly longer trip duration at 6 minutes with 34,151 rentals. Unknown genders do not have a distinct peak like males and females but the maximum amount of rentals for them does occur at a 11 minute trip duration with 7,389 rentals.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/August_Peak_Hours.png)

“Peak Hours for August 2019” was then graphed to show the peak rental hours throughout a typical day in August 2019. The graph shows two peaks, one in the morning (8am) and one in the evening (5pm) with respective rentals of 170,730 and 224,566.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Trips_by_Weekday_per_Hour.png)

Here, we see a heatmap of trips per hour based on day of the week. Red indicates more rentals whereas gold indicates less. We can see the busiest hours are 8am Monday through Friday and 5-6pm Monday through Friday.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Trips_by_Weekday_per_Hour_Gender.png)

This heatmap is much like the previous but instead is broken up by gender. As before, we see that males tend to rent the bicycles much more frequently than females.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Trips_per_Weekday_Gender_User.png)

This heatmap takes things one step further by differentiating between walkup customers and subscribers. As you can see, most customers are subscribers.

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Top_Starting_Locations.png)

Here we see a map of the busiest starting locations in the city. The larger and darker the dot, the busier the location. You can see that as you get further outside the city, the more sparse the locations become as well as the less business these locations bring in. 

![]( https://github.com/thomasstvr/bikesharing/blob/master/Resources/Top_Ending_Locations.png)

This map indicates top ending locations in the city. The same trend continues, as with top starting locations. You can also see that the very same locations that are the busiest starting locations are also the busiest ending locations. 

## Summary 

In summary, most of Citi Bike’s customers in NYC are male subscribers who tend to use the bicycles based around a regular (8-5 M-F) work schedule. The busiest starting locations are also the busiest ending locations and most trips are relatively short. 

A couple visualizations that would be interesting to see are a map of start and end locations that have the longest trip duration. A visualization which compares trip duration against user type would also be interesting.

New York is an incredibly unique city that is densely populated and has a great public transit system. Car ownership is rare for those living in the city and most walk to their respective public transit stations. These conditions make the city ideal for a subscription-based bicycle rental service. These same conditions are not found in Des Moines, Iowa which makes the city less than ideal for a pilot Citi Bike location. It goes against the objective of this project, but I personally would advise against launching a pilot in Des Moines.


