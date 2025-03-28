# Data

## Training Set (UROMOL Cohort); Metadata Only
Column names: 
- Progression : Progression data.
- PFS_time. : Progression-free survival time (i think?)
- Recurrence: **Has the patient had a recurrence event**
- RFS_time: Recurrence-free survival. 
- FUtime_days. : Follow-up time in days. 
- Age
- Sex 
- Smoking: Categorical. One of "Never", "Former", "Current", and "NA"
- Tumor.stage: all Ta. **To remove**
- Tumor.grade: all low grade. **To remove**
- Concomitant.CIS: Categorical. "Yes" or "No"
- Tumor.size: Categorical. "<3cm", ">3cm", or missing
- Incident.tumor: Categorical. "Yes" or "No"
- EAU.risk: Categorical. "Low", "Intermediate", "High" risk groups, and "NA"
- BCG : Categorical (Boolean); has undergone BCG treatment. "0" or "1"
- UROMOL2021.classification: Categorical. Molecular Classification of Tumor

## Testing Set; Metadata Only

Testing set is missing the following columns: `Smoking`, `Tumor.size`, `Incident.tumor`, `EAU.risk`