# Credit Card Fraud Detection

This project applies anomaly detection methods to identify fraudulent credit card transactions. Fraud detection is a critical task for financial institutions to reduce losses and protect customers from unauthorized purchases.

The dataset used consists of 284,807 transactions carried out by European cardholders in September 2013, including 492 fraudulent cases, representing only 0.172% of the total. All features are numerical, most of them obtained through PCA transformation (V1–V28), with two original variables: `Time` and `Amount`. The target variable `Class` indicates whether a transaction is legitimate (0) or fraudulent (1).

The methodology followed in this work is as follows. Data analysis was performed to examine the class imbalance and feature distribution. Feature engineering was applied to process the variables for modeling. Several machine learning techniques were implemented to detect anomalies. PyCaret (AutoML) was employed to automate model training, comparison, and optimization. Model evaluation was carried out using the Area Under the Precision-Recall Curve (AUPRC) and the confusion matrix, since accuracy is not a reliable metric in the case of imbalanced data.

The project was developed in Python using Pandas, NumPy, Matplotlib, and Seaborn for analysis and visualization, Scikit-learn for machine learning models, and PyCaret for AutoML.

## Repository structure

```
credit-card-fraud-detection/
├── Credit_Card_Fraud_Detection.ipynb   # Jupyter notebook
├── creditcard.csv                      # Dataset (excluded from GitHub, download from Kaggle)
```

Open the notebook and execute the cells step by step: