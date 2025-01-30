# Background
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data.  Multiple linear regression analysis was performed on the data.

# Preprocessing
The first thing to do is to do a data preprocessing. The first step is importing the data. Next, checking the data if it has missing values on it. Because the data has missing values, the next step is dropping the missing values. After that, choose longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, and target as important variables with the first 9 variables as independent variables, and target as dependent variables.

# Regression
After data preprocessing, continue to the regression part. First, calculate the correlations between longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, and median_house_value with target. Based on the correlation which are calculated, median_house_value has biggest correlations among the other independent variables which is 1. Next, divide the variables into training and testing data. After that, create a regression model with the training data. 
