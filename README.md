# Regression_Analysis_on_Household_Victimization
Overview
This project analyzes household victimization patterns during two major crises—2008 Mortgage Crisis and the 2018 COVID-era—using regression techniques. The goal is to model the likelihood of victimization based on socio-economic and demographic factors.

Dataset
Source: National Crime Victimization Survey (NCVS) - ICPSR 38604

Timeframe: 1992–2022

Size: ~4.2 million observations, 226 variables

Key Steps
Variable Selection: Chose ~25 relevant variables influencing victimization (e.g., income, education, family structure).

Data Cleaning: Removed or replaced NAs, filtered irrelevant variables, and split data into pre-, during-, and post-crisis periods.

Modeling:

Linear Regression: Initially attempted but violated OLS assumptions.

Logistic Regression: Used for classification, followed by stepwise selection and cross-validation.

Validation:

Used 5-fold cross-validation.

Accuracy: Train (98.31%), Test0 (97.55%), Test1 (99.04%), Validation (99.23%)

Conclusion
University education and income levels have shifting impacts during crises.

Logistic regression provided robust, high-accuracy predictions.

Results can support policy and community-level decision-making in crisis planning.

Tech Stack
Language: R

Methods: Logistic Regression, Stepwise Regression, Cross-Validation
