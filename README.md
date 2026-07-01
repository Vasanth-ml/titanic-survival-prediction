# Titanic Survival Prediction

## Problem Statement
Predict whether a passenger survived the Titanic 
disaster based on features like age, gender, 
ticket class and fare using Machine Learning.

## Dataset
- Source: Kaggle - Titanic Dataset
- Size: 891 rows, 12 features
- Target: Survived (0 = Died, 1 = Survived)

## Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 79.8% |
| Decision Tree | 79.8% |
| Random Forest | 82.1% |

## Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Data Loading and Exploration
2. Data Cleaning (missing values - Age, Cabin, Embarked)
3. Feature Engineering (encoding categorical variables)
4. Train Test Split (80/20)
5. Model Training (3 algorithms compared)
6. Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
7. Visualization (Confusion Matrix Heatmap, Feature Importance)

## Key Findings
- Random Forest outperformed both models with 82.1% accuracy
- Sex was the most important feature (Women and children first!)
- Fare was second most important feature in Random Forest
