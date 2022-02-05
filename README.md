# Arvato-Project
Customer Segmentation Report for Arvato Financial Services


Installation and Library Used

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Sklearn

These libraries can be installed using simple pip command or conda (if you are using Jupyter).

Project Motivation:
This project is a part of my course curriculum in UDACITY DataScientist NanoDegree.

File Description

This project consists of following files:
1. Python File consists of the working of the Recommendation Engine
2. README

As the data is not for public use, I will not be sharing the data.

How to Interact with the project:

This project is divided into following tasks:

0. Get to Know the Data : It will involve the cleaning of our Dataset, Imputing Null Values and Scaling the data.
1. Customer Segmentation Report : It involves Features decomposition and clustering to get the understanding of variability in the dataset.
2. Supervised Learning Model : This will build our prediction model on train dataset.
3. Kaggle Submission: This is the final model to be applied to Test dataset.

Summary:
In this project, we will analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. we'll use unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, we'll apply what we've learned on a third dataset with demographics information for targets of a marketing campaign for the company, and use a model to predict which individuals are most likely to convert into becoming customers for the company.

We find that Gradient Boosting Classifier for supervised learning is the best model, however, it was the slowest of the lot for training. The second best is AdaBoost Classifier and it took lesser time. Upon further tuning of Hyper parameters using GridSearch CV, Adaboost performed better.

Licensing, Authors, Acknowledgements, etc.

Thanks to UDACITY for providing various starter codes as well as tests. Referred to StackOverflow as well as previous UDACITIANs for help in queries.

Reference:

365DataScience: https://365datascience.com/tutorials/python-tutorials/pca-k-means/

StackOverflow: https://stackoverflow.com/questions/52573275/get-all-items-in-a-python-list
