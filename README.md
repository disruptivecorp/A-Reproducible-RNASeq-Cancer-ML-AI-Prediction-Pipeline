# A-Reproducible-RNASeq-Cancer-ML-AI-Prediction-Pipeline
A Reproducible Cancer ML/AI Prediction Pipeline Trained on TCGA Pan-Cancer RNA-seq Data (11,000 patient samples across 33 cancer types)

# Cancer Prediction Model (Binary and Multiclass) – TCGA PANCAN Dataset

This project trains machine learning models on the TCGA Pan-Cancer dataset (>10,000 patients, 33 cancer types) to predict cancer presence and classify cancer type from genomic data.

The workflow is divided into four parts:

1. **Exploratory Data Analysis (EDA)**
   - Cleaned and analyzed raw RNA-seq expression data.
   - Processed and merged genomic data with metadata.

2. **ML Pipeline Setup**
   - Applied variance-based feature selection.
   - Tested off-the-shelf models for binary and multiclass classification.
   - Scaled and split the data for training and evaluation.

3. **Binary Classifier (Cancer vs. Non-Cancer)**
   - Hyperparameter tuning with cross-validation.
   - Built a stacking model combining Logistic Regression and XGBoost.
   - Achieved ~99% accuracy.

4. **Multiclass Classifier (Cancer Type Classification)**
   - Trained on 33 cancer types.
   - Used hyperparameter tuning and stacking ensemble.
   - Achieved ~97.6% accuracy across cancer types.

---

## Key Features
- Full exploratory data analysis of genomic and metadata.
- Machine learning pipeline automation for preprocessing and evaluation.
- Stacking ensemble approach for state-of-the-art performance.
- Results validated with accuracy, precision, recall, and F1 score.

## Results
- **Binary Classification:** 99%
- **Multiclass Classification:** 97.6%

## Repository Contents
- `eda_ML_cancer_genomics_final_scaffa.ipynb` – Full EDA, training, and analysis (long runtime).
- `grading_document.ipynb` – Lightweight notebook to reproduce results quickly.
