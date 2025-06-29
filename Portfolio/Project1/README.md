 Tesla Supercharging Stations Prediction (USA)
Overview
This project analyzes and predicts the geographic expansion of Tesla Supercharging Stations in the United States. Since reliable charging infrastructure is one of the top concerns for EV buyers, this model identifies high-potential areas for new station installations. These predictions can aid Tesla, city planners, and prospective EV buyers in making data-driven decisions.

Objective
Analyze the distribution of existing Supercharger stations.

Identify key geographic, demographic, and infrastructure-related variables influencing placement.

Build a predictive model to forecast potential expansion zones within the U.S.

Dataset & Scope
Geographic scope: United States only.

Data sources:

Tesla Supercharger locations (public APIs / Kaggle)

U.S. Census demographic data

Highway and road network data

Regional EV adoption rates

Methods Used
EDA: Heatmaps and clustering to explore current Supercharger gaps.

Feature Engineering: Population density, proximity to major roads, EV registration density.

Modeling:

Logistic Regression

Decision Trees

Visualization: Interactive maps of high-probability expansion zones using Folium and Plotly.

Key Findings
High-probability expansion zones were often:

Near high-traffic interstate corridors not yet well-covered

In suburban regions with rising EV registrations

In underserved regions like parts of the Midwest and Southeast

Tools & Technologies
Language: Python

Libraries: Pandas, Scikit-learn, GeoPandas, Matplotlib, Plotly, Folium

IDE: Jupyter Notebook

Version Control: Git/GitHub

Challenges & Assumptions
Data gaps: Not all station data is publicly available (especially private charging stations).

Geographic bias: Tesla’s internal expansion criteria are not fully known.

Model limitation: Focused only on geographic and demographic factors — does not include real estate, grid access, or corporate strategy.

References
Tesla Station Map: https://www.tesla.com/findus

Kaggle EV Charging Datasets

U.S. Census Bureau

EV-Volumes, CleanTechnica, OpenChargeMap API
