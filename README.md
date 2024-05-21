# Description
The idea behind this small project is that I used the Linear Regression model to predict the accuracy scores of the titanic dataset in different scenarios. Basically, I have filled in the missing values of the '**Age**' column of the titanic dataset in three ways and tried to implement Logistic Regression on all these cases to predict the **accuracy scores**_.

The dataset which I used was a trimmed dataset from the original titanic dataset consisting only the columns; **'Age','Fare' and 'Survived'**.

The first implementation consists of modeling by eliminating all the rows of the feature 'Age' containing 'NaN'.

The second implementation was based on filling the missing values in our numerical data 'Age' with mean.

And the last one consisted the use of first training the model through Linear Regression to predict the missing values of 'Age' column and then using the Logistic Regression algo. to predict the 'Survived' column values while training on the 'Age' and 'Fare' columns data.

The **LR1.ipynb** is the first implementation carried out in Jupyter Notebook and like wise other files also in a similar way.

In every model, you can observe that I have used a train and a test dataset to train my model and predict the results based on it.
