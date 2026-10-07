# Healthcare Analytics for Doctor Visits

This project explores healthcare utilization patterns using a doctor-visit dataset. The analysis focuses on understanding how patient demographics, illness burden, insurance status, income, and health conditions relate to the number of doctor visits.

## Project Objective

The notebook analyzes how doctor visits vary across:

- gender
- age groups
- illness count
- health status
- income level
- chronic conditions
- private insurance coverage
- reduced activity days

The goal is to identify patterns and drivers of healthcare usage and support data-informed insights about access, risk, and treatment demand.

## Dataset

- File: `DoctorVisits - DA.csv`
- Contains patient-level records with variables such as:
  - `visits`
  - `gender`
  - `age`
  - `income`
  - `illness`
  - `reduced`
  - `health`
  - `private`
  - `freepoor`
  - `freerepat`
  - `nchronic`
  - `lchronic`

## Analysis Included

The notebook covers questions such as:

- How are doctor visits distributed among patients?
- Does the average number of doctor visits differ by gender?
- How do doctor visits vary by age group?
- Does illness count influence doctor visits?
- How does health status affect visit frequency?
- How does income affect doctor visits?
- Are chronic conditions associated with more visits?
- Is there a difference between patients with and without private insurance?
- Which variables are most strongly related to doctor visits?
- How does reduced activity relate to healthcare usage?

## Files in the Project

- `Healthcare_Analytics.ipynb` — main notebook with data exploration, analysis, and visualizations
- `DoctorVisits - DA.csv` — source dataset
- `HealthCareProject.pptx` — presentation file related to the project
- `Dataset explanation.docx` — dataset documentation

## Requirements

To run the notebook, install the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## How to Run

1. Open the project folder.
2. Launch Jupyter Notebook or JupyterLab.
3. Open `Healthcare_Analytics.ipynb`.
4. Run the cells in order to reproduce the analysis and visualizations.

## Key Insights Summary

The analysis shows that:

- doctor visits increase with illness burden
- older patients tend to visit doctors more often
- poorer health status is associated with higher visit counts
- reduced activity days are strongly linked to healthcare utilization
- chronic conditions increase the need for medical care
- women have a slightly higher average number of doctor visits than men


