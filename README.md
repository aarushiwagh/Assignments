# Assignments
## Assignment-1
The prediction of the house prices was a regression problem. Hence, I used three regression techniques - Linear regression, Support Vector Regression and Random Forest Regression for prediction. It was observed that the Random Forest Regressor gave the least error. On plotting boxplots of the models, the max, min, median and interquartile range of the Random Forest Regression Model was the closest to that of the original house price distribution, hence that model was chosen as the best one.
The dataset for the given problem was in .xlsx format, so I converted it to .csv.
## Assignment-2
For proceeding with this problem, we first needed to clean our data by removing the unnecessary columns, taking care of the NaN values and out of place values (like prices being negative).
After preprocessing the data, we have to merge the two datasets to give a final dataframe. I tried various approaches for the same:
1. Using the isin pandas function, but this gave us NaN values in the final dataframe.
2. Using the intersection and addition set operations.
3. Using the merge pandas function.
I finally chose the merge function to perform this operation, as it was concise and gave the best result in a few lines of code.
