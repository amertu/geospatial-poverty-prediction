# ML-Based Global Poverty Risk Modeling
![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-%E2%9C%94-F37626?logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.x-150458?logo=pandas&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-0.14.2-lightgrey)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4.2-orange)
![LightGBM](https://img.shields.io/badge/LightGBM-3.3.5-green)
![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-ROS-E67E22)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Plotly](https://img.shields.io/badge/Plotly-Visualization-3F4F75?logo=plotly&logoColor=white)
![World Bank Data](https://img.shields.io/badge/World%20Bank-Data%20API-0071BC)
![Git](https://img.shields.io/badge/Git-2.49.0-F05032?logo=git&logoColor=white)

## Project Overview

This project focuses on analyzing and predicting patterns of extreme poverty using geospatial and socio-economic data. As an **Analytics Engineer**, the primary goal was to uncover key factors driving poverty and provide actionable insights to support targeted interventions.

## Objectives

- Analyze global poverty trends using geospatial and socio-economic datasets.
- Build and evaluate predictive machine learning models to identify countries at high risk of extreme poverty.
- Recommend strategic actions based on model results to aid poverty alleviation efforts.

## Key Features

- **Machine Learning Modeling**: Developed predictive models using Python to analyze the impact of various factors on extreme poverty.
- **Geospatial Data Integration**: Combined spatial and socio-economic data to provide a comprehensive view of poverty distribution.
- **Data-Driven Insights**: Delivered insights to support policymaking and strategic planning for poverty reduction.

## System Architecture
```markdown
                                    +--------------------------+
                                    |   Data Sources           |
                                    |--------------------------|
                                    | - World Bank             |
                                    | - UNDP                   |
                                    | - Geospatial Datasets    |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | Data Cleaning &          |
                                    | Preprocessing            |
                                    | (Python, Pandas, etc.)   |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | Feature Engineering       |
                                    | (Geo & Socio-Econ. Data)  |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | ML Modeling              |
                                    | - Train Models           |
                                    | - Evaluate Accuracy      |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | Prediction Engine        |
                                    | - Identify High-Risk     |
                                    |   Countries              |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | Strategic Insights       |
                                    | - Recommend Interventions|
                                    | - Suggest Escape Routes  |
                                    +-----------+--------------+
                                                |
                                                v
                                    +--------------------------+
                                    | Decision Support         |
                                    | - NGOs                   |
                                    | - Policymakers           |
                                    | - Development Agencies   |
                                    +--------------------------+
```
