# 🚗 Electric Vehicle Market & Adoption Analysis Using Python
End-to-end exploratory data analysis of electric vehicle registrations using Python, Pandas, Matplotlib and Seaborn.

## 📌 Project Overview

This project performs an end-to-end exploratory data analysis (EDA) of electric vehicle population data using Python.

The analysis focuses on understanding electric vehicle adoption patterns across model years, manufacturers, vehicle types, geographic regions, vehicle models, and electric driving range.

The project demonstrates the complete data analytics workflow, from data loading and cleaning to exploratory analysis, statistical analysis, visualization, insight generation, and recommendations.

---

## 🎯 Objectives

The main objectives of this project are to:

* Understand the structure and quality of the EV dataset.
* Identify missing values and duplicate records.
* Clean and transform the dataset for analysis.
* Analyze EV distribution across model years.
* Identify leading EV manufacturers and models.
* Compare Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
* Analyze geographic distribution of EV registrations.
* Examine electric-range patterns.
* Identify statistical patterns and potential outliers.
* Generate actionable insights and recommendations.

---

## 📊 Dataset

**Dataset:** Electric Vehicle Population Data

**Source:** U.S. Department of Transportation / Data.gov

The dataset contains information about electric vehicles including:

* Model year
* Manufacturer
* Vehicle model
* Electric vehicle type
* Electric range
* County
* City
* State
* Postal code
* Legislative district
* Electric utility
* CAFV eligibility

The dataset contains approximately **299,705 records and 16 features**.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined rows, columns and data types.
* Reviewed the first and last records.
* Generated descriptive statistics.

### 2. Data Cleaning

* Checked missing values.
* Checked duplicate records.
* Standardized column names.
* Corrected data types.
* Converted geographic identifier fields to appropriate string types.
* Investigated unusual model-year values.
* Assessed electric-range data quality.

### 3. Feature Engineering

Additional analytical features were created, including:

* Vehicle Age
* Electric Range Category
* Model Year Group
* Range Availability

### 4. Exploratory Data Analysis

The project includes:

* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* GroupBy analysis
* Pivot tables
* Correlation analysis
* Statistical summaries
* IQR-based outlier detection

---

## 📈 Visualizations

The analysis contains more than 10 visualizations, including:

1. EV Registrations by Model Year
2. Top 10 EV Manufacturers
3. EV Type Distribution
4. Electric Range Distribution
5. Electric Range Box Plot
6. Top 10 EV Models
7. EV Registrations by State
8. Average Range by EV Type
9. Model Year vs Electric Range
10. Correlation Heatmap
11. Top Manufacturers by Model Year
12. Electric Range Category Distribution
13. CAFV Eligibility Distribution

---

## 🔍 Key Insights

### 1. EV Type Distribution

Battery Electric Vehicles (BEVs) represent the majority of records in the dataset, while Plug-in Hybrid Electric Vehicles (PHEVs) account for a smaller share.

### 2. Manufacturer Concentration

Tesla has the highest representation among manufacturers, indicating strong dominance within this EV registration dataset.

### 3. Model Concentration

A relatively small number of EV models account for a significant portion of the recorded vehicles.

### 4. Recent Model Years

Recent model years represent a large proportion of the dataset, indicating strong representation of newer EVs.

### 5. Geographic Concentration

EV registrations are heavily concentrated in Washington State and particularly in a number of major counties and cities.

### 6. Electric Range Differences

Battery Electric Vehicles generally have substantially higher measured electric ranges than Plug-in Hybrid Electric Vehicles.

### 7. Data Quality

A large number of records have unavailable or unresearched electric-range information. Therefore, range-related analysis should distinguish between unavailable range and genuinely measured zero range.

---

## ⚠️ Data Quality Considerations

One important data-quality issue involves the `Electric Range` column.

Zero values should not automatically be interpreted as vehicles having zero driving range. Some records correspond to situations where battery range information has not been researched.

Therefore, the analysis preserves the original electric-range field and creates a separate analytical representation for range calculations.

Outliers are identified using the IQR method but are not automatically removed because unusually high range values may represent legitimate EV models.

---

## 💡 Recommendations

Based on the analysis:

1. Use broader geographic datasets for nationwide EV adoption comparisons.
2. Normalize EV registration counts by population when comparing regions.
3. Collect more complete electric-range information.
4. Investigate manufacturer and model-level adoption trends over time.
5. Combine EV registration data with charging-station infrastructure data for deeper adoption analysis.
6. Future analysis could include vehicle price, battery capacity, income, population and charging infrastructure.

---

## 📁 Repository Structure

```text
electric-vehicle-market-analysis/
│
├── README.md
├── notebooks/
│   └── Electric_Vehicle_Market_Adoption_Analysis.ipynb
├── data/
│   └── Electric_Vehicle_population.csv
├── images/
│   └── project_visualizations/
└── requirements.txt
```

---

## ▶️ How to Run

### Option 1 — Jupyter Notebook

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Open the notebook:

```text
notebooks/Electric_Vehicle_Market_Adoption_Analysis.ipynb
```

### Option 2 — Google Colab

Upload the `.ipynb` file to Google Colab and run the notebook from top to bottom.

---

## 🎓 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Pandas
* NumPy
* Data Visualization
* Statistical Analysis
* GroupBy Analysis
* Pivot Tables
* Correlation Analysis
* Outlier Detection
* Feature Engineering
* Insight Generation
* Data Storytelling

---


**Ajeesha**

Data Analytics Learner | Accounting Background | Aspiring Data Analyst
