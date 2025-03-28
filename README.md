# Improving Risk Stratification in TaLG Bladder Cancer

Code repository for BIOF520 assignment 4. Goal is to create a machine learning classifier for predicting recurrence of bladder cancer. 

### Deliverables
- Create an ML classifier that can improve clinical stratification of recurrence-free survival
- Want to predict whether or not a patient will have a recurrence
- Remove `Progression`, `PFS_time.`, `Recurrence`, `RFS_time`, and `FUtime_days.` column from training. Also remove `Smoking`, `Tumor.size`, `Incident.tumor`, `EAU.risk` since test set is missing these columns
