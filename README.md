# Store Sales - Time Series Forecasting
This repository provides data to solve Kaggle challenge "Store Sales - Time Series Forecasting" by using plots and scatter plots to view the data and make a prediction sale for the thousands of products being sold.

# Overview
The task of the challenge is to build a model that more accurately predicts the unit sales for thousands of items sold at different stores. The approach in this repository is training dataset of dates, store, and item information, promotions, and unit sales to make the prediction. This problem forumulates Data Visualization and Regression Task, we compared all stores to its category.

# Data
* train.csv, test.csv, stores.csv, oil.csv, holiday_events.csv
* 124.76 MB

I started by downloading all my data files using pandas. To better visualize my data and make connections and comparisons, I merged my train data and oil data together by specifying I was looking for similiar dates they had (naming it merged_file). After, I made a list of several products(family) such as automotive, boooks, and poultry to speficy on specific products. I built a scatterplot for automotives and books, plotted the data oil file, plotted data for holiday events, and plotted data for both oil and train data.
By looking at these plots, I could tell that the oil data and train data had a lot in common because their dates were the same and correlated as I merged them. 

# Future Work
Next thing I will do is pick out spefic stores/products
