# Hospital Length of Stay Prediction

## SCI Paper Reproduction and Reanalysis using R

**NYCU Quantitative Data Analysis Final Project**

---

## Overview

This project reproduces and extends the methodology described in:

**Jain et al. (2024)**

The study predicts hospital Length of Stay (LoS) using machine learning models on the New York SPARCS inpatient discharge dataset.

The entire workflow is implemented in **R 4.6.1** using **Jupyter Notebook** on **Apple Silicon macOS**.

---

## Objectives

### Reproduction

- Data Audit
- Data Preprocessing
- Exploratory Data Analysis
- Regression Models
- Classification Models
- Model Evaluation

### Reanalysis

- Random Forest Feature Importance
- Decision Tree Interpretation
- Permutation Importance
- Clinical Interpretation
- Error Analysis

---

## Workflow

```text
01 Data Audit
        ↓
02 Preprocessing
        ↓
03 Exploratory Data Analysis
        ↓
04 Model Development
        ↓
05 Model Evaluation
        ↓
06 Model Interpretation
        ↓
07 Discussion
```

---

## Repository Structure

```text
notebook/
figures/
output/
report/
paper/
```

---

## Environment

- macOS Apple Silicon
- R 4.6.1
- Jupyter Notebook
- IRkernel

---

## Main Packages

- tidyverse
- ranger
- Matrix
- data.table
- rpart
- ggplot2

---

## Dataset

The original SPARCS dataset is **NOT** included due to licensing restrictions.

Please download it from the New York State Department of Health（https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/gnzp-ekau/about_data）.

---

## Reference

Jain et al. (2024)

Hospital Length of Stay Prediction Using Machine Learning Techniques.

---

## Author

Wei-Ping Li

National Yang Ming Chiao Tung University
