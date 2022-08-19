# RFDs Feature Selection for Fake Account

Fundamentals of Data Science and Machine Learning Project a.a. 2021/2022
University of Salerno

Social networks allow you to share information between users of all ages, at any time and in any part of the world.
Social interaction platforms like Instagram, Twitter, Tumblr, etc. have a significant impact on the daily lives of their users and society as a whole.
The popularity of a profile can be increased by buying fake followers at a low price.
This can be dangerous as it could be used to gain popularity to promote particular services, deceptive sites, scam services etc.

It is therefore necessary to define the fake profiles present on the various social networks.

## Purpose of the project
The aim of this project is to test Feature Selection techniques, known in literature, on the set of Relaxed Functional Dependencies (RFDs) to verify their validity.
The extrapolation of RFDs starting from a dataset leads to a conspicuous increase of the columns within the dataset and therefore of the Features, but it is not certain that all these new features contribute to the construction of a machine learning model that gives better results.

For this reason, the purpose is to use through Feature Selection techniques, which of the features calculated by RFD, in addition to the 15 basic features, are important in the training process of a Machine Learning model.

**Three Feature Selection techniques selected for experimentation:**
1. Variance Filtering Method
2. Correlation Bades Filtering Method
3. Boruta Method

## **How to re-execute Feature Selection techniques**
* Open the Python notebook and execute the first cell
* In the third cell select the dataset you want to use
* Specify the path and execute cells 4, 5, 6 and 7 to perform String data transformations and perform data splitting
* Position yourself after the textual cell that explains the various Feature Selection techniques (this is in Italian)
* Execute the various cells of Python code
* Each technique ends with the obtaining of the new training and testing datasets, so if you want to rerun any model you have to change the parameters passed to the various .fit () methods.

(For the Variance Filtering method, the code was rewritten to rerun the AdaBoost model, while for the Correlation Filtering method, the code was rewritten to rerun the kNN model on the five feature subsets.)

