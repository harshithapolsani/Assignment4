# Assignment4
# Summary

**In the first question**

I am using Jupyter Notebook as my IDE and Pandas to iterate through the data and create a two dimensional dataframe.
Pandas has inbuilt functions to read data from CSV, JSON, Parquet and other files, I am reading the sample file
provided in the Google Drive with read_csv function. At this time all the other parameter values are default.
The inbuilt function describe gives the details of the data such as mean, max, min.. etc, Pandas have functions like
info() and external mean, max.. etc functions to analyze the data.

The isnull() function gives the response in boolean values adding sum() function to it will count the True count
and displays them accordingly.
fillna() function will replace the null values, it can be implemented on a dataframe or a single column in a dataframe.

Aggregating the data works with agg() function and groupby() function helps to index the columns to group.

Filtering can be done with inbuilt functions or implying the conditions with the chosen dataframe columns.

using df.columns we can pass the columns which should be in the dataframe or we can drop the columns from the existing
dataframe using drop() function.
We can use astype() function to change the dataframe column dtype.
matplotlib function helps to plot and scatter the data on two dimensional X and Y axis according to the arguments 
passed.

**In the second question:**

Pythons inbuilt functions makes it a primary goto language for data analysis.

I am using LinearRegression class from sklearn package to get the expected output as per the assignment guidelines.

The inbuilt function train_test_split from sklearn helps to pass the percentage of train data and test data.
The fit() function in the linearRegression class helps us to fit the train data into the model.
Prediction on Y can be done with the predict() function which is the extension of Linear Regression class.

As always matplot lib plt and scatter helps to visualize the data in the final step.
