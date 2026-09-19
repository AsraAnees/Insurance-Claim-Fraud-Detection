# Insurance Claim Fraud Detection

A machine learning project for detecting potentially fraudulent automobile insurance claims from structured claim and policy data.

The project treats fraud detection as an imbalanced binary-classification problem. It preprocesses numerical and categorical features, preserves an untouched test set, and uses **SMOTE only within the training workflow** to reduce the risk of data leakage.

The revised notebook compares **Logistic Regression, Random Forest, and Extra Trees** using stratified cross-validation. Model performance is evaluated with metrics that are more informative for fraud detection than accuracy alone, including **precision, recall, F1-score, ROC-AUC, and PR-AUC**.

The strongest ensemble approach is then tuned with cross-validation and evaluated on the held-out test set. The workflow also includes confusion-matrix, ROC-curve, and precision-recall-curve analysis.

The original coursework report is included as supporting documentation, while the notebook has been cleaned and corrected to use a more reliable machine-learning evaluation process.
