# Loan Application Risk Assesment

In this project 10 000 historical loan application samples are analysed in order to create a Machine Learning classification model.
\
This model determines if a new client will default or pay back the loan in 30 days from the loan repayment period.
\
The target variable for the model is First Payment Delay 30 days (fdp30).

## Project Process

The project was developed in Google Colab Notebook by using Python as the programming language.
\
Python libraries used in the project are Pandas, NumPy and Scikit-learn.
\
Data visualization was done using Matplotlib and Seaborn.
\
1. After initial, exploratory data analysis data was pre-processed for model training by encoding all features to be numeric.
2. Afterwards the data set was split between dependent variable(fdp30) and the other, independent variables, which were used to determine the model outcome.
3. The initial data set was then spilt between the training sub-set, with which the model was trained, and test sub-set, which was used to determine the accuracy of the model. The division ratio of the sub-sets was 80:20.
4. Features were then scaled using data standardization, transforming the feature values to center around a mean of 0 with standard deviation of 1.
5. By implementing the Logistic Regression Algorithm, model was able to predict, if the client will be able to pay back the loan on time, with a precision of 81%.
6. In the conclusion, the model performance was analysed and proposal for optimal model was made.
