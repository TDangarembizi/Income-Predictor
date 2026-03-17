# Income Level Prediction

This project uses **machine learning** to predict income levels based on demographic and personal attributes of developers. The model leverages features such as age, gender, area of residence, immigration status, English proficiency, and education level to estimate income categories.

---

## Dataset Overview

The dataset contains information on developers:

| Column      | Description                               | Type         |
|------------|-------------------------------------------|-------------|
| Developer  | Developer's role or background            | Categorical |
| Age        | Age of the individual                      | Numerical   |
| Gender     | Gender of the individual                   | Categorical |
| Area       | Area of residence                          | Categorical |
| Immigrant  | Immigration status                         | Categorical |
| English    | English proficiency                        | Categorical |
| Education  | Highest education level attained           | Categorical |
| Income     | Income level (target variable)            | Categorical |

**Data Summary:**

- Total entries: 16,702  
- Missing values: Present in multiple columns, particularly the target variable `Income`.  

---

## Project Objectives

### 1. Data Preprocessing
- Handle missing values appropriately  
- Encode categorical variables for machine learning models  
- Normalize or scale numerical data if required  

### 2. Exploratory Data Analysis (EDA)
- Identify patterns and relationships in the dataset  
- Visualize correlations between features and income levels  

### 3. Model Development
- Train and evaluate machine learning models to predict income levels  
- Algorithms explored:  
  - Logistic Regression  
  - Decision Trees  
  - Random Forests  
  - Gradient Boosting  

### 4. Model Evaluation
- Evaluate performance using:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  

### 5. Deployment (Optional)
- Build a simple interface for users to input personal attributes and receive income predictions  

---

## Requirements

- Python 3.8+  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib`  
  - `seaborn`  
- Jupyter Notebook (for interactive use)  

---

## How to Run

1. Clone the repository
2. Install required libraries
3. launch the notebook
4. follow steps in the notebook
