# Data Cleaning Portfolio

This project demonstrates **systematic data cleaning** with Python and Pandas, using the [Chicago Food Inspections dataset](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5).  
The goal was to take a messy, real-world dataset and transform it into a **clean, analysis-ready version**.

## Cleaning Highlights
- Standardized column names and formats.
- Normalized categorical fields (`facility_type`, `risk`, `results`).
- Cleaned geographic data (`latitude`, `longitude`, ZIP codes).
- Validated dates (`inspection_date` 2010–2025).
- Removed duplicates and invalid records.
- Produced a final **gold dataset**: `food_inspections_clean.csv`.

## Structure
- `data/raw/` → raw datasets (ignored in Git)  
- `data/processed/` → cleaned datasets (ignored in Git)  
- `notebooks/` → Jupyter notebooks for cleaning and analysis  
- `src/` → helper functions and scripts  
- `.vscode/` → editor settings  

