# coefficient-of-variation-
Well Pressure Variability Analysis Using CV
Overview
This project uses the Coefficient of Variation (CV) to analyze pressure variability across production wells.
Methods
• Rolling CV: Tracks changes in pressure variability using a 7-observation rolling window.
• Overall CV: Summarizes pressure variability for each well over the available observation period.
Formula
[
CV = \frac{\text{Standard Deviation}}{\text{Mean Pressure}}
]
Applications
• Monitor changes in well pressure variability.
• Compare pressure behavior between wells.
• Identify wells that may require further investigation.
Note
A high or increasing CV indicates greater relative pressure variability but does not identify its underlying cause. Results should be interpreted alongside production data and reservoir conditions.
Requirements
• Python
• Pandas
Data Requirements
The input DataFrame, production_df, should contain the following columns:
well_id
pressure_psi
