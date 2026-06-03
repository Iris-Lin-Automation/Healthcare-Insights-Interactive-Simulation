# Healthcare Data Analytics: Survival Modeling & Consumable Cost Optimization

## 📌 Project Overview
This repository contains the end-to-end data pipeline, statistical modeling, and commercial reporting for a healthcare analytics project. The project successfully bridges hard clinical data science with data-driven corporate decision-making.

The analysis is divided into two core phases:
1. **Clinical Predictive Modeling:** Developing an R-based Nomogram model using an N=3,964 dataset to forecast 1-year and 3-year survival probabilities for lung cancer brain metastasis.
2. **Commercial Cost-Control Analytics:** Conducting a quantitative metric analysis on medical consumable ratios and overspending patterns for endoscopic staplers (manual vs. electric).

---

## 🛠️ Tech Stack & Architecture
* **Data Engineering & Cleaning:** Power Query & R (Tidyverse) for automated data cleaning and anomaly detection.
* **Statistical Modeling:** R (`rms`, `survival` packages) for Cox Proportional Hazards regression and Nomogram visualization.
* **Commercial Reporting:** Structured into an executive-ready, bilingual (English/Chinese) Evidence-Based Market Insight Report.

---

## 📂 Repository Structure
```text
├── data/
│   └── mock_healthcare_data.csv  # Anonymized/sample data for demonstration
├── scripts/
│   ├── 01_data_cleaning.R        # Automated data pipeline & validation
│   └── 02_survival_nomogram.R    # Cox regression & Nomogram plotting
├── output/
│   ├── nomogram_plot.png         # High-resolution model visualization
│   └── executive_summary.pdf     # McKinsey-style commercial presentation (PDF)
└── README.md                     # Project documentation
