# CIS-5560---INTRO-TO-BIG-DATA-SCIENCE

**Introduction**

This project focuses on applying machine learning algorithms to combat money laundering.

Using the IBM Transactions dataset, the objective is to develop a predictive model capable of accurately classifying transactions as suspicious or legitimate based on various features.

**Data Set Used**

The dataset, sourced from Kaggle.com, comprises 8GB of data in CSV format, specifically the "LI_Medium_Trans.csv" file. 

It includes crucial details such as timestamps, bank information, account details, amounts, and a column indicating whether the transaction is flagged as suspicious.

**Technical Specifications**

The project leverages Hadoop version 3.1.2, PySpark version 3.0.2, and Databricks Community Version 10.4LTS for processing and analysis. 

The technical specifications include information on HDFS, Oracle, Hadoop, and Databricks setups.

**Classification**

Six machine learning algorithms - Logistic Regression, Gradient Boost Tree, Decision Tree, Random Forest, Factorization Machine, and Support Vector Machine - are implemented and evaluated. 

Metrics such as precision, recall, and feature importance are employed for model evaluation.

**Data Cleaning**

Cleaning steps include converting hexadecimal values to integers for consistency, enhancing data integrity, and preparing the dataset for analysis.

**List of Algorithms Used**

-Random Forest (RF): Achieved precision - 0.06, recall - 0.48, and AUC - 0.81.

-Gradient Boost Tree (GBT): Demonstrated precision - 0.0936, recall - 0.979, and AUC - 0.9077.

-Factorization Machine (FM): Displayed precision - 0.0422, recall - 0.7868, and AUC - 0.7461.

-Support Vector Machines (SVM): Showed precision - 0.0285, recall - 0.5, and AUC - 0.5.

-Logistic Regression (LR): Indicated precision - 0.0285, recall - 0.5, and AUC - 0.5296.

-Decision Tree Classifier (DT): Presented precision - 0.0285, recall - 0.5106, and AUC - 0.6415.

**Comparison Table**

The provided table compares algorithm performance based on various metrics, including AUC, computation time, precision, and recall.

**Results**

The analysis highlights Gradient Boost Tree and Random Forest as the most effective algorithms for detecting suspicious transactions. 

However, optimization and further exploration of machine learning techniques are suggested for improved performance. 

The project contributes to advancements in combating financial crimes and offers insights for AML practitioners.
