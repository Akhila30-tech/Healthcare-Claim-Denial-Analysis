# Healthcare Claim Denial Analysis

## Overview
This project analyzes insurance claim data to understand patterns behind claim denials. The notebook explores key factors like late submissions, claim type, and claim amount to identify claims that are more likely to be denied.

## Objective
- Identify key drivers of claim denials
- Visualize trends to communicate insights
- Provide actionable recommendations

## Dataset
- Simulated insurance claim data
- Columns include:
  - `claim_id` – unique claim identifier
  - `claim_amount` – claim requested amount
  - `claim_type` – type of service (emergency, outpatient, inpatient, pharmacy)
  - `days_to_submit` – how late the claim was submitted
  - `provider_type` – hospital, clinic, private practice
  - `diagnosis_group` – medical category
  - `denied` – 1 if claim denied, 0 otherwise

## Key Insights
- Claims submitted after 30 days are more likely to be denied
- Pharmacy claims with high amounts are denied more frequently
- Emergency claims are generally approved more often

## How to Run
Open `claim_denial_analysis.ipynb` in Jupyter Notebook and run all cells to reproduce the analysis and visualizations.

## Conclusion
This project demonstrates a typical data scientist workflow: exploring data, identifying patterns, and communicating insights in a business context.
