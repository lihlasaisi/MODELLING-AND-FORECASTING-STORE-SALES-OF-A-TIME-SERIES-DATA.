# MODELLING-AND-FORECASTING-STORE-SALES-OF-A-TIME-SERIES-DATA.

This is a time-series forecasting project. In this project we'll train a model that accurately predicts the sales of items in different stores. We'll use store sales data from large Ecuadorian-based grocery retailer.

I used Python and Jupyter for this project.

# Data
## train.csv
The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
store_nbr identifies the store at which the products are sold.
family identifies the type of product sold.
sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

## test.csv
The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
The dates in the test data are for the 15 days after the last date in the training data.

## transaction.csv
Contains date, store_nbr and transaction made on that specific date.

## sample_submission.csv
A sample submission file in the correct format.

## stores.csv
Store metadata, including city, state, type, and cluster.
cluster is a grouping of similar stores.

## oil.csv
Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)

## holidays_events.csv
Holidays and Events, with metadata
Additional holidays are days added a regular calendar holiday, for example, as typically happens around Christmas (making Christmas Eve a holiday).

## Additional Notes
Wages in the public sector are paid every two weeks on the 15th and on the last day of the month. Supermarket sales could be affected by this.
A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.

# Hypothesis

H0: Stores with products onpromotion make more sales than stores without onpromotion products.


Thank you.

Link to article on Medium: [https://medium.com/@lihla.saisi/indian-startup-eco-system-analysis-2018-2021-da13ad670108](https://medium.com/@lihla.saisi/modelling-and-forecasting-store-sales-of-a-time-series-data-c16e86519318)
