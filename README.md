# Identifying Recruitment Targets with Machine Learning Models

### Objective
A recruiting team has been tasked to hire new members for their company's Data Science department from a pool of candidates currently enrolled in a skills development program. The traditional selection process of combing through the enrollees and manually weighing all the pros and cons to decide who to target consumes a lot of time and resources and a mroe sophisticated system is needed. The recruiting team would like a model to be built that will highlight the enrollees who are most likely to be interested in a career change and therefore should be targeted for recruitment. The model must be accurate to at least 80% and focus on the recall score of it's classification to ensure as few potential candidates are slipping through as possible. The recruitment team would like a ranked list to work off of once the model is completed. The recruiting team has provided a list of enrollees that includes various pieces of information about them and whether they would be considered a target or not along with a preliminary list of enrollees that need to be classified.

### Introduction
This project will walk through the process of building and testing various machine learning models to accomplished the objective stated above. It begins with null value treatment followed by exploratory data analysis and feature engineering. We then build and test two linear models, logistic and support vector, as well as K-nearest Neighbors, Decision Tree, Random Forrest, and finally a bagged model. Each model goes through hyperparameter optimization and some cross validation. These models are then compared based on their accuracy, precision, recall, and run time to determine the best fit for our objective.

### Conclusion
Throughout this project many different model types and configurations were tested to produce a KNN / Decision Tree ensemble model that will correctly identify recruitment targets with an accuracy of 82%. This model runs and produces a ranked list in much less time than a traditional manual strategy would while using less resources. This increase in efficiency will allow the recruiting department to focus their time and energy on reaching out to and interviewing the enrollees who are the most likely to change jobs. This project demonstrates how data science and machine learning can be used to support and augment departments throughout a company's structure with the goal of increasing efficiency by automating menial tasks to save time and free up resources.

### Concepts
* Null Value Treatment
* Univariate Analysis
* Feature Celaning and Manipulation
* SMOTE Oversampling
* Recursive Feature Reduction
* Logistic Regression
* Support Vector Classification
* K-Nearest Neighbors
* Decision Trees
* Random Forest
* Bagged Voting Classifier (Ensemble Model)
* Hyper Parameter Optimization
* Model Application and Product Delivery
