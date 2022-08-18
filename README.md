# PyBer_Analysis

## Overview:

The purpose of the project was to analyze data for a ridesharing company called PyBer. Datasets containing ride and city data were used to calculate such metrics such total rides, total drivers, total fares, average fare per ride, and average fare per driver for each of the respective city types (Rural, Suburban, and Urban). The data frame from the analysis was then used to create a multiple-line graph that illustrates the total weekly fares for each city type for the period of January 1, 2019, to April 29, 2019. 

## Results:

### PyBer Summary DataFrame

After merging two data sets and using the GroupBy function, the Average Fare per Ride and Average Fare per Driver were calculated. This resulted in the summary DataFrame below that shows the discrepancies between the three city types.

![image](https://user-images.githubusercontent.com/109227896/185276444-eee7f967-21b3-40a7-b998-fe160990652c.png)

It’s easy to note the greater volume of rides and fare revenue generated in the Urban city category. Naturally, there would be a greater demand for rides in an urban environment and with more drivers available that demand can be met. However, rural drivers comprise about 7.7% of the driver workforce compared to Urban yet generate 40 percent revenue per ride. One must believe this is due to longer rides in rural areas compared to likely shorter rides in an urban setting. 

### Total Fare by City Type

A line chart below was created as part of the analysis to help visualize the Total Fares from January 1, 2019, to April 29, 2019, for each of the three city types.

![image](https://user-images.githubusercontent.com/109227896/185276561-5f210100-737e-4521-a4de-99bb3ae622ae.png)

During the period analyzed we can quickly see the Urban city type had the highest total fares for all the weeks while the rural areas had the lowest. It is also apparent that there was a peak in demand during about the third week in February with a significant drop in demand for all three city types during the end of March into the start of April. 

## Summary:

   As previously mentioned, the PyBer Summary DataFrame results are likely due to how compact/dense the Urban city type is. So naturally these rides would be shorter in distance and therefore collect a lower fare per ride when compared to Suburban and (especially) Rural rides that are more spread out and thus collect a higher per ride fare. It would be interesting if PyBer included some data pertaining to per ride mileage for analysis.   
  
  Because there are approximately 50% more total drivers than total rides in the Urban city category, the Urban drivers may not have enough work to adequately support themselves. PyBer may want to consider an investment in advertising toward the Urban city type to increase the total rides. As it stands now, PyBer may be at risk of losing Urban drivers or may need to consider reducing that particular workforce. 
  
  Rural cities account for the least volume of rides and the least total fare revenue amongst the city types, however Rural average fare per ride is the highest. Perhaps marketing PyBer’s service in this market could be beneficial in increasing ridership and thus revenue. 
