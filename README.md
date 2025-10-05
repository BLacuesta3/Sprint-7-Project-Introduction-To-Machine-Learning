Project Name: Sprint 7 Project/ Introduction To Machine Learning

Project Description: This project involves developing a model that could help analyze Megaline (hypothetical company) subscribers' behavior in regards to whether subscribers 
were more like to choose the Smart or Ultra Plans. This project involvles the use of machine learning models that can be used in order to help the company predict whether subscribers
are more likely to choose the Smart Plan or the Ultra Plan. The task being solved in this project is binary classification task.  This project include the following skilled tasks: 
data cleaning/ data preprocessing, data splitting, machine learning model parameter tuning with the use of GridSearch CV, evaluating machine learning model perforamces using: 
accuracy score metric, confusion matrix and classification report.

Project Dataframe: 'users_behavior.csv' 

Task Presented In Project: Mobile carrier Megaline has found out that many of their subscribers use legacy plans. 
They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. 

Project Minium Model Accuracy Score Metric Requirement: 0.75

Project Libraries And Tools Used:

* pandas

* sklearn.model_selection (function: train_test_split())

* sklearn.linear_model (function: LogisticRegression())

* sklearn.tree (function: DecisionTreeClassifier())

* sklearn.metrics (functions: accuracy_score(), recall_score())

* sklearn.ensemble (function: RandomForestClassifier())

* sklearn.metrics (functions: confusion_matrix(), classification_report())

* sklearn.model_selection (function: GridSearchCV())

Machine Learning Models Included In Project:

* Logistic Regression

* Decision Tree Classifier
  
* Random Forest Classifier

Project Methodology:

1) Importing The Neccesary Libraries And Tools

2) Data Cleaning/ Data Preprocessing

3) Splitting Data Into Training And Validation Sets

4) Logistic Regression Model Predictions/ Model Evaluation:
   
5) Decision Tree Classifier Model Predictions/ Model Evaluation:
   
6) Random Forest Tree Classifier Model Predictions/ Model Evaluation:
  
7) Choosing The Best Model Based On Accuracy Score And Confusion Matrix Results Comparison
   
   Best Model Choice: Decision Tree Classifer Model

   Decision Tree Classifier Model Results:
   
   * Decision Tree Classifier Model Training Set Accuracy Score: 0.84
   * Decision Tree Classifier Model Validation Set Accuracy Score: 0.79

   * Decision Tree Classifier Model Confusion Matrix Result:
     
     [[424,  21]
     
     [110,  88]]

   * Decision Tree Classifer Model Classification Report:
     
              precision    recall  f1-score   support

           0       0.79      0.95      0.87       445
           1       0.81      0.44      0.57       198

    accuracy                           0.80       643
   macro avg       0.80      0.70      0.72       643
weighted avg       0.80      0.80      0.78       643
