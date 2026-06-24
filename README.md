# Quantium Retail Data Analytics Virtual Experience
> **An End-to-End Data Analytics Case Study Completed via Forage**

## 📌 Project Overview
This repository contains a comprehensive, data-driven retail analytics project modeled after real-world consultant workflows at Quantium[cite: 3, 4]. The study is divided into two core phases: commercial data engineering to uncover chips category performance, followed by a rigorous statistical evaluation of a newly implemented physical store layout across designated trial locations.

The final strategic recommendations deliver an actionable roadmap designed to maximize network revenue and optimize shelf-space assortment.

---

## 🛠️ Tech Stack & Methodologies
*   **Data Engineering & Analytics:** Python (`Pandas`, `NumPy`)[cite: 2]
*   **Data Visualization:** `Matplotlib`, `Seaborn`[cite: 2]
*   **Statistical Analysis:** Composite Baseline Matching (`Pearson Correlation Coefficient`, `Standardized Magnitude Distance`), Independent `t-Testing`
*   **Executive Reporting:** Microsoft PowerPoint, PDF Exporting[cite: 2, 4]

---

## 📂 Repository Structure
```text
├── data/                               # Raw transactional and behavioral datasets
│   ├── QVI_transaction_data.xlsx
│   └── QVI_purchase_behaviour.csv
├── notebooks/                          # Production-ready Jupyter Notebooks
│   ├── Task_1_Exploratory_Analysis.ipynb
│   └── Task_2_Trial_Evaluation.ipynb
└── final_delivery/                     # Executive stakeholder presentations
    ├── Quantium Presentation.pdf       <-- Click to view natively in browser!
    └── Quantium Presentation.pptx      <-- Original editable deck


## 📊 Core Insights & Executive Summary

### Phase 1: Customer Segmentation & Assortment Optimization
*   **Demographic Anchors:** Total category revenue is primarily anchored by two distinct groups: **Budget Older Families** (who drive the highest sales volume due to massive quantities purchased per transaction) and **Mainstream Young Singles/Couples** (who represent a premium growth segment due to a high willingness to pay premium unit prices)[cite: 4].
*   **Assortment Sweet Spot:** Granular pack-size analysis confirms that **175g variants** vastly dominate the category, generating the single highest total sales value across the entire national grid[cite: 4].
*   **Recommendation:** Prioritize shelf facings for 175g products while executing range rationalization on slower-moving, lagging smaller pack sizes[cite: 4].

### Phase 2: Physical Layout Trial Evaluation
To ensure a mathematically fair assessment of the new physical category layout, test stores were matched with control store pairs from a repository of 260+ candidate locations[cite: 4]. Stores were programmatically binned into monthly performance buckets (`{YEARMONTH} = {Year} * 100 + {Month}`) and paired using a composite baseline score prioritizing **Pearson Correlation** (trend direction) and **Standardized Magnitude Distance** (sales volume size)[cite: 4].

Independent $t$-tests proved that the layout modifications delivered overwhelming commercial success across independent test grids during the trial window, passing the 95% critical threshold baseline ($\pm2.447$)[cite: 4]:

| Performance Metric | Trial Store 77 | Trial Store 86 | Trial Store 88 |
| :--- | :---: | :---: | :---: |
| **Control Match Candidate** | Store 233 | Store 155 | Store 178 |
| **Profile Match Confidence** | **96.8%** | **94.2%** | **80.0%** |
| **Peak Sales Growth (%)** | **+36.65%** | **+31.59%** | **+22.07%** |
| **Statistical Significance ($t$-stat)**| **$t = 3.68$** | **$t = 8.38$** | **$t = 3.86$** |
| **95% Alpha Threshold ($\alpha = 0.05$)** | **Passed** | **Passed** | **Passed** |

*   **Isolating the Driver:** Parallel analysis of unique loyalty cardholders proves that revenue surges were perfectly synchronized with expanding physical customer foot traffic rather than localized inflation[cite: 4].







