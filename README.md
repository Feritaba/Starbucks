# Starbucks Capstone Project

## Project overview and motivation

Marketing analysis is a great way to find out whether offers received by customers are successful or not. With statistical knowledge combined with programming skills, nowadays, we can leverage marketing techniques like predicting customers' patterns of their purchases.

How does this analysis help Starbucks to gain more profit?
The answer lies under different analysis view points:
1. Know the best months to send any kind of discount offers.
2. Know the best age range of targeted customers that are more likely to order items from Starbucks.
3. Optimizing marketing by sending offers to customers who responded before.
4. Find the patterns using machine learning techniques to predict if a customer/member would respond to an offer or not.

To achieve the goal of the project we first ask some questions about the dataset to find out the obvious patterns and answer them by visualization. Then, we build a model to find the hidden patterns and predict whether a customer would respond to an offer or not.

## Summary:

In this project as mentioned above the goal is to find the obvious and hidden patterns of the dataset. First, we aimed for the analysis of finding easy patterns with asking 4 different questions that can be found below:
1. What category of offers has been received by customers more?
2 types of discounts have been sent out the most.
2. What is the age distribution of the members?
Age distribution is close to normal distribution with the mean around 60 years old.
3. How many people joined Starbucks as a member each year?
In 2013 less than 5,000 members joined, in 2014 less than 10,000 , in 2015 slightly less than 20,00 , in 2016 more than 30,000 , in 2017 more than 55,000 , and in 2018 around 35,000 members joined.
4. What is the offer completion rate?
Offer completion rate for bogo_3 is 29% higher than all other categories, this bogo_3 used web, email, mobile for their point of contact. The next rate is for all discount categories which is 27%. We can infer that discounts play a huge role in helping customers use their promotions and complete their orders.

To find the hidden patterns we used different machine learning techniques to classify the person whether responds to an offer or not. These models are, Logistic Regression, Random Forest, Ada Boost, Gradient Boosting, Gaussian Naive Bayes and Decision Tree.
All the models performed well but Decision Tree worked better in terms of time for learning.

The evaluation metrics used were, accuracy, f-1 score, precision and recall. For the decision tree all evaluation metrics were 1.0. This means that our model performed well but might not be well generalized for the future unseen data.

## Libraries used in this project are:
1. Seaborn version 0.11.2 for visualizations
2. Matplotlib version 3.3.4 for visualizations
3. Numpy version 1.19.5 for some math
4. Pandas for dealing with dataframes
5. Math for calculating
6. Json for accessing json files, profile, portfolio and transcript
7. Sklearn for using classifier models, evaluation metrics, scaling the features and splitting to test and train

## Files in the repository:
1. Data folder which contains json files of profile, portfolio and transcripts. These json files are our raw dataset.
2. Starbucks_Capstone_notebook.ipynb which is the python code for the project and final model that has been chosen to predict the customer response to an offer.
3. Readme.md file

## Link to the blog post:
https://medium.com/@foroozan-akhavan/starbucks-marketing-analysis-project-13160d2d8eae

## Acknowledgements:
This project was completed as part of the Udacity Data Science Nanodegree Program. The dataset used in this project contains  data that shows customer behavior on the Starbucks rewards mobile app provided by Starbucks itself. 


