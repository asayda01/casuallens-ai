# casuallens-ai





In this challenge, you will explore a public dataset containing various 
hourly air quality measurements from a roadside sensor in an Italian city.

You can find the data here

https://archive.ics.uci.edu/ml/datasets/Air+Quality

Read the dataset information on that page carefully and answer the following questions using
python libraries.

Q-1
"______" was the maximum CO concentration recorded during May 2004.

Q-2
Looking at the highest recordings of NOX, "______" hour of the day and "______" as the
 day of the week was most common.

Q-3
"______" was the total NO2 recorded in January 2005.

Q-4
Month "______" of the "______"  year had the lowest average absolute humidity.

Q-5
Month "______" of the "______"  year had the highest variability in temperature (maximum - minimum)

Q-6
Which two columns have the most values missing? Seperate your answer with a comma.
Columns:"______" ,"______" 


Q-7

In this section you will build a linear model to predict CO concentration on hour ahead and compare
it to a simple benchmark.

Construct a new column called "target" which is the CO concentration lagged forward by one time step.

Calculate the Pearson correlation matrix for all variables.
Which 5 variables are most correlated with "target" (excluding the CO concentration itself)
from highest to lowest?

"______" 

"______" 

"______" 

"______" 

"______" 



Q-8

Use these variables(along with the CO concentration) as inputs for a linear regression predicting
the CO concentration one hour ahead. 

For simplicity we recommend using the scikit-learn LinearRegression implementation, but you should
exclude rows containing any missing values. 

Split your dataset into a training and testing set with a 60-40 ratio.

Calculate the mean absolute error, root mean squared error and coefficient of determination
("R squared") of your model on the test set.

Mean absolute error
"______" 

Root mean square error
"______" 

R squared
"______" 


Q-9

Construct a simple benchmark model that says the prediction for the CO concentration for the next
hour is the same as the current hour.

Calculate the same 3 regression metrics.

Mean absolute error
"______" 

Root mean square error
"______" 

R squared
"______" 


"""
