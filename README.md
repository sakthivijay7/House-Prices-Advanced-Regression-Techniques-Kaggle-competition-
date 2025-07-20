# House-Prices-Prediction- Advanced-Regression-Techniques-Kaggle-competition
#### Date:June22 -2025
Kaggle competition page: (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

- **Data collection:**
Data collect through the kaggle competition page train and test datasets.

- **Null check:**
Pandas to read the files then check null values ,numerical values and categorical values .
SimpleImputer-Median and most frequent to fill null values.

- **Features:**
Only select importent features 59 columns to training ,it contains total 81 columns ,drop most null value columns.

- **Target:**
"SalePrice"

- **Encoding:**
categorical values `pd.get_dummies` to one hot encoding.

- **Features scalling:**
StandardScaler to scalling the training datas.

- **Model:**
Tensorflow & keras for `Dense neural network` layers.set Loss mean_squared_error and metrics mean_absolute_error. 

- **Submission:**
submit the test data id and Predicted SalePrice in csv file format.

- **Result:**
Got `Errorscore- 0.2132 , Leaderboard - 4025`

