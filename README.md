# Unsolved Homicides Analysis (CA2, DBMS71008 Data Analytics)

**Student:** Anastasiia Tkachenko (T00258101), MTU Kerry
**Lecturer:** Andrew Shields

## Research question
Which characteristics of a homicide case that are known when it is reported are associated with the case staying unsolved, and can we use them to predict if the case will be solved?

## Dataset
- **Source:** Murder Accountability Project (MAP), case-level Supplementary Homicide Report, 1976–2025 (`SHR76_25a`)
- **Size:** 929,433 rows, 31 columns
- **Licence:** no licence is stated on the MAP website, so the data is **not uploaded** to this repository.

### How to get the data
1. Go to https://www.murderdata.org/p/data-docs.html
2. Download the case-level Supplementary Homicide Report file in **CSV** format.
3. Rename the file to `SHR76_25a-2.csv` (the name used in the notebook).

The data dictionary from MAP is in `references/MAPdefinitionsSHR.pdf`.

## How to run
1. Open `unsolved_homicides_analysis.ipynb` in Google Colab.
2. Upload `SHR76_25a-2.csv` in the **Files** panel and wait until the upload is finished.
3. Click **Runtime → Run all**.

**Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn (all are already installed in Google Colab).
**Random seed:** 42.

## Repository structure
- `unsolved_homicides_analysis.ipynb` – main CRISP-DM notebook
- `paper/` – final conference-style paper (PDF)
- `references/` – MAP data dictionary
- `README.md` – this file

## Project status
- [x] Business Understanding
- [x] Data Understanding
- [x] Data Preparation
- [x] Modelling
- [x] Evaluation
- [x] Deployment
- [x] Reflection and AI Collaboration Statement
- [x] Paper
