# 🏦 Bank Customer Churn Prediction
## 🔍 Problem Statement

Customer churn poses a significant challenge for banks. 
By predicting churn, institutions can proactively retain customers, reduce revenue loss, and improve satisfaction. 
This project aims to classify potential churners using historical banking data.
## 💻 Technologies Used

- Python  
- Google Colab  
- scikit-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Imbalanced-learn

## 🔧 Workflow Overview

1. **Data Cleaning & Preprocessing**
   - Handled categorical variables using Label Encoding
   - Normalized features using StandardScaler

2. **Class Balancing Techniques**
   - Explored original, under-sampled, and over-sampled datasets
   - Used `RandomUnderSampler` and `RandomOverSampler` to address class imbalance

3. **Modeling**
   - Implemented Support Vector Classifier (SVC)
   - Tuned hyperparameters with `GridSearchCV`

4. **Evaluation**
   - Measured accuracy, precision, recall, and F1-score
   - Visualized confusion matrices to interpret model effectiveness

## 📈 Results

- Achieved improved recall for minority class after oversampling  
- Best performance obtained using SVC with tuned hyperparameters on balanced data
