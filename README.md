# 📊 Predictive Churn Analysis for Telecom X

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/status-Completed-brightgreen)]()
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 📚 Summary

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Applied Methodology](#applied-methodology)
- [Key Churn Factors](#key-churn-factors)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Strategic Recommendations](#strategic-recommendations)
- [Conclusion](#conclusion)

---

## 🚀 Project Overview

This repository contains the complete solution for the **Alura Machine Learning Challenge in partnership with Oracle (ONE)**. The challenge consisted of developing a customer churn prediction system for **Telecom X**, a fictitious company in the telecommunications sector.

The project covers the entire lifecycle of a Machine Learning project, from data analysis and preparation to training, model evaluation, and the creation of an inference pipeline. The result is a robust predictive model with **79% accuracy**, capable of identifying customers with a high probability of cancellation, providing the company with a strategic tool for retention campaigns.

---

Veja também: - [Project ETL_ONE]([#project-overview](https://github.com/CidQueiroz/etl_one))

---

## 🗂️ Repository Structure

```text
/TelecomX_BR_2
│
├── data/
│ ├── TelecomX_Data.json # Raw data provided in the challenge
│ └── telecom_data_tratado.csv # Processed data
│
├── notebooks/
│ └── TelecomX_BR_2_Completo.ipynb # Original notebook with EDA and development
│
└── README.md # Project documentation

```

---

## 🧠 Applied Methodology

The development followed a structured approach, divided into four main stages:

1. **Data Preparation**

- Loading the JSON Data

- Cleaning inconsistencies, correcting types, and removing incomplete records

2. **Feature Engineering**

- Conversion of categorical variables via **One-Hot Encoding**

- Normalization of numerical variables with **StandardScaler**

3. **Training and Evaluation**

- Models: **Logistic Regression** (baseline) and **Random Forest** (final)

- Evaluation: accuracy, precision, recall, F1-score, and confusion matrix

4. **Pipeline Construction**

- Scikit-learn pipeline integrating preprocessing and model

- Ready for production use and real-time predictions

---

## 🔑 Key Churn Factors

Feature importance analysis revealed the main churn indicators:

- **Contract Type:** Monthly contracts are the main risk factor.

- **Contract Tenure:** Customers with short tenure periods are more likely to churn.

- **Internet Service (Fiber optic):** Fiber optics is associated with higher churn, suggesting potential expectation vs. reality issues.

---

## 💻 How to Run the Notebook

### ⚙️ Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

- Install the dependencies:

``bash
pip install pandas scikit-learn matplotlib seaborn joblib

``

### ▶️ Execution

1. Open the file [`notebooks/TelecomX_BR_2_Completo.ipynb`](notebooks/TelecomX_BR_2_Completo.ipynb) in Jupyter Notebook or JupyterLab.

2. Run the cells sequentially to reproduce the entire analysis, from data preparation to generating insights and recommendations.

> 💡 **Tip:** You can run the notebook online via [Google Colab](https://colab.research.google.com/) by dragging the `.ipynb` file to the platform.

---

## 💡 Strategic Recommendations

The model's insights allow Telecom X to adopt a proactive stance in customer retention:

- 🎯 **Focus on Long-Term Contracts**: Encourage customers to migrate from monthly plans to annual or biannual contracts by offering clear benefits.

- 🤝 **Onboarding Program for New Customers**: Create a welcoming journey to ensure a positive experience in the first few months.

- 🔍 **Fiber Optic Offer Analysis**: Investigate the causes of high churn rates among fiber customers, evaluating pricing, quality, and support.

---

## 🏁 Conclusion

This project delivers not just a Machine Learning model, but an end-to-end solution that translates raw data into business intelligence.

The ability to predict churn with high accuracy allows Telecom X to allocate its resources more efficiently, maximize customer retention, and increase its revenue and market competitiveness.

---

## 📬 Contact

Questions or suggestions? Open an issue at [https://github.com/CidQueiroz/Machine_learning_alura/issues] or get in touch!

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-ciddy--queiroz-blue?logo=linkedin)](hthttps://www.linkedin.com/in/ciddy-queiroz/)

- [![Email](https://img.shields.io/badge/Email-cydy.queiroz@gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:cydy.queiroz@gmail.com)

---

<p align="center">

<img src="https://img.shields.io/badge/feito%20com-❤%20por%20Queiroz-blue" alt="Made with love by ONE and Alura"/>
</p>
