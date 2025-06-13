# Stimulus Usage Prediction with Interpretable Machine Learning

This repository contains the analysis and modeling code for a research project conducted at the University of Georgia's AFiRM Lab under the supervision of Professor Gaurav Sinha.

## 🧠 Project Overview

This study investigates whether machine learning models can accurately predict how individuals used their COVID-19 stimulus payments — specifically whether they **spent**, **saved**, or **paid down debt** — based on pre-existing financial vulnerability indicators.

We use the 2021 **National Financial Capability Study (NFCS)** microdata and apply a range of models including logistic regression, random forest, and XGBoost. We further interpret the models using **SHAP (SHapley Additive Explanations)** to extract insights about which features influenced each class of behavior.

## 📊 Key Contributions

- **Data Engineering**: Cleaned and labeled a behavioral outcome from NFCS survey responses.
- **Modeling**: Trained and tuned classifiers with class imbalance handling.
- **Interpretability**: Applied SHAP to analyze feature importance globally and per class.
- **Policy Relevance**: Identified financial fragility, income volatility, and savings access as key predictors of stimulus usage.

## 📁 What’s Inside

| Folder | Description |
|--------|-------------|
| `notebooks/` | Contains all EDA, modeling, and interpretation notebooks |
| `plots/` | Visualizations used in the paper (e.g., SHAP plots, confusion matrix) |
| `outputs/models/` | Trained model and label encoder (excluded from GitHub) |
| `data/` | Cleaned CSVs and intermediate files (excluded from GitHub) |

> ⚠️ Raw data from the NFCS is not included due to licensing. Users should request access via the FINRA Foundation.

## 📍 Status

📝 This research is currently in the **process of being prepared for publication**.  
Please cite or contact the authors before reusing material.

## 🧪 Lab & Affiliation

This project was conducted as part of undergraduate research in the  
**AFiRM Lab**  
at the **University of Georgia**, under the direction of **Dr. Gaurav Sinha**.

## 📬 Contact

- **Lead Researcher**: Varun Venkatagiri  
- **Lab**: https://afirm.uga.edu  
- **Email**: [your-email@example.com]

