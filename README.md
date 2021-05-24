# PyBer_Analysis

### Analysis Overview
Our friends at PyBer, a Python-based ride sharing company, operate a pay-for-ride service across urban, suburban, and rural cities. As a result, they provide many rides at varying fares. The decision makers at Pyber are looking for some compelling insights and supporting visualizations to help them with decision making for how PyBer should adjust their approach in the different city types in which they operate. 

This analysis uses Python and Pandas in Jupyter Notebook with graph visuals creating using Matplotlib.

### Results
#### Rides and Fares
PyBer does considerably more business in an urban city were total fares amounts to close to $40k compared to just under $20k in suburbs and just over $4.3k in rural cities. The quantity of rides is also 13 times as much in an urban environment compared to rural and 2.6 times suburban ride totals. This is to be expected where more drivers may provide more opportunities to generate fares revenue for short trips, likely with minimal time for drivers without an active fare in their vehicle. Meanwhile, rural areas may have longer distances to cover for fares and lower overall demand, leading to fewer total rides and fewer drivers. Our data did not assess ride distances, consumer wait times, ride duration, nor driver wages/ride profitability.

#### Drivers
When it comes to the drivers' perspectives, rural drivers earn almost 2.4 times per ride compared to what their suburban counterparts earn per ride and about 3.4 times more than urban drivers, who may face much more competition with other drivers and alternative forms of transportation. There are over 2400 drivers in urban cities while only 490 in suburban and just 78 in rural areas. See Figure 1. for a breakdown of average fares per ride and average fares per driver. 

##### Figure 1. Table of PyBer Fares by City Type.
![Image of PyBer DataFrame for Fares by City Type](https://github.com/ozloty06/PyBer_Analysis/blob/main/Analysis/Pyber_fare_by_city_DF.png)

Without ride duration or driver wage information, it's unclear if drivers are earning reasonable wages and withough profitability data and ride demand data, it's unclear if PyBer has enough or too many drivers in any city type.

#### Q1 Assessment
In Q1 of 2019, we begin to see some fare trends across all city types. For example, both urban and suburan fares are lowest in early January before climbing higher over the month for all city types. There's a peak for total fares in late February with higher volitility in fares for all city types, most especially for urban cities through the whole of March. Both urban and suburban fares are at their highest point for the quarter in late Febrary. For both urban and rural cities, there's a sharp increase in fares in early april while in suburban areas, that increase begins slightly later in the month. It's worth noting that the rural increase quickly tapers off.

From the information provided, it's difficult to assess the nature of the price fluctuations and would require additional effort, perhaps some qualitative analysis, to understand what's driving the fares, particularly during times like early January when demand for rides may have dropped off, late January and February to understand what's driving increased fares, and late February/March to better understand the increased fare volitility. Comparing results year over year and across other quarters also would be helpful to understanding macro trends impacting PyBer. See Figure 2 for Fares by City Type for Q1 2019.

##### Figure 2. Line Graph of PyBer Fares by City Type.
![Image of PyBer Line Plot for Fares by City Type](https://github.com/ozloty06/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

### Summary
Based on the results of our analysis, PyBer can address disparities among city types by:
- Evaluating ride duration and driver wages to analyze profitability in each city type.
- Evaluating ride duration and average fare by city type to ensure rides are appropriately priced.
- Evaluating total fare volatility, ride demand and macro trends across city types to ensure fares and driver availability appropriately meet fluctuating demand.
