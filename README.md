# Home-credit-default-risk

In the final phase, after proving our hypothesis that tuned machine learning techniques can outperform baseline models to aid Home Credit in their evaluation of loan applications, we believe expanding our framework will create a more robust environment with improved performance.

Logistic regression, XGBoost, Random Forest and LightGBM were selected to run with RFE, PCA, SelectKBest and Variance Threshold for feature selection, and SMOTE for data imbalance. The best performance for each algorithm was included in the classification ensemble using soft voting. The resulting Kaggle score was 0.72592 ROC_AUC.

Single and Multi-layer deep learning models, including linear, sigmoid, ReLu, and hidden layers were added with binary CXE, custom hinge loss using adam & sgd optimizer. The deep learning Kaggle score fell short of the ensemble model; additional experimentation will result in a better performing deep learning models. By combining and continuing to refine our extended loss function, we can further demonstrate our effectiveness.
