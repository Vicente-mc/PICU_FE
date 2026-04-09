# PICU-FE: A longitudinal dataset of hourly vital sign time-series from a Spanish Paediatric Intensive Care Unit

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19420944.svg)](https://doi.org/10.5281/zenodo.19420944)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the code and public documentation for the **PICU-FE** dataset, as described in the manuscript submitted to *Scientific Data*. 

PICU-FE is a high-resolution, analysis-ready pediatric intensive care dataset spanning 14 years of clinical activity (2011–2024) at Hospital Universitari i Politècnic La Fe (Spain). It contains over 1 million harmonized hourly vital sign records from 11,891 unique patients.

## 📁 Repository Structure

*   `code/`: Analytical pipeline and code.
    *   `EDA.ipynb`: Jupyter notebook containing the Exploratory Data Analysis (EDA) and the Machine Learning mortality prediction benchmark.
    *   `requirements.txt`: Python environment dependencies.
*   `data/`: Data dictionaries and sample structure. *(Note: The full dataset is securely hosted on Zenodo).*
*   `docs/`: Ethical approvals, Data Use Agreement (DUA) templates, and compliance checklists.
*   `figures/`: High-resolution figures generated during the EDA.

## 📊 Data Access Policy

Due to the highly sensitive nature of pediatric clinical records and European GDPR regulations, the primary dataset (`PICU_LaFe_dataset.csv`) is hosted under **Restricted Access** on Zenodo: [10.5281/zenodo.19420944](https://doi.org/10.5281/zenodo.19420944).

**To request access:**
1. Researchers must submit a formal request via the Zenodo portal.
2. Applicants must provide a brief project proposal and evidence of academic/institutional affiliation.
3. Access is contingent upon the execution of a Data Use Agreement (DUA) with the *IIS La Fe Big Data, AI, Biostatistics, and Bioinformatics Platform*. Re-identification attempts are strictly prohibited.

## 🚀 Running the Code

To reproduce the mortality prediction benchmark and EDA:

1. Clone this repository.
2. Install dependencies: `pip install -r code/requirements.txt`
3. Once data access is granted, place `PICU_Fe_dataset.csv` inside the `data/` folder.
4. Run the Jupyter Notebook: `jupyter notebook code/EDA.ipynb`

## 📄 License
The source code in this repository is licensed under the Apache 2.0 License. The dataset (hosted on Zenodo) is licensed under CC BY-NC-ND 4.0, subject to the DUA.