# Red Wine Quality Project

Project for the TC DS Statistical Modeling Sprint.

## The Dashboard

A Looker dashboard had to be created as a part of this project. It can be found [here](https://lookerstudio.google.com/).

## The Dataset

This study will consider Vinho Verde, a unique product from the Minho (north-west) region of Portugal. Medium in alcohol, is it particularly appreciated due to its freshness (specially in the summer). This wine accounts for 15% of the total Portuguese production, and around 10% is exported, mostly white wine. In this work, we will analyze the two most common variants, white and red (rose is also produced), from the demarcated region of vinho verde. The data were collected from May/2004 to February/2007 using only protected designation of origin samples that were tested at the official certification entity (CVRVV). The CVRVV is an inter-professional organization with the goal of improving the quality and marketing of vinho verde. The data were recorded by a computerized system (iLab), which automatically manages the process of wine sample testing from producer requests to laboratory and sensory analysis. Each entry denotes a given test (analytical or sensory) and the final database was exported into a single sheet (.csv). During the preprocessing stage, the database was transformed in order to include a distinct wine sample (with all tests) per row. To avoid discarding examples, only the most common physicochemical tests were selected. Since the red and white tastes are quite different, the analysis will be performed separately, thus two datasets 1 were built with 1599 red and 4898 white examples. Regarding the preferences, each sample was evaluated by a minimum of three sensory assessors (using blind tastes), which graded the wine in a scale that ranges from 0 (very bad) to 10 (excellent). The final sensory score is given by the median of these evaluations. **(Cortez et al., 2009)**

## Objective


- Perform data inspection and cleaning.
- Perform exploratory data analysis, extract insights, formulate hypotheses and understand the data for upcoming modeling.
- Perform hypothesis testing.
- Atempt to model alcohol content and quality with linear models, make predictions and summarize the influence of independent variables.

## Quickstart Guide

  


- Install dependencies.

  

```pip install -r requirements.txt```

  

- Run the notebook.

  

```jupyter notebook```
