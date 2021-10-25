# predicting-happiest-countries
Using a dataset of the World's Happiness Report 2019, which summarised world happiness levels from 2005 to 2018, we aimed to predict the world's happiest countries in 2019.
(Update: Our prediction for the World's Happiest Country of 2019 was accurate)

# Cleaning and Preparing the Data
To begin with, we isolated the top 5 factors affecting the highest life ladder scores (which represents the happiest countries).
We dropped the remaining columns.
We isolated the top 10 countries from each year and compiled them into one dataframe.
After this, we cleaned the dataset from missing values & mistaken values.
We filled in missing values with the mean value, and removed the insignificant indexes.

# Prediction
We used the Time Series Method and Autoregressive Model, to effectively capture the trends.
We plotted each factor alongside the years and computed the lag in the graph, to see which has the best correlation. We then run an algorithm using the lag to predict the next factor value.

Lastly, we used the Random Forest Regression to combine the factors and predict the happiness level of these countries.

