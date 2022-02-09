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

Brief Description of the DATA

There are four data files associated with this project:

    Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
    Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
    Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
    Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. Use the information from the first two files to figure out how customers ("CUSTOMERS") are similar to or differ from the general population at large ("AZDIAS"), then use your analysis to make predictions on the other two files ("MAILOUT"), predicting which recipients are most likely to become a customer for the mail-order company.

The "CUSTOMERS" file contains three extra columns ('CUSTOMER_GROUP', 'ONLINE_PURCHASE', and 'PRODUCT_GROUP'), which provide broad information about the customers depicted in the file. The original "MAILOUT" file included one additional column, "RESPONSE", which indicated whether or not each recipient became a customer of the company. For the "TRAIN" subset, this column has been retained, but in the "TEST" subset it has been removed; it is against that withheld column that our final predictions will be assessed in the Kaggle competition.

For more information about the columns depicted in the files, two Excel spreadsheets provided. 

1. DIAS Information Levels - Attributes 2017.xlsx is a top-level list of attributes and descriptions, organized by informational category.
2. DIAS Attributes - Values 2017.xlsx is a detailed mapping of data values for each feature in alphabetical order.


Summary:
In this project, we will analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. we'll use unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, we'll apply what we've learned on a third dataset with demographics information for targets of a marketing campaign for the company, and use a model to predict which individuals are most likely to convert into becoming customers for the company.

We find that XGBoost Classifier for supervised learning is the best model. Upon further tuning of Hyper parameters using GridSearch CV, we improved our model to some extent.

Licensing, Authors, Acknowledgements, etc.

Thanks to UDACITY for providing various starter codes as well as tests. Referred to StackOverflow as well as previous UDACITIANs for help in queries.

Reference:

365DataScience: https://365datascience.com/tutorials/python-tutorials/pca-k-means/

StackOverflow: https://stackoverflow.com/questions/52573275/get-all-items-in-a-python-list
