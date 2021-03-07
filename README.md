# PyBer_Analysis
**Programming software used: Anaconda, Jupyter Notebook; Language: Python -- Matplotlib & Pandas**
**Code for analysis:**

## Purpose of Analysis
PyBer; a ride-sharing app company, wants all of the rideshare data from January to early May of 2019 to be analyzed and to have a visualization of the results. The analysis will showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of the total fares, riders, and drivers by type of city. This will help PyBer improve access to ride sharing services and determine the affordability for underserved neighborhoods.

To do this analysis, I created a summary DataFrame of the ride-sharing data by city type and created a multiple-line graph that shows the total weekly fares foreach city type.

## Analysis Results
**Summary of ride-sharing data by city type**
(image)
**Graph representing total weekly fares for each city type**
(image)

## Analysis Summary
Looking at the data, there is over 10 times more ride activity in urban cities than rural cities. This makes sense due to urban cities naturally having a higher population density than rural areas. It is also observed that fare rides are cheaper in urban cities than rural cities. Suburban cities are in the between when it comes to ride/driver count and fare price. Since there tends to be a significant difference between city size and population size among the types of cities, we need to take these variables into consideration when deciding ways to reduce fare price to be more affordable for underserved neighborhoods.  

**Proposed steps to determin affordability for ride services:**
- Analyze the duration of individual rides and their distances. 
  - This will show if time of ride or distance of ride is determining prices for fares. 
- If distance is the reason -> change our price methods by making time as the price factor. 
- If there is no correlation among those two variables with fare price -> look at the amount of drivers per area. 
- If drivers are the factor to fare price -> promote more driver positions in underserved areas to increase rides to then create lower prices. 
  - Drivers that are not getting enough rides leads to a decrease in their pay, which can then lead to a increase in fare price.  

**Other variables to take into consideration:**
- Geography of terrain
- Traffic density 
- Wear-and-tear of vehicle 
- Price per gallon








