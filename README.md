# Medical Insurance Cost Prediction

## Project Overview
This project aims to predict medical insurance charges using Machine Learning techniques, specifically Linear Regression.

The project explores the relationship between different personal factors and medical insurance costs, then builds and evaluates a prediction model.

## Dataset
The dataset used in this project is the Medical Cost Personal Dataset from Kaggle.

**Dataset Source:**  
https://www.kaggle.com/datasets/mirichoi0218/insurance

The dataset contains information such as:
- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region
- Insurance Charges (Target Variable)

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Steps

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Inspected the dataset structure and statistical information.
- Checked for missing values and duplicate records.
- Removed duplicate records.

### 2. Data Preprocessing
- Applied One-Hot Encoding to categorical features.
- Separated the features (X) from the target variable (y).

### 3. Exploratory Data Analysis (EDA)
- Used scatter plots to explore relationships between features and insurance charges.
- Visualized the relationship between age and insurance charges.

### 4. Model Training
- Split the dataset into training and testing sets (80% training and 20% testing).
- Trained a Linear Regression model.
- Generated predictions on the test set.

### 5. Model Evaluation
The original Linear Regression model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| MSE | 35,478,020.68 |
| RMSE | 5,956.34 |
| MAE | 4,177.05 |

### 6. Model Improvement Experiment
Polynomial Features were applied to the age and BMI features to experiment with improving the model.

However, the new model achieved higher MAE and RMSE values than the original model. Therefore, the original Linear Regression model was retained as the final model.

## Conclusion
This project demonstrates the complete workflow of a basic Machine Learning regression task, including data preprocessing, exploratory data analysis, model training, prediction, and evaluation.

The results show that the original Linear Regression model captured general patterns in the dataset, although prediction errors remain and further improvements could be explored.
