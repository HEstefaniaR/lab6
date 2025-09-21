# Lab 6 - ETL with Great Expectations

## Description
Implementation of an ETL pipeline with quality control using Great Expectations for retail data.

## Project Structure
lab6/  
├── data/ # Raw and cleaned data 
│   ├── cleaned/
│   └── raw/
├── notebooks/ # Jupyter notebooks with the full workflow  
│   ├── 01_extract_and_EDA.ipynb # Extraction and exploratory analysis  
│   ├── 02_exploratory_DQC.ipynb # Exploratory data quality check  
│   ├── 03_clean_data.ipynb # Data cleaning  
│   ├── 04_validation_DQC.ipynb # Post-cleaning validation  
│   └── 05_visualize_kpis.ipynb # Visualizations and KPIs  
├── .gitignore # Files to ignore in Git  
└── README.md # This file  

## Requirements
- Python 3.8+  
- Great Expectations  
- Pandas  
- Jupyter Notebook  
- Matplotlib/Seaborn  

## Usage
Run the notebooks in sequential order:

- **01_extract_and_EDA.ipynb** - Data extraction and initial analysis  
- **02_exploratory_DQC.ipynb** - Initial data quality assessment  
- **03_clean_data.ipynb** - Data cleaning and transformation  
- **04_validation_DQC.ipynb** - Validation of cleaned data  
- **05_visualize_kpis.ipynb** - Visualizations and KPI generation  

## Results
The project generates:

- Data quality reports before and after cleaning  
- A clean and validated dataset  
- Visualizations for each business objective  
- Quality and business intelligence KPIs  



Made by: Natalia Paredes, Estefania Hernández, Fabian Gomezcasseres