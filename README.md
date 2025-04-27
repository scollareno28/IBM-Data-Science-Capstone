



# 🚀 Predicting SpaceX First Stage Landing Success
## Overview
## This project applies machine learning techniques to predict the success of SpaceX Falcon 9 rocket first-stage landings.
Given the high variability in reported launch costs (ranging from $62M to $165M), understanding and predicting reusability is key to assessing cost advantages.
The goal is to identify factors influencing successful landings to support strategic decision-making for competitive bidding and operational improvements.

## Key Accomplishments
Collected and wrangled data from the SpaceX API and Wikipedia using Python (requests, BeautifulSoup) and stored it in structured pandas DataFrames.

Performed exploratory data analysis (EDA) through SQL and data visualization (Matplotlib, Seaborn) to uncover key features influencing launch outcomes.

Built interactive visualizations using Folium and Plotly Dash to map launch sites, success rates, and payload impacts.

Developed and tuned classification models (SVM, Logistic Regression, Random Forest) achieving 87% accuracy in predicting landing success, with SVM performing the best.

Created a live dashboard to simulate different payload scenarios and visualize success rates across launch sites.

## Technologies Used
Python (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium)

SQL (SQLite3 for EDA querying)

Web Scraping (requests, BeautifulSoup)

Machine Learning (SVM, Logistic Regression, Random Forest, GridSearchCV)

Interactive Dashboards (Plotly Dash)

## Project Structure

## Module	Description	Link
Data Collection	SpaceX API data and Wikipedia web scraping	API Notebook / Web Scraping Notebook
Data Wrangling	Data cleaning, normalization, imputation	(same as above)
EDA	Visualization and SQL-based exploration	EDA Visualization / SQL EDA
Interactive Map	Launch site success/failure mapping with Folium	Folium Map Notebook
Dashboard	Plotly Dash interactive app	Dashboard Code
Machine Learning	Classification modeling and evaluation	ML Prediction Notebook
Results
SVM model achieved the highest predictive performance with an accuracy of 87%.

KSC LC-39A identified as the most successful launch site with a 76.9% success rate.

Success rates correlated strongly with orbit type, payload mass, and number of previous launches at a site.

Interactive dashboard and visualizations provide insights into operational conditions that favor success.

## Conclusion
Through this project, machine learning models have shown strong potential in helping predict SpaceX launch outcomes.
Understanding these patterns allows stakeholders to better estimate costs, strategize competition, and optimize operations.
