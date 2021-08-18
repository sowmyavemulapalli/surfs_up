# Surf_Up Analysis

## Overview Of This Project
    - This project contains the hawaii weather data through out the year.
### Purpose 
      - The Purpose of this project is to analyze the hawaii temperature in the months of June and december to open the surfing shop business
      
##  Surf_Up Result
      The Results of this project are  the statistics of June and December temperatures. From the below statistics screen shot we can say.
         - The average temperatures in the months of June and December are 74.94 and 71.04.It has only 3 degrees difference.
         - The Minimum temperatures in the month of June and December are 64.0 and 56.0. It has 8 degree difference.
         - The Maximum temperatures in the month of June and December are 85.0 and 83.0. It has 2 degree difference only.
   ![image](https://user-images.githubusercontent.com/86328230/129934025-3e4092f7-181f-4227-b296-99133326ddaa.png)
   ![image](https://user-images.githubusercontent.com/86328230/129934148-6d2ab98c-8aec-4d1f-91fe-a13dc9771826.png)


# Surf_up Summary
      The Summary of this project is to analyze the weather data of hawaii in the months of June and December to open the surfing business.we can perform two more queries to analyze the more weather conditions. one is to calculate the temperatures in june and december months and also in specific year. for example 2017. 
       results_june = session.query(Measurement.tobs).\
       filter(extract('year',Measurement.date) ==2017).filter(extract('month',Measurement.date )== 6).
       And the other one is for december month.
       results_december = session.query(Measurement.tobs).\
       filter(extract('year',Measurement.date) ==2017).filter(extract('month',Measurement.date )== 12).


