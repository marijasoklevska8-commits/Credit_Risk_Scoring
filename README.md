# 💳 Credit Risk Scoring

## Machine Learning for Loan Default Prediction

> A complete end-to-end machine learning project for predicting loan
> default using the German Credit dataset. The project compares multiple
> classification algorithms, evaluates fairness, investigates temporal
> generalization, and applies cost-sensitive decision analysis.

------------------------------------------------------------------------

## 📌 Project Overview

This project was developed as part of the **Avenga Academy Data Science
Program**.

The objective is to build an interpretable and reliable credit risk
scoring model capable of identifying loan applicants with a high
probability of default.

### Project Sections

-   Exploratory Data Analysis (EDA)
-   Modeling
-   Research Direction
-   Conclusions

------------------------------------------------------------------------

## 🎯 Business Problem

Banks must decide whether to approve or reject loan applications.

Two types of errors have different business consequences:

-   **False Positive** -- Rejecting a reliable customer
-   **False Negative** -- Approving a borrower who later defaults

The goal is to minimize business risk while maintaining strong
predictive performance.

------------------------------------------------------------------------

## 📊 Dataset

### German Credit Dataset

  Property   Value
  ---------- ---------------------------------
  Source     UCI Machine Learning Repository
  Samples    1,000
  Features   20
  Task       Binary Classification

Target

``` text
0 = Good Credit
1 = Default
```

### External Validation

-   South German Credit Dataset

------------------------------------------------------------------------

## 📁 Repository Structure

``` text
CreditRisk.ML/
│
├── data/
│   ├── german_credit/
│   └── south_german_credit/
│
├── notebooks/
│   └── Project_Credit_Risk_Scoring.ipynb
│
├── presentation/
│   └── Credit_Risk_Scoring_Presentation.pdf
│
├── README.md

```

------------------------------------------------------------------------

## ⚙️ Installation

``` bash
pip install -r requirements.txt
```

Required libraries include:

-   numpy
-   pandas
-   matplotlib
-   scipy
-   scikit-learn
-   joblib
-   jupyter
-   ipykernel
-   openpyxl

------------------------------------------------------------------------

## 🚀 Running the Project

``` bash
jupyter notebook
```

Open:

``` text
Project_Credit_Risk_Scoring.ipynb
```

Then execute:

``` text
Kernel → Restart & Run All
```

------------------------------------------------------------------------

## 🤖 Machine Learning Models

-   Logistic Regression
-   Decision Tree
-   Random Forest
-   Neural Network (MLP)

Evaluation Metrics

-   Accuracy
-   Precision
-   Recall
-   F1 Score
-   ROC-AUC

Cross-validation uses **Stratified 5-Fold Cross Validation**.

------------------------------------------------------------------------

## 📈 Project Results

### Best Model --- Random Forest

  Metric              Value
  ------------- -----------
  CV Accuracy     **0.765**
  CV F1 Score     **0.601**
  CV ROC-AUC      **0.799**

### German Test Set

  Metric           Value
  ---------- -----------
  Accuracy     **0.785**
  F1 Score     **0.639**
  ROC-AUC      **0.804**

### South German Validation

  Metric           Value
  ---------- -----------
  Accuracy     **0.882**
  F1 Score     **0.800**
  ROC-AUC      **0.941**

------------------------------------------------------------------------

## 🔬 Research Direction

-   Temporal Generalization
-   Algorithmic Fairness Screening
-   Model Interpretability
-   Cost-sensitive Threshold Optimization

------------------------------------------------------------------------

## 📂 Project Outputs

Running the notebook generates:

-   Exploratory Data Analysis
-   Model Comparison
-   Confusion Matrix
-   ROC Curve
-   Temporal Validation
-   Fairness Analysis
-   Feature Importance Analysis
-   Cost-sensitive Threshold Analysis
-   Final Conclusions

------------------------------------------------------------------------
