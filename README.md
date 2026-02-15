# Airbnb Asheville Market Analysis

## Project Overview
This project analyzes Airbnb listing and review data to evaluate Asheville as a potential
market for expansion. The analysis focuses on pricing trends, neighborhood activity,
host behavior, and demand patterns using real Airbnb data.

The work is being carried out in Jupyter Notebook using a structured,
phase-based analytical workflow.

---

## Objectives
- Understand nightly pricing trends across Asheville
- Identify the most active neighborhoods and hosts
- Analyze review activity as a proxy for guest demand
- Assess risks and opportunities for market expansion

---

## Data Sources
- `listings.csv` – Property-level information (price, room type, host details, availability)
- `reviews.csv` – Guest reviews with timestamps (used for demand analysis)
- `neighbourhoods.csv` – Reference neighborhood data

Raw data is stored separately from processed data to maintain reproducibility.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Project Structure

Airbnb Listings Analysis/
│
├── dataset/
│ ├── listings.csv
│ ├── reviews.csv
│ ├── neighbourhoods.csv
│ └── processed/
│ └── clean_listings.csv
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ └── 02_descriptive_analysis.ipynb
│
└── README.md


---

## Work Completed So Far

### Phase 1 – Data Cleaning & Preparation
- Loaded raw Airbnb datasets into Jupyter Notebook
- Performed detailed missing value analysis
- Dropped non-informative columns:
  - `neighbourhood_group`
  - `license`
- Removed listings with missing `price`
- Validated and confirmed `price` as numeric (`float64`)
- Conducted sanity checks on price range (min = 20, max = 1000)
- Preserved missing review-related fields as meaningful demand signals
- Exported cleaned dataset as:
  - `dataset/processed/clean_listings.csv`

The dataset is now clean and analysis-ready.

---

### Phase 2 – Descriptive Analysis (In Progress)

#### 1. Overall Pricing Analysis
- Mean nightly price: ~167
- Median nightly price: ~127
- Identified right-skewed price distribution
- Observed significant price variability across listings

#### 2. Room Type Distribution
- Entire home/apartment listings dominate the market
- Private rooms represent a small secondary segment
- Hotel and shared rooms are minimal
- Indicates a market driven primarily by leisure and full-property stays

---

## Current Status
Phase 1 (Data Cleaning) – Completed  
Phase 2 (Descriptive Analysis) – In Progress  

Next steps include neighborhood-level analysis, pricing comparison by area,
and review-based demand analysis.

---

## Next Steps
- Analyze listings by neighborhood
- Compare average price by neighborhood
- Merge listings with reviews dataset
- Study demand trends and seasonality
- Conduct host-level analysis
- Generate market expansion recommendations

---

## Author
Kaushal Kumar
