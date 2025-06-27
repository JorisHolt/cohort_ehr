# Cardiovascular Risk Model Validation: Cohort vs EHR Data

This repository contains the code, documentation, and supporting files for the study comparing prediction models developed using different sources of patient data.

The goal is to assess how data source impacts model performance when predicting risk of recurrent cardiovascular events.

## Models

- **Cohort model**: Model developed on the data from the UCC-SMART cohort  
- **EHR Only**: Model developed on the data as recorded in the EHR data  
- **Augmented EHR model**: Model developed on the data as recorded in the EHR data with medical history augmented from the national registries

## Repository Structure

- [`validation_code.html`](https://jorisholt.github.io/cohort_ehr/validation_code.html)
  Full model development and validation output for all models (cohort, EHR only, augmented EHR)

- [`baseline_presence.html`](https://jorisholt.github.io/cohort_ehr/baseline_presence.html) 
  Code-based disease history presence summaries using DBC and ICD definitions

- `Validation/` — R code for model development, validation, calibration, and decision curve analysis  
- `DBC_codes/` — Code lists and logic used to define disease history from EHR data

