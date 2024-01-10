The project encompassed exploratory data analysis, train-test splitting, and regression modeling on two distinct datasets. Logistic Regression was applied to the digit dataset, emphasizing label balancing and feature selection. Linear Regression was utilized for the 529-pollen dataset, focusing on mean absolute error and additional feature selection. The project shows an approach to data analysis, modeling, and evaluation across different machine learning tasks.

Digit Dataset Analysis and Logistic Regression:

Loaded the digits dataset and conducted preliminary analysis.
Employed Sklearn's test_train_split to create test and train sets for various ratios.
Trained Logistic Regression on the train-set and evaluated accuracy on the test-set.
Created an unbalanced sub-dataset from a balanced 1800 samples dataset.
Implemented label balancing to create a new balanced dataset.
Repeated logistic regression on the balanced dataset for different test-size ratios.
Ran a naive k-features selection algorithm, selecting the best features for k = 2.

529-Pollen Dataset Analysis and Linear Regression:

Loaded the 529-pollen dataset and conducted preliminary analysis.
Used test_train_split to split data into test-set and train-set for various ratios.
Trained Linear Regression on the train-set and evaluated mean absolute error on the test-set.
Plotted mean absolute error against different test-size ratios.
Ran a naive k-features selection algorithm using mean absolute error for k = 2 and k = 3.