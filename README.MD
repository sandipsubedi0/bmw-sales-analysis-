# BMW Sales Data Analysis (2010–2024)

A data analysis project exploring 14 years of BMW sales data to uncover regional trends, pricing patterns, fuel type shifts, and model performance.

---

## 📌 Objective

Analyze BMW sales data from 2010 to 2024 to answer key business questions:
- Which region generates the highest average sales volume?
- How does price vary across regions and transmission types?
- Are electric vehicles growing as a share of BMW's inventory?
- Which models sell the most consistently?

---

## 🗂️ Dataset

- **Source:** Kaggle — BMW Sales Data 2010–2024
- **Records:** ~10,000+ entries
- **Columns:** Model, Year, Region, Color, Fuel_Type, Transmission, Engine_Size_L, Mileage_KM, Price_USD, Sales_Volume, Sales_Classification

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data loading, cleaning, groupby analysis |
| Matplotlib | Charts and dashboard |
| Seaborn | Heatmaps |
| Jupyter Notebook | Development environment |

---

## 📊 Analysis Breakdown

### 1. Exploratory Data Analysis (EDA)
- Shape, data types, missing value check
- Descriptive statistics for numeric and categorical columns
- Correlation heatmap across all numeric columns

### 2. Value Counts & Distribution Charts
- Bar charts for all categorical columns (Model, Region, Fuel Type, Transmission, Sales Classification)
- Histograms for all numeric columns (Price, Mileage, Sales Volume, Engine Size)
- Line chart for Year distribution (time-ordered)

### 3. Groupby Analysis (8 groupings)
- Average Price by Region
- Average Engine Size by Sales Classification
- Average Sales Volume by Model
- Average Sales Volume by Region
- Average Engine Size by Fuel Type
- Average Price by Transmission Type
- Average Sales Volume by Year (2010–2024 trend)
- Average Sales Volume by Sales Classification

### 4. Advanced Charts
- Scatter plot: Mileage vs Price
- Boxplot: Price distribution by Transmission
- Crosstab Heatmap: Region vs Fuel Type

### 5. Final Dashboard
A 3×3 summary dashboard combining the 9 most important charts in one view.

---

## 🔍 Key Findings

- **Sales volume remained stable** across all 14 years — BMW maintained consistent market positioning
- **Pricing is evenly spread** across Entry-level Luxury and High-end Luxury tiers
- **Electric vehicles** make up a notable share of the inventory, reflecting BMW's EV push
- **No strong correlation** between Mileage and Price — suggesting other factors drive pricing
- **All regions show similar average prices**, indicating BMW's global pricing consistency

---

## 📁 Project Structure

```
bmw-sales-analysis/
│
├── BMW_sales_analysis.ipynb   ← Main notebook
├── bmw_sales_data.csv         ← Dataset
└── README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/sandipsubedi0/bmw-sales-analysis

# 2. Install dependencies
pip install pandas matplotlib seaborn numpy

# 3. Open the notebook
jupyter notebook BMW_sales_analysis.ipynb
```

---

## 👤 Author

**Sandip Subedi**
- Hashnode: https://pythoninnercode.hashnode.dev/i-analyzed-14-years-of-bmw-sales-data-here-s-what-i-found?utm_source=hashnode&utm_medium=feed
- Instagram: [@sandipsubedi0](https://instagram.com/sandipsubedi0)

---

*Part of my Data Analyst Portfolio — building real projects to land my first internship.*
