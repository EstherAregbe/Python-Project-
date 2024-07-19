Movies Dataset Exploration
This repository contains the Python code and analysis for exploring a movies dataset. The goal of this exploration is to analyze various aspects of the dataset, including budget and gross correlations, missing data handling, and general statistics.
Dataset Description
The dataset includes the following columns:

Name,
Rating,
Genre,
Released,
score,
Year,
votes,
director,
writer,
star,
Budget,
Gross,
runtime,
Country,
company.

Analysis Overview

Missing Data Handling - Missing values were handled using the SimpleImputer from sklearn. Depending on the column, missing values were replaced with the median, mean, or most frequent value. Columns with an excessive number of missing values were dropped.

Correlation Analysis

A detailed analysis of the correlation between the budget and gross was conducted to understand their relationship.

General Statistics

Various statistical measures were calculated to provide insights into the dataset, including:

-Mean and median of numerical columns
-Distribution of categorical columns

Requirements
Python 3.x,
pandas,
numpy,
sklearn,
matplotlib,
seaborn,
