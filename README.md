# Predictive-analysis-in-diabetes
The main goal of this project is to develop a predictive model that can accurately determine whether a person is likely to have diabetes based on diagnostic measurements such as glucose level, BMI, age, blood pressure, and other medical attributes. 

## Methodology (Step-by-Step Process):
Step 1: Data Collection & Understanding
  Imported the Pima Indians Diabetes dataset.

  Analyzed its structure, checked data types, and identified missing or zero values.

Step 2: Data Preprocessing

  Handled missing values by replacing zeros with mean/median where necessary.

  Normalized or standardized numerical features for better model performance.

  Split the dataset into training (75%) and testing (25%) sets using train_test_split.

Step 3: Handling Data Imbalance

Observed imbalance in classes (more non-diabetic than diabetic samples).

Applied SMOTE (Synthetic Minority Oversampling Technique) to balance classes.

Step 4: Model Building (Supervised Learning)

Trained multiple supervised ML algorithms:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Step 5: Model Evaluation

Evaluated models using:

Accuracy

Precision

Recall (important for detecting diabetic patients)

F1-score

Confusion Matrix
