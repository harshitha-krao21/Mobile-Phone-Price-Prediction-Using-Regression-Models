# Mobile-Phone-Price-Prediction-Using-Regression-Models
This is based on Linear Regression and Logistic Regression models. In this notebook,  these fundamental regression models are used, which are widely used for prediction and classification tasks. This includes to train and interpret both models using a cell phone pricing dataset (predicting rating and price).

# Introduction to Regression Models
Linear Regression is a linear approach to modeling the relationship between a dependent variable and one or more independent variables. It aims to fit a linear equation to the observed data.

# Logistic Regression 
It is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). It estimates the probability that a given instance belongs to a certain class.

# Overview

Train a Linear Regression model to predict a continuous outcome (price), using different regularization terms

Train a Logistic Regression model to predict a categorical outcome (rating), with both sklearn.linear_model.LogisticRegression and sklearn.linear_model.SGDClassifier ('loss="log_loss"').

Compare and interpret the predictions of the models

# Data Description

The dataset mobile phone price prediction.csv contains informationn on various mobile phones, including their specifications, features, and prices. This data has been collected by scraping online websites.

The first objective is to train a model to predict the price of mobile phones based on their features. The second objective is to train a model to predict the rating of mobile phones based on their features and price.

# Data Attributes:

Name: Name of the mobile phone

Rating: High Rating or Not (0/1)

Spec_score: Specification score

No_of_sim: Number of SIM cards supported (e.g., Dual Sim, 3G, 4G, 5G, VoLTE)

Ram: RAM size (e.g., 4 GB RAM)

Battery: Battery capacity (e.g., 6000 mAh Battery)

Display: Display size (e.g., 6.6 inches)

Camera: Camera specifications (e.g., 50 MP + 2 MP Dual Rear & 13 MP Front Camera)

External_Memory: External memory support (e.g., Memory Card Supported, upto 1 TB)

Android_version: Android version (e.g., 13)

Price: Price of the mobile phone (in currency units)

company: Manufacturer of the mobile phone (e.g., Samsung)

Inbuilt_memory: Inbuilt memory size (e.g., 128 GB inbuilt)

fast_charging: Fast charging support (e.g., 25W Fast Charging)

Screen_resolution: Screen resolution (e.g., 2408 x 1080 px Display with Water Drop Notch)

Processor: Processor type (e.g., Octa Core Processor)

Processor_name: Name of the procen building a predictive model.n building a predictive model.n building a predictive model.

# Model Training

Read and Understand the Data

Data Preprocessing

Model Training and Evaluation: Linear Regression

Model Training and Evaluation: Logistic Regression

Model Prediction and Evaluation
