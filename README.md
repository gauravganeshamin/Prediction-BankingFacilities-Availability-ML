# Prediction-BankingFacilities-Availability-ML
Files for prediction of banking facilities availability
Primary requirement is to obtain the relevant data to train the models. We have obtained three datasets, each dataset speaks
about different aspects of the customers finances. The initial task was to determine customer satisfaction. The data is available
for ten thousand customers. 

Customers Churn Dataset has information regarding customers Behaviour such as credit
score, credit card ownership, activeness, no of bank products owned, tenure etc. Target is whether the customer is satisfied
or not, with unsatisfied implying that he/she is likely to exit. 

Customers Finances and Loan Dataset has information regarding customers such as Age, Annual income, Home ownership, employment length, Historical default. Loan details such as loan intent, loan amount, interest rate, loan percent income. 
Target is whetherloan is repaid or not. 

Default of Credit Card Clients Dataset has Information regarding customers bank balance and credit card bills such as payment status (how
late/early the bill was paid), amount to be paid, amount paid for credit card bills of six months. It is used to predict if the
customer will be able to pay his credit card bills without defaulting. Target is whether the customer will repay his next credit
card bill in time or not. The dataset was obtained from University of California Irvine Machine Learning repository.

After data collection, appropriate data preprocessing steps such as removal of
redundant attributes, filling up of null/NaN values with the respective column’s average value or removing the respective row
depending upon the situation, scaling, encoding, data visualization, removing of outliers, etc were done.

We have compared six machine learning algorithms (Decision Tree, Naive Bayes, Support Vector Machine (SVM), Logistic
Regression, Random Forest, XGBoost) and Artificial Neural Networks (ANN). The approach that displays maximum
efficiency for a model has been used for making final predictions for the respective model.
We have also used the Shapely Additive Explanations or SHAP analysis to determine how and by how much each feature
impacts in the final decision of the model.
