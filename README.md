# Comment-Classification

This project implements a multi-class text classification pipeline using ensemble of LightGBM, XGBoost and Logistic Regression models on a dataset of 198,000+ comments.

Feature engineering was done using CountVectorizer (vocabulary size: 5000 tokens) and was optimized via hyperparameter tuning, reducing classification error by 11% over single model baselines.

Macro-F1 score of 0.834 was achieved on real world dataset, outperforming a logistic regression baseline (Macro-F1: 0.741) by 9.3 percentage points.
