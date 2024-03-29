# SYRIA TELECOM CUSTOMER CHURN

This project focuses on analyzing customer churn for Syria Telecom, aiming to understand the factors influencing customer attrition and develop strategies to reduce, how much money is lost. ( This is a binary classification problem.)

PROBLEM STATEMENT

The primary challenge at hand involves crafting a predictive framework capable of precisely pinpointing customers at the verge of churning from SyriaTel's offerings. By harnessing historical customer data and pertinent variables, the aim is to construct a classifier adept at distinguishing between customers inclined to maintain their subscriptions and those inclined to churn imminently.
Objectives:

1.Prediction: Forge a robust binary classification model for precise customer churn prediction.

2.Uncover Key Drivers: Identify and scrutinize the pivotal factors influencing customer churn.

3.Strategic Retention Initiatives: Furnish actionable intelligence to facilitate the implementation of targeted retention tactics for vulnerable customers.

4.Revenue Safeguarding: Mitigate revenue erosion by curtailing the exodus of customers discontinuing services.

kaggle datasets download -d becksddf/churn-in-telecoms-dataset


## Description

To provide a more detailed description of encoding categorical variables for machine learning projects, it is essential to understand that categorical variables are those that represent categories rather than numerical values.
One Hot Encoding: Represents each category as a binary vector.
Machine learning algorithms require numerical data; hence, encoding categorical variables is crucial for model building.
The SyriaTel Customer Churn dataset provides valuable insights into predicting customer churn for the telecommunications company, SyriaTel. This README aims to provide an overview of the dataset, its context, methodology, results, and future recommendations based on the analysis conducted.
Context of Project
The project focuses on analyzing the churn dataset from the telecom industry to predict customer churn and understand the key factors driving churn for SyriaTel. The dataset includes information on customer behavior, plan details, and churn status.
Data
The dataset contains information on 3333 customers who have held accounts with SyriaTel for less than 243 days.
Features include locational information, plan details (call charges, customer service calls, international plan), and churn status.
The target variable for prediction is the churn column.
Process
Various classification models were tested, including Decision Tree Classifier, Logistic Regression Classifier, KNN Classifier, Random Forest Classifier, and Gradient Boost Classifier.
Models were evaluated based on the recall score metric and confusion matrices to assess performance.
Results
The best model identified was a Gradient Boost model with a recall score of 0.81 on the test data.
This model showed significant improvement over previous models in terms of recall score and false predictions.
Future Investigations and Recommendations
Further investigation is recommended to explore additional characteristics of customers contributing to churn.
Focus on understanding why international plan holders have a high churn rate.
Implement strategies to reduce churn by analyzing customer behavior and improving service quality.
For more detailed analysis and findings, refer to the Jupyter Notebooks provided in the repository. This README provides a comprehensive overview of the SyriaTel Customer Churn dataset analysis conducted to predict customer churn and offer insights into improving customer retention strategies.

https://public.tableau.com/views/Book1_17100973279380/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link