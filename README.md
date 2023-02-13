# C1-Data-Science-Challenge

This repository contains my solution for the  [Capital One Data Science Challenge (https://github.com/CapitalOneRecruiting/DS). The goal of the challenge is to process, analyze synthetic data from Capital One, and implement different predictive models to determine whether a given transaction will be fraudulent or not.

## Data Exploration
Take a first look at the data

## Data Wrangling
- Remove duplicate transactions
- Remove reversal transactions
- Remove multi-swipe transactions
- Remove unuseful attributes 
- Transform attributes

## EDA
- Analyzed cleaned data

## Predictive Modeling
- Decision Tree
- Random Forests
- XGBoost
- LightGBM

## Model with under sample data
Undersample is a technique to balance uneven datasets by keeping all of the data in the minority class and decreasing the size of the majority class. It is one of several techniques data scientists can use to extract more accurate information from originally imbalanced datasets. Here I impelemented the RandomUnderSampler from imblearn library to perform that technique.

## Conclusion
In conclusion, the main problem that I have while working on this dataset is its imbalance. As I have mentioned multiple times, the dataset is highly imbalanced with 0.15% True labels, while the rest are False labels due to the nature of the problem. Therefore, I believe the result would be better if we had more True labeled samples. Another issue I encountered was that attributes seem not correlated with the response variables, making the models hard to learn

## References
[What Is Undersampling? ](https://www.mastersindatascience.org/learning/statistics-data-science/undersampling/)

[GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)

[What is balanced accuracy?](https://statisticaloddsandends.wordpress.com/2020/01/23/what-is-balanced-accuracy/)

[A Data Science Framework: To Achieve 99% Accuracy](https://www.kaggle.com/minhdnguyen/a-data-science-framework-to-achieve-99-accuracy#Step-5:-Model-Data)

[LightGBM model](https://www.kaggle.com/kirshoff/fraud-detection-lightgbm-xgboost)
