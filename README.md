# A Bayesian Approach to Salary Analysis for Data Scientists

**Author:** Vera Bruzzese  
**Date:** 2025-10-01

## Objective
This project applies Bayesian statistics to analyze salary patterns for data scientists worldwide. The goal is to understand how experience, company size, remote work, and geographic location influence salaries.

## Methods
- Exploratory data analysis on raw and log-transformed salaries
- Correlation and ANOVA analyses
- Mixed-effects modeling treating company location as a random effect
- Bayesian hierarchical modeling using **NIMBLE** in R
- Posterior estimation and diagnostics via MCMC

## Tools
- **R** for data analysis and modeling  
- **LaTeX** for PDF report generation  
- **ggplot2** for data visualization

## Data
- CSV file used: `ds_salaries.csv`  
- Preprocessing included removing duplicates, filtering missing salaries, creating log-salary variable and encoding categorical variables

## Output
- PDF report: `bayesian-salary-analysis.pdf`  
- Includes all plots, summary tables, model code snippets, and posterior diagnostics

## Key Findings
- Experience level is the strongest factor affecting salary  
- Large companies show slightly lower pay than expected  
- Geographic location explains substantial variability  
- Bayesian hierarchical model provides robust estimates and uncertainty quantification

