# Predicting-Customer-Churn



CELL 1 CODE:

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


CELL 2 CODE:

Import necessary libraries - This code imports pandas, numpy, train_test_split, logistic regression, accuracy_score, classification_report, and confusion_matrix libraries.

Load the dataset - The code loads the dataset from a CSV file named 'telecom_churn.csv' using pandas.

Check the first 5 rows of the dataframe - This code displays the first 5 rows of the dataset to get an overview of the data.

Check the shape of the dataframe - This code prints the shape of the dataset to know the number of rows and columns in the dataset.

Check the summary statistics of the dataframe - This code shows the summary statistics of the dataset such as mean, standard deviation, minimum and maximum values, etc.

Check the information of the dataframe - This code displays information about the dataset such as column names, data types, and non-null values.

Drop unnecessary columns - This code removes unnecessary columns from the dataset that won't be useful in the analysis.

Check the first 5 rows of the updated dataframe - This code displays the first 5 rows of the updated dataset after dropping unnecessary columns.

Check the shape of the updated dataframe - This code prints the shape of the updated dataset after dropping unnecessary columns.

Check for missing values - This code checks the dataset for missing or null values.

Convert categorical variables to numerical variables - This code converts categorical variables to numerical variables using replace method.

Split the dataset into train and test sets - This code splits the dataset into train and test sets using train_test_split function from sklearn.

Initialize and fit the logistic regression model on the training data - This code initializes the logistic regression model and fits it on the training data using fit method.

Make predictions on the test data - This code makes predictions on the test data using predict method.

Evaluate the performance of the model using accuracy score, classification report, and confusion matrix - This code evaluates the performance of the logistic regression model using accuracy_score, classification_report, and confusion_matrix methods.





