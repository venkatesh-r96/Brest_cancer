# Brest_cancer

FINAL-PROJECT: Breast Cancer Prediction
To Predict Breast Cancer using SVM and Ensemble ML models..

STEP 1: Problem Statement: Given the details of cell nuclei taken from breast mass, predict whether or not a patient has breast cancer using the SVM and Ensembling Techniques. Perform necessary exploratory data analysis before building the model and evaluate the model based on performance metrics other than model accuracy.

STEP 2: Data collection:

1.Importing Necessary packages like Pandas, Numpy, SKlearn, Seaborn, Matplotlib etc.
2.Importing the Historical Breast Cancer dataset..

STEP 3: Data Cleaning:

1.Dropping Unnecessary columns..
2.Checking for Null values in the dataset and Imputing or Removing those datapoints..
3.Checking datatype of each column, to find whether data is in right format..
4.Checking for Outliers, using Inter Quantile technique (IQR)
5.Checking for Duplicates

STEP 4: Exploratory Data Analysis:

1.Checking distribution of each features.. Using Histogram..
2.Checking relationship between Feature vs Features.. Using Pairplot from seaborn..
3.Finding value ranges of 'M' and 'B' classes..

STEP 5: Data Preprocessing:

1.Encoding.. Here, Only one categorical feature is there.. 'Diagnosis' column.. So, Label Encoding is done, because of Binary Categorical feature..
2.Splitting.. Splitting the dataset into Train and Test with split percentage of 75% and 25%..
3.Scaling.. In SVM, Distance metric is used.. So, scaling is mandatory here..

STEP 6: Building ML Model:

1.Fitting SVM model, by finding best Regularisation parameter 'C' using Cross validation..
2.Fitting Random Forest model..
3.Fitting XGBoost model, by finding best learning rate (lambda) using Cross validation..

STEP 7: Validation of Model:

1.Validating SVM, Random Forest, XGBoost model with Accuracy score, F1 score, AUROC score..
2.Finding Confusion matrix for each model..
3.Finding Classification report, Specificity, Sensitivity of each model..
