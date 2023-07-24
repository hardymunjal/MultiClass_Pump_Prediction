# Pump Health Prediction

## Problem Statement
We worked on a predictive modeling (multi-class) problem where we used data from Taarifa and the Tanzanian Ministry of Water, to predict which pumps were functional, which need some repairs, and which don't work at all. 

We predicted one of these three classes based on a number of variables about what kind of pump is operating, when it was installed, and how it is managed.

> Competition Source - [Driven Data](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/)

## Business Value
A smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

## Dataset Description
More information on the variables used and their description can be found in the file - [dataset-description.md](./dataset-description.md)

## Methodology
We performed a series of steps to work on the problem as highlighted below:

### Data Cleaning
This step included various numerical and categorical data cleaning steps which include:
- Zero-Variance column analysis
- Missing value analysis
- Categorical data binning
- Duplicated data analysis
- Column-specific analysis

> Code - [data_cleaning_final.ipynb](./src/data_cleaning_final.ipynb)


