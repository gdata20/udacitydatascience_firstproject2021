# udacitydatascience_firstproject2021


# Libraries used: 
numpy 
pandas
matplotlib.pyplot
sklearn.linear_model
sklearn.model_selection
sklearn.metrics
sklearn.ensemble RandomForestRegressor
seaborn



# Motivation for the project:
I am curious on what factors affect the price of the accomodation the most for airbnb accomodation. 
Also, I would like to know more about:
neighbourhood numbers,
accommodatation in each neighbourhood,
average price in each neighbourhood, max/min price,
room type, property type,
average price of accomodation,
reviews/ ratings




# The files in the repository

seattle_listing.csv
boston_listing.csv

The data include all the current listing on Airbnb.
Each row in the Boston and Seattle dataset represents a listing on Airbnb 

The data is downloaded from http://insideairbnb.com/get-the-data.html in July 2021




# Results of the analysis
**Boston**

For Boston dataset, the RMSE from linear regression is 57.4 and RMSE from random forest regressor is 52.32 which is slightly better. The range of the price (y values) is 500, so RMSE of 5x is acceptable but further improvement can be done e.g parameter optimization or feature selection.

The most important variables determining the price is the room type. If the room type is private, then the price is likely to be higher

**Seattle**

For the seattle data set, the RMSE from linear regression is super large and RMSE from random forest regressor is 53.69 which the data is fitted much better. Seems that the relationship between most of the variables and price is not linear.

he most important variables determining the price is the number of bedrooms. 
