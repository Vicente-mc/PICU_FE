# PICU-FE: a longitudinal hourly vital sign dataset from a Spanish paediatric intensive care unit

[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.20475499-blue.svg)](https://doi.org/10.5281/zenodo.20475499)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository contains the code and public documentation for the **PICU-FE** dataset, as described in the manuscript submitted to *Scientific Data*. 

PICU-FE is a high-resolution, analysis-ready pediatric intensive care dataset spanning 14 years of clinical activity (2011–2024) at Hospital Universitari i Politècnic La Fe (Spain). It contains 1,151,836 harmonized hourly vital sign records from 12,014 unique patients.

## 📁 Repository Structure

*   `code/`: Analytical pipeline and code.
    *   `EDA.ipynb`: Jupyter notebook containing the Exploratory Data Analysis (EDA) and the Machine Learning mortality prediction benchmark.
    *   `requirements.txt`: Python environment dependencies.
*   `data/`: Data dictionaries and sample structure. *(Note: The full dataset is securely hosted on Zenodo).*
*   `docs/`: Data Use Agreement (DUA) templates and compliance checklists.
*   `figures/`: generated during the EDA.

## 📊 Data Access Policy

Due to the highly sensitive nature of pediatric clinical records and European GDPR regulations, the primary dataset (`PICU_LaFe_dataset.csv`) is hosted under **Restricted Access** on Zenodo: [10.5281/zenodo.20475499](https://doi.org/10.5281/zenodo.20475499).

**To request access:**
1. Researchers must submit a formal request via the Zenodo portal.
2. Applicants must provide a brief project proposal and evidence of academic/institutional affiliation.
3. For scientific research purposes, data release entails coordination with either the CEIm or the Big Data, AI, Biostatistics & Bioinformatics Platform of IIS La Fe.

## 🚀 Running the Code

To reproduce the mortality prediction benchmark and EDA:

1. Clone this repository.
2. Install dependencies: `pip install -r code/requirements.txt`
3. Once data access is granted, place `PICU_Fe_dataset.csv` inside the `data/` folder.
4. Run the Jupyter Notebook: `jupyter notebook code/EDA.ipynb`

## 📄 License
The source code in this repository is licensed under the Apache 2.0 License. The dataset (hosted on Zenodo) is licensed under CC BY-NC-ND 4.0, subject to the DUA.
