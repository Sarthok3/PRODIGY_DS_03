# **BANKING ANALYTICS WITH DECISION TREES: UNVEILING KEY PREDICTORS OF CUSTOMER CONVERSION** #

**Data Loading and Initial Checks:**
- Reads the `bank-full.csv` dataset using `pandas`.
- Displays the first few rows and checks for missing values.

**Data Preprocessing:**
- Converts the target column `y` to binary values (`1` for "yes" and `0` for "no").
- Applies one-hot encoding for categorical features using `pd.get_dummies()`, dropping the first category to avoid multicollinearity.

**Feature and Target Selection:**
Splits the dataset into features `(X)` and target `(y)`.

**Train-Test Split:**
Splits the data into training (80%) and testing (20%) sets using `train_test_split()`.

**Decision Tree Model Training:**
Trains a Decision Tree Classifier using `DecisionTreeClassifier()`.

**Model Evaluation:**
- Predicts target values on the test set.
- Computes performance metrics:
     Accuracy: Overall correctness of predictions.
     Precision: Correct positive predictions out of total predicted positives.
     Recall: Correct positive predictions out of actual positives.
     F1-Score: Harmonic mean of precision and recall.
- Displays the Confusion Matrix for classification results.

**Visualization:**
Decision Tree Plot: Visualizes the decision tree up to depth 3 using `plot_tree()`.

**Feature Importance Plot:** 
Visualizes the importance of features based on the decision tree.

## **Key Objective:** ##
The objective is to train and evaluate a decision tree classifier on the bank dataset, assess its performance through metrics, and visualize the decision-making process and feature importance for predicting customer conversion outcomes.







