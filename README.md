# student-performance-project
Classification of student performance into low, medium, and high categories using ML.
# Student Performance Classification Project

This project aims to classify students' academic performance into three categories:
**low**, **medium**, and **high**, based on their average exam scores.

## Dataset
The dataset includes student demographic information and exam scores in:
- Math
- Reading
- Writing

## Methodology
- Data preprocessing using `ColumnTransformer`
- Feature engineering with average score calculation
- Stratified train-test split
- 5-fold Stratified Cross-Validation on the training set
- Model comparison using weighted evaluation metrics

## Models Used
- Decision Tree
- Random Forest
- Support Vector Machine (RBF kernel)
- Multinomial Logistic Regression

## Evaluation
Model performance is evaluated using:
- Accuracy
- Weighted Precision
- Weighted Recall
- Weighted F1-score
- Confusion Matrices

## Files
- `Student_Performance_Classification.ipynb`: Full implementation and results
