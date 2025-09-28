# Population Size vs Air Quality – Data Wrangling Project

## Context & Objective
This project was completed as part of the Udacity Data Analyst Nanodegree Program.  
The research question: **Is there a relationship between the population size of a U.S. state and its Air Quality Index (AQI) in 2021?**

The goal was not only to explore this relationship, but also to practice the full data wrangling workflow:  
- Gathering datasets using two different methods.  
- Identifying and fixing at least two quality and two tidiness issues.  
- Cleaning and merging the data.  
- Preparing it for analysis and visualization.  

## Steps Taken

### 1. Data Gathering
- Collected AQI data from Kaggle via API.  
- Collected population estimates from the U.S. Census Bureau via programmatic download.  
- Restricted scope to the year 2021, which was common to both datasets.  

### 2. Data Assessment
- Checked datasets for completeness, consistency, and structure.  
- Identified quality issues: missing values, inconsistent naming, datatype mismatches.  
- Identified tidiness issues: monthly AQI values spread across columns, redundant ranking fields.  

### 3. Data Cleaning
- Handled missing and invalid values.  
- Standardized state naming conventions for merging.  
- Reshaped AQI data from wide to long format.  
- Dropped unnecessary ranking variables.  

### 4. Data Transformation
- Merged AQI and population datasets into a single analytical table.  
- Built the final dataset with AQI (2021) and population (2021) for each state.  

### 5. Visualizations
- Scatter plot of population size vs AQI to directly test the research question.  
- Boxplot of AQI distributions by state to compare variation.  

## Key Findings
- Large populations do not necessarily correspond to worse air quality. Even the most populous state remains within a moderate AQI range.  
- Among smaller states, AQI values vary widely, from very low to relatively high.  
- Results suggest that other factors beyond population size are more influential for air quality.  

## Deliverables
- Jupyter Notebook documenting the complete wrangling workflow (gathering, assessment, cleaning, merging, analysis).  
- HTML version of the notebook for easier viewing and sharing.  

