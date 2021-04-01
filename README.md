# Application_Fraud_Detection
Application Fraud Detection Project

Overview: 
  Applied complet CRISP-DM process in this fraud detection project on financial product applicaiton data.
  For executive summary and each stage of the work please read the final report pdf.

Table of Content:
1. Data:
  - raw data: 'applications data.csv'
  - train test data: 'train_test.csv'
  - out of time validation data: 'oot.csv'
  
2.DQR:
  - a simple data quality report for the raw data
  
3.Candidate Variables:
  - feature enginnering process on creating expert variables
  - two version of notebooks (3200 variables & 400 variables)
  - did not include working dataset due to file sizes but dataset can be obtained from running the notebook

4. Feature Selection
  - top 80 candidate variables selection
  - applied ks score and fraud detection rate (fdr) as measure of goodness
  - two version of notebooks (2700 variables & 400 variables)
  
5. Final Features
  - finalized 30 variables for model building
  - applied multiple classification model algorithms to obtain initial performance results
  - applied hyperparameter tuning on the top performance model (gradient boosting model)
  - executed ensemble stacked modeling 

6. Result Reports
  - fine tuned final gradient boosting model and obtained training results
  - obtained final training, testing, validation data results
  
