# ⚖️ Recidivism Risk Prediction with MLP  
*A fairer approach to risk assessment in criminal justice*

## 🌟 Overview  
In the U.S. criminal justice system, decision-makers increasingly rely on AI-based risk assessment tools—such as **COMPAS**—to estimate an individual’s likelihood of reoffending. However, these tools are far from impartial.

A [landmark ProPublica investigation](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) exposed troubling patterns:
- **Black defendants** are disproportionately labelled as “high risk” even when they do not reoffend (high false-positive rates).
- **White defendants** who reoffend are more likely to be wrongly assessed as low-risk (high false-negative rates).

This project proposes a **Multi-Layer Perceptron (MLP)** model aimed at reducing this diagnosis bias, offering a more equitable alternative to current tools.

## 🌟 Project Structure  
- `final_mlp.ipynb` — Core notebook containing the MLP model, evaluation metrics, and visualisations.
- [Dataset Repository](https://github.com/propublica/compas-analysis) — Original data and analysis scripts by ProPublica.
- [Extended Project Repo](https://github.com/devyanimahajan/compas-analysis) — Additional models, preprocessing steps, and exploratory analysis.

## 🌟 Model Highlights  
- Implemented using **PyTorch**
- Trained on COMPAS dataset features (demographics, prior offenses, charge degree)
- Evaluated with **confusion matrices**, **ROC-AUC**, and **feature importance analysis**
- Focused on **mitigating racial bias** in predictions

## 🌟 Academic Context  
This model was developed as part of a **final project** for the **Machine Learning II** course at the **University of Chicago** (MS in Applied Data Science).

---
