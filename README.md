# PyBer Analysis Report

## Project Overview and Objective
The objective of this analysis project is to analyze the Pyber ride-hailing company to identify opportunities to optimize access to their ride-hailing services for various types of cities. Pyber provides services to three types of cities:  urban, suburban, and rural neigbhorhoods. The project scope involved performing statistical analysis of several large files containing city and ridership data and creating several types of visualizations to create a compelling story about the data and provide recommendations.

The analysis examined the relationship of cities and number of drivers and riders, as well as revenue per driver and rides by city type, the mean and median total fares, drivers and riders by type of city. The combined data analysis and visualization can be utilized by the Pyber CEO to identify oppotunities and strategies to improve access to ride sharing services and determine ride fare afforability for underserved neighborhoods.

This project used python script, Pandas library, Jupyter Notebook,  NumPy and SciPy to perform statistical analysis, and matplotlib to create a variety of charts to visualize the data.


# Results
The table of ride sharing data by city type shown below summarizes the average fare per ride and average fare by driver by city type.

![image](https://user-images.githubusercontent.com/80140082/115128328-e1a9ad80-9f91-11eb-87d0-fe078c97291f.png)

The chart shown below compares the total fares by city types. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/80140082/115128472-d2772f80-9f92-11eb-905c-8bba061dbcb1.png)


# Summary
Overall, Urban cities have a higher number of rides and drivers. However, the average fare per ride and average fare per driver are lower than the suburban and rural city types. Rural cities have fewer rides and drivers in comparison to urban and suburban cities. However, they generate higher average fare per ride and average fare per driver over rural and suburban city types. 

This analysis did not examine and compare any data about the distances in the rides by city type. One hypotheisis for the rural cities having higher average fares per ride and per driver is the linkage to travel link. The result could be correlated to the travel distance per ride for rural cities relative to urban rides. Further analysis would be needed to validate this observation.

# Recommendations

1. Perform additional analyis on the distance covered per ride per city type
 give another dimension to the analysis and clarify even more the differences between city types.

2. Additional Analysis 2
Description of Approach. Analysing the weather conditions and the time during the day (day time fare? night time fare?) per ride might give even more dimensions to the analysis and clarify in detail the differences between city types.

