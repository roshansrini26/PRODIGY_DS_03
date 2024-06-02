# Prodigy-Infotech
Tasks of Prodigy infotech virtual internship May-June
Task 3:
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.
Preprocessing:
The target value is separated for the Decision classifiers and is converted into binary using a lambda function. The features are separated into categorical and numerical. The categorical data is pre-processed with Pipeline of SimpleImputer to check on the missing value and replace it with the specific value. Onehotencoder will convert categorical to numerical and numerical data subjected to Onhotencoder for further value change. Both the features are transformed and at last, they are combined.
Model:
The dataset is split into train and test data and is fetched to the model to evaluate the predictions
Metrics:
Our model reported an overall 82% accuracy with an 89% F1 score and a confusion matrix with more true positives and true negatives.
Visualization:
A feature importance bar chart is depicted to see the distribution of features, a confusion matrix with true positive, true negative, false positive, and false negative, a Decision tree is shown for all the features, and a heatmap for the attributes is shown.
Additionally for the column features whether the customer will choose the plan or not is also shown.

-Roshan S
