# credit_risk_classification

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Table of contents:
Credit_Risk - main folder containing code and dataset
Resources - contains lending_data.csv(dataset)
credit_risk_classification.ipynb - contains code used in assignment
README.md - contains analysis and description of processes

Analysis:
Explain the purpose of the analysis.
This analysis aims to construct a predictive model for classifying credit risk, leveraging financial data to determine the likelihood of a loan applicant having either a healthy loan or a high-risk loan. The objective is to anticipate whether applicants are prone to defaulting on payments or maintaining a stable repayment status.

Explain what financial information the data was on, and what you needed to predict.
The dataset provided comprehensive financial details for each applicant and loan, encompassing factors such as loan size, interest rate, income, debt-to-income ratio, number of accounts, presence of derogatory marks, and total debt. This dataset was utilized to forecast the likelihood of an applicant defaulting on their loan payments, thereby categorizing it as a high-risk loan.

Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The model aims to predict the loan status, with two potential outcomes: "healthy loan" or "high-risk loan." Upon examining the distribution of these status variables, it's evident that there are more instances of healthy loans (75,036) compared to high-risk loans (2,500).

Describe the stages of the machine learning process you went through as part of this analysis.
The machine learning journey commenced with data cleansing and exploratory analysis to gain insights into the dataset. Features for both independent (X) and dependent (y) variables were selected for testing. Subsequently, the dataset was split into training and testing sets. The model was then fitted, and its performance evaluated using the test sample, considering accuracy and other relevant metrics.

Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
We utilized logistic regression, a widely employed classification algorithm, to model the credit risk.

Results:
**Accuracy Scores:**
- Overall accuracy: 0.99

**Precision and Recall Scores:**
- Class 0 (Healthy Loan):
  - Precision: 1.00
  - Recall: 0.99
- Class 1 (High-Risk Loan):
  - Precision: 0.85
  - Recall: 0.91

Summary:
  **Summary of Machine Learning Model Results:**

Following a thorough evaluation, the logistic regression model emerges as the top performer for credit risk classification. Here's a summary of its performance:

1. **Performance Assessment:**
   - The logistic regression model demonstrates superior precision, recall, and accuracy compared to alternative models.
   - With perfect precision (100%) for predicting healthy loans (class 0) and high recall (91%) for identifying high-risk loans (class 1), it exhibits exceptional predictive capabilities.
   - Its overall accuracy of 99% underscores its effectiveness in accurately classifying credit risk instances.

2. **Relevance to Problem Solving:**
   - The logistic regression model's strong performance is particularly relevant in the context of credit risk assessment.
   - Effective detection of high-risk loans (class 1) is crucial for mitigating potential financial losses, and the model's high recall ensures the identification of actual high-risk instances.

**Recommendation:**
Given its outstanding performance and alignment with the problem domain, the logistic regression model is the recommended choice for credit risk classification tasks. Its robust predictive capabilities, balanced precision, recall scores, and high accuracy make it a reliable tool for identifying both healthy and high-risk loans accurately.

