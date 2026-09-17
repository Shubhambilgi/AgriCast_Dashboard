# AgriCast – Agriculture Data Analysis & Dashboard

AgriCast is an agriculture-focused data analytics project that combines crop production, rainfall, soil, and market-price data to explore agricultural trends and identify factors associated with crop yield and profitability.

## Project Overview

The project brings together multiple agricultural datasets and processes them into a consolidated dataset for analysis and visualization. The analysis is performed in Python, while Power BI is used to build an interactive dashboard.

### Key Areas

- Crop yield and production analysis
- Rainfall and crop-related trend analysis
- Soil information including pH and nutrient values
- Crop market-price analysis
- District and state-level comparisons
- Interactive Power BI visualizations

## Project Structure

```text
AgriCast_Dashboard/
│
├── Data/
│   ├── raw/
│   │   ├── crop_prices.csv
│   │   ├── crop_production.csv
│   │   ├── district wise rainfall normal.csv
│   │   ├── rainfall in india 1901-2015.csv
│   │   └── soil_data.csv
│   │
│   └── processed/
│       └── final_agri_dataset.csv
│
├── notebooks/
│   └── AgriCast_Crop_Yield_Prediction.ipynb
│
├── Power_Bi/
│   └── AgriCast_Dashboard.pbix
│
├── docs/
│   └── New Microsoft Word Document.docx
│
├── screenshots/
├── .gitignore
└── README.md
```

## Technologies Used

- **Python** – data processing and analysis
- **Pandas** – data manipulation
- **Jupyter Notebook** – exploratory analysis and project workflow
- **Power BI** – interactive dashboard and visualization
- **CSV** – source and processed datasets

## Data Workflow

```text
Raw Agricultural Data
        ↓
Data Cleaning & Preparation
        ↓
Data Integration
        ↓
Processed Agricultural Dataset
        ↓
Python Analysis / Jupyter Notebook
        ↓
Power BI Dashboard
```

## Dashboard

The Power BI dashboard is designed to provide interactive views of agricultural data using filters and visualizations for dimensions such as crop, year, state, and district.

The dashboard file is available in:

`Power_Bi/AgriCast_Dashboard.pbix`

## Notebook

The main analysis notebook is available at:

`notebooks/AgriCast_Crop_Yield_Prediction.ipynb`

It contains the project's data preparation and analysis workflow.

## Dataset

The project separates source data from the processed dataset:

- `Data/raw/` contains the source datasets used in the project.
- `Data/processed/` contains the consolidated dataset prepared for analysis.

## Project Goal

The goal of AgriCast is to demonstrate how multiple agricultural data sources can be combined and analyzed to support data-driven understanding of crop yield, rainfall, soil characteristics, production, and market conditions.

## Author

**Shubham Bilgi**

- GitHub: [Shubhambilgi](https://github.com/Shubhambilgi)
- LinkedIn: [Shubham Bilgi](https://www.linkedin.com/in/shubham-bilgi-234044283/)
