# Data-Scientist-Professional
## 🍽️ Recipe Traffic Prediction Project

Welcome to the **Recipe Traffic Prediction** repository! This project focuses on building a machine learning model to predict recipe popularity based on various recipe features. The goal is to help product managers choose recipes that are more likely to generate high traffic and increase user engagement and subscriptions.

## 📊 Project Overview

With thousands of recipes published, it's important to select those most likely to attract attention. This project addresses this challenge by:

- Performing data validation and cleaning
- Engineering relevant features (e.g., cooking time, ingredients, tags)
- Analyzing patterns in recipe popularity
- Building and evaluating predictive models
- Defining and optimizing for a custom business metric

### 🎯 Business Goal

The model aims to correctly predict which recipes will drive **high traffic at least 80% of the time**, while **minimizing the chance of promoting low-traffic recipes**.

## 🛠️ Tech Stack

- Python (Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
- PowerPoint (for final presentation)

## 📑 Key Files

- `recipe_site_traffic_2212.csv` — Data used for the analysis
- `notebook.ipynb` — Exploratory Data Analysis, feature insights and model building 
- `recipe_traffic_prediction_presentation.pptx` — Final project presentation  


## 🧠 Model Summary

After comparing several models, the final selected approach balances precision and recall to optimize for the business goal. The model predicts the likelihood of a recipe being a **high-traffic candidate**, enabling smarter content curation for the homepage.

## 📊 Business Metric

A custom metric was defined to capture the trade-off between **true positives (popular recipes shown)** and **false positives (unpopular recipes promoted)**, tailored to the business context.

## 📽️ Presentation

A PowerPoint slide deck summarizing the entire project is provided under `presentation/`. It includes:

- Project motivation
- EDA highlights
- Model performance
- Recommendations for product managers

## 🧩 Future Work

- Integrate the model into a dashboard for live recipe selection
- Refine predictions using time-based traffic trends
- Test model impact through A/B experiments

## 📬 Contact

For questions or collaborations, feel free to reach out via GitHub issues or email.


**Let’s bring only the best recipes to the spotlight! 🌟**



