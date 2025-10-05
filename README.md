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

Machine Learning Models Included In The Project:

* Logistic Regression

* Decision Tree Classifier
  
* Random Forest Classifier

Project Methodology:

1) Importing The Neccesary Libraries And Tools

2) Data Cleaning/ Data Preprocessing

3) Splitting Data Into Training And Validation Sets

4) Logistic Regression Model Predictions/ Model Evaluation
   
5) Decision Tree Classifier Model Predictions/ Model Evaluation
   
6) Random Forest Tree Classifier Model Predictions/ Model Evaluation
  
7) Choosing The Best Model Based On Accuracy Score And Confusion Matrix Results Comparison
   
   Best Model Choice: Random Forest Classifer Model

   Random ForestClassifier Model Results:
   
   * Random Forest Classifier Model Training Set Accuracy Score: 0.84
   * Random Forest Classifier Model Validation Set Accuracy Score: 0.79
     Random Forest Classifier Model Test Set Accuracy Score: 0.85
     
   * Random Forest Classifier Model Confusion Matrix Result:
     
     [[403,  42]
     
     [ 85, 113]]
     
   * Random Forest Classifer Model Classification Report:
     
              precision    recall  f1-score   support

           0       0.83      0.91      0.86       445
           1       0.73      0.57      0.64       198

    accuracy                           0.80       643
   macro avg       0.78      0.74      0.75       643
weighted avg       0.80      0.80      0.80       643

Final Model Conclusion:

Overall, the Random Forest model appeared to be the best model to solve the task in order to predict whether Megaline users were more likely to choose 
the Smart or Ultra plans. The Random Forest Classifier model's accuracy scores when working with the training and validation sets were above the project's 0.75 accuracy 
score threshold. The Random Forest Classifier model also had good values for precision, recall, f1-score, support and accuracy according to the classification report as well. 
The main determining factor as to why I chose the Random Forest Classifier model as the best model for the task is because the confusion matrix determined that the Random Forest 
Classifier model only generated 97 errors when making predictions with the validation set, where as the Logistic Regression model generated 159 errors and the Decision Tree model generated 131 errors. Finally, the Random Forest Classifier model's accuracy score when working with the testing set was greater than the 0.75 accuracy score threshold required 
for this project, thus making the Random Forest Classifier model a good model for predicting whether Megaline users were more likely to choose the Smart or Ultra plans in the future.
