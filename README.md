# Predictive Quality for Injection Moulding

Machine learning framework for predicting **injection moulding defect types** from industrial process data using **leakage-aware evaluation** and **interpretable machine learning**.

## Overview

Traditional quality inspection detects defects only after a part is manufactured, resulting in material and production losses. This project predicts **seven defect types** directly from machine process data, enabling early quality assessment and supporting process optimization.

## Key Features

- Predicts **7 injection moulding defects**
- Multi-label classification
- Leakage-free feature engineering
- Honest grouped cross-validation
- Comparison of classical ML and Deep Learning (TCN)
- Interpretable predictions with process recommendations

## Dataset

- **564** production cycles
- **47** experimental settings
- **334** process variables
- **2** materials (PP & ABS)

> **Note:** The ProBayes dataset is not included in this repository and must be obtained from the original source.

## Models Evaluated

- Logistic Regression
- Random Forest
- Histogram Gradient Boosting
- Temporal Convolutional Network (TCN)

## Results

| Metric | Score |
|---------|------:|
| Honest Macro ROC-AUC | **0.895** |
| OK/NOK ROC-AUC | **0.942** |
| OK/NOK F1 Score | **0.879** |
| Validated Process Rules | **6 / 7** |

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Matplotlib

## Repository Structure

```
quality-predictor/
│── quality_predictor_final.ipynb
│── README.md
│── requirements.txt
├── report/
│   ├── Quality_Predictor_Report.pdf
│   └── Presentation.pdf
```

## Team

- Abeera Biju
- Pratiksha Satish Ramane
- Ephraim Neke Kamalu
- Geo Shajan

**Supervisor:** Prof. Dr.-Ing. Felix G. Müller

---

*Developed as part of the M.Sc. Industrial Artificial Intelligence programme at Hochschule Albstadt-Sigmaringen.*
