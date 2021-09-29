# Overview
## These analyses are looking into the Citibike bike sharing program data from August 2019. Data vizualizations in Tableau will be genereated to convince investors that a bike-sharing program in Des Moines is a solid business proposal. The analyses will look at the data broken down by gender, customer type, day of the week, checkout times and locations.

# Results

<br/>

### **Tableau Story board**

<br/>

[Link to Tableau Public Dashboard] (https://public.tableau.com/views/NYCBikeChallenge14/NYCCitibikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

#### Each visualization has a summary beneath in the storyboard as well

<br/>


## Checkout Times for Users
#### Most of the trip durations are less than an hour. The peak duration is only 5 minutes. Most trips are very short in duration between 4 and 30 minutes.
<br/>

![Check out times](/Resources/Checkout_times_for_users.png) 

<br/>

## Checkout Times by Gender
#### As seen in the previous story point, most trips are less than 3 minutes. Male riders during the peak times check out almost three time as as many bikes. The difference between genders gets much smaller with longer trip durations.
<br/>

![Check out times gender](/Resources/Checkout_times_gender.png) 

<br/>

## Trips by Weekday for Each Hour
#### The busiest times are 5-7 pm monday, Tuesdays and Thursdays. The morning hours of 8-9 have higher bike checkouts as well. The early morning hours have very few bike checkout for all days of the week. There is also a little higher bike checkouts on the weekends during the day.
<br/>

![Trips weekday/hour](/Resources/Trips_weekday_hour.png) 

<br/>

## Trips by Gender (Weekday per Hour)
#### The same pattern of trips is seen when broken down by gender but males riders checkout more bikes than female riders. The busiest times are 5-7 pm monday, Tuesdays and Thursdays. The morning hours of 8-9 have higher bike checkouts as well. The early morning hours have very few bike checkout for all days of the week. There is also a little higher bike checkouts on the weekends during the day.
<br/>

![Trips weekday/hour/gender](/Resources/Trips_weekday_hour_gender.png) 

<br/>

## Trips by Gender (Weekday per Hour)
#### There are many more bike checkouts for subscribers, especially male subscribers
<br/>

![Trips weekday/gender](/Resources/User_trips_gender_weekday.png) 

<br/>

## Overall Citibike data
### Here is the overall breakdown of Citibike customers for the month of August 2019. Above are the Total number of bikes checked out as well as the customers by subscription type and gender. The vast majority of customers are Subscribers (81.1%) and Male (65.3%).
<br/>

![Overall data](/Resources/Overall.png) 

<br/>

## Citibike start location
#### The two maps show where the bikes were checked out. The size of the circles are proportional to the number of bikes. The greatest number of bikes are checked out in the middle of Manhattan where most of the tourists would be (map on the left). The map on the right shows the Bronx where very few bike are checked out.
<br/>

![Location data](/Resources/Locations.png) 

<br/>

# Summary

<br/>

####  These analyses and visualizations are to be used to determine the feasability of a bike sharing business in Des Moines, IA based on data from New York City CitiBike data for August 2019. NYC is 302 square miles and Des Moines is 91 square miles (Only 3 time larger). The population of NYC is 8,420,000 while Des Moines is 699,292 (120 times greater). Des Moines bike sharing business would be on a much smaller scale and easier to implement. Most of the bike stations should be in the center of Des Moines as they are in NYC in Manhattan (highest tourest area in NYC). Most of the biker renters in NYC are sunscribers so the Des Moines business should start with promotional material to attract subscribers. There are numerous colleges in Des Moines for a good customer base. For instance, bike stations near Drake University would be ideal for students to explote the city. Most of the tripn in NYC are short in duration (< 1 hour). Des Moines also has river parks, museums and botanical gardens that would lend themselves to bike riders. The Iowa state capital is in Des Moines which may attract government employees after work to ride to nearby attractions. The heaviest usage in NYC was for the hours between 5-7 pm. 

#### Two additional analyses of the NYC data that could be of use are the average distance between start and stop location by user type and that same distance on a map. These additional analyses could give more insight as to how far riders are travelling with their bikes. To do this, I created a new calculated variable called "Distance between stops" the gives the distance in miles from where a rider picked up a bike and where it was dropped off. 

#### **Both of these vizzes are added to the end of the Tableau story published to Tableau Public.**

<br/>

![Calculated fields](/Resources/field.png) 

<br/>

## Additional Viz #1
#### The chart below shows the average distance by user type. It look like Subscribers are not taking the bikes as far as the Customers. THis may indicate more pleasure riding for non-subscribers.  

<br/>

![Calculated fields](/Resources/distanceAverage.png) 

<br/>

## Additional Viz #2
#### The chart below shows the average distance by user type and length of time the bike was checked out. The Trip duration filter can choose multiple lenths to look by hours. The vast majority of the trips are less than an hour sot the map is a mess of lines. This visualization is getting at how far away riders dropped off their bikes after a long day. Thios could help inform the Des Moines business if stations needed to be place fara aprt from each other. The viz below has green dots for start location and red dots for end location. As seen below, ever trip lasting 21+ hours are not dropping bikes off too far from where they checked them out. This is encouraging for Des Moines to know stations don't have to be placed too far out within the city.

<br/>

![Calculated fields](/Resources/distance.png) 

<br/>

