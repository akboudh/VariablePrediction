<h1>Heart Disease Prediction</h1>

<h2>Description</h2>
This project aims to predict the presence of heart disease based on patient characteristics using three different machine learning methods: logistic regression, decision trees, and shallow neural networks.

Files included:
1. heart_disease_prediction.ipynb - Jupyter Notebook containing the implementation of the three methods and analysis of results.
2. heart_disease_dataset.csv - CSV file containing the "Heart Disease UCI" dataset used for training and testing.
3. README.md - This file containing detailed information about the project, methods, results, and references.

### Methods Used
1. Logistic Regression
2. Shallow Neural Nets
3. Decision Trees

<h2>Experimental Results</h2>
The accuracy of each model on the testing set:
- Logistic Regression: 85.5%
- Decision Trees: 75.0%
- Shallow Neural Network: 86.8%

The shallow neural network outperformed both logistic regression and decision trees in predicting the presence of heart disease.

<h2>Discussion of Results</h2>
The superior performance of the shallow neural network suggests its ability to capture non-linear correlations between input data and the target variable. Logistic regression also showed promising results, indicating its simplicity and interpretability. However, decision trees exhibited lower accuracy, possibly due to overfitting.

These results can guide future research in developing more accurate algorithms for heart disease prediction based on patient characteristics.

<h2>References</h2>
1. Heart Disease UCI dataset. Retrieved from https://archive.ics.uci.edu/ml/datasets/heart+disease
2. Bishop, C. M. (2006). Pattern recognition and machine learning (Vol. 4). New York: Springer.
3. Hastie, T., Tibshirani, R., & Friedman, J. (2009). The elements of statistical learning: Data mining, inference, and prediction (2nd ed.). New York: Springer.
4. Breiman, L. (2001). Random forests. Machine Learning, 45(1), 5-32.
5. Huang, G. B., Zhu, Q. Y., & Siew, C. K. (2006). Extreme learning machine: Theory and applications. Neurocomputing, 70(1-3), 489-501.
