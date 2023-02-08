# EmployeeAttrition
A data science project exploring the impact of different attributes of IBM HR Analytics Employee Attrition &amp; Performance dataset in employee attrition.


## Introduction
Employee attrition is a big issue in the HR industry. The loss of employees causes organizations to face financial losses, reduce productivity, and prolong the hiring process. Employee attrition is also very costly for institutions because they are expected to find and hire new employees from scratch. To understand the causes of employee attrition and its impact on organizations, this blog will apply data science methods to IBM’s HR Analytics dataset to understand which factors have a great impact on employee attrition. Then using machine learning algorithms on Scikit-Learn, we will predict employee resignation. This blog will focus on two main problems:

1. Predicting employee turnover using machine learning algorithms
2. Understanding the factors that contribute to employee turnover.

## About the Dataset
The IBM HR Analytics Employee Attrition & Performance dataset is available on Kaggle.com. The dataset was created by Pavansubhasht, who used the data from the IBM Institute for Business Value (IBV) to model employee attrition and performance.

This dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?resource=download.)

## About the Repository
This repository contains a set of jupyter notebooks for each phase of the project.

### Phases of the Project
This project includes the following phases:

1. **Data Cleaning Phase** - In this stage, the dataset will be downloaded, previewed, and assesed for potential data formatting problems. It is in this stage where missing data, incorrect values and data forats will be dealt with.

2. **Data Familiarization Phase** - In this stage, the dataset will be visualized in order to identify potential problems during modelling. At this stage, histograms, ECDFs, heatmaps, and more will be used to detect potential problems.

3. **Data Pre-processing** - In this stage, the dataset will be formatted so that it can be used in machine learning model. That is, all data should be encoded numerically. At this stage, one-hot encoding and ordinal encoding will be used to encode non-numeric data.

4. **Feature Selection** - Once the dataset is ready, we will conduct feature selection to identify which among all of the feautures were helpful in modelling our machine learning algorithms

5. **Machine Learning Modelling** - With features carefully selected we can now proceed to the exciting part -- machine learning. In this stage, a series of machine learning model will be trained, evaluated, and compared. The objective of this phase is to find a good model that will predict reliably which employee is most likely to leave the company.

6. **Model Understanding** - At this phase, we will utilize one of the more explainable models developed from the previous phase. The goal is to quantify the relationship of each of the selected features with employee attrition.

7. **Conclusions and Recommendations** - A closing note summarizing the results, findings, and recommendations.