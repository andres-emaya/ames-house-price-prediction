# House Price Prediction: Regression and Classification on Ames Housing

📄 [Read the paper](paper/ames-housing-ml-pipeline.pdf)

End-to-end scikit-learn pipeline that predicts house prices (regression) and reframes the same target into price bands (affordable, standard, expensive) for classification. Imbalance is measured first and handled with class weights or oversampling only when needed.

**Models:** Linear Regression, Ridge, KNN, SVR/SVC, Random Forest, Extra Trees, Gradient Boosting, Logistic Regression

**Results:** Best regressor was Linear Regression (RMSE ≈ $22.7k, R² = 0.93). Best classifier was Gradient Boosting with oversampling (≈87% accuracy).

**Dataset:** Ames Housing, loaded automatically by the notebook.

**Built with:** Python, scikit-learn, pandas, Matplotlib
