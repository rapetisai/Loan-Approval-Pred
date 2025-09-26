# Loan Approval Prediction

A supervised ML project to predict loan approvals using applicant and loan attributes. Includes end-to-end steps from EDA and preprocessing to model training, evaluation, and reproducibility.

## 🔍 Problem
Given applicant features (e.g., income, credit characteristics) and loan attributes, predict whether a loan should be **approved**.

## 📦 Repository Contents
- `LoanApprovalPred.ipynb` — full workflow: EDA → preprocessing → modeling → evaluation
- `Loan Approval Project Report.pdf` — concise write-up (data prep, models, results, recommendations)
- `data/` — (optional) place your dataset here if not using Colab

## 📊 Dataset
- Source: Kaggle “Loan Approval” dataset (binary target: `loan_status`)
- Size (as used in the report): ~45,000 rows, 14 attributes
- Target: `loan_status` (Approved / Rejected)
> _If your file path differs, update it in the notebook. Current notebook expects `/content/loan_data.csv` (Colab)._

## 🧰 Tech Stack
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
