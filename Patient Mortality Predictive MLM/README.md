# Patient Mortality Prediction

## Overview

This project focuses on developing an end-to-end machine learning pipeline to predict patient mortality within 180 days of their last recorded medical visit.
The analysis was conducted using a EHR data set curated by the University of Washington as part of [the EHR Dream Challenge](https://www.synapse.org/Synapse:syn18405991/wiki/589657) 

The project was completed as part of the **HIDS 6001: Massive Health Data Fundamentals** course in Health Informatics and Data Science Graduate Program at Georgetown University.

---

## Objectives

1. **Predict patient mortality** within 180 days using retrospective data.
2. Design and implement a **machine learning pipeline** tailored for healthcare datasets.
3. Address challenges such as **class imbalance** and integrate domain-specific features for model training.


## Contributions

- **Austin Cherian**  
  - Extracted the age feature, ran the logistic regression and random forest models, performed hyperparameter tuning, and conducted the feature importance analysis.  
  - Worked on the presentation slides and final report.  

- **Hanane Bousfoul**  
  - Calculated the outcome variable, identified and grouped the conditions of interest, and transformed them into binary features.  
  - Merged demographic data, analyzed the results from various models, and worked on the presentation slides and final report.  

- **Natalie Ellis**  
  - Performed EDA on observations and identified high-risk admissions using keyword searches.  
  - Analyzed the medications table, categorized high-risk drugs into relevant groups, and created binary flags for these categories.  
  - Ran the models for Feature Group 2 and worked on the presentation slides and final report.  

---

## References

1. [EHR DREAM Challenge - Synapse.org](https://www.synapse.org/Synapse:syn18405991/wiki/589657)
2. [Charlson Comorbidity Index - MDCalc](https://www.mdcalc.com/calc/3917/charlson-comorbidity-index-cci)
