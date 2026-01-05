# PCOD Image Processing Project

## Description
This project implements an image processing and machine learning pipeline for medical image analysis. 
Texture features are extracted using the Gray Level Co-occurrence Matrix (GLCM) after image enhancement 
with Contrast Limited Adaptive Histogram Equalization (CLAHE).

Statistical feature selection using t-test is applied to identify significant features, followed by 
feature normalization and dimensionality reduction using Principal Component Analysis (PCA). 
Multiple machine learning models including Support Vector Machine (SVM), Random Forest, 
K-Nearest Neighbors (KNN), Logistic Regression, and Gradient Boosting are trained and evaluated.

The project compares model performance using accuracy, confusion matrix, and classification reports.

## Tools & Technologies
- Python
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib

## Applications
- Medical image analysis
- Disease classification using texture features
