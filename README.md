# AdventureWorks2019_HumanResources.Employee-
This is a tabular data representation of an employee dataset, where each row represents an employee and columns represent their information.

## Here's a summary of what we've done so far

* I retrieved data from AdventureWorks2019 SQL database using Python and the pyodbc library and a connection string that included the database name, server name, and authentication credentials.
* I performed some initial data exploration and cleaning, such as checking for missing values and duplicates.
* I converted the cleaned data into a CSV file called employee.csv using the Pandas library.
* I imported the necessary libraries and loaded the employee dataset.
* I then performed exploratory data analysis (EDA) to get a better understanding of the dataset. This included checking for missing values, examining the distribution of each feature, and identifying potential correlations between features.
* Next, I split the cleaned csv dataset into training and testing sets using the train_test_split function from scikit-learn.
* I used the cleaned CSV file to build a classification model using the DecisionTreeClassifier from the Scikit-learn library.
* I evaluated the model's performance using accuracy, precision, recall, F1 score, and the ROC/AUC curve.
* After that, I used GridSearchCV to perform hyperparameter tuning on the Decision Tree Classifier. This involved trying out different combinations of hyperparameters and selecting the combination that resulted in the best performance.
* Finally, I used the Random Forest Classifier to build a new model on the same dataset. This algorithm constructs multiple decision trees and combines their predictions to improve the overall accuracy and reduce overfitting. I evaluated the performance of the Random Forest model using the same metrics as before.
