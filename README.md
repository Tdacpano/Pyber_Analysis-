# Pyber_Analysis-
Module 5 
# Overview of the analysis
   In this analysis, we are analyzed all the rideshare data from January to early May of 2019 for the ride-sharing app, Pyber. The analysis consists of a summary DataFrame of the ride-sharing data by city type. Followed by a multiple line graph showing the total weekly fares for each city type. 

# Results
  To begin the analysis we needed to gather the total amount of fares, total rides, and total drivers per each city type. We then took this data and found the average fare per each ride and driver for each city. This allowed us to create a summary DataFrame to outline how Pyber did within each city. 
  
<img width="535" alt="Screen Shot 2022-12-16 at 10 17 30 AM" src="https://user-images.githubusercontent.com/117120227/208163195-aecd3453-354d-422c-b9f5-27b24e78124f.png">

  Looking at the chart, it indicates that Pyber has more total rides, drivers, and fares in Urban cities then both Rural and Suburban. However, Urban cities have the least average fare among both rides and drivers. Rural cities tend to have a highest average followed by Suburban. 
  To futher our analysis we created another dataframe by grouping the data by date and city type, showing the sum of all fares in each city. This allowed us to create a pivot table showing the total fares for each city type by the date. 
  
  <img width="263" alt="Screen Shot 2022-12-16 at 10 37 38 AM" src="https://user-images.githubusercontent.com/117120227/208166260-20b15ca0-55d3-4c7b-849c-dd22277c22e2.png">
  
  However, because the variable 'date' has the hourly time included a lot of cities do not have available data for every time. In order to make the table more efficient we used the resample function to advance the dataframe to show total fares for each city type by each week. 
  
  <img width="263" alt="Screen Shot 2022-12-16 at 10 39 54 AM" src="https://user-images.githubusercontent.com/117120227/208166640-f9d6be5b-36a8-42b4-a5c7-1165f03d65ef.png">
 
 This now allowed us to create the multiple line graph showing the total weekly fares for each city type. 
 <img width="892" alt="Screen Shot 2022-12-16 at 10 42 56 AM" src="https://user-images.githubusercontent.com/117120227/208167161-0053d62e-d62b-4112-9e6d-86c02fdc8b46.png">


# Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
