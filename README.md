# Credit Card Fraud Detection

End-to-end ML pipeline to detect fraudulent European credit card 
transactions from September 2013.

## Business Problem
0.17% of 284,807 transactions are fraudulent. Standard accuracy 
is misleading here — catching fraud without flagging legitimate 
customers is the real challenge.

## Key Results
- Compared Logistic Regression vs Random Forest vs Decision Tree
- F1-Score and AUPRC used as primary metrics (not accuracy)
- SMOTE applied to handle extreme class imbalance
- Top fraud indicators: V14, V10, V12 (PCA-transformed features)

## Approach
1. EDA on severely imbalanced dataset (0.17% fraud rate)
2. Feature scaling — StandardScaler on
