# Customer_Churn_Prediction

## Description
This project aims to predict customer churn in the telecommunications sector using machine learning techniques. The analysis leverages classification models to identify customers likely to leave based on various service and demographic features.

## Table of Contents
- Skills Gained
- Tools and Libraries
- Dataset
- Project Workflow
  - Step 1: Load and Explore the Dataset
  - Step 2: Data Preprocessing
  - Step 3: Train and Evaluate Models
  - Step 4: Model Comparison and Interpretation
- Results
- Conclusion
- How to Run

## Skills Gained
- Binary classification
- Model evaluation (accuracy, precision, recall)
- Data visualization and feature engineering

## Tools and Libraries
- Scikit-learn: Model building and evaluation
- Pandas: Data manipulation
- Seaborn & Matplotlib: Visualization tools

## Dataset
The dataset contains customer information, including:
- Features: Contract type, Monthly charges, Tenure, Internet service type, etc.
- Target: 0 (Not Churn) / 1 (Churn)

## Project Workflow
### Step 1: Load and Explore the Dataset
- Load the dataset using Pandas
- Explore the data using functions like `head()`, `describe()`, and `value_counts()`

### Step 2: Data Preprocessing
- Handle missing values if any
- Encode categorical variables
- Normalize numerical features
- Split the data into training and testing sets

### Step 3: Train and Evaluate Models
#### 1. Logistic Regression
- Train a Logistic Regression model
- Evaluate performance using:
  - Accuracy
  - Classification Report (Precision, Recall, F1-Score)
  - Confusion Matrix

#### 2. Random Forest Classifier
- Train a Random Forest model
- Evaluate the model using the same metrics as Logistic Regression

### Step 4: Model Comparison and Interpretation
- Compare the accuracy of both models
- Visualize Confusion Matrices for deeper insights

## Results
| Model               | Accuracy |
|--------------------|---------|
| Logistic Regression | 85%     |
| Random Forest      | 89%     |

The Random Forest model performed better in terms of accuracy.

## Conclusion
In this project:
- We built and evaluated machine learning models for churn prediction.
- Accuracy and confusion matrices were used to assess model performance.
- The Random Forest model outperformed Logistic Regression.

## How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/telco-churn-prediction.git
cd telco-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook telco.ipynb
```
