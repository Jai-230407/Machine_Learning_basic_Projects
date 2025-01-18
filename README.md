The dataset for the projects are as follows:
Credit Card Fraud detection Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
The dataset for the Price Prediction model over Boston Housing dataset has already been uploaded in the repository.

Credit card fraud detection identifies fraudulent transactions using machine learning. A popular Kaggle dataset for this contains anonymized features (V1-V28), Time, Amount, and a target column (Class) where 1 indicates fraud and 0 legitimate transactions. The dataset is highly imbalanced, with very few fraudulent cases.
Steps to Build the Model
Data Preprocessing:
Handle class imbalance using techniques like SMOTE or undersampling.
Scale Amount and Time.
Split into train-test datasets.
Model Selection:
Use models like Logistic Regression, Random Forest, or Gradient Boosting (XGBoost).
Evaluate with metrics like Precision, Recall, F1-Score, and AUC-ROC, focusing on fraud detection performance.
Challenges:
Highly imbalanced data.
Limited interpretability due to feature anonymization.


The Boston Housing Price Detection model predicts house prices using the Boston Housing dataset, which contains features like crime rate, property tax, number of rooms, etc. The target variable is the Median Value of Owner-Occupied Homes (MEDV). This dataset is used for regression problems.
Key Points:
Features: Includes 13 numerical/categorical predictors like RM (average number of rooms per dwelling), LSTAT (% of lower status population), and PTRATIO (pupil-teacher ratio).
Goal: Predict MEDV, the median house price in $1000s.
Models: Linear Regression, Decision Trees, Random Forest, and Gradient Boosting are commonly used.
Evaluation: Metrics like RMSE, MAE, and R² score assess the model's performance.
