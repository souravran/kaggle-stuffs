### Walmart Sales Predictive Analysis

_KaggleFun_ to predict and analize the sales for each department using historical markdown data from the Walmart stores. 


#### Motivation

This work answers the following questions:
1. Which stores have maximum  and sales?
2. Which store has maximum standard deviation i.e., the sales vary a lot?. Also, find out the coefficient of mean to standard deviation.
3. Which store/s has good quarterly growth rate in Q3’2012?
4. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together.
5. Provide a monthly and semester view of sales in units and give insights.
6. Build prediction to forecast demand.


#### Installation <a name="installation"></a>

- Python versions 3.*.
- Python Libraries: sklearn, Pandas, numpy, seaborn, matplotlib, datetime.


#### Data

There are sales data available for 45 stores of Walmart in [Kaggle](https://www.kaggle.com/aditya6196/retail-analysis-with-walmart-data). This is the data that covers sales from 2010-02-05 to 2012-11-01. 


#### Implementation 
This work features an exploratory analysis and use of predictive models [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) and [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) for sales forcasting.

