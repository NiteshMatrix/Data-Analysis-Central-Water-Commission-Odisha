# Data Analysis on Central Water Commission Odisha
Implementation of Machine Learning and Data Analytics techniques to find insights from the Central Water Commission, Odisha Dataset

## Dataset
The dataset used in this analysis is stored in an Excel file named "Book2.xlsx" and is located in the path "/Users/niteshchandra/Desktop/Book2.xlsx". The dataset is loaded into a pandas DataFrame named "df".

## Correlation Matrix
A correlation matrix is calculated using the "corr()" method of the pandas DataFrame. The correlation matrix is plotted as a heatmap using the seaborn library.

## Data Preparation
The independent variables (Weight and Age) and dependent variable (Average Heart rate) are separated into their own variables. The dataset is split into a training set and a test set using the "train_test_split" function from sklearn.model_selection.

## Model Training
A linear regression model is trained on the training set using the "LinearRegression" function from sklearn.linear_model. The model is fitted on the training set using the "fit()" method of the LinearRegression object.

## Model Evaluation
The coefficients of the model are printed and plotted using a scatter plot of the predicted values and actual values. An Ordinary Least Squares (OLS) regression model is also trained on the dataset using the "OLS" function from the statsmodels.api library. The results of the OLS model are printed using the "summary()" method of the OLSResults object.

## Results
The adjusted R-squared value of the model is calculated and printed. The result shows that the model is not a good fit for the data as the adjusted R-squared is negative.
