# 🧬 Machine Learning–Based Classification and Biomarker Discovery in Triple-Negative Breast Cancer (TNBC)

> An end-to-end computational biology pipeline integrating machine learning, bioinformatics, network biology, survival analysis, and explainable AI for the identification of prognostic biomarkers in Triple-Negative Breast Cancer.

---

## 📖 Overview

Triple-Negative Breast Cancer (TNBC) is one of the most aggressive breast cancer subtypes, characterized by the absence of estrogen receptor (ER), progesterone receptor (PR), and HER2 expression. Due to the lack of targeted therapies, identifying reliable prognostic biomarkers remains a significant research challenge.

This project presents a reproducible computational workflow that integrates transcriptomic analysis, machine learning, functional enrichment, protein interaction analysis, survival analysis, and explainable AI to identify biologically meaningful biomarkers associated with TNBC.

---

# 🎯 Objectives

- Develop machine learning models to classify TNBC samples.
- Identify consensus biomarkers across multiple ML algorithms.
- Perform functional enrichment analysis.
- Construct Protein–Protein Interaction (PPI) networks.
- Identify hub genes using network centrality analysis.
- Evaluate prognostic significance using Kaplan–Meier survival analysis.
- Interpret model predictions using SHAP (Explainable AI).

---

# 🧬 Dataset

**Source**

- The Cancer Genome Atlas (TCGA-BRCA)

**Data Used**

- Gene expression (RNA-Seq)
- Clinical information

---

# ⚙️ Computational Workflow

```text
TCGA-BRCA Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Differential Gene Expression Analysis
        │
        ▼
Machine Learning Models
(Random Forest, ExtraTrees,
XGBoost, CatBoost)
        │
        ▼
Consensus Biomarker Selection
        │
        ▼
GO / KEGG / Reactome Enrichment
        │
        ▼
STRING PPI Network
        │
        ▼
Hub Gene Identification
        │
        ▼
Kaplan–Meier Survival Analysis
        │
        ▼
SHAP Explainability
        │
        ▼
Final Validated Biomarkers
```

---

# 🤖 Machine Learning Models

- Random Forest
- ExtraTrees
- XGBoost
- CatBoost

Models were compared to identify robust and reproducible biomarker candidates.

---

# 🔬 Bioinformatics Analyses

- Differential Gene Expression
- Gene Ontology (GO)
- KEGG Pathway Analysis
- Reactome Pathway Analysis
- STRING Protein–Protein Interaction Network
- Hub Gene Analysis
- Kaplan–Meier Survival Analysis
- SHAP Explainability

---

# 📂 Repository Structure

```
TNBC-Prognostic-Biomarkers
│
├── notebooks/
├── data/
│   ├── raw/
│   ├── processed/
│   └── validation/
│
├── outputs/
├── figures/
├── docs/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 📊 Key Outputs

- Consensus Biomarkers
- Functional Enrichment Results
- Protein–Protein Interaction Network
- Hub Gene Ranking
- Kaplan–Meier Survival Analysis
- SHAP Feature Importance
- Final Validated Biomarkers

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- GSEApy
- NetworkX
- Matplotlib
- SHAP

---

# 🚀 Future Scope

- External validation using independent TNBC cohorts.
- Experimental validation of candidate biomarkers.
- Multi-omics integration.
- Deep learning-based biomarker discovery.

---

# 👩‍🔬 Author

**Sharmistha Debgoswami**

Biotechnology Undergraduate | Computational Biology | Bioinformatics | Machine Learning

Interested in Cancer Genomics, Precision Medicine, AI in Healthcare, and Translational Bioinformatics.
