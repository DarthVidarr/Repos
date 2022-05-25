# Introduction

This repository contains collection of code, documentation, and sample outputs which have been produced for various data science, wrangling, and analysis projects. 

# Purpose

The purpose of this repository is to keep versions of code for future development use and to continue contributing to when new or improvements to existing code is produced 

# Example of contents

_Power BI heatmap to track clients user data_

<img src="https://github.com/DarthVidarr/Repos/blob/main/heatmap.JPG" width="450" height="350">

_Visualising the linear regression of significant features used to predict temperature_

<img src="https://github.com/DarthVidarr/Repos/blob/main/linear_regression.JPG">

_Output of Autoregressive Integrated Moving Average (ARIMA) model to predict a count of future university professor citations_

<img src="https://github.com/DarthVidarr/Repos/blob/main/ARIMA_model.JPG" width="500" height="350">

# Contents

### GUID performance by data type (Power BI)
A [publicly available Power BI report](https://app.powerbi.com/view?r=eyJrIjoiMjQ2MWM5ZTUtMDJlYi00YThlLWE5MGUtMGIwNzQ5Y2E0N2RjIiwidCI6ImU3ZTAzMWZjLWY1MGEtNDA2OS05NWE5LTZmNGQ4OTgxYzdmMiJ9)
 which investigates the difference in processing performance between data types 

### GUID_performance_script (R)
The script behind the GUID perfomance Power BI report which is used to run the performance test

### TaxonomyPerformanceTest.csv

Output of 'GUID_performance_script.R', and used as an input to the Power BI report.

### Linear_Regression_sample.ipynb (Python)

Train a linear model for predicting temperature by reading a weather patterns dataset and identifying significant features which correlate with temperature

### Machine_Learning_sample.ipynb (Python)

Train a model to predict a class/category using machine learning techniques such as Clustering, ANOVA & Chi-Squared feature selection, dimensionality reduction

### Data_Analysis_sample.ipynb (Python)
Read, clean, analyse and visualise dataset 

### Data_Manipulation_sample.ipynb (Python)
Read, clean, transform, analyse, and visualise data 

### EDR_Senior_Analyst (Rmd)
A markdown file used to assess the technical competency of potential developers, using a version of the iris flower dataset with bugs deliberately introduced

### SampleDataset.csv
Used as an input for 'EDR_Senior_Analyst.Rmd'

### working_location_script

A script which reconciles latitude / longitude coordinates to locations which are entered as free-text. For example: "Melbourne", "Melbourne 3212", Melbourne VIC" should all result in the same latitude / longitude coordinates. This is useful for plotting free-text geographic information on a map visual.

### Documentation > Documentation sample

An example of documentation including data transformations, modelling, lineage and brief wireframe.

### Documentation > Wireframe sample

A wireframe for a proof-of-concept Power BI report

