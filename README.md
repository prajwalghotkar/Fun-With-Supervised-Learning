# Fun-With-Supervised-Learning 💡

## Objectives:

* Fit a model using binary classification using logistic regression.
* Identify correlated variables and from a less complexmodel.

## Questions:

* Load the dataset from “voice.csv”, identify the target variable and do a one-hot encoding for the same. Split the dataset in train-test with 20% of the data kept aside for testing. [Hint: Refer to Label Encoder- one hot encoding not required  since the label column has only two values ]

* Fit a logistic regression model and measure the accuracy on the test set. [Hint: Refer to Linear Models  in scikit-learn]

* Compute the correlation matrix that describes the dependence between all predictors and identify the predictors that are highly correlated. Plot the correlation matrix using seaborn heatmap. [Hint: Explore dataframe methods to identify appropriate method]

* Based on correlation remove those predictors that are correlated and fit a logistic regression model again and compare the accuracy with that of previous model. (Remove the columns with co relation above 0.7) [Hint: Identify correlated variable pairs and remove one among them]


