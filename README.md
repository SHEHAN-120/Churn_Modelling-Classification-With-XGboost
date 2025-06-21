# Churn_Modelling-Classification-With-XGboost

This repository contains a machine learning project focused on predicting customer churn using the **XGBoost Classifier**. The goal of this project is to identify which customers are likely to leave a bank's services based on demographic and account-related information.

## 📊 Dataset

The dataset used is `churn_modelling.csv`, which includes features such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, active membership, estimated salary, and a churn label.

## 🔧 Project Workflow

### 1. Data Preprocessing
- **Missing Values**: Checked for and confirmed no missing data.
- **Categorical Variables**: Handled using **one-hot encoding** (dummy variables).
- **Feature Selection**: Selected relevant features to train the model.

### 2. Model Building
- Used **XGBoost Classifier** to train the predictive model.
- Split the dataset into **training and testing sets** to evaluate performance.

### 3. Model Evaluation
- **Confusion Matrix**: Used to visualize and evaluate the classification results.
- **K-Fold Cross Validation**: Implemented to ensure the robustness and generalizability of the model.

## 🛠 Tools and Libraries
- Python
- Pandas
- scikit-learn
- XGBoost


## 📈 Results

The XGBoost model demonstrated strong predictive capabilities with reliable accuracy across cross-validation folds and clearly defined classification metrics.
