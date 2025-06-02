# Naukri_Analysis_Data-Science-Project
Project Overview
This project analyzes job postings from Naukri.com to understand current job market trends, including top hiring companies, in-demand skills, experience requirements, and salary trends. The analysis aims to provide data-driven insights for both job seekers and HR professionals.

Key Objectives
Analyze job postings to identify market trends

Extract insights about top companies, skills, experience, and salaries

Provide actionable insights for job seekers and HR professionals

Dataset
Source: Naukri.csv

Size: 560 job listings

Key Columns:

Company

Experience

Location

Ratings

Salary

Skills

Title

Methodology
Data Understanding & Preprocessing

Cleaned unstructured fields (salary ranges, experience, multi-value skills)

Standardized inconsistent formats

Extracted skills using tokenization and keyword matching

Exploratory Data Analysis (EDA)

Univariate and bivariate analysis

Visualization of key trends

Model Building

Data split into 77% training and 23% testing

Standard Scaler for normalization

Label encoding for categorical variables

Multiple classification models tested (Logistic Regression, Random Forest, SVM)

Hyperparameter tuning with GridSearchCV

Model Deployment

Streamlit interface for no-code predictions

Generic framework for both regression and classification problems

Key Findings
Job Market Trends
Top Hiring Companies: Accenture leads with 30% of postings, followed by Oracle (10%) and BNY Mellon (6.7%)

Top Job Titles: Finance Analyst (43.3%), Senior Analyst, Research Analyst

Experience Requirements: Most postings target mid-level professionals (2-5 years experience)

Top Locations: Chennai, Mumbai, Pune, Hyderabad dominate tech hiring

Skills in Demand
Technical Skills: Python, SQL, Machine Learning, AWS

Finance Skills: Financial analysis, financial reporting, finance expertise

Salary and Ratings
Most salaries fall in the Medium range

Company ratings clustered between 4.0-4.5

High-rated companies generally have fewer reviews

Model Performance
Best Performing Models: Random Forest and Gradient Boosting

Evaluation Metrics: Accuracy score and classification report (precision, recall, F1-score)

Improvements: Feature importance analysis and handling class imbalance could enhance performance

Challenges Faced
Inconsistent data formats in experience, salary, and skills fields

High dimensional categorical variables

Basic skill extraction logic that may miss variations

Overfitting risk with small dataset (560 rows)

Future Improvements
Enhance skill extraction with more sophisticated NLP techniques

Address class imbalance in the dataset

Add performance metrics to the deployment interface

Incorporate feature engineering and scaling in the deployment pipeline

How to Use
The deployed model allows users to:

Select a target column

Train a classification model on the Naukri dataset

Input features (company, experience, job post date, etc.)

Receive predictions about job URLs

Conclusion
This analysis provides valuable insights into the current job market trends on Naukri.com, particularly highlighting:

The dominance of finance and analytics roles

The importance of technical and financial skills

The concentration of opportunities in major metro cities

The effectiveness of Random Forest models for this classification task

The project demonstrates the importance of thorough data preprocessing and exploratory analysis before model building, and shows how machine learning can be applied to job market analysis.

