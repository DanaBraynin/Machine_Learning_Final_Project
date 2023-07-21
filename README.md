# Machine Learning Final Project
This project was done as a final project as part of a Machine Learning course at Tel Aviv University.
We were given information about several features of executable files (.exe)and were asked to build a model that predicts the chance of a particular file to be malicious through static analysis of the files.
This project is a binary classification problem in which we classified files into two categories - is the file malicious (1) or not (0), based on the features in the data set. Some of the features we received are known and some are anonymous.
We were given 60,000 observations that were classified as a malicious/non-malicious file. We analyze the given data, processed it and selected the best model to predict the patterns in the unseen test data.
We achieved a test AUC score of 0.9579 using "XGBoost classifier".
The project is in Jupyter Notebook in Python and Markdown.
