# Accuracy_score-Linear_Regression-
The idea behind this small project is that I used the Linear Regression model to predict the accuracy scores of the titanic dataset in different scenarios.
The dataset which I used was a trimmed dataset from the original titanic dataset consisting only the columns; 'Age','Fare' and 'Survived'.
The first implementation consists of modeling by eliminating all the rows of the feature 'Age' containing 'NaN'.
The second implementation was based on filling the missing values in our numerical data 'Age' with mean.
And the last one consisted the use of first training the model through Linear Regression to predict the missing values of 'Age' column and then using the Logistic Regression algo. to predict the 'Survived' column values while training on the 'Age' and 'Fare' columns data.
