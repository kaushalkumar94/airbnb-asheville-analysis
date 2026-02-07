# Airbnb Asheville Market Analysis

## Project Overview
This project analyzes Airbnb listing and review data to evaluate **Asheville** as a potential
market for expansion. The analysis focuses on pricing trends, neighborhood activity,
host behavior, and demand patterns using real Airbnb data.

The work is being carried out entirely in **Jupyter Notebook** with a structured,
step-by-step analytical approach.

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

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## Work Completed So Far

### 1. Project Setup
- Created a clean and organized project structure
- Set up GitHub repository and version control
- Configured Jupyter Notebook environment

---

### 2. Data Loading & Initial Inspection
- Loaded all datasets (`listings`, `reviews`, `neighbourhoods`) from local directory
- Inspected dataset dimensions, column names, and data types
- Verified schema consistency across datasets

---

### 3. Missing Value Analysis
- Performed a detailed missing value assessment on all columns
- Identified columns with 100% missing values:
  - `neighbourhood_group`
  - `license`
- Dropped non-informative columns from the dataset

---

### 4. Processed Dataset Export
- Saved the cleaned dataset as `clean_listings.csv`
- Maintained separation between raw and processed data
- This dataset will be used for all further analysis and visualization


---

## Current Data Status
- Dataset is structurally clean and analysis-ready
- Core pricing and location fields have no missing values
- Review-related missing values are preserved intentionally for demand analysis

---

## Next Steps
- Clean and standardize the `price` column (convert to numeric, inspect outliers)
- Merge listings and reviews datasets
- Perform exploratory data analysis (EDA):
  - Price distribution (mean vs median)
  - Room type distribution
  - Listings per neighborhood
- Analyze review trends to identify demand seasonality
- Conduct host-level analysis
- Generate market expansion recommendations

---

## Status
**Work in progress**  
This repository is under active development with incremental commits.

---

## Author
Kaushal Kumar
