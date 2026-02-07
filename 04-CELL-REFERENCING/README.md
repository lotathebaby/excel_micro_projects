# Micro Project Number 4 - Cell Referencing

## Question

How do fixed overhead and tax rates affect total costs across departments when applied consistently to all usage records?

## Dataset

Synthetic hospital dataset created in Excel.
Columns: Item_ID, Dept, units_Used, cost_per_Unit, Base_cost, verhead_cost, tax, total_cost
Rows: 10

## Method(Excel)

- Splited data set into separate columns per delimiter.
- Converted data range into excel table.
- Calculated the base cost by multiplying the cost_per_unit by the units_used
- created the fixed parameters table and entered the overhead_rate and tax_rate manually
- calculated overhead_cost by multiplying the overhead_rate by the base cost
- calculated tax by multiplying the tax rate by the base_cost.
- calculated the total cost by adding the tax to the overhead_cost and base_cost
- used SUMIF to get the total cost per department
- used XLOOKUP to extract the department with the highest total cost.

## Results

- Total Cost (ER) - $369.15
- Total Cost (Clinic) - $395.60
- Total Cost (Imaging) - $2,219.50
- Department with highest total cost - Imaging

## Validation

- Double checked to ensure that the overhead_rate and tax_rate were accurately referenced.

## Evidence

- screenshots attached to the github repository
