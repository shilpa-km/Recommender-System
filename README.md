# Recommender-System :project overview
* For this example project I built a Recommender System for E-commerce companies like Amazon , flipkart.
* we are using item-item collaberrative filtering which produces high quality Recommentation System in the Real time.
* This system is a kind of a information filtering system which seeks to predict the "rating" or preferences which user is interested in.
* We need to built a model so that we can predict top 10 products with Recommentation System

# Code and Resources Used
**Python Version:** 3.7
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, json,joblib,KNNWithMeans

# Data used
* userId
* productId	
* Rating
* timestamp

# Data Cleaning
Next process is need to clean the data 
* We need to handle the missing value
* Check Number of missing values across columns

# EDA
I looked at the distributions of the data and the value counts for the various categorical variables

# Collaberative filtering (Item-Item recommedation)
* It is based on assumption that people like things similar to other things they like 
* It is  liked by other people with similar taste. it is mainly of two types: a) User-User b) Item -Item

# Model-based collaborative filtering system 
* The utility matrix obtaned above is sparce, I have filled up the unknown values wth 0.
* Decomposing the Matrix
* Correlation for all items with the item purchased by this customer based on items 
rated by other customers people who bought the same product

# performance
Here are the top 10 products to be displayed by the recommendation system to the above customer based on the purchase
history of other customers in the website.
