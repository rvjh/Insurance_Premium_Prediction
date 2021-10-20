# Insurance_Premium_Prediction

#### Kaggle dataset [link](https://www.kaggle.com/faisalmoizhussain/insurance-premium-prediction/data).

#### The purposes of this exercise to look into different features to observe their relationship, and plot a multiple linear regression based on several features of individual such as age, physical/family condition and location against their existing medical expense to be used for predicting future medical expenses of individuals that help medical insurance to make decision on charging the premium.

#### The insurance.csv dataset contains 1338 observations (rows) and 7 features (columns). The dataset contains 4 numerical features (age, bmi, children and expenses) and 3 nominal features (sex, smoker and region).

Methods followed : 

### 1. Dataset loading and preprocessing of dataset: 
        * At the begining I loaded some important libraries for the preprocessing like pandas, matplotlib, seaborn etc.
        * Next checked the null values if present.
### 2. EDA
       * In this step i checked what are the colums present and their datatypes.
       * unique values present
       * converted the categorical features into numerical by using pandas get_dummies
### 3. Feature selection
       * here I converted the data using Standard Scaler
       * also separated the features and the labels
       * checked the multiclinearity conditions using statsmodels [VIF](https://www.investopedia.com/terms/v/variance-inflation-factor.asp).
       * also generated a correlation heatmap to see the corelations between the features.
       
       
