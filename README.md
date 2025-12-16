# Himalayan Expeditions Research

This project analyzes Himalayan expedition outcomes using statistical modeling, with a focus on survival analysis, uncertainty quantification, and probabilistic prediction.

The goal is to demonstrate the application of statistical reasoning to a real, complex, non-financial dataset involving censoring, rare events, and heterogeneous risk factors.

---

## Research Objective

To understand how environmental, temporal, and expedition-level factors influence:
- survival and fatality risk,
- summit success probability,
- and outcome uncertainty in high-risk mountaineering expeditions.

This project emphasizes **statistical interpretability** and **uncertainty-aware modeling** rather than purely predictive performance.

---

## Dataset

- Public Himalayan expeditions dataset
- ~65 variables per expedition
- Multiple decades of observations
- Key challenges:
  - right-censoring
  - missing values
  - class imbalance
  - heterogeneous risk across routes, seasons, and nationalities

---

## Project Structure & Phases

### Phase 1 — Data Foundation
**Goal:** Establish a clean and well-documented dataset.

**Key components:**
- Data exploration and documentation
- Missing value analysis
- Temporal coverage inspection
- Basic exploratory data analysis (EDA)

**Deliverables:**
- Cleaned and annotated dataset
- Initial EDA visualizations
- Data quality and limitation notes

---

### Phase 2 — Statistical Modeling (Survival Analysis)
**Goal:** Model time-to-event outcomes under censoring.

**Key components:**
- Kaplan–Meier survival curves
- Cox proportional hazards model
- Hazard ratio interpretation
- Survival comparison by:
  - climbing season
  - nationality
  - route characteristics

**Deliverables:**
- Survival curves and hazard estimates
- Statistical interpretation of risk factors
- Draft methodology and results sections

---

### Phase 3 — Advanced Modeling (Predictive Analysis)
**Goal:** Complement inferential models with probabilistic prediction.

**Key components:**
- Logistic regression for summit success
- Random forest classifier
- Feature importance analysis
- Predicted probability distributions
- Model comparison and limitations

**Deliverables:**
- Predictive performance summaries
- Feature importance visualizations
- Interpretation of model uncertainty

---

### Phase 4 — Final Paper & Documentation
**Goal:** Present the project at a research-report standard.

**Key components:**
- Abstract
- Introduction
- Methods
- Results and figures
- Conclusion
- Final repository cleanup and documentation

**Deliverables:**
- Complete written report
- Final figures and tables
- Fully documented GitHub repository

---

## Methodological Emphasis

- Survival analysis and censoring
- Interpretability over black-box prediction
- Uncertainty-aware statistical modeling
- Reproducible research workflow
  
---

## Disclaimer

This project is intended for academic and research purposes only.  
All analyses are observational and do not imply causal conclusions.

---

**Status:** 🚧 Work in Progress
