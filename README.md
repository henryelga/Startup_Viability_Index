<div align="center">

# Startup Viability Index (SVI)

### A Composite Index for Evaluating Global Startup Ecosystems

</div>

---

# 📖 Project Overview

The **Startup Viability Index (SVI)** is a composite indicator framework developed to evaluate and compare startup ecosystem conditions across countries.

The index measures the structural conditions that support entrepreneurial activity using a multidimensional approach built around four major dimensions:

| Dimension | Description |
|---|---|
| **Finance & Investment** | Financial market access and investment activity |
| **Technology & Innovation** | Digital infrastructure and innovation capacity |
| **Economic Growth & Stability** | Macroeconomic performance and stability |
| **Talent & Productivity** | Human capital and workforce productivity |

The project follows a full composite indicator methodology including preprocessing, normalisation, correlation analysis, PCA, aggregation, validation, and visualisation.

---

# 🌍 Global Startup Viability Map

<p align="center">
  <img width="900" alt="image" src="https://github.com/user-attachments/assets/8cf5bd79-190f-4b1e-85c4-7303d5f31733" />
</p>

---

# 📊 Example Visualisations

<p align="center">
  <img width="900" alt="image" src="https://github.com/user-attachments/assets/b09ac15e-39cc-4c11-be2f-f29b95832bbe" />
</p>
<p>
  <img width="900" alt="image" src="https://github.com/user-attachments/assets/00bf5d6a-bc03-4c81-9033-f988d167dc9a" />
</p>

---

# ⚙️ Methodology

The Startup Viability Index was constructed using the following workflow:

```text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Missing Value Treatment
      ↓
Outlier Analysis
      ↓
Normalisation
      ↓
Correlation & Redundancy Testing
      ↓
Sub-Index Construction
      ↓
Weighting & Aggregation
      ↓
Composite Index Creation
      ↓
Validation & Visualisation
```
---

# 🧠 Analytical Techniques

The project applied several statistical and analytical methods throughout the index construction process:

- Correlation Analysis
- Variance Inflation Factor (VIF)
- Principal Component Analysis (PCA)
- Min-Max Normalisation
- Composite Indicator Construction
- Pearson & Spearman Correlation Validation

---

# 🏆 Key Findings

- Hong Kong, Singapore, United States, Korea, and Switzerland achieved the highest SVI scores.
- High-income economies generally demonstrated stronger startup ecosystem conditions.
- Strong positive relationships were identified between:
  - Startup Viability Index (SVI)
  - Global Innovation Index (GII)
  - Global Entrepreneurship Index (GEI)
- Innovation, finance, and talent productivity showed strong association with startup ecosystem performance.

---

# 📂 Project Structure

```text
startup-viability-index/
│
├── notebooks/
│   ├── 01_theoretical_framework.ipynb
│   ├── 02_data_selection.ipynb
│   ├── 03_data_imputation.ipynb
│   ├── 04_multivariate_analysis.ipynb
│   ├── 05_normalisation.ipynb
│   ├── 06_weighting_aggregation.ipynb
│   └── 07_link_other_indices.ipynb
│   └── 08_visualisation.ipynb
│
├── data/
│   ├── external_indices/
│   └── results/
│   └── other...
│
├── artifacts/
│   └── correlations/
│   ├── figures/
│   └── index_comparisons/
│   └── visualisations/
│
├── README.md
└── requirements.txt
```

---

# 🔀 Version Control Workflow

The project followed a structured Git workflow to maintain organisation, reproducibility, and clear development tracking.

## Practices Used

- Separate branches for major project sections
- Pull requests before merging into `main`
- Gitmoji-based commit messages
- Clean and modular repository structure
- Well-documented project workflow

---

# 📈 External Validation

The Startup Viability Index was externally validated against:

- Global Innovation Index (GII)
- Global Entrepreneurship Index (GEI)

Strong Pearson and Spearman correlations supported the reliability and consistency of the framework.

| Comparison | Pearson | Spearman |
|---|---|---|
| SVI vs GII | 0.92 | 0.95 |
| SVI vs GEI | 0.84 | 0.88 |

These results indicate strong alignment between the SVI and established global measures of innovation and entrepreneurship.

---
