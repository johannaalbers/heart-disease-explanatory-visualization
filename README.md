# Heart Disease – Diagnostic Markers Visualization  
Exploratory Analysis (Python) + Explanatory Dashboard (Power BI)

---

## Project Overview

This project investigates diagnostic markers for heart disease using structured clinical data.

The goal was to:

- Perform exploratory data analysis
- Identify statistically significant predictors
- Translate findings into an explanatory visualization
- Communicate clinically relevant insights to healthcare professionals

---

## Dataset

CardioHealth Risk Assessment Dataset  
Source: Kaggle (MIT License)  
https://www.kaggle.com/datasets/kapoorprakhar/cardio-health-risk-assessment-dataset

The dataset contains:

- 270 patients
- 14 clinical variables
- Binary outcome: Heart Disease (Presence / Absence)

---

## Exploratory Analysis (Python)

Performed using:

- pandas
- numpy
- seaborn
- matplotlib
- scipy

Key findings:

- Exercise-related variables (Max Heart Rate, ST Depression, ST Slope) show strong separation between groups.
- Cholesterol shows weaker but significant differences.
- Resting blood pressure not statistically significant (p ≈ 0.11).

Statistical tests used:

- t-tests
- Chi-square tests
- Likelihood ratio test

---

## Explanatory Dashboard (Power BI)

The final visualization was built using Microsoft Power BI Desktop.

Main message:

> Functional stress-test variables show a much stronger separation between patients with and without heart disease than traditional resting indicators such as cholesterol.

Dashboard highlights:

- Max Heart Rate vs ST Depression (strong separation, p < 0.001)
- ST Slope distribution (Chi-square, p < 0.001)
- Resting Blood Pressure comparison
- Log-transformed cholesterol distribution

---

## Intended Audience

Cardiologists and healthcare professionals aiming to:

- Improve early detection of heart disease
- Understand which diagnostic markers provide the strongest separation

---

## Tools Used

Exploratory phase:
- Python 3.11
- pandas
- seaborn
- matplotlib
- scipy

Explanatory phase:
- Microsoft Power BI Desktop (v2.137.751.0)

---

## Skills Demonstrated

- Exploratory data analysis
- Statistical hypothesis testing
- Clinical interpretation
- Data storytelling
- Dashboard design
- Translating analytics into decision-support visuals
