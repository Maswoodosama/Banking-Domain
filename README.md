# Banking-Domain
Customer Credit Risk Scoring using Banking Data

# Problem Statement:
Objective:
To build a model that predicts whether a bank customer is likely to default or pay back a loan using diverse data sources such as customer profiles, geographic scores, behavioral data, and risk weights.

This is a classification problem, where the target is to classify a customer as good or bad (likely defaulter or not).

Built a Loan Defaulter Prediction model using credit history, income, and behavioral data of customers.

Applied data preprocessing and feature engineering using pandas, groupby, and lambda logic.

Trained and tuned a Logistic Regression model, achieving 99.91% accuracy and F1-score of 1.00 on test data.

Implemented an automated training workflow to streamline model reproducibility.

Helped financial institutions reduce potential losses by identifying high-risk loan applicants early.



# Data Sources:
The project involves multiple CSV files:

train.csv: Main training dataset

test_share.csv: Test dataset

Geo_scores.csv: Location-based risk scores

instance_scores.csv: Behavior-based scores

Lambda_wts.csv: Feature-wise risk weightage

Qset_tats.csv: Questionnaire set performance (probably assessment scores)

# Tech Stack Used:
Python

Pandas, NumPy for data handling

Matplotlib, Seaborn for EDA/visualization

Scikit-learn for modeling

# Performance Metrics:
Train Accuracy: 99.92%

Test Accuracy: 99.91%

F1-Score: ≈ 1.00 (Perfect, based on classification report lines)

