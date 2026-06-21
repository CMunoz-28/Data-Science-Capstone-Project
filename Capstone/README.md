# Applied Data Science Capstone — SpaceX Launch Prediction

![Python](https://img.shields.io/badge/Python-Data%20Science-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![SQL](https://img.shields.io/badge/SQL-EDA-lightgrey)
![Folium](https://img.shields.io/badge/Geospatial-Folium-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Project Overview

This capstone applies a full data science workflow to predict whether SpaceX's Falcon 9 first stage will successfully land — enabling cost estimation for competing launch providers. SpaceX advertises Falcon 9 launches at $62M vs. competitors at $165M+; the cost difference hinges largely on first-stage reusability.

---

## Workflow

| Step | Notebook | Description |
|---|---|---|
| 1. Data Collection | `jupyter-labs-spacex-data-collection-api.ipynb` | Pull launch data from the SpaceX REST API |
| 2. Web Scraping | `Data Collection with Web Scraping.ipynb` | Scrape additional launch records from Wikipedia |
| 3. Data Wrangling | `SpaceX_Data Wrangling.ipynb` | Clean, transform, and prepare data for analysis |
| 4. EDA with SQL | `EDA with SQL.ipynb` | Explore launch patterns using SQL queries |
| 5. EDA with Visualization | `EDA with Data Visualization.ipynb` | Visual EDA — trends, correlations, distributions |
| 6. Geospatial Analysis | `lab_jupyter_launch_site_location.ipynb` | Map launch sites and proximity analysis with Folium |
| 7. ML Prediction | `SpaceX_Machine Learning Prediction_Part_5.ipynb` | Classification models to predict landing success |

---

## Key Findings

- Orbit type, payload mass, and launch site were the strongest predictors of landing success
- Decision Tree and SVM classifiers achieved the highest prediction accuracy
- Launch success rate has improved significantly over time as SpaceX refined its technology

---

## Skills Demonstrated

- REST API data collection and web scraping
- Data wrangling and feature engineering
- SQL-based exploratory analysis
- Geospatial visualization with Folium
- Classification modeling (Logistic Regression, SVM, Decision Tree, KNN)
- Model evaluation and hyperparameter tuning
