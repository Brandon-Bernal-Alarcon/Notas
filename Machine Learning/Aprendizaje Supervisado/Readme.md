# Supervised Learning

This folder contains structured notes and implementations of **Supervised Machine Learning** algorithms using **Python and scikit-learn**.  
Each notebook focuses on a specific model or concept, following a progressive learning path from fundamentals to model evaluation and tuning.

---

## 📚 Index

---

## [01. Introduction to Supervised Learning](01_Introduccion.ipynb)

- Introduction to supervised learning
- Difference between regression and classification
- Training data, features, and labels
- General machine learning workflow

**Core concepts & functions**

- Supervised learning paradigm  
- Feature matrix `X` and target vector `y`  
- `fit()`  
- `predict()`

---

## [02. Supervised Models – General Overview](02_Modelos_Supervisados_Panorama_General.ipynb)

- Overview of common supervised models
- When to use each algorithm
- Bias–variance trade-off
- Underfitting vs overfitting

**Core concepts & tools**

- Model selection principles  
- Generalization error  
- `train_test_split()`

---

## [03. K-Nearest Neighbors (Classification)](03_KNN_Clasificación.ipynb)

- Classification using distance-based learning
- Effect of number of neighbors `k`
- Decision boundaries
- Distance metrics

**scikit-learn functions & classes**

- `KNeighborsClassifier`  
- `fit()`  
- `predict()`  
- `predict_proba()`  
- `accuracy_score()`

---

## [04. KNN – Regression and Hyperparameter Tuning](04_KNN_Regresión_y_Ajuste.ipynb)

- KNN applied to regression problems
- Effect of `k` on bias and variance
- Hyperparameter tuning

**scikit-learn functions & classes**

- `KNeighborsRegressor`  
- `mean_squared_error()`  
- `r2_score()`  
- `GridSearchCV`

---

## [05. Linear Regression](05_Regresión_lineal.ipynb)

- Simple and multiple linear regression
- Interpretation of coefficients
- Assumptions of linear regression

**scikit-learn functions & metrics**

- `LinearRegression`  
- `coef_`  
- `intercept_`  
- `mean_squared_error()`  
- `r2_score()`

---

## [06. Ridge Regression](06_Regresion_Lineal_Ridge.ipynb)

- Linear regression with L2 regularization
- Controlling model complexity
- Bias–variance trade-off

**scikit-learn functions & classes**

- `Ridge`  
- `alpha`  
- `fit()`  
- `predict()`

---

## [07. Lasso and Polynomial Regression](07_Regresión_Lasso_y_Polinomial.ipynb)

- Feature selection using L1 regularization
- Polynomial feature expansion
- Modeling non-linear relationships

**scikit-learn functions & transformers**

- `Lasso`  
- `PolynomialFeatures`  
- `Pipeline`  
- `StandardScaler`

---

## [08. Logistic Regression (Binary Classification)](08_Regresión_logística_(clasificación_binaria).ipynb)

- Binary classification using logistic regression
- Sigmoid function
- Decision thresholds

**scikit-learn functions & metrics**

- `LogisticRegression`  
- `predict()`  
- `predict_proba()`  
- `confusion_matrix()`  
- `classification_report()`  
- `accuracy_score()`

---

## [09. Support Vector Machines (Linear & Non-Linear)](09_Support_Vector_Machines_(Lineales_y_no_Lineales).ipynb)

- Maximum margin classifiers
- Linear and non-linear decision boundaries
- Kernel trick

**scikit-learn functions & classes**

- `SVC`  
- `kernel` (`linear`, `rbf`, `poly`)  
- `C`  
- `gamma`  
- `decision_function()`

---

## [10. Cross Validation](10_Cross_validation.ipynb)

- Model evaluation using resampling
- Preventing overfitting
- Reliable performance estimation

**scikit-learn functions & utilities**

- `cross_val_score()`  
- `KFold`  
- `StratifiedKFold`  
- `GridSearchCV`

---

## [11. Decision Trees](11_Decision_Trees.ipynb)

- Tree-based supervised learning
- Splitting criteria
- Model interpretability

**scikit-learn functions & classes**

- `DecisionTreeClassifier`  
- `DecisionTreeRegressor`  
- `max_depth`  
- `min_samples_split`  
- `feature_importances_`

---

## 🎯 Learning Outcomes

By completing this section, you will be able to:

- Distinguish regression and classification problems  
- Train and evaluate supervised ML models  
- Apply regularization and hyperparameter tuning  
- Understand model interpretability and generalization  

---

## 📌 Notes

These notebooks serve as **learning notes and applied examples**, and can be used as:

- Study material  
- Reference documentation  
- Templates for real machine learning projects
