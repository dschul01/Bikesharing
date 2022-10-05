# Bikesharing
Utilize Tableau to provide visualizations and analysis on a bike sharing program in New York City.

## Purpose

The purpose of this project is to utilize Tableau to provide investors a view into how the CitiBike share program works in New York City in order to implement a simliar model in Des Moines, IA.  Trip data from the CitiBike program collected during Aug'19 is the source behind the visualizations for this project.  Summer data is used as it likely contains the most data due to pleasant weather enticing locals to bike as well as tourists.  The Tableau story 
provides multiple charts which answer multiple questions investors would have when taking on such a venture.  Details behind the story charts are seen in the [Results](#Results) section.

##  Results <a name="Results"></a>

The decision to initiate a bike sharing program in Des Moines, Iowa was based on analysis from the NYC CitiBike program.  The visualizations and analysis can be viewed within [my Bike Analysis Tableau story](https://public.tableau.com/app/profile/david.b.schultz/viz/Bike_Challenge_16647409152970/BikeSharinginNYC).  Screenshots are also provided below highlighting key metrics.

![Checkout%20Time%20for%20Users.png](https://github.com/dschul01/Bikesharing/blob/main/Images/Checkout%20Time%20for%20Users.png)

Majority of ride times per user are between 1 - 20 minutes with a nominal percentage of rentals lasting over 40 minutes.

![Checkout%20Time%20for%20Users%20by%20Gender.png](https://github.com/dschul01/Bikesharing/blob/main/Images/Checkout%20Time%20for%20Users%20by%20Gender.png)

Ride time behaviors are similar across all genders but we do see males utilizing the bikes significantly more than females. 

![Trips%20by%20Weekday%20per%20Hour.png](https://github.com/dschul01/Bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour.png)

Bike utilization mainly occurs between 7 - 10 a.m. and 5 - 7 p.m. on weekdays and 10 a.m. - 7 p.m. on weekends.  Wednesday's do show an anomoly in the latter part of the day which needs further research.

![Trips%20by%20Weekday%20per%20Hour%20by%20Gender.png](https://github.com/dschul01/Bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour%20by%20Gender.png)

Bike utilization by hour and gender is similiar across the genders as we see in ride times by gender.

![User%20Trips%20by%20Gender%20by%20Weekday%20by%20Usertype.png](https://github.com/dschul01/Bikesharing/blob/main/Images/User%20Trips%20by%20Gender%20by%20Weekday%20by%20Usertype.png)

The Subscriber based model shows same trends on daily utilization as previous charts but also significantly higher utilization for male 'Subscribers'.  A subscriber model should be reviewed for consideration to implement in Des Moines.

![User%20Count%20Per%20Bike.png](https://github.com/dschul01/Bikesharing/blob/main/Images/User%20Count%20Per%20Bike.png)

Most bikes are utilized less than 8 times a day.  This should be considered when forecasting repair costs and bike placement throughout a month.  Consider rotating lower utilized bikes with those used more to allow a longer bike life.

![August%20Peak%20Hours.png](https://github.com/dschul01/Bikesharing/blob/main/Images/August%20Peak%20Hours.png)

The Peak hours chart shows 2 - 5 a.m. is the window with the least usage.  This would be the recommended timeframe to repair and rotate bikes around the city. 

## Summary
The NYC CitiBike data does appear successful in Aug '19 based on the dataset provided.  Additional analysis should be done on the remaining months as well as YoY to provide a more holistic view of the program.  Other items to consider are the differences between the two cities including traffic congestion, population densities, and distances between popular destinations.  However, there are several similarities between NYC and Des Moines which can be leveraged in deciding the success of launching a bike share program in Des Moines.  These would include fairly level elevations, four-season climates, and outdoor activity options.  In order to provide more guidance with the provided dataset, I would provide visualizations on the utilization by age group and distances traveled per ride.  

Another key element necessary to provide guidance on moving forward with this program is looking at the financial data; revenue from casual users v subscribers, bike costs, overhead, payroll, insurance, fees, etc.  This data is critical before making a decision to move forward with the Des Moines bike share program.