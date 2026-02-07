# Micro Project Number 3 - Comparison Operators

## Question

Create rule-based flags using comparison operators to classify health records.

## Dataset

Synthetic hospital dataset created in Excel.
Columns: Visit_ID, Dept, Wait_Min, Acuity, Breach flag, High_Acuity_Flag, Risk_Tier
Rows: 30

## Method(Excel)

- Splited data set into separate columns per delimiter.
- Converted data range into excel table.
- Created the breach_flag column by using IF to check if the Wait time is greater than 60 minutes.
- Created the high_acuity_flag using IF to check if acuity is less than or equal to 2.
- Using nested IF, I categorized the risk tier into High, medium, and low. Identifying High to be those with high acuity and wait times above 60 minutes, medium to be those with either high acuity or wait times above 60 minutes and low for those with neither.
- Generated the count of high_risk_tier per department using COUNTIFS
- Retrieved the department with the highest number of high_risk visits.

## Results

- Total High risk visit: 6
- Total Medium risk visit: 11
- Total Low risk visits: 13
- Department with highest number of high risk visits: Clinic(3)

## Validation

- Used count to ensure that the number of high counts tallied with the occurences on the data.

## Evidence

- screenshots attached to the github repository
