# LOAN APPROVAL PREDICTION MODEL 

# Project overview
The project aims to predict the eligibility of loan applicants based on various features such as income, 
education, employment status, and credit history.
It uses machine learning models to classify applicants as either eligible or not for loans. 
The dataset consists of information on 614 loan applicants and includes missing values that were handled during the preprocessing stage

# Dataset features
.Loan_ID: Unique Loan Identifier
.Gender: Male/Female
.Married: Applicant's marital status
.Dependents: Number of dependents
.Education: Applicant's education level (Graduate/Not Graduate)
.Self_Employed: Whether the applicant is self-employed
.ApplicantIncome: Applicant's income
.CoapplicantIncome: Co-applicant's income
.LoanAmount: Loan amount requested
.Loan_Amount_Term: Term of loan in months
.Credit_History: Whether the applicant has a credit history (1 for Yes, 0 for No)
.Property_Area: Urban, Rural, or Semiurban
.Loan_Status: Whether the loan was approved or not (Y/N)

# Employed Libraries
1. pandas: Data manipulation and analysis
2. numpy: Numerical computations
3. matplotlib: Data visualization
4. Seaborn: Data visualization as well
5. sklearn: Machine learning models (Decision Tree, Naive Bayes)
6. StandardScaler: Data normalization
7. LabelEncoder: Encoding categorical variables into numerical variables
# Data Preprocessing
  - Handled missing values in columns such as #Gender, # Married, #Dependents, # Self_Employed, and # LoanAmount by filling them with appropriate statistical measures (mode or mean).
  - Created new features #TotalIncome and #TotalIncome_log to combine applicant and co-applicant incomes for better model performance.
  - Normalized features using #StandardScaler.

# Data Modoling
Two models were used to predict loan eligibility:

- Decision Tree Classifier
      .Accuracy: 69.92%
 - Naive Bayes Classifier
      .Accuracy: 81.30%

# Results
The Naive Bayes classifier outperformed the Decision Tree in predicting loan eligibility, with an accuracy of 81.3%. 
Further improvements could involve tuning the models, handling class imbalance, 
and testing other machine learning algorithms.

# Use it with:
1. cloning the repository
2. install all the listed libraries in above using
    . pip install (all libararies).

Kindly, help me to improve my working by suggesting me or comments on my works. via: https://www.linkedin.com/in/samuel-bizimana-0849b026b/ or email me: kabashibizimana@gmail.com
   
