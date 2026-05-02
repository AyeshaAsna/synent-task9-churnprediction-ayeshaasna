# synent-task9-churnprediction-ayeshaasna

### 📌 Description 
End-to-end churn prediction project including data preprocessing, model training, evaluation, and deployment using Streamlit with user input interface.

---

# 📘 README.md (Task 9)

```markdown
# Task 9: End-to-End Churn Prediction

## Problem Statement
Build a complete data science project to predict customer churn and deploy it as a web application.

## Dataset
- Telco Customer Churn dataset
- Target: Churn (Yes/No)

## Approach
1. Data Cleaning
   - Converted TotalCharges to numeric
   - Handled missing values
   - Encoded target variable

2. Feature Engineering
   - Separated numerical & categorical features
   - Applied preprocessing pipelines

3. Model Building
   - Random Forest Classifier
   - Train-test split with stratification

4. Evaluation
   - Accuracy score
   - Classification report

5. Deployment
   - Streamlit app
   - User input → prediction output

## Results
- Accuracy achieved on test data
- Fully functional web app
- Model saved as .pkl file

## Output Files
- churn_model.pkl
- evaluation.csv
- evaluation_report.txt
- app.py
- eda.py

## How to Run (VS Code)

Step 1: Open terminal in task9 folder

Step 2: Install dependencies:
```bash
pip install -r requirements.txt
