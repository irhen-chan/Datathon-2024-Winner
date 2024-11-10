![1726818696694](https://github.com/user-attachments/assets/8c0e79be-9e70-44b4-a594-e6a252d33177)
# 🏆 2024 Inter Uni Datathon Winning Project

## Overview
First place winner at the 2024 Inter Uni Datathon (MONASH x USYD x UNSW x UNIMELB x MACQUARIE), organized by Citadel Securities and H20.ai. This repository showcases the code and methodology used by Team Error 404: Not Found to build a high-accuracy fraud detection model that achieved an impressive 99.9% accuracy.

## Problem Statement
The objective was to investigate and mitigate revenue loss caused by fraudulent activities in financial transactions, where 36.4% of the 2023 transactions were fraudulent, amounting to AUD 1,739,455.09 AUD.

## Key Highlights
#### Model Achieved: 99.9% accuracy with a Random Forest Classifier (RFC).
#### Key Techniques: Hyperparameter tuning with GridSearchCV, feature importance analysis, and robust data cleaning.
#### Outcome: Detected 99% of fraudulent transactions, potentially preventing fraud worth AUD 1,739,455.09.
## Presentation
#### Insights were presented to a panel of senior risk management executives, showcasing strong data-driven decision-making and communication skills.
#### link: https://www.canva.com/design/DAGQvodJiKM/tRwLJnKc4kEMcOJSGbV1BA/edit?utm_content=DAGQvodJiKM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## Project Insights
### Top Features:
#### Hour of transaction: Most significant indicator with 0.449 importance.
#### Transaction Type: Withdrawal transactions showed high correlation with fraud.
#### Transaction Time: Number of fraudulent transactions at odd hours from 12 am to 5 am were high.
#### Location: Transactions outside Melbourne had high fraud ratings.
### Approach and Methodology
#### 1. Data Cleaning
#### Age Correction: Fixed erroneous age values.
#### Currency Conversion: Standardized all amounts to AUD.
#### Location Normalization: Harmonized transaction locations to key Australian cities.
#### 2. Model Selection and Tuning
#### Chose Random Forest Classifier for its balance of simplicity and high performance on categorical variables.
#### Applied GridSearchCV for optimal hyperparameter tuning.
#### 3. Results
#### Precision: 99.85%
#### 99% of the fraudulent transactions in 2023 were detected. Our model would prevent fraud totalling 1,739,455.09 AUD.

### Future Steps
#### Real-time Flagging: Build a feedback loop for continuous improvement.
#### Model Testing: Experiment with advanced models like XGBoost and CatBoost.
#### Deployment: Implement a scalable real-time fraud detection system.

## Instructions to run the models
### Main notebooks : 
- preprocess.ipynb
- feature_engineering.ipynb
- solutions.ipynb

1) Make a folder called landing in the data folder like so /data/landing
2) Download the inter-uni-datathon-2024-vic dataset and extract in /data/landing folder
3) Run the following programs in order (All jupyter notebook files):
- preprocess.ipynb
- feature_engineering.ipynb
- solutions.ipynb
4) The results would be in the results folder


## Team Members
#### Chin Chee Henn
#### Kelly Truong
#### Mahathir Lutfullah
#### Nihaal Ahmed
#### Snehar Singh


