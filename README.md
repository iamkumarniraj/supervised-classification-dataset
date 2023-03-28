# supervised-classification-dataset 

Introduction


A supervised classification dataset that includes details about credit card transactions is the Credit Card Fraud Detection dataset. The objective of this dataset is to create a model that can correctly predict if a transaction is fraudulent or not based on several characteristics including time, amount, and V1-V28 variables. 284,807 transactions total in the dataset, 492 of which are fake. Because of the extreme imbalance in the information, there are far fewer fraudulent transactions than legitimate ones.


This README file contains information about the dataset and the steps involved in preprocessing the data, performing exploratory data analysis (EDA), testing and evaluating the model, and finalizing the model for making predictions.

Dataset Preprocessing
The first step in working with any dataset is to preprocess the data. In this dataset, the following steps were taken:

Handling missing values: Since the dataset had no missing values, this step was not necessary.
Managing imbalance data: Only 492 out of 284,807 transactions in the sample were fraudulent, which is severely unbalanced. Having this imbalance might lead to issues with the model's training. We can utilize methods like undersampling, oversampling, or a mix of the two to overcome this problem. Here, we employed the undersampling technique, creating a second dataframe with the same number of valid transactions as fraudulent ones.

Scaling features: It is required to scale the features in order to make them comparable because the characteristics in the dataset have various sizes. We scaled the features in this dataset using both normalization and standardization for column time and amount.

Analyzing Exploratory Data
Understanding the dataset and finding patterns or links between the characteristics requires the use of EDA. The following EDA stages were carried out on this dataset:

Data visualization: In order to see the data clearly and spot trends, we displayed numerous graphs and charts. To see their distributions, for instance, we generated a combination plot of the time and quantity characteristics.
The most crucial elements for the model were determined by analyzing the association between various features and the target variable.

Testing and Evaluation of Models
The model has to be built and evaluated after that. To create the model for this dataset, we employed a variety of machine learning techniques, including Logistic Regression, Random Forest, DecisionTree, and SVM. Several measures, including accuracy, precision, recall, and F1-score, were used to evaluate the model.


Finalizing the Model for Prediction
The final stage is to finish the model for generating predictions after testing and evaluation. Based on the assessment measures, we chose the model that performed the best in this dataset. We didn't undertake any hyper parameter adjusting because we had already achieved a respectable accuracy level.


Conclusion
The Credit Card Fraud Detection dataset calls for handling unbalanced data and feature scaling because it is a supervised classification dataset. While testing and assessing the models is required to choose the best-performing model, EDA aids in analyzing the dataset and spotting trends. After completing all of these processes, we discovered that the Logistics Regression model performed the best of all the models we explored.

 

