The code builds a simple linear regression model to predict salaries based on years of experience using data stored in a CSV file named "Salary_Data.csv". Here’s a step-by-step explanation:

Import Libraries:

numpy for array operations.
matplotlib.pyplot for plotting graphs.
pandas for data manipulation and loading.
Load Data:

Load the data from a CSV file into a pandas DataFrame.
Split Data:

Separate the data into features (x) and target variable (y).
Split the data into training and test sets (80% training, 20% testing).
Build Linear Regression Model:

Create and train a linear regression model using the training data.
Make Predictions:

Use the trained model to predict salaries on the test set.
Visualize Results:

Plot the training set results.
Plot the test set results.
Predict New Value:

Predict the salary for someone with 12 years of experience.
Extract Model Parameters:

Extract the coefficients (coef_) and intercept (intercept_) of the linear regression model.
