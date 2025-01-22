# Exploratory Data Analysis on the Titanic Dataset
## Project Overview

This project involves performing Exploratory Data Analysis (EDA) on the Titanic dataset to uncover insights about passenger demographics, survival rates, and correlations among features. The insights gained can be applied to business use cases such as customer segmentation, predictive maintenance, and risk assessment.

## Skills Gained

* Data wrangling and cleaning

* Data visualization using Seaborn and Matplotlib

* Feature engineering and insights extraction

## Tools and Technologies

* Python

* Pandas for data manipulation

* Seaborn and Matplotlib for data visualization

## Problem Statement

* Perform EDA on the Titanic dataset to:

* Analyze passenger demographics.

* Investigate survival rates.

* Identify correlations among features.

## Approach

1. Data Loading

Import the dataset into a Pandas DataFrame.Display the first few rows to understand the structure and types of data.

2. Data Cleaning

Handle Missing Values:Identify columns with null values (e.g., Age, Cabin).Impute missing values (e.g., median for Age, 'Unknown' for Cabin).
Remove Duplicates:Check for and remove duplicate rows, if any.Correct Data Types:Convert categorical variables like Sex and Embarked to appropriate types.

3. Univariate Analysis

 Analyze individual features to understand their distributions:Categorical Features: Use count plots for Survived, Pclass, Sex, and Embarked.Numerical Features: Use histograms and KDE plots for Age and Fare.

4. Bivariate Analysis

Investigate relationships between two variables:Survival by Gender: Compare survival rates for males and females.
Survival by Class: Analyze survival rates across passenger classes (Pclass).Age vs. Fare: Use scatter plots to explore the relationship between Age and Fare.

5. Multivariate Analysis

Explore patterns involving more than two features:Survival by Gender and Class: Use stacked bar charts or heatmaps.
Correlation Matrix: Calculate and visualize correlations between numerical features.

6. Feature Engineering

Create New Features:Extract titles from Name.Group Fare into ranges (e.g., low, medium, high).Create a family size feature: FamilySize
Analyze how the engineered features relate to survival.

## Insights and Conclusions
Summarize key findings:
1. Females had a higher survival rate than males.
2. Passengers in first class were more likely to survive than those in third class.
3. Younger passengers had a higher survival rate.
4. Passengers with smaller family sizes were more likely to survive.


## Developed By:B.N.Piraviena
