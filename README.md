## About Lazy predict


Lazy predict is an awesome Python library that helps you quickly build machine learning models at scale and choose the best suitable model.


Actually,If you are working in the field of Machine Learning or Data science then you are definitely at the right place. Selecting the best model for your Machine Learning problem statement is one of the difficult tasks.

First, you have to import all the libraries then tune the parameters, then compare all the models, then check the model performance using different objectives. This process takes a lot of time. To avoid this problem, Lazy Predict comes into the picture.

 
The **LazyPredict** library is designed to quickly build and evaluate a variety of machine learning models for classification and regression tasks. The goal is to give a fast comparative analysis of multiple algorithms to help you identify which one might perform best on your dataset without manually tuning each model. It automates the process of model selection and testing with minimal code.

For classification tasks, **LazyPredict** includes the following models:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Random Forest Classifier**
4. **Support Vector Classifier (SVC)**
5. **Naive Bayes**
6. **Decision Tree Classifier**
7. **AdaBoost Classifier**
8. **Gradient Boosting Classifier**
9. **XGBoost**
10. **LGBM (LightGBM)**
11. **CatBoost**
12. **Quadratic Discriminant Analysis (QDA)**
13. **Linear Discriminant Analysis (LDA)**
14. **Gaussian Naive Bayes**
15. **Ridge Classifier**
16. **MLP Classifier (Multilayer Perceptron)**
17. **Bagging Classifier**
18. **ExtraTrees Classifier**
19. **HistGradientBoosting Classifier**

These models are run with default settings, and **LazyPredict** provides the output in the form of performance metrics (like accuracy, ROC-AUC, and F1 score) for each algorithm, helping you identify which model performs the best.

You can use **LazyPredict** with the following code snippet:

```python
from lazypredict.Supervised import LazyClassifier

# Assume X_train, y_train are your data
clf = LazyClassifier()
models, predictions = clf.fit(X_train, y_train)
print(models)
```


![image](https://github.com/user-attachments/assets/910e1f46-4c50-4d80-8174-af0c4646d865)


This will display the evaluation results for each of the models listed above, so you can easily compare their performance.
