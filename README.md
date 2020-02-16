# Credit-risk-analysis

The objective of Credit Risk Analysis project is to put ourselves in the shoes of a issuer and manage credit risk by using the past data and deciding whom to give the loan to in the future. Model has to analyzing the XYZ Co-operation Data to analyze and detect defaulters by building models on data from June 2007 to May 2015 and testing it on data from June 2015 to December 2015. Based on the accuracy of each model we can determine how good a model is for predicting that a person applying for loan will default or not.

# Need of the study

In Credit Risk Analysis, The purpose of the project is to predict whether a borrower will default or not, so that investors can avoid those borrowers using manual investing feature provided by lending club. This, however, does not necessarily lead to highest return on investment because by completely avoiding potential defaults, one also avoid riskier loans that may lead to higher return on investment even though they default at some point in the future. In order to maximize return on investment, one needs to optimize return on investment instead. In this project, we work on the simpler problem that is to predict loan defaults.

0 represents – Not Defaulter
1 represents – Defaulter

# Data Sources

The provided dataset corresponds to all loans issued to individuals in the past from 2007-2015. The dataset has 855969 observations and 73 features. The data contains the indicator of default, payment information, credit history, etc. Customers under ‘current’ status have been considered as non-defaulters in the dataset. We have also been provided with a Data dictionary that best describes the features.

The dataset has quite a lot of missing values and the figures can be considered as ground truth, but lots of columns are irrelevant, very sparse or non informative. Moreover, the dataset is unbalanced.

# Tools & Techniques

Tools: python 3.7.2, Jupyter Notebook, Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, Scipy.

Techniques: Logistic regression, Decision Tree, Random Forest Classifier, Gradient Boosting Classifier
