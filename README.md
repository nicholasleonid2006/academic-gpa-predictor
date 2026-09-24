# 🌙 Academic GPA Predictor (ML Analysis)

> *Exploring the hidden boundaries between sleep metrics, circadian consistency, and semester GPA performance.*

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## Overview

Predicts student GPA using sleep tracking metrics from Carnegie Mellon University and University of Washington datasets ($n=634$).

- **Exploratory Data Analysis:** Feature distributions and correlation matrices connecting sleep metrics to academic results.
- **Predictive Model:** Gradient Boosting Regressor pipeline for GPA forecasting.
- **Interactive UI:** Streamlit app for real-time GPA predictions and visualization.
---

## Repository Structure

```text
ML - Sleep Quality/
├── data/
│   ├── cmu-sleep.csv         # Raw dataset
│   └── cmu-sleep-clean.csv   # Cleaned & preprocessed dataset
├── EDA.ipynb                 # Exploratory data analysis & modeling notebook
├── app.py                    # Streamlit web application
├── requirements.txt          # Environment dependencies
└── README.md                 # Documentation
