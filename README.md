# Cancer Survival Analysis using Kaplan–Meier Curves, Log-Rank Tests, and a Cox Proportional Hazards Model

## Project Overview
This project analyzes survival outcomes in a clinical cohort of breast cancer patients using the GBSG2 dataset (German Breast Cancer Study Group, n=686). The goal is to explore survival patterns and compare age group survivability. 

## Methods
- **Kaplan–Meier Estimator:** Non-parametric survival curves for the overall cohort and age subgroups.  
- **Log-Rank Test:** Statistical comparison of survival between age groups.  
- **Cox Proportional Hazards Model:** Multivariate regression estimating hazard ratios (HR) and assessing risk factors.

## Repository Contents
- `survival_analysis.ipynb` – Colab notebook containing full data processing, analysis, and plots.  
- `cancer-survival-analysis.pdf` – Report detailing methods, results, interpretations, and figures. 

## How to Use
1. Open `survival_analysis.ipynb` in [Google Colab](https://colab.research.google.com/).  
2. Run all cells to reproduce plots, tables, and survival analyses.  
3. Reference figures and tables in `cancer-survival-analysis.pdf` for explanations.

> **Note:** The datased is loaded programatically; no separate CSV is required. 

## License
This project is for educational and research purposes. Data is sourced from the GBSG2 dataset.
