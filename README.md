# TruSource Customer Churn Prediction

## Business Problem
TruSource wants to identify customers likely to cancel service so the retention team can intervene early. The goal is to predict churn risk using customer usage, billing, and account behavior data.

## Key Results
- Best model ROC-AUC: [0.9002]
- Most important churn drivers: [Month-to-month contract], [No technical support], [No security add-on]
- Selected decision threshold captured [78]% of churners

## How to Run
1. Open the main notebook
2. Run all cells from top to bottom
3. Review model evaluation section
4. Adjust cutoff threshold if desired

## Limitation
The model may be sensitive to changes in customer behavior over time (data drift), so periodic retraining is required.
## Notes
This repository was created as part of the MSBA predictive analytics final project.
