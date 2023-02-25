# Predicting-Customer-Churn





First, the necessary libraries are imported, including pandas for data manipulation, scikit-learn's LogisticRegression model for building the classification model, and various modules for evaluation such as train_test_split and accuracy_score.

Next, the CSV file containing the data is read into a pandas DataFrame object.

Any blank spaces in the TotalCharges column are replaced with NaN values.

Any rows with NaN values are dropped from the DataFrame.

Categorical variables are converted to numerical variables using one-hot encoding.

The features and target variable are separated from the DataFrame and assigned to X and y, respectively.

The data is split into training and test sets using train_test_split.

A logistic regression model is trained on the training data.

The model is used to predict the target variable of the test set.

The accuracy of the model is evaluated using accuracy_score and printed to the console
