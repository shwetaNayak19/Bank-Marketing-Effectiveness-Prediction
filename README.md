# Bank-Marketing-Effectiveness-Prediction

# Creating a model to predict if the client will subscribe a term deposit.

Tags: Data Science, Data Analysis, Machine Learning, Logistics regression, Class Imabalance.

![image](https://user-images.githubusercontent.com/105973170/190308939-c830f19b-90c2-46c6-ae40-8a1aa3bd6a90.png)

# Summary

# Introduction :-

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y).

# Working Process :-

In this project we present our analysis of the data. We have employed some of the most widely used classification algorithms for this project namely;

Logistic Regression
Decision Tree
Random Forest
XGBoost

Data from a marketing campaign run by Portugal is examined. The campaign’s aim was to increase customers’ subscription rates to fixed-term deposit products. Using knowledge a number of machine learning algorithms are implemented to answer the question: How can banks successfully market these products in the most efficient way possible and with the highest possible rate if success?

# Process Involved:-

We followed step by step process for the project like data collection, data cleaning, EDA, Visualization, Model Training and Testing, Hyperparameter Tuning and Evaluation. In the first step we collected data and explored data set to get a rough idea about data.

In EDA we divided analysis into several part to get better idea about data like we checked distribution of numerical and categorical data checked relationship between independent and dependent variable. We used box plots to visualize how each feature was distributed over each of the two target classes. This gave us a clear idea as to which variable was contributing more. We also used bar plot to check the distribution of category of the independent variable into dataset and also checked their relationship with dependent variable to understand what factors are contributing for different cause.

# Feature Engineering:-

After that we perform feature engineering, in feature engineering we created some new feature form available features with the goal of simplifying and speeding up data transformation while also improving model performance. Then we used oversampling technique to handle class imbalance to make classes even for training model.

After feature engineering we selected feature to use to train our model and encoded categorical variables as ML model works with numerical data to do computation. We used label encoding and one hot encoding.

# Conclusion

As our data was highly Imbalance, We used Random Over Sampler Technique to balance our training set before training model. Finally we started the machine learning part on the choosen feature subsets, did cross validation for each of the models' hyperparameters and recorded the performance in each case into a compact dataframe. The evaluation metrics we chose for our project include roc_auc score, precision, recall, f1-score Benchmarked XGBoost Classifier algorithm against Logistic Regression, Decision Tree and Random Forest.
