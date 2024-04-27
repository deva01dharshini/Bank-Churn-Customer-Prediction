# Bank-Churn-Customer-Prediction
## Task
 To Build a machine learning model to identify and predict customers who are likely to leave from a bank..</br>
Tool Used: Python, Google colab
## Dataset:
Dataset is taken from Kaggeles "Bank Customer churn prediction Dataset". Dataset contains 10000 different datas with 14 features.
- id: An integer representing a unique identifier
- CustomerId: An integer representing the customer Id.
- Surname: A string representing the customer’s surname.
- CreditScore: An integer representing the customer’s credit score.
- Geography: A string representing the customer geo location.
- Gender: A string representing the customer’s age.
- Age: A float representing the customer’s age.
- Tenure: An integer representing the number of years the customer has been with the bank.
- Balance: A float representing the customer’s account balance.
- NumOfProducts: An integer representing the number of bank products the customer uses.
- HasCrCard: A float indicating whether the customer has a credit card.
- IsActiveMember: A float indicating whether the customer is an active member.
- EstimatedSalary: A float representing the estimated salary of the customer.
- Exited: An integer indicating whether the customer has exited (1) or not (0). </br></br>

Credit: Bank Turnover Dataset, TARUN SUNKARANENI, https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/input

## Step Followed:
### Load the necessary Libraries:
- numpy
- pandas
- matplotlib
- seaborn
- StandardScaler
- train_test_split
- accuracy score
- confusion matrix
- classification report
- display from IPython
- SMOTE from imblearn.over_sampling
### Data Collection and Analysis :
- Load the data using pandas read_csv
- Analyse the data
### Exploratory data analysis:
 ### Data cleaning
 - Removing irrelevant columns
 ### checking for null values
 - Find and remove the null values
### Feature Engineering:
 ### Encoding categorical data
 - Converting categorical data into numerical data
### Data visualizations:
 - Analyse categorical features through count plot
 ### Handling the Imbalanced Dataset
 - Synthetic Minority Oversampling Technique(SMOTE): SMOTE first selects a minority class instance a at random and finds its 
  k nearest minority class neighbors. The synthetic instance is then created by choosing one of the k nearest neighbors b at 
  random and connecting a and b to form a line segment in the feature space. The synthetic instances are generated as a 
  convex combination of the two chosen instances a and b.
 - Get the new set of X and Y sample using SMOTE, the sample contains equal number of both the classes
### Data splitting
 - Split the data into feature and target
 - Split the feature and target into Training and test sets
### Feature Scaling
  - Scale numerical features to have a similar range, using Standardization to improve model convergence
 ### Model Building
 - Build a model using algorithms
 - Logistic Regression
 - Decision Tree
 - Random Forest
 - XG boost
  - Compile the model
  - Get the Y_predict values
  - Train the model
  - Plot the accuracy and precision
  - Plot the classification report
  - Plot Confusion Matrix
  -Conclusiion
