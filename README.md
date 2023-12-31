# Project to Develop a ML Model in the Cloud
ADS-508 Final Project using AWS Cloud Resources

#### -- Programming Languages:
Python, Jupyter Notebooks, SQL
#### -- Amazon Web Services:
Amazon SageMaker (SM) Studio, SM Autopilot, S3, Athena, and AWS Glue 
#### -- Project Status: [Active]

## Overview
This graduate project is focused on creating a scenario in which the team heads a company called Community First Consulting (CFC), which is a mid-range consulting firm specializing in the cooperation between the city of New York (NYC), law enforcement agencies (e.g., NYPD), and community-focused mental health resource groups. NYC has recently contracted CFC to develop a machine learning model to identify boroughs of the city that could benefit from increased community resources based on previously collected data. The goal is to optimize this identification process, so that the resources and funding once required to analyze this data can be used directly in the communities that need it.\
*Note:* The company is not real, but all data, analyses, and developed models are. See references for data sources.

## Business Problem
CFC has been hired by NYC to investigate relationships between crime rates, eviction coutns, and census data demographics with the aim of identifying communities that would benefit from increased non-traditional policing services, such as outreach, mental health resources, and community leader partnerships.
* What insights do descriptive analytics efforts provide when examining the intersection between public employment opportunities, high school graduation rates, crime, and socioeconomic indicators?
* Can existing data facilitate the creation of machine learning models that predict where resources are most needed?

## Goals
* Provide recommendations for mental health and community outreach response, as opposed to traditional police response to mental health related issues. 
* Provide recommendations on targeted community resource allocations. 
* Identify correlations between community demographics and key quality of life indicators, such as job opportunities and crime rates.
* Provide NYC with an accurate and efficient model for automated prioritization of community resources.

## Team Members
* Aaron Carr
* Mackenzie Carter

## Methods Used
* Exploratory data analysis (EDA)
* Train/test split
* Regression
* Machine learning
* SQL queries (Athena)
* data storage and access (S3)
* Hyperparameter tuning
* Model evaluation (e.g., RMSE, R-sq)

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](data) within this repo.
3. Data processing/transformation scripts are being kept [here](deliverables)

## References
* Muonneutrino. (2017, August 3). New York City census data. *Kaggle*. https://www.kaggle.com/datasets/muonneutrino/new-york-city-census-data?select=census_block_loc.csv
* NYC OpenData. (2022, May 9). *2005-2010 graduation outcomes - school level*. Retrieved March 13, 2023, from https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a
* NYC OpenData. (2022, May 9). *2014-2015 DOE high school directory*. Retrieved March 13, 2023, from https://data.cityofnewyork.us/Education/2014-2015-DOE-High-School-Directory/n3p6-zve2
* NYC OpenData. (2022, June 9). *NYPD complaint data historic*. Retrieved March 13, 2023, from https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
* NYC OpenData. (2023, January 26). *Evictions*. Retrieved March 13, 2023, from https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4
* NYC OpenData. (2023, March 7). *NYC jobs*. Retrieved March 13, 2023, from https://data.cityofnewyork.us/City-Government/NYC-Jobs/kpav-sd4t