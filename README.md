# linear-regression
The first few lines of code import the necessary libraries (NumPy, pandas, scikit-learn's LinearRegression model, and scikit-learn's mean_absolute_error, mean_squared_error, and train_test_split functions), and read in a CSV file containing data.
Next, the code selects the 'Balance' column from the data as the feature variable (X) and the 'CustomerId' column as the target variable (y), and fits a linear regression model to this data.
The code then predicts the 'CustomerId' value for a new 'Balance' value of 1000 using the trained model, and prints the predicted value to the console.
The code generates a random dataset of 100 samples with 1 feature variable ('X') and 1 target variable ('y'), and splits this data into training and testing sets using the train_test_split function from scikit-learn.
Finally, the code fits a linear regression model to the training data, uses the model to predict target values for the test data, calculates the mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE) between the predicted values and the actual values.
