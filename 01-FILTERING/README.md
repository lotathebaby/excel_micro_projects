# Micro Project Number 1 - Filtering: Top 10 and Bottom 10 Analysis

##Question
Which records are in the Top 10 and Bottom 10 by **Score**, and which **Category** appears most in each group?

## Dataset

Synthetic student dataset created in Excel.
Columns: ID, Category, Hours_Studied, Score
Rows: 30

## Method(Excel)

- Splited data set into separate columns per delimiter.
- Converted data range into excel table.
- Used filters to filter:
- Top 10 by Score
- Bottom 10 by Score
- Calculated the Average based on each filtered set.
- Drafted the most common category for top 10 and bottom 10 using XLOOKUP, MAX, and COUNTIF

## Results

- Top 10 average Score: 80
- Bottom 10 average Score: 51.1
- Most common Category in Top 10: A
- Most common Category in Bottom 10: C

## Validation

- Used count to confirm that the top and bottom 10 filters returned exactly 10 records each.
- ensured that the sorted score values matched the filtered groups.

## Evidence

- screenshots attached to the github repository
