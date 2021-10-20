# PyBer Analysis: Analysis of PyBer ride share company

---
## Overview:
---  
Using Python and Pandas to create a data frame that group fare data by city type, (Urban, Suburban, Rural).  

## Results: 
---
Using PyBer ride and city data, I imported each csv file to create one merged Pandas data frame to complete the analysis.  
I then grouped the data by city type before calculating the average fare.  There are more drivers in the Urban city types 
which can do more rides per day; however the rides are shorter and the average fare per driver is only $16.57.  There are 
less drivers within the Rural areas, however, they drives are further in length so the average fare per driver is 
higher, $55.49  

![Average Fare](/analysis/PyBer_avg_fare.PNG)

Extrapolating the PyBer data into weekly summary's and using data for the months of January - April, you can see the difference in 
average fare for the given timeframe.  Urban drivers have more rides per week which results in higher average fare per week, with 
approximately 10 times higher average fare per week than Rural drivers.   

![PyBer Fare Summary](/analysis/Pyber_fare_summary.png)

## Summary: 
---
With the average fare per driver being lower in the Urban areas than Rural, consider moving some of the Urban drivers to the 
Rural areas.  This would increase the number of drivers in the area potentially increasing the number of rides. 

The data did not consider customer satisfaction regarding wait time in any of the city types or availability of drivers in 
the area.  Capturing customer input and wait times needs to be analyzed before considering further recommendations.
