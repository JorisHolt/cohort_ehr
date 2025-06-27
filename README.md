# Cardiovascular Risk Model Validation: Cohort vs EHR Data

This repository contains the code, documentation, and supporting files for the study comparing prediction models developed using different sources of patient data.

The goal is to assess how data source impacts model performance when predicting risk of recurrent cardiovascular events.

## Models

- **Cohort model**: Model developed on the data from the UCC-SMART cohort  
- **EHR Only**: Model developed on the data as recorded in the EHR data  
- **Augmented EHR model**: Model developed on the data as recorded in the EHR data with medical history augmented from the national registries

## Repository Structure

- `Validation/` — Full validation pipeline and model evaluation  
- `DBC_codes/` — Code lists and definitions used to derive predictor history from EHR  

