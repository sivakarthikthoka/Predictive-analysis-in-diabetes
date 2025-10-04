# Predictive-analysis-in-diabetes
The main goal of this project is to develop a predictive model that can accurately determine whether a person is likely to have diabetes based on diagnostic measurements such as glucose level, BMI, age, blood pressure, and other medical attributes. 

## Methodology (Step-by-Step Process):
# Step 1: Data Collection & Understanding

  1)Imported the Pima Indians Diabetes dataset.
  2) Analyzed its structure, checked data types, and identified missing or zero values.

# Step 2: Data Preprocessing

  1)Handled missing values by replacing zeros with mean/median where necessary.
  2)Normalized or standardized numerical features for better model performance.
  3)Split the dataset into training (75%) and testing (25%) sets using train_test_split.

# Step 3: Handling Data Imbalance

  1)Observed imbalance in classes (more non-diabetic than diabetic samples).
  2)Applied SMOTE (Synthetic Minority Oversampling Technique) to balance classes.

# Step 4: Model Building (Supervised Learning)
  1)Trained multiple supervised ML algorithms:
  2)Logistic Regression
  3)Decision Tree Classifier
  4)Random Forest Classifier
  5)Support Vector Machine (SVM)
  6)K-Nearest Neighbors (KNN)

# Step 5: Model Evaluation

Evaluated models using:

  1)Accuracy
  2) Precision
  3)Recall (important for detecting diabetic patients)
  4) F1-score
  5) Confusion Matrix
