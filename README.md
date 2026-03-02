# Iris Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Iris dataset. The goal is to understand the differences between Iris species based on their physical measurements and identify which features are most useful for classification.

The dataset contains measurements of sepals and petals for three Iris species:
- Setosa
- Versicolor
- Virginica

---

## Dataset Features

The dataset includes the following columns:

- sepal_length (cm)
- sepal_width (cm)
- petal_length (cm)
- petal_width (cm)
- species

Each row represents one flower observation.

---

## Objectives

The main objectives of this analysis are:

- Inspect and understand the dataset structure
- Analyze feature ranges (min, max, mean) per species
- Identify which features best distinguish species
- Study correlations between features
- Visualize relationships using scatter plots, pairplots, and heatmaps

---

## Key Findings

### 1. Petal Length
- Setosa: 1.0 – 1.9 cm
- Versicolor: 3.0 – 5.1 cm
- Virginica: 4.3 – 6.9 cm

Petal length clearly separates the three species.

### 2. Petal Width
- Virginica has the widest petals
- Setosa has the narrowest petals
- Strong separation between species

### 3. Correlation Analysis
Petal length and petal width show very strong positive correlation (r = 0.96), meaning longer petals are associated with wider petals.

### 4. Visualization Insights
Scatter plots and pairplots show clear clustering of species, especially using petal measurements.

### 5. Feature Importance
Petal length and petal width are the most useful features for distinguishing species.

---

## Tools Used

- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook (Google Colab)

---

## Project Files

- iris-data-analysis.ipynb → Full analysis notebook

---

## Author

Yazan Ballan  
