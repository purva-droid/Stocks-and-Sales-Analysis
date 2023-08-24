# **Stocks and sales analysis**
In this project we've three sub parts:- Stock prices prediction of five multinational companies, Housing Price prediction, Future sales prediction.

## **Stock prices prediction of five Multinational Companies**

### Introduction
Predicting stock prices for different companies has been a topic of interest among both analysts and researchers for a long time. Stock prices are hard to predict because of their high volatile nature which depends on diverse political and economic factors, change of leadership, investor sentiment, and many other factors.
In this project we are predicting the stock prices of five Multinational companies namely-"Microsoft", "Tesla", "Samsung", "Reliance", "Apple". 

### Dataset
We took historical data of five different companies from Yahoo finance and just download it for the particular company.In these datasets, the Close column contains the values whose future values we want to predict.

### Modelling
First we described our dataset, plotted different graphs to see the anamoly of changing stock prices. Then we looked for the correlations between different features of our dataset. Then we fit our dataset, after splitting into test set and training set, in the model & we used Random-forest regression model for predicting the prices.
We also compared the predicted values of several companies to see which company is performing well in the market with respect to others in upcoming future.


## **Housing Price prediction**

### Introduction
Predicting house prices can help to determine the selling price of a house of a particular region and can help people to find the right time to buy a home. 

### Dataset
Dataset for this project is taken  from the California census. The data includes features such as population, median income, and median house prices for each block group in California.

### Modelling
1. First we've done modification of dataset like finding it's info using which deleted NULL values.
2. We described the dataset using histogram  plot for each numerical attribute, histogram of median income, visualized the data in terms of longitude and latitude using scatter plot, and also plotted scatter matrix to find correlations between different attributes.
3. We fit our dataset into LinearRegression model, DecisionTreeRegressor model and RandomForestRegressor model and compared the accuracy score for all the models to get the best fit model for our dataset.
4. The best model we found is DecisionTreeRegressor model.

## **Future sales prediction**

### Introduction
Predicting the future sales of a product helps a business manage the manufacturing and advertising cost of the product.

### Dataset
The dataset is about the advertising cost incurred by the business on various advertising platforms. The dataset includes features such as TV, Radio, Newspaper which contains advertising cost spent in dollars for advertising them and Sales for number of units sold.

### Modelling
1. Modified the dataset by removing NULL values.
2. Visualized the dataset by comparing scatter plot for money spent on TV, Radio and newspaper ads. We also compared graphs for  Sales vs Newspaper, Sales vs Radio.
3. Then we split tha dataset into training set and test set and performed RandomForestRegression to find the accuracy of the model.

## Summary
This is how using various machine learning models we can predict stock prices and future sales.





Contribution:- 
1. Jaya Meena
2. Antariksh Choudhary


