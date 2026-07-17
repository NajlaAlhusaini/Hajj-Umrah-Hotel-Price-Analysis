# 🕋 Hajj & Umrah Hotel Price Analysis

<p align="center">
Data Science Project
</p>

---

## Overview

This project analyzes hotel prices in **Makkah**, **Madinah**, and **Taif** during the Hajj and Umrah seasons using data science techniques. The analysis investigates how religious seasons, hotel ratings, geographical location, and booking patterns influence hotel pricing.

The project combines a custom dataset collected from Google Hotels through SerpAPI with a public hotel booking dataset to perform exploratory data analysis, predictive modeling, and comparative analysis. :contentReference[oaicite:0]{index=0}

This project was developed as part of the **IT362 – Data Science** course at **King Saud University**.

---

## Objectives

- Analyze hotel price trends across different cities.
- Compare hotel prices during Hajj, Ramadan, Pre-Hajj, and Regular Umrah.
- Study the relationship between hotel ratings and prices.
- Compare a custom dataset with a public hotel booking dataset.
- Build and evaluate machine learning models for hotel price prediction. :contentReference[oaicite:1]{index=1}

---

## Project Resources

### Jupyter Notebook

The complete data analysis, preprocessing, visualizations, and machine learning models.

**Notebook**

[DataScience.ipynb](DataScience.ipynb)

---

### Project Presentation

The presentation explains the research, methodology, EDA, modeling process, and results.

**Presentation**

[Data Science Presentation](Data%20science%20Presentation.pdf)

---

## Dataset

### Primary Dataset

Collected using **SerpAPI (Google Hotels API)** covering hotels in:

- Makkah
- Madinah
- Taif

The dataset includes:

- Hotel Name
- Price (SAR)
- Rating
- Reviews
- City
- Check-in / Check-out Dates
- Season Type
- Religious Context

---

### Secondary Dataset

Public Hotel Booking Dataset used for comparison and validation.

---

## Project Workflow

- Data Collection
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Model Evaluation
- Result Interpretation

---

## Machine Learning Models

The project evaluates multiple regression models:

- Mean Baseline
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Linear Regression achieved the best overall performance among the evaluated models. :contentReference[oaicite:2]{index=2}

---

## Key Findings

- Hotel prices are highest in Makkah.
- Ramadan and Pre-Hajj show noticeable price increases.
- Hotel ratings have little correlation with hotel prices.
- Geographic location has a significant influence on pricing.
- Simpler models outperformed more complex tree-based models for this dataset. :contentReference[oaicite:3]{index=3}

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SerpAPI
- Jupyter Notebook

---

## Course Information

**Course:** IT362 – Data Science

**Institution:** King Saud University
