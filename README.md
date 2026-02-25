# PALMARES2_Early_Progression
This repository contains the analysis pipeline used to develop and validate a machine-learning model for the prediction of early progression (i.e., disease progression occurring within 6 months from treatment initiation) in patients with HR+/HER2− advanced breast cancer treated with first-line endocrine therapy plus CDK4/6 inhibitors, within the PALMARES-2 real-world study.
The code also includes statistical analyses describing patients’ and tumor characteristics, as well as clinical outcomes, comparing patients who experienced early progression with those who did not.

## Project overview
- Data preparation (R)
- TabPFN models (Python)
- Machine learning and MLP models (R)
- Model explainability (R)
- Prediction probability visualizations (R)
- Patient and tumor characteristics analyses (R)

## Data availability
Due to General Data Protection Regulation (GDPR) restrictions, patient-level data used in this project are not publicly available.

The `data/` directory is intentionally excluded from version control.  
To reproduce the analysis, users must provide their own authorized version of the PALMARES-2 dataset (derived from the second study data cut-off) with the same variable structure.

## Reproducibility
The analysis pipeline, which contains both R and Python code, is implemented in a single Quarto document: code/PALMARES2_EARLY_PROGRESSION_ML.qmd

## Software requirements
- R (4.4.2)
- Python (3.10.11)
- Quarto

## Contact
Leonardo Provenzano: leonardo.provenzano@istitutotumori.mi.it
Claudio Vernieri: claudio.vernieri@istitutotumori.mi.it
