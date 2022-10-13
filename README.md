# Winning the Space Race with Data Science
SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. 


## File Names and Structure
1) **Data Collection API.ipynb:** Data Collection with SpaceX REST API
2) **Data Collection with Web Scraping.ipynb:** Data Collection with Web Scraping (utilizing the Beautiful Soup Library)
3) **Data Wrangling.ipynb:** Data Wrangling (Pandas, Numpy)
4) **EDA with Visualization.ipynb:** Exploratory Data Analysis (EDA) with Visualization (Matplotlib, Seaborn)
5) **EDA with SQL.ipynb:** EDA with SQL
6) **Interactive Visual Analytics and Dashboard.ipynb:** Interactive Visual Analytics and Dashboard (Folium maps and Plotly Dash dashboard)
7) **SpaceX_Machine Learning Prediction_Part_5.ipynb:** Predictive Analysis - Classification with SVM, Classification Trees and Logistic Regression (scikit-learn)

## Executive Presentation
See details on the methodology and results [here](https://github.com/vnemala/spacexanalysis-ibm/blob/main/Executive%20Presentation%20-%20DS_ML%20Methodology.pdf) in the executive presentation

## Executive Summary

* Predictions about whether or not SpaceX rockets’ first stages can be reused is something that can be predicted using machine learning techniques.
* Using classification techniques such as Support Vector Machines & K Nearest Neighbors, we can accurately predict if the first stage of a SpaceX rocket will successfully land and be able to be reused.
* We have achieved an accuracy of prediction of 83.3%. 

## Introduction
* The goal is to determine if Falcon 9 first stage will land successfully. Falcon 9 rocket launches by SpaceX are at a cost of 62 million dollars (vs 165 million dollars for its competitors). This is because savings made possible by reusing the first stage.
* By deciding on and feeding important parameters into a machine learning algorithm, we can determine if the first stage can land successfully and be reusable.
* This is information that can be useful for the company to predict rocket success, as well as if an alternate company wishes to bid against SpaceX for a rocket launch.

## Methodology
* Data collection methodology:
  * Data was acquired with the SpaceX REST API (official data about launches) as well as  web scraping of Wikipedia pages for more useful information.
* Perform data wrangling
  * Data was processed by checking the larger trends and success rates of various launches  and parameter combinations.
* Perform exploratory data analysis (EDA) using visualization and SQL
* Perform interactive visual analytics using Folium and Plotly Dash
* Perform predictive analysis using classification models
  * Build, tune, and evaluate classification models such as SVM and Decision Tree

## Conclusions
* Logistic Regression, Support Vector Machines, and K Nearest Neighbors provided the highest accuracy with predictions, at about 83.3%. 
* Decision Trees provided the lowest accuracy about predictions, at about 72%.
