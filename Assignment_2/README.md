# MATH-CSCI485_Daniel_Lee

# Task 1
Load the 10 physical indicators (such as age, BMI, blood pressure, etc.) 
and split the data into training data (X_train) and testing data (X_test) using an 80:20 ratio.

# Task 2
Before performing feature selection, evaluate the performance of the initial model using all features.
The R² score calculated here serves as a baseline to compare performance changes after features are removed.

# Task 3
Using the RFE, remove the least important features sequentially until only one feature remains.
At each step, collect the coefficients of the remaining features to identify the key variables.

# Task 4
As the number of features decreases, examine how the influence of each feature changes in a table.
As shown in the table, BMI, s5, and bp maintain the highest importance throughout the feature elimination process.