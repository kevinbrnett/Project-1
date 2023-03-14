# Grocery Store Sales Predictions

## Analyzing Various Factors to Predict Future Sales of Grocery Stores

Kevin Barnett

**Business Problem**:

Help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
 
## Data Source:

 Original Dataset: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
 
 In this dataset there are 12 columns and 8523 rows.
 
 ## Data Dictionary:
 
 ![image](https://user-images.githubusercontent.com/103015330/224993248-db3d7178-c2fb-4065-bf12-1a7bd38e2846.png)

## To Prepare the dataset, it was cleaned, and the following processes were performed:

## Exploratory Data Analysis:

**Item Sales Count Histogram**

![image](https://user-images.githubusercontent.com/103015330/224999173-f4d3e32e-d074-4990-93f1-61f9207edf37.png)

> We can see that the data for item sales and visibility are both skewed to the right. Both of these features also have a significant amount of outliers.

## Explanatory Data Analysis:

![image](https://user-images.githubusercontent.com/103015330/224999532-066730d9-9c18-4fe0-9327-d36370d5f711.png)

>We can see that medium size outlets account for a majority of sales

## Models Evaluated and Results:

- Linear Regression Model (Testing Set)
  - Model testing MAE: 803.98
  - Model testing MSE: 1194496.09
  - Model testing RMSE: 1092.93
  - Model testing R2: 0.57
 
- Decision Tree Model (Testing set)
  - Model testing MAE: 1044.70
  - Model testing MSE: 2260854.78
  - Model testing RMSE: 1092.93
  - Model testing R2: 0.18

## Final Recommendations:

The model I recommend using is the linear regression model. The testing model performed better than the decision tree and the training and testing set of the linear regression model performed similarly suggesting that there is low bias.
