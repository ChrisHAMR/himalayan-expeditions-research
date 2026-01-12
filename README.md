# Himalayan Expeditions Research — Statistical Modeling Case Study

This repository presents a **secondary statistical research case study** designed
to demonstrate the transferability of modern statistical modeling techniques to a
complex, non-financial, real-world dataset.

Using a comprehensive dataset of Himalayan expeditions, the project illustrates
an end-to-end analytical workflow—from data validation and exploratory analysis to
survival modeling, predictive analysis, and integrated synthesis—emphasizing
**uncertainty, censoring, nonstationary risk, and real-world data limitations**.
The primary objective is to demonstrate **methodological transferability** beyond
financial risk applications.

---

## Dataset Description

The dataset contains expedition-level information on Himalayan expeditions,
including:

- expedition characteristics and logistics  
- routes, seasons, and host regions  
- team composition and oxygen use  
- summit outcomes and expedition termination  
- fatality and survival indicators  

The dataset comprises approximately **11,400 expeditions** with **65 variables**,
spanning more than a century of Himalayan climbing history. Variables exhibit mixed
data types and substantial, structured missingness reflective of real-world
reporting and archival practices.

(See `data/raw/Himalayan Expeditions.xlsx` for the original data structure.)

---

## Project Structure & Phases

### Phase 1 — Data Foundation ✅ *Completed*
- Data ingestion, cleaning, and documentation  
- Identification and characterization of missingness patterns  
- Exploratory data analysis (EDA)  
- Assessment of temporal structure, imbalance, and data limitations  

_No statistical modeling is performed in this phase; the focus is strictly on data
integrity, transparency, and reproducibility._

---

### Phase 2 — Statistical Modeling (Survival Analysis) ✅ *Completed*
- Kaplan–Meier survival estimation  
- Log-rank tests for group comparisons  
- Cox proportional hazards modeling  
- Hazard ratio interpretation  
- Diagnostic evaluation of proportional hazards assumptions  

This phase models expedition outcomes using a **time-to-event framework under
right-censoring**, explicitly treating expedition failure risk as a
time-dependent process.

---

### Phase 3 — Predictive Modeling (Machine Learning) ✅ *Completed*
- Logistic regression as a predictive baseline  
- Random forest classification for nonlinear structure  
- Feature importance analysis  
- Predicted probability distributions for success and failure  
- Comparative model evaluation  

Predictive modeling is used as a **complement** to inferential survival analysis,
emphasizing probabilistic interpretation and uncertainty rather than pure
classification accuracy.

---

### Phase 4 — Integration & Synthesis ✅ *Completed*
- Unified interpretation of inferential and predictive results  
- Framing expedition failure as a **time-domain risk process**  
- Evidence of nonstationary and regime-dependent risk behavior  
- Interpretation of early expedition failure as extreme risk realization  
- Discussion of irreducible uncertainty and limits of prediction  

No new models are introduced in this phase; all results are synthesized from
validated outputs in Phases 1–3.

---

## Methodological Emphasis

This project emphasizes:

- survival analysis and censoring  
- hazard-based and time-domain risk modeling  
- nonstationarity and regime-dependent behavior  
- probabilistic prediction under uncertainty  
- model diagnostics and interpretation  
- reproducible research workflows  

The goal is **demonstration of statistical competency and methodological rigor**,
not domain specialization in mountaineering research.

---

## Disclaimer

This project is intended for academic and research demonstration purposes only.  
All analyses are observational and do not imply causal conclusions.

---

**Status:** ✅ Completed (Secondary Research Project)
