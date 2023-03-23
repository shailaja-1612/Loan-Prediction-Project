# Loan-Prediction-Project
*This Project helps to automate the loan eligibility process (real-time) based on customer detail provided while filling out online application forms. These details are Gender, Marital Status, Education, number of Dependents, Income, Loan Amount, Credit History, and others.
*It is a project on analytical vidhya and the data sets are acuired from there.
# EDA(Exploratory Data Analysis)
The data is distributed and categorial data is analysed
# Model Building
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.

I tried three different models and evaluated them using Accuracy Score. I chose Accuracy_Score because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.

I tried three different models:

** Logistic Regression** – Baseline for the model
Decision Trees – The problem at hand is a classification problem.
Random Forest – Again, with the sparsity associated with the data, I thought that this would be a good fit.
# Model Performance
The Random Forest model far outperformed the other approaches on the test and validation sets.

*Random Forest : accuracy_score = 0.7950819672131147
*Logistic Regression: accuracy_score = 0.7886178861788617
*Decision Trees: accuracy_score = 0.6885245901639344
