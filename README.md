# Titanic Exploratory Data Analysis

## Overview

This project is based on the Titanic dataset. I used Python and different data analysis libraries to explore the data and understand what factors were related to passenger survival.

The main purpose of this project was to clean and understand the dataset, find useful patterns, create visualizations, and then use those findings to make some practical observations and recommendations.

## What I Did

During the project, I worked on:

- Understanding the dataset and checking its structure
- Checking missing and duplicate values
- Creating new features from the existing data
- Exploring passenger survival patterns
- Comparing survival based on gender and passenger class
- Looking at age, fare, and family size
- Performing basic statistical analysis
- Creating different charts and a dashboard
- Finding correlations between numerical variables
- Writing business insights based on the analysis
- Giving practical recommendations based on the findings

## New Features I Created

I created a few additional features to make the analysis easier:

- **Family Size**: shows the total number of people in a passenger's family.
- **Is Alone**: shows whether the passenger was travelling alone or not.
- **Age Group**: divides passengers into groups such as Child, Teenager, Adult, and Senior Citizen.
- **Fare Category**: groups passengers according to the fare they paid.

## Some Key Findings

From my analysis, I found that:

* More passengers did not survive than survived.
* Female passengers had a higher survival rate than male passengers.
* Passenger class had a noticeable connection with survival.
* Higher-class passengers generally paid higher fares.
* Age and family size also showed different survival patterns.
* Fare and passenger class had a noticeable relationship.

## Machine Learning

As an additional part of the project, I created a simple **Logistic Regression model** to predict whether a passenger survived or not.

The model used information such as:

- Passenger class
- Age
- Ticket fare
- Family information
- Family size

I also checked the model's accuracy and classification report.

## New Filter

I also added interactive filters to the notebook so that the data can be explored more easily.

For example, passengers can be filtered by:

- Passenger class
- Survival status

This makes it easier to look at specific groups without manually changing the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- IPyWidgets
