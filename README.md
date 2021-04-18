# PyBer Analysis Report

## Project Overview and Objective
The objective of this analysis project is to analyze the Pyber ride-sharing company to identify opportunities to optimize access to their ride-sharing services for various types of cities. Pyber provides services to three types of cities:  urban, suburban, and rural neigbhorhoods. The project scope involved performing statistical analysis of several large files containing city and ridership data and creating several types of visualizations to create a compelling story about the data and provide recommendations.

The analysis examined the relationship of cities and number of drivers and riders, as well as revenue per driver and rides by city type, the mean of total fares, drivers and riders by type of city. The combined data analysis and visualization can be utilized by the Pyber CEO to identify oppotunities and strategies to improve access to ride sharing services and determine ride fare afforability for underserved neighborhoods.

This project used python script, Pandas library, Jupyter Notebook,  NumPy and SciPy to perform statistical analysis, and matplotlib to create a variety of charts to visualize the data.


# Results
The table of ride-hailing data by city type shown below summarizes the average fare per ride and average fare per driver by city type.

![image](https://user-images.githubusercontent.com/80140082/115128328-e1a9ad80-9f91-11eb-87d0-fe078c97291f.png)

The chart shown below compares the total fares by city types. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/80140082/115128472-d2772f80-9f92-11eb-905c-8bba061dbcb1.png)


# Summary
Overall, Urban cities have a higher number of rides and drivers. However, the average fare per ride and average fare per driver are lower than the suburban and rural city types. Rural cities have fewer rides and drivers in comparison to urban and suburban cities. However, they generate higher average fare per ride and average fare per driver over rural and suburban city types. 

**Summary Statistics**
* Rural cities account for 5% of total rides, 3% of total drivers and 7% of total fares.
* Suburban cities account for 26% of total rides, 16% of total drivers and 30% of total fares.
* Urban cities account for 68% of total rides, 81% of total drivers and 63% of total fares.

Based on these statistics, urban cities are under-served in the number of drivers in comparison to suburban and urban cities. There might be an opportunity to increase driver coverage in to rural cities and suburban cities. Given that urban and suburban rides earn higher average fare per ride, increasing the number of drivers in those neighborhoods could also increase the total rides and total fares, and ultimately, revenue.

This analysis did not examine and compare any data about travel distances in the rides by city type. One hypotheisis for rural cities having higher average fares per ride and per driver might be correlated to travel distance. Typically, urban trips are more frequent due to population density and shorter in travel distance which results in more rides but lower average fare per ride. However, additional inspection and data gathering would be needed to validate the hypothesis.

The dataset used this analysis was limited to cities in the three in-scope city types (urban, suburban, rural), the number of drivers and riders, and fare information by city type. Therefore, the analysis did not explore other dimensions and factors, such as rider preferences, travel distance, traffic and weather conditions that might impact the number of rides, etc.


# Recommendations

1. Expand the data and perform additional analyis on other factors such as traffic and weather conditions, time of day, travel distance, availability of drivers    by city types etc. to further enrich the analysis and add more dimensionality to determine the relationships and impacts.

2. In conjuntion with the above additional analysis, conduct small pilots or experiments to test some hypotheses on factors that might affect ridership. For         example:
        * Increasing the number drivers in the rural and suburban areas to determine if increasing the number of available drivers would improve the total 
          number of rides and fares. 
        * Adjusting the frequency or availability of drivers in rural and suburban ciies to determine if it will affect the number of rides. 
     

