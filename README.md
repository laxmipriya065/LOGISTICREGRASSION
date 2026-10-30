# Diabetes Prediction Using Logistic Regression

## Project Overview
This project focuses on predicting diabetes using Machine Learning. It uses the Pima Indians Diabetes Dataset and applies Logistic Regression to classify whether a person has diabetes (1) or does not have diabetes (0).

## Dataset Information
- **Dataset:** Pima Indians Diabetes Database
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Total Rows:** 768
- **Total Columns:** 9
- **Input Features:** 8
- **Target Variable:** Outcome

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithm
**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for binary classification.

## Project Workflow

1. Import required libraries.
2. Load the diabetes dataset.
3. Perform dataset inspection.
4. Check missing and duplicate values.
5. Replace invalid zero values with NaN.
6. Perform Exploratory Data Analysis (EDA).
7. Univariate Analysis.
8. Bivariate Analysis.
9. Multivariate Analysis.
10. Split the dataset into training and testing sets (80:20).
11. Handle missing values using Median Imputation.
12. Apply StandardScaler for feature scaling.
13. Train the Logistic Regression model.
14. Predict the output.
15. Evaluate model performance.
16. Visualize the confusion matrix and ROC curve.
17. Interpret model coefficients.

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Visualizations

The project includes:
- Histograms
- Boxplots
- Glucose vs Outcome analysis
- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Logistic Regression Coefficient Plot

## Conclusion

This project demonstrates how Logistic Regression can be used for diabetes prediction. Data cleaning, exploratory data analysis, median imputation and feature scaling are performed before model training. The model is evaluated using different classification metrics to understand its performance.

## Disclaimer

This project is developed for educational purposes only. It should not be used as a substitute for professional medical diagnosis.

## Author

**Name:** Your Name  
**Project:** AIML Minor Project  
**Topic:** Diabetes Prediction Using Logistic Regression
