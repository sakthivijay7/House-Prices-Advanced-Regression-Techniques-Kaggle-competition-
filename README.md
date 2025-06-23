# House-Prices---Advanced-Regression-Techniques-Kaggle-competition-
Kaggle competition page: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
Data collection:
Data collect through the kaggle competition page train and test datasets.

Null check:
Pandas to read the files then check null values ,numerical values and categorical values  SimpleImputer to Median and most frequent to fill it.

Features:
Only select importent features 59 columns to training ,it contains total 81 columns ,drop most null value columns.

Target:
"SalePrice"

Encoding:
categorical values get dummies to one hot encoding.

Features scalling:
StandardScaler to scalling the training datas.

Model:
Tensorflow & keras for Dense neural network layers.set Loss mean_squared_error and metrics mean_absolute_error. 

Submission:
submit the test data id and Predicted SalePrice of csv file.

Result:
Got errorscore just 0.21326 ,leaderboard - 4025

