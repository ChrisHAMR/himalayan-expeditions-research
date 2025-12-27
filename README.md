# Himalayan Expeditions Research — Statistical Modeling Case Study

This project is a **secondary research case study** demonstrating the application of statistical methods to a complex, non-financial dataset.

Using a comprehensive Himalayan expeditions dataset, the project illustrates an end-to-end statistical workflow — from data cleaning and exploratory analysis to survival modeling and predictive methods — with a focus on uncertainty, censoring, and real-world data complexity.

The primary purpose of this repository is to show **methodological transferability** of statistical skills beyond financial applications.

---

## Dataset Description

The dataset contains expedition-level and climber-level information on Himalayan expeditions, including:

- expedition characteristics  
- climber demographics and experience  
- routes, seasons, and peaks  
- summit outcomes  
- fatality and survival indicators  

The dataset includes approximately **65 variables** with mixed data types and non-trivial missingness patterns.

(See `Himalayan Expeditions.xlsx` for raw data structure.)

---

## Project Phases

### Phase 1 — Data Foundation
- Data loading, cleaning, and documentation  
- Handling missing values and inconsistencies  
- Exploratory data analysis (EDA)  
- Identification of imbalance and temporal patterns  

_No modeling is performed in this phase._

---

### Phase 2 — Statistical Modeling (Survival Analysis)
- Kaplan–Meier survival curves  
- Cox proportional hazards model  
- Hazard ratio interpretation  
- Survival comparisons by:
  - season  
  - nationality  
  - route characteristics  

This phase focuses on **time-to-event modeling under censoring**.

---

### Phase 3 — Advanced Modeling (Predictive Analysis)
- Logistic regression for summit success prediction  
- Random forest classifier  
- Feature importance analysis  
- Predicted probability distributions  
- Model comparison  

Predictive modeling is used here as a complement to inferential analysis.

---

### Phase 4 — Final Documentation
- Abstract  
- Introduction  
- Methods  
- Results and figures  
- Conclusion  
- Final repository organization  

---

## Methodological Emphasis

This project emphasizes:

- survival analysis and censoring  
- hazard modeling and interpretation  
- probabilistic prediction  
- uncertainty-aware modeling  
- reproducible research workflow  

The goal is **demonstration of statistical competency**, not domain specialization in mountaineering research.

---

## Disclaimer

This project is intended for academic and research purposes only.  
All analyses are observational and do not imply causal conclusions.

---

**Status:** 🚧 Work in Progress
