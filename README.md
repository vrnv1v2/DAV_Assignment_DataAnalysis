# Multi-Domain Data Analytics & Machine Learning Suite

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-%23145A32.svg?style=flat)](https://xgboost.readthedocs.io/)
[![NLTK](https://img.shields.io/badge/NLTK-NLP-Green.svg)](https://www.nltk.org/)

This repository contains end-to-end analytical and machine learning workflows built to solve seven diverse, real-world data problems[cite: 1]. The work spans energy analytics, pollution trend assessment, market segmentation, supervised and unsupervised ML, model validation, and NLP-based spam detection, based on the structured assignment described in the accompanying PPT.

> 🏆 **Project Impact:** Based on the analytical depth, engineering quality, and performance of these workflows across all seven tasks, alongside a subsequent technical interview, I was selected as a **Project Lead** in the Data Analytics and Visualization Team.

---

## 📂 Core Problems Solved

### 1. Energy Infrastructure Analytics
* **Task:** Cleaned and engineered a dataset of 46,675 rows to map regional and temporal power generation trends across India. 
* **Key Outcome:** Resolved widespread unit inconsistencies and isolated severe systemic anomalies from 2008.

### 2. Pollution Trend Assessment
* **Task:** Designed a cross-correlation framework to merge power plant operational metrics with historical CPCB/WHO ambient air quality data.
* **Key Outcome:** Created a clear pipeline to map structural emission footprints across distinct corporate and public energy sectors.

### 3. Safety Capacity & Operations Audit
* **Task:** Engineered a risk-tracking operational delta matrix ($\text{Installed Capacity} - \text{Actual Energy Generated}$).
* **Key Outcome:** Identified that while 78% of plants have room to safely scale, critical over-capacity hotspots exist—revealing that ~50% of dangerously strained plants are operated by Private IPPs.

### 4. Supervised ML: Strategic Market Segmentation
* **Task:** Addressed non-linear customer profiles featuring highly independent variables where traditional imputation failed.
* **Key Outcome:** Built a pipeline utilizing mode-imputation, categorical label encoding, data scaling, and an optimized **XGBoost Classifier** tuned via `GridSearchCV`.

### 5. Unsupervised ML: Cluster Replication
* **Task:** Re-engineered the segmentation task for a zero-label testing environment to uncover latent customer traits without historic grouping boundaries.
* **Key Outcome:** Deployed **K-Means Clustering** ($K=4$) and conducted rigorous structural diagnostic comparisons against the supervised models.

### 6. Model Validation & Forecasting Diagnostics
* **Task:** Evaluated and diagnosed a daily renewable energy production time-series model displaying severe regular deviations and high variance.
* **Key Outcome:** Mapped actionable architectural fixes including dimensionality reduction for co-linearity, feature engineering, and dropout/early-stopping regularization.

### 7. NLP-Based Spam Detection
* **Task:** Built a text processing architecture to clean, tokenize, and strip stop-words from unstructured email corpora.
* **Key Outcome:** Benchmarked multiple models to deploy a highly accurate **Logistic Regression Classifier** achieving a **97% overall accuracy** and an $F_1$-score of $0.94$.

---

## 🛠️ Technical Stack
* **Core Analytics:** `Pandas`, `NumPy`, `SciPy`
* **Machine Learning:** `Scikit-Learn` (`GridSearchCV`, `StandardScaler`, `SimpleImputer`), `XGBoost`
* **Natural Language Processing:** `NLTK` (Text Regularization, Vectorization, Normalization)
* **Visualization:** `Matplotlib`, `Seaborn`

---

## 🚀 Execution & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
