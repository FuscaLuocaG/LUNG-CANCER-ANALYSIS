# LUNG-CANCER-ANALYSIS

- End-to-End Clinical Risk Pipeline & Synthetic Data Fidelity Audit.

What about if we can make an estimation of survival of one of the most criticals fields in medicine of nowadays; "Lung Cancer", with the sample of 890,000 patients (Synthetic Data) and the power of the Machine Learning we can use years of records process them and get valuable insights. Thankfully to the history and the math, we can develop a system which checks for patterns that could be lost by human-eyes due to the amount of information, and get important hallmarks and behaviors of one of the most dangerous cancers in human-history, also one of the most common. So like this, we can act quick and save another life.

Project Overview
This project demonstrates two different analytical approaches to lung cancer patient data. It scales from a traditional machine learning classification task using general synthetic data to an advanced, industry-standard Survival Analysis using real clinical trial data.

Phase 1: Binary Mortality Classification (Synthetic Kaggle Data)
- *Objective:* Predict whether a patient will survive or not (Binary target: 0 or 1) based on demographic and lifestyle risk factors.
- *Data Source:* Synthetic Lung Cancer Dataset (Kaggle).
- *Tech Stack:* Python (scikit-learn), *Power BI* for stakeholder dashboards.
- *Models used:* Logistic Regression and Random Forest Classifier.
- *Evaluation Metrics:* Accuracy, Recall, and F1-Score (with a strict focus on minimizing False Negatives).
- *Core Insight:* This phase delivers a high-level business intelligence dashboard in Power BI to analyze risk factors and baseline predictions..

Phase 2: True Time-to-Event Survival Analysis (Real Clinical Data)
- *Objective:* Model when the event (mortality) is likely to occur over time, successfully handling right-censored data (patients who left the study or survived past the timeline).
- *Data Source:* *NCCTG Lung Cancer Dataset* (Real clinical trial data from the Mayo Clinic, available natively via the lifelines library).
- *Tech Stack:* Python (lifelines, scikit-survival), matplotlib.
- *Models used:* Kaplan-Meier Estimator (for clinical curves) and Cox Proportional Hazards Model.
- *Evaluation Metrics:* *Concordance Index (C-index)*.
- *Core Insight:* This phase upgrades the project to a specialized Data Science level, capturing the complex temporal dynamics required in healthcare, pharma, and insurance industries.

By spliting the data set at the very beginning of the project into these 3 blocks we make sure there is not Data-Leakeage in the model or even humans in the modeling phase.


