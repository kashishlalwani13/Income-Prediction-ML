
# 💼 Income Prediction using Machine Learning

Predicting whether a person earns **more than $50K/year** using demographic and employment-related data from the UCI Adult Census dataset.

## 📊 Project Overview

We explored various machine learning models to classify income levels (`<=50K` vs. `>50K`). The dataset comes from the **1994 Census database**, a classic benchmark for classification problems.

Key goals:
- Build accurate classification models
- Evaluate models on performance metrics
- Select the best-performing model


## 🧠 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Neural Networks 

## 🛠️ Preprocessing Highlights

- ✅ **Label Encoding** & **One-Hot Encoding** for categorical features  
- ✅ **Standard Scaling** for numerical features  
- ✅ **SMOTE** for handling class imbalance  
- ✅ **Feature Selection** via importance scores  

## 📈 Evaluation Metrics

Each model was evaluated on the **test set** using:

- ✅ **Confusion Matrix**
- ✅ **Accuracy**
- ✅ **Sensitivity** (Recall for >50K class)
- ✅ **Specificity** (Recall for <=50K class)
