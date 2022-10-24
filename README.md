# Turkish Restaurant Revenue Estimation 💰

## **Project Idea 🔎**
------

Project for building machine learning model for  predication of Turkish restaurant revenue based on some features. I'm applying some of data analysis and data visualization techniques in the data for understanding the domain more and more . After data understanding then perform some of data preprocessing before modelling and bulding machine learning model to estimate How many will be the Revenue ? .


## **About Dataset ▶**
-----

TFI has provided a dataset with 137 restaurants in the training set, and a test set of 100000 restaurants. The data columns include the open date, location, city type, and three categories of obfuscated data: Demographic data, Real estate data, and Commercial data. The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. 

Dataset is splited two csv files (train.csv - test.csv).

**Dataset link :** https://www.kaggle.com/competitions/restaurant-revenue-prediction/data


## **Data Columns ⚡**
-------

1. Id : Restaurant id. 
2. Open Date : opening date for a restaurant
2. City : City that the restaurant is in. Note that there are unicode in the names. 
3. City Group: Type of the city. Big cities, or Other. 
4. Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile
5. P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.
6. Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values. 


## **Final Conclusion ❤**
-------

* Most of Resturaunts're  Food Court  With Percentage of 57% and Inline  With Percentage of 40.5% 

* Opening Restaurant did not affect by season as numbers of Opening Restaurants in each season is close to each other

* Most restaurants has been opened in the Autumn

* Number of Restaurants in Big Cities ['İstanbul','Ankara' ,'İzmir'] Contribute 49.3% of All Restaurant Number

* Resturaunt Revenue in big cities ['İstanbul' 'Ankara' 'İzmir'] is more than other cities

*  Resturaunt Revenue in big cities ['İstanbul','Ankara' ,'İzmir'] is more than other cities 

*   Restaurant Revenue Average in big cities = 4983480.077

*  Restaurant Revenue Average in other cities = 3752924.102
 
* 2013 is the year in which the largest number of restaurants were opened

* 2002 is the year in which the smallest number of restaurants were opened

* 2000 is the year in which the highest average of revenue restaurants

* Top 5 Cities in Resturaunt Revenue 're İstanbul, İzmir, Bursa, Kayseri and Ankara

* Restaurant age does not significantly affect revenue as they 'are weakly correlated

