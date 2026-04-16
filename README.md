# Data_Science_Project
# Credit Risk Prediction Project (Python)

## Project Overview

This project develops a machine learning model to predict whether a borrower is likely to experience financial distress within the next two years. The solution uses borrower-level credit behavior variables such as debt ratio, credit utilization, delinquency history, and income level.

The objective of this project is to demonstrate a practical **credit risk analytics workflow** similar to those used in modern banking environments for:

* Early warning systems
* Loan portfolio monitoring
* Customer risk segmentation
* Lending decision support
* Branch performance analytics

This project is designed for portfolio presentation in **banking analytics, financial risk modeling, and data science roles**.

---

## Dataset Description

Dataset: `cs-training.csv`

Target Variable:

**SeriousDlqin2yrs**

* 1 = Borrower experienced financial distress within 2 years
* 0 = Borrower remained financially stable

Feature Variables:

| Feature                              | Description                              |
| ------------------------------------ | ---------------------------------------- |
| RevolvingUtilizationOfUnsecuredLines | Ratio of credit balance to credit limits |
| age                                  | Borrower age                             |
| NumberOfTime30-59DaysPastDueNotWorse | 30–59 days delinquency frequency         |
| DebtRatio                            | Monthly debt payments / monthly income   |
| MonthlyIncome                        | Borrower monthly income                  |
| NumberOfOpenCreditLinesAndLoans      | Active credit accounts                   |
| NumberOfTimes90DaysLate              | Severe delinquency count                 |
| NumberRealEstateLoansOrLines         | Mortgage and housing loans               |
| NumberOfTime60-89DaysPastDueNotWorse | Mid-level delinquency frequency          |
| NumberOfDependents                   | Number of dependents                     |

---

## Project Objectives

This project aims to:

* Clean and preprocess real-world financial dataset
* Explore borrower behavioral risk patterns
* Identify high-risk credit indicators
* Build classification model for default prediction
* Evaluate model performance using standard ML metrics
* Generate interpretable feature importance insights

---

## Tools & Technologies Used

Programming Language:

* Python

Libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Development Environment:

* Jupyter Notebook / VS Code / Google Colab

---
## Project Structure

Credit_Risk_EDA_Project/
│
├── Credit_Risk_EDA.ipynb
├── cs-training.csv
└── README.md

## How to Run the Project

1. Open notebook in Google Colab
2. Upload dataset
3. Run all cells

View outputs:

* Charts
* Accuracy score
* Risk classification report

---

## Project Workflow
-Data loading
- Data cleaning
- Missing value analysis
- Outlier detection
- Visualization
- Correlation analysis

### Step 1: Data Extraction

The dataset is loaded from a /content/drive/MyDrive/Dataset/ .

### Step 2: Data Cleaning

Performed:

* Removal of index column
* Handling missing income values
* Handling missing dependent values

### Step 3: Exploratory Data Analysis (EDA)

EDA includes:

* Dataset summary statistics
* Target variable distribution
* Correlation heatmap
* Risk indicator visualization

### Step 4: Feature Engineering

Features prepared for model training:

* Target variable separation
* Train-test dataset split
* Feature scaling using StandardScaler

### Step 5: Model Development

Model Used:

Logistic Regression

Reason:

* Interpretable
* Suitable for binary classification
* Widly used in banking credit scoring

### Step 6: Model Evaluation

Evaluation metrics:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

---

## Key Insights from Analysis

Model identifies strong predictors of borrower financial distress:

High Risk Indicators:

* High credit utilization ratio
* High debt-to-income ratio
* Frequent past-due payment history
* Low monthly income
* Large number of dependents

These indicators align with industry-standard credit scoring logic used in retail lending.

---

## Business Value (Banking Perspective)

This solution supports:

-Early Warning System Development

-Helps identify customers likely to default before risk materializes.

-Loan Portfolio Monitoring

-Supports segmentation of risky vs safe borrowers.

-Branch-Level Risk Tracking

-Helps branches monitor borrower quality.

-Credit Approval Decision Support

-Improves consistency in lending decisions.

-Customer Risk Ranking

-Allows prioritization of follow-up and intervention.

---

## Model Output Example

Outputs generated:

* Default prediction probability
* Classification labels
* Feature importance visualization
* Correlation heatmap

These outputs can be integrated into dashboards or reporting pipelines.

---

## Future Improvements

Potential upgrades:

* Random Forest classifier
* Gradient Boosting model
* XGBoost risk scoring
* ROC-AUC optimization
* Cross-validation tuning
* Hyperparameter optimization
* Deployment as web-based scoring tool
* Integration with Power BI dashboards

---


## Project Value

This project demonstrates capabilities in:

* Financial data analytics
* Credit risk modeling
* Machine learning classification
* Data preprocessing
* Business interpretation of ML outputs

Suitable for roles in:

* Banking analytics
* Risk management
* Data science
* Credit portfolio supervision

---

## Author

Seleshi Mekonnen Damtew

MBA | MSc Computer Science |BA Managment| Banking Professional (CSM) | Data Analytics Enthusiast

Specializations:

* Banking performance analytics
* Digital banking KPI tracking
* Website developer

