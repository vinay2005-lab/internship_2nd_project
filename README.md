# 🏠 House Price EDA Project

## 📌 Problem Statement
The goal of this project is to analyze house characteristics (area, bedrooms, age, distance from city) and understand how they influence house prices.  
This dataset is used for exploratory data analysis (EDA), cleaning, and feature engineering.

---

## ⚙️ Approach
1. **Data Loading**  
   - Imported dataset using pandas.  
   - Inspected structure, data types, and summary statistics.

2. **Data Cleaning**  
   - Removed duplicate rows.  
   - Handled missing values and invalid entries (negative area).  
   - Filled missing values with median.  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions (histograms, boxplots).  
   - Checked relationships (scatterplots, correlation heatmap).  
   - Identified outliers and trends.

4. **Feature Engineering**  
   - Created `price_per_sqft` (price per square foot).  
   - Categorized houses by age (`New`, `Mid`, `Old`).  

5. **Final Dataset**  
   - Separated features (`X`) and target (`y`).  
   - Exported cleaned dataset as `house_price_cleaned.csv`.

---

## 📊 Insights
- Larger area and more bedrooms generally increase house price.  
- Newer houses tend to have higher price per square foot.  
- Distance from city shows an inverse relationship with price.  

---

## 📂 Deliverables
- `house_price_eda.ipynb` → Jupyter Notebook with code, cleaning, plots, and features.  
- `02_house_price.csv` → Raw dataset.  
- `house_price_cleaned.csv` → Processed dataset (clean + engineered features).  
- `README.md` → Project explanation and instructions.  

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/house_price_eda.git
