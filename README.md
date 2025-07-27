# Breast-Cancer-with-Multiple-Models-Capston
## Breast Cancer Prediction using Machine Learning
This project demonstrates various machine learning techniques using the Wisconsin Breast Cancer dataset. The analysis includes data cleaning, Exploratory Data Analysis (EDA), feature engineering, and the implementation of several machine learning models for cancer prediction. The model could serve as a useful tool for supporting medical diagnosis.

The purpose of this model is to predict whether a breast tumor is Benign (non-cancerous) or Malignant (cancerous). It does this by analyzing images taken from a breast tissue sample and looks at features such as:

- Texture of cells - how smooth or rough the cells appear
- Radius - the size of the cells
- Symmetry - how uniform the cell shapes are
- Concave points - how many indentations or "dips" are in the cell surface
- Concavity - how deep these indentations are
- Area - the total size of the cell clusters

This model can help with early detection of a potentially cancerous tumor. It can also act as a "second opinion" to help doctors make more accurate and speedy diagnoses with consistency.

## Dataset
The Wisconsin Breast Cancer dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image. The target variable classifies tumors as either malignant or benign. The dataset can be found on https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

## Analysis Overview
The project covered:
- Data loading
- Data cleaning 
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data preprocessing
- Model training and evaluation
- Model comparison
- Hyperparameter tuning
- Model selection
- Feature importance
- Final evaluation and conclusion

## Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine
- K-Nearest Neighbors
- Neural Network

## Results
Model Performance:
   
 - The Logistic Regression model is the best performer for predicting breast cancer
 - It achieves an F1-Score of 0.9861 after hyperparameter tuning

Feature Importance:
   - The top 10 most important features for prediction are shown below in the order of importance, which can be useful for medical professionals:
        * texture_smoothness_product
        * worst_mean_ratio
        * worst concave points
        * mean concave points
        * mean compactness
        * worst concavity
        * worst area
        * worst radius
        * area_perimeter_ratio
        * area error     

Clinical Implications:
   - The model could serve as a useful tool for supporting medical diagnosis
   - High accuracy in both malignant and benign cases suggests reliable predictions
   - Important features identified could guide future medical research


