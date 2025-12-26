# Bayesian Modelling of Crop Yields

## Introduction

This project explores the use of Bayesian statistical modeling to analyze and predict crop yields across different countries and years. Leveraging a dataset compiled from the FAO and World Bank, the analysis investigates how environmental factors such as rainfall, temperature, and pesticide usage influence agricultural productivity, with a particular focus on maize yields in Brazil and India.

The project demonstrates:
- Data cleaning and exploratory data analysis (EDA)
- Hypothesis testing using both frequentist and Bayesian approaches
- Model building with PyMC and ArviZ
- Interpretation of results and posterior distributions

The goal is to provide insights into the drivers of crop yield variability and showcase the advantages of Bayesian methods for agricultural data analysis.

## Project Outline

1. **Data Preparation and Exploratory Data Analysis (EDA)**
	- Description of the dataset and sources
	- Data cleaning and transformation
	- Visualizations and key findings

2. **Hypothesis Testing**
	- Frequentist approach (t-tests)
	- Bayesian approach (modeling mean differences)
	- Prior sensitivity analysis
	- Posterior probability and comparison with frequentist results

3. **Regression Modeling**
	- Bayesian regression models for crop yield prediction
	- Choice of priors and likelihoods
	- Robust likelihoods and predictive checks

4. **Hierarchical and Unpooled Normal Models**
	- Implementation of hierarchical and unpooled models
	- Model comparison and predictive distributions
	- WAIC for model selection

Each section demonstrates practical Bayesian modeling techniques and interprets results in the context of agricultural data analysis.