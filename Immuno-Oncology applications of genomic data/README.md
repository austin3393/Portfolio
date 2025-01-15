# Immuno-Oncology Applications of Genomic Data: Bladder Cancer

## Project Overview

This project was conducted as part of the **HIDS-7003-01 Final Project** 
to explore molecular and immune-related changes in **Bladder Cancer** using genomic data. 
The primary goal was to identify potential biomarkers, pathways, and immune cell types associated with different stages of bladder cancer, 
providing insights into diagnostics and treatment from an **Immuno-Oncology** perspective.
Our team specifically focused on comparing Pre-cancerous Tissue (Bladder Cancer Surrounding Mucosa) to Normal Tissue samples to uncover biomarkers and therapeutic targets. 
The ultimate goal was to facilitate the early detection of bladder cancer and prevent its progression into invasive stages.
## Major Steps

### Step 1: Differential Gene Expression Analysis (individual)
-Compiled a list of differentially expressed genes (DEGs) by comparing precancerous tissue samples to normal tissue samples from the bladder mucosa using **T-test group comparison** in R.


### Step 2: Pathway and Gene Ontology Enrichment Analysis (individual)
- Conducted **pathway enrichment** and **gene ontology (GO) enrichment** analysis for DEGs (differentially expressed genes) using EnrichR package in R.
- Identified statistically significant pathways associated with the DEGs.

### Step 3: Immuno-Oncology Analysis (individual)
- Utilized the **CIBERSORT** package to analyze and compare the average immune cell type profiles between precancerous and normal tissue samples.

### Step 4: Comparative Analysis (group)
- Compared results from **pathway enrichment** and **CIBERSORT** analysis to identify key tumor-related pathways and immune responses.


### Step 5: Results and Discussion (group)
- Selected important tumor-related and immune-related pathways, top-ranked DEGs, and immune cell types.
- Conducted an analysis to demonstrate how the dysfunction of specific pathways and alterations in immune cell type proportions contribute to tumorigenesis and immune evasion, supported by existing scientific literature.


---
## Tools and Techniques

- **Programming Language:** R
- **Bioinformatics Tools:** 
  - Gene expression analysis using T-test
  - Systems biology and pathway analysis
  - Immune cell profiling with CIBERSORT

---

## Team Members

- **Austin**: conducted DEG identification, EnrichR pathway analysis, Cibersort immune profiling and Stacked Bar plot individually. Also, added analysis of the "Toll-like Receptor Cascades (R-HSA-168898)" pathway. 

---



For further information, feel free to explore the presentation slides and generated output files included in this repository.
