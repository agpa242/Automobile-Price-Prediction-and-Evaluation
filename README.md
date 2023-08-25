# Automobile Price Prediction and Evaluation


## Intro:

A vehicle that has had one or more retail owners in the past is referred to as a used automobile, pre-owned car, or secondhand car. Franchise and independent vehicle dealers, rental car agencies, buy here pay here dealerships, leasing offices, auctions, and private party sales are just a few of the places where used cars can be purchased. Some auto dealers provide "no-haggle prices," "certified" pre-owned vehicles, and extended service agreements or warranties.



## **File Description:**

- **Data Visualization.ipynb:** The Jupyter notebook that contains a detailed analysis of the data using various data Visualization techniques

- **Data Preprocessing and Feature Engineering.ipynb:** The Jupyter notebook that contains all the data preprocessing steps including data cleaning, null value treatment, feature engineering.

- **Model creation and evaluation.ipynb:** The Jupyter notebook where different Machine Learning models were tested and evaluated.

- **Model.py:** Python file to recreate the model. Simply run it and the model will be created again.

- **CatBoostRegressor.pickle:** Pickle file of the model object.

- **scaler.pickle:** Pickle file for the scaler object to scale new data.


## Resources:

**Python version :** 3.7
**Packages Used:** pandas, numpy, matplotlib, seaborn, sklearn, pickle.


## **Project architecture:**

- **Exploratory Data Analysis**

    - Visualization of different features and their relationships
    - Plotting graphs of relation between different features to find any meaningful insight
    - Statistical analysis test like Chi-Squared test to draw important conclusion

- **Data Preprocessing**

    - Data Cleaning, Null value imputations, Removal of outliers
    - Scaling data (Standardization)

- **Feature engineering**

    - Encoding of categorical features
    - Encoding types include both Label Encoding and One-Hot encoding

- **Model Building**

    - Trying out six different models.
    - Validating model performance on Validation data

- **Testing**

    - Generating test predictions


### 1. Exploratory Data Analysis(EDA):

### 2. Data Preprocessing and Feature Engineering:

a) Data preprocessing includes data cleansing, treatment of null values and handling categorical data.

b) Categorical data is encoded using two techniques :-
- Label Encoding
- One-Hot Encoding

c) Removal of unncessary columns.

d) Scaling of data is done using MinMaxScaler from sklearn package.

### 3. Model Building:

a) Six different Machine Learning models were tested and evaluated for this project.

- Linear regression

- Random Forest

- K Nearest Neighbors

- Light GBM(LGBM)

- XGBoost

- CatBoost


### 4. Testing:

The CatBoost model tested on the test set and showed remarkable results.

- RMSLE score:  0.03488305748337859

- Accuracy score:  91.596

