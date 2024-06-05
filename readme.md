# Linear Regeression Model 

Here we are implementing a Linear regression model to predict house prices based on their square footage, number of bedroom, and number of bathrooms.

## Steps to implement the model:

### 1.Data Preparation
First we will load our choosen dataset from our folder.In our case we are using Kaggle(https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

Load the training and test data from CSV files into Pandas DataFrames.


### 2. Identify and Map Relevant Columns
Create new columns for SquareFootage and Bathrooms in both the training and test DataFrames. Rename 'SalePrice' to 'Price' in the training data.


### 3.Clean the Data
Select the relevant features and target variable from the training data. Handle missing values by filling them with the median.

### 4.Model Training
Train a linear regression model using the cleaned training data.

### 5.Model Evaluation 
Make predictions on the test set and prepare the submission DataFrame. Round the predicted sale prices to four decimal places and save the DataFrame to a CSV file.


