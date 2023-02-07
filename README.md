# deep-learning-bank-deposit: Bank Marketing 🏦

Topic: **Development of An Enhanced Deep Learning Model to Predict Client's Intention to Subscribe to the Bank's Term Deposit**

No | Dataset | Information
--- | --- | --- 
1 | URL | https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets?select=train.csv
2 | Dataset Name | Portuguese Bank Direct Marketing 
3 | File Type | csv file
4 | Observation | 45,211
5 | Features | 17
6 | Data label | “Yes” referred to bank clients successfully subscribing to the term deposit. “No” referred to bank clients that rejected the subscription.

# Introduction
## A brief overview into the project domain
- Marketing functions have always been playing a central role in the financial industry, especially in the banking sector
- Retail banks often used direct marketing as a telemarketing strategy to contact potential customers and sell their products
- Crucial for retail banks to ensure that they are targeting groups with a high chance of success

## What more could be done?
- Data analysis. Understand the consumers needs and preferences!
- Leverage on deep learning techniques to make better predictions

## What is the problem statement of the project?
- Retail banks urgently need a reliable and accurate machine learning model as a competitive advantage to help them predict customer intention to subscribe to term deposits
- Offerings of financial products like providing “term deposits” slightly vary from the other retail banks. In other words, every bank offerings are almost identical)

## Aims & Objectives (What do I aim to achive?) 🌟
**The Aims**
- The overall aim of this project is to enhance retail banks’ marketing effectiveness and reduce marketing costs through the development of a reliable deep learning machine learning model to accurately predict bank clients’ possibilities in subscribing to bank term deposit. 

**The Objectives**
- To identify features that play a major role in affecting the bank clients’ intention to subscribe to the bank term deposit. 
- To develop a reliable deep learning technique and predict bank clients’ intention to subscribe to a financial product - bank term deposit.
- To evaluate the performance of the deep learning models with the evaluation metrics benchmarked by past studies.

# Initial Data Exploration & Exploratory Data Analysis (EDA)
- Finding out the following: 
  - What is the data shape? 
  - Are there any missing values? 
  - How many categorical / numerical variables are there?
  - What is the dependent variable, how's the distribution? 
  - Are there any class imbalance issue? 
  - and many more...!
- EDA --> Univariate Analysis & Bivariate Analysis

# Data Pre-Processing
![git_5_dl_pre-process](https://user-images.githubusercontent.com/116934441/216932602-7027758a-9ba6-4247-b911-c63c1e620f30.png)

- Correlation Analysis
- Label Encoding
- One Hot Encoding
  - [Label vs. One-Hot Encoding Short Explaination on Kaggle](https://www.kaggle.com/getting-started/187540)
- Data Partitioning
- Class Re-Sampling
- Data Normalisation
- Feature Selection

# Modelling
## Models Developed
- 1 Baseline Model
- 4 ANN Model
- 2 RNN Model
- 1 LSTM Model

## Proposed Deep Learning Model Flowchart 
![git_7_ann_flow_dl](https://user-images.githubusercontent.com/116934441/217275836-c7187894-b789-437c-b155-70ea8a8b35bc.png)

## Hyperparameters Involved
- Learning Rate ✅
- Epoch ✅
- Dropout ✅
- Batch Size ✅

# Performance Evaluation
![git_6_perform_eval)dl](https://user-images.githubusercontent.com/116934441/216936051-bd8b7058-385c-460f-baaa-5db28bd8267f.png)

## Critical Analysis
- Among all the models developed, the highest accuracy of 90.29% ✅ was achieved by model 4 
- Class imbalance issue was resolved with the application of the SMOTE technique
  - [What is SMOTE technique?](https://towardsdatascience.com/smote-fdce2f605729)
- Some evaluation metrics carry more weight as compared to others
- Focus of the retail bank should be on correctly predicting the bank clients that would subscribe to the deposits 
- Hence, high sensitivity or TPR will be much more important
  - Banks prefer to correctly predict clients that would most likely purchase their term deposits
  - Banks stand to lose out more in terms of the sales opportunity if highly potential clients are missed out by the model 
  - On the other hand, banks could afford to wrongly identifying not interested clients as highly likely to purchase





