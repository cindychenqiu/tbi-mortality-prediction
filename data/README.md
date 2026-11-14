# Data

This folder contains no data. The project uses MIMIC-III v1.4, a critical
care database from the Beth Israel Deaconess Medical Center (Boston,
2001 to 2012). MIMIC-III is available only to credentialed users who have
completed data use training and signed the PhysioNet data use agreement,
and the agreement does not allow the data or datasets derived from it to be
shared publicly.

## How to get access

1. Create a PhysioNet account and complete the required human research training.
2. Request access to MIMIC-III on PhysioNet and sign the data use agreement.
3. Load the database following the MIMIC documentation.

## How the dataset is built

The SQL query for cohort selection and feature extraction is in the first
section of `notebooks/tbi_mortality_prediction.ipynb` and in
`docs/supplementary_methods.pdf`. Running it on your own copy of MIMIC-III
produces the patient-level table used in the analysis (2716 patients with
traumatic brain injury). Export it as CSV into this folder, as described in
the notebook.