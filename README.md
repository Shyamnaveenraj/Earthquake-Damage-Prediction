# Earthquake-Damage-Prediction

🌍 Earthquake Damage Prediction & Analysis

📊 Project Overview

This project analyzes post-earthquake survey data from the 2015 Gorkha earthquake in Nepal. The goal was to uncover the primary factors that cause building destruction and build a predictive model to classify the level of damage (Low, Medium, Complete Destruction).

🛠️ Tech Stack

Data Cleaning & EDA: Python (Pandas, Matplotlib, Seaborn)

Database / Querying: SQLite (via Python)

Machine Learning: Scikit-Learn, XGBoost (Random Forest, Decision Trees)

Data Visualization: Power BI

💡 Key Insights & Recommendations

Foundation Type is Critical: Buildings with anonymized foundation type 'r' suffered catastrophic failure rates compared to type 'i'. Recommendation: Subsidize retrofitting for 'r' type foundations.

Age & Mass: Older, taller, and heavier buildings showed a strong correlation with higher damage grades. Recommendation: Update zoning laws to restrict building volume in high-risk zones.

Location: Proximity to the epicenter (geo_level_1) was the strongest predictor of damage. Recommendation: Pre-deploy emergency supplies to these specific high-risk regions.

🚀 How to Run

Clone this repository.

Open Earthquake_Analysis.ipynb in Jupyter Notebook or Google Colab.

Run the cells sequentially to view the EDA, SQL queries, and model training.

Open the .pbix file to view the interactive Power BI dashboard.
