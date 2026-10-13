# MetroLink Transit Insight

Public transport demand and delay analysis for MetroLink Transit Services (Use Case 16).

## Problem
How does passenger demand vary by route, stop, time and events, and where do delays happen, so service planning can improve?

## Files
- metrolink_transit_data.csv: raw dataset (512 records, 16 attributes)
- clean_data.csv: cleaned data (500 records)
- selected_features.csv: features chosen for modelling
- Colab notebook (.ipynb): cleaning, EDA, feature engineering and ML model
- MetroLink_Analysis.xlsx: Excel workbook with pivot tables, charts and Summary sheet
- MetroLink_Pitch.pptx: 7-slide pitch deck

## Key results
- R5, R1 and R3 carry about 52% of all boardings.
- Peak periods (7-9 AM, 5-7 PM) carry nearly twice the passengers of off-peak.
- Weekend demand is about 22.8% lower than weekday demand.
- R3, R5 and R8 have the worst delays.
- Event days raise ridership by about 10.6%.
- Model: Random Forest Regressor, RMSE about 12.5, R2 about 0.72.

## Author
Sristi Pokharel
