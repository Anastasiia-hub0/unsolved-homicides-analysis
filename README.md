# unsolved-homicides-analysis

# Unsolved Homicides Analysis (CRISP-DM)

Data Analytics (DBMS71008). Individual project.

## Question
Which factors are associated with a homicide case in the US remaining unsolved?

## Data
- Source: Murder Accountability Project (MAP), Supplementary Homicide Report, case-level file (SHR76_25)
- Link: https://www.murderdata.org/p/data-docs.html
- Unit of analysis: one row = one homicide case
- Target: `Solved` (Yes/No)
- Date downloaded: 12 Oct 2026
- The data file is NOT included in this repository (size/licence). Download the CSV from the link above and put it in the `data/` folder.

## Method
Classification with a simple baseline and comparison of models, following the six CRISP-DM phases.

## How to run
1. Download the data file (see above)
2. Open the notebook in `notebooks/` in Jupyter or Google Colab
3. Run all cells in order

## Status
- [x] Project idea and dataset chosen
- [ ] Lecturer approval
- [ ] Business Understanding
- [ ] Data Understanding
- [ ] Data Preparation
- [ ] Modelling
- [ ] Evaluation
- [ ] Paper
