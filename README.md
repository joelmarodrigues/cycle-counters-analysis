# 🚲 Cycling Traffic - Dublin Council Counters

This project applies **Exploratory Data Analysis (EDA)** techniques to investigate cycling traffic patterns in Dublin City. The dataset, provided by the Dublin City Council, contains the number of cyclists counted hourly across different street sensors.

---

## Objectives

- Identify high and low traffic areas for cyclists.
- Understand seasonal variations in cyclist volume.
- Analyse peak cycling hours.
- Suggest improvements for urban planning based on data.

---

## Methods

**Data Preparation**
- Handling missing values (mean, KNN, temporal interpolation).
- Feature engineering.

**Exploratory Analysis**
- Descriptive statistics (mean, median, quartiles, std).
- Outlier detection (IQR).
- Correlation matrix and PCA.

**Clustering & Visual Analysis**
- K-Means clustering for traffic density classification.
- PCA for dimensionality reduction.
- Visual insights using Matplotlib and Seaborn.

---

## Findings

- **Grove Road** had the highest cycling traffic in 2023 (~1 million cyclists).
- Traffic dropped in **December**, peaked in **May and June**.
- Peak hours: 8AM (~1560 cyclists), 5PM (~1510 cyclists).
- Winter drop confirmed seasonal impact on traffic.
- Urban planning recommendations based on cluster behaviour.

---

## Technologies/Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

---

## Project Structure

- `cycling_data_analysis.ipynb`: Full analysis in Jupyter
- `cycle_data.csv` and variations: Processed datasets
- `outputs/`: Plots and images used in the presentation
- `poster.png`: Academic poster summarising the project

---

## Academic Context

- Final-year project | BSc in Computing & IT  
- Module: Data Exploration & Preparation  
- CCT College Dublin | 2024-2025