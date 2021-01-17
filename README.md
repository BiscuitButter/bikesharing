# NYC Citibike Analysis

[Tableau Story](https://public.tableau.com/profile/adam.womer#!/vizhome/Module14_Challenge_16108275371180/NYCCitibikeAnalysis?publish=yes "link to dashboard")

### Overview
The purpose of this analysis is to determine best practices for bike sharing utilizing NYC Citibike data. 

### Results
#### Tableau Viz
1. **Checkout Times for Users.** The average duration that bikes are checked out.
2. **Checkout Times by Gender.** The average duration that bikes are checked out based on the rider's gender.
3. **Trips by Weekday per Hour.** A heatmap showing peak checkout times by weekday per hour.
4. **Trips by Gender (Weekday per Hour).** A heatmap showing peak checkout times by weekday per hour based on the rider's gender.
5. **User Trips by Gender by Weekday.** A heatmap showing ridership by Usertype, Gender, and Weekday.
6. **Peak Hours.** A bargraph showing peak checkout times.
7. **Starting Location Activity.** A geographical map showing starting location activity.
8. **Ending Location Activity.** A geographical map showing ending location activity.


### Summary
#### Analysis Note
Based on the visualizations within the challenge instructions, the datetime unit parameter for tripduration needs to be set to minutes to replicate the results in the module. However, based on the results of the analysis, I feel that it is supposed to be set to seconds. The hottest start and stop locations are at West 39th St Terminal, Grand Central Terminal, Union Square, and West St & Chambers St during the hours of 8am and 5pm. The largest rider demographic are males with a Citibike subscription. When all these pieces of information are combined, you have male commuters that take mass transit into Manhattan and then take a Citibike for the last mile of their journey. This last leg on a bike should only take about 5 minutes. Ergo, I am inclined to believe that the tripduration is indeed in seconds and not minutes.
