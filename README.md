# Customer Feedback & Retention Prediction in Online Food Delivery

## 1. Project Title & Team Information
 **Project Title: Customer Feedback & Retention Prediction in Online Food Delivery Platforms
 **Track: Machine Learning & Predictive Analytics (Milestone 1)
 **Team Member:
AREEN AHMAD METQAL ALJARRAH
ABDALLAH MA'MON SULEIMAN ALDARADKEH
Osama Jamal Yousef Nayfeh
Rama Ahmad Mohammed AlJufout
Ra'fat Osama Falah Aldiabat
 
  **Date:September 2026

---

## 2. Business Problem Statement
Online food delivery aggregators operate in an intensely competitive environment with high customer acquisition costs and low switching barriers. A critical operational challenge is silent customer churn—where dissatisfied users stop ordering without submitting formal complaints. 

This project builds a predictive machine learning solution to detect at-risk customers early using customer demographics, income brackets, and regional delivery patterns, enabling platforms to deploy proactive retention incentives before customer drop-off.

---

## 3. Project Objectives & Success Criteria
1. **Exploratory Data Analysis (EDA): Identify the key demographic and regional drivers correlated with customer sentiment.
2. **Predictive Modeling: Train and evaluate supervised classification models (such as Logistic Regression and Random Forest) to predict customer sentiment (`Positive` vs. `Negative`).
3. **Target Success Metric: Achieve an **F1-Score ≥ 80%** specifically on the minority class (`Negative` feedback) to overcome dataset class imbalance.

---

## 4. Dataset Overview & Feature Dictionary
**Source: Bangalore Online Food Delivery Customer Survey (Kaggle Verified Dataset).
 **Dataset Size: 388 customer records, 12 operational features (after removing 1 duplicate column).
 **Missing Values: 0 missing values (100% complete schema).
 **Target Variable: `Feedback` (Binary Classification):
  * **Positive: 317 records (~81.7%)
  * **Negative: 71 records (~18.3%)
