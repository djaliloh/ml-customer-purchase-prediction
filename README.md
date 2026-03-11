# Customer Purchase Prediction Using Website Session Data

## Overview
This repository contains a machine learning case study that analyzes website session data to understand customer behavior and predict whether a visitor will complete a purchase. The objective is to extract operational insights, identify behavioral patterns, and build a predictive model that classifies customer sessions into **purchase (True)** or **no purchase (False)** outcomes.

The analysis supports decision-making for improving website performance, customer experience, and operational planning.

## Problem Statement
An e-commerce company is experiencing operational inefficiencies, including unexpected failures, interruptions, and increased operational costs. These issues negatively impact customer satisfaction and company performance.

The organization seeks analytical methods to better understand website activity and operational performance indicators. By analyzing website session data, the goal is to:

- Identify behavioral patterns and performance trends
- Support data-driven decision making
- Predict potential operational or behavioral outcomes
- Build a predictive model to determine whether a visitor will make a purchase

## Objectives
The main objectives of this project are:

- Identify trends and behavioral patterns in customer website sessions
- Provide analytical insights that support strategic decision making
- Develop predictive models to classify customer purchase behavior
- Evaluate model performance and predictive capability

## Dataset
The dataset contains **12,330 customer session records** from an e-commerce website collected over a one-year period. Each session represents an independent user visit to avoid bias from repeated users, campaigns, or specific time periods.

**Source:** Sahu (2021)

### Dataset Characteristics
- **Total observations:** 12,330
- **Numerical features:** 10
- **Categorical features:** 8
- **Target variable:** Revenue (True / False)

Each row represents a single website session.

## Features Description

### Target Variable
- **Revenue**  
  Indicates whether the session resulted in a purchase.  
  Values: `True` or `False`

### Numerical Features
- **Administrative**  
  Number of administrative pages visited during the session.

- **Administrative Duration**  
  Total time spent on administrative pages.

- **Informational**  
  Number of informational pages visited.

- **Informational Duration**  
  Total time spent on informational pages.

- **Product Related**  
  Number of product-related pages visited.

- **Product Related Duration**  
  Total time spent on product-related pages.

- **Bounce Rate**  
  Percentage of visitors who enter the site and leave without further interaction.

- **Exit Rate**  
  Percentage of exits from a specific page.

- **Page Value**  
  Average value of pages visited before completing a transaction.

- **Special Day**  
  Indicates the closeness of the visit to a special day (e.g., holiday or promotional event).

### Categorical Features
- **Month** – Month of the session
- **Operating Systems** – Visitor operating system
- **Browser** – Browser used by the visitor
- **Region** – Geographic region of the visitor
- **Traffic Type** – Source of traffic
- **Visitor Type** – Returning or new visitor
- **Weekend** – Indicates whether the visit occurred on a weekend

## Project Workflow

### 1. Data Exploration
- Dataset inspection
- Summary statistics
- Missing value checks
- Feature distribution analysis

### 2. Data Preprocessing
- Handling categorical variables
- Encoding categorical features
- Feature scaling (if applicable)
- Train-test split

### 3. Exploratory Data Analysis (EDA)
- Feature correlation analysis
- Behavioral pattern exploration
- Purchase vs non-purchase comparisons

### 4. Model Development
Machine learning models are trained to predict the **Revenue** variable.

Typical classification algorithms include:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- Gradient Boosting

### 5. Model Evaluation
Models are evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

## Expected Outcomes
The predictive model helps the company:

- Understand user behavior patterns
- Identify high-value customer sessions
- Improve website design and marketing strategies
- Support proactive operational decision making
- Increase conversion rates and reduce inefficiencies

## Repository Structure



## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Reference
Sahu, A. (2021). *Online Shoppers Purchasing Intention Dataset.*

## Contact
OUSSEINI HAMZA Abdoul Djalil (abdouldjalilo@gmail.com)