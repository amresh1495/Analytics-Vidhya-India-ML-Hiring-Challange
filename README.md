## Approach Document - 
### India ML Hiring Challenge 2019
###### Amresh Giri (amresh.giri14@gmail.com)

### Step by step approach - 
1. After undesrtanding the problem statement and going through the dataset, I understood that this is a binary classification problem. 
2. Did some basic data preprocessing like calculating for na values, missing values, checking types of variables, varibale stats, etc.
3. After doing some basic analysis, I found that the target variable was hugely imbalanced. 
4. Converted the categorical values to numeric by encoding them.
5. Selected the best features by using Recursive Feature Engineering. 
6. Tried different techniques like under-fitting, over-fitting, EasyEnsemble and SMOTE for balancing the target variable. 
5. Tried different classification algorithms with best balancing technique and best selected features. 
6. Combination of Gradient Boosting Classifier with its best params (through GridSearchCV) with SMOTE gave me the best F1-score. 

 ##### Packages Used - 
 - pandas==0.24.2
 - sklearn==0.21.3
 - xgboost==1.0.0
 - imblearn==0.5.0
 
##### Setup - 
 - Install the required packages and run cells in the Jupyter Notebook. 

> I had a rank of 485 out of 3740 registered participants (Top 12 percent).
