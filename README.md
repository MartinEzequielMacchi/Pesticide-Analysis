🧪 Pesticide Usage Analysis (US)

This project analyzes county-level pesticide usage for 423 compounds across the contiguous United States. The dataset includes two estimation methods—low (assumes zero when unreported) and high (imputes missing values). By comparing these methods, the analysis highlights how different assumptions impact agricultural risk assessment and public health interpretations.

Dataset Columns

COMPOUND – Pesticide name

YEAR – Measurement year

STATE / COUNTY / CODES – Location identifiers

LOW_ESTIMATE / HIGH_ESTIMATE – Pesticide usage in kilograms

Objectives

Find states and counties with the highest pesticide use

Compare low vs. high estimation methods

Analyze usage distribution by state

Explore yearly trends for selected pesticides

Libraries Used

pandas, numpy, matplotlib, seaborn, missingno, scipy
