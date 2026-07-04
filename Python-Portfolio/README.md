# Python Data Analytics Portfolio

Data analytics projects completed as part of the **Mission Ready HQ Level 5 Data Analyst** programme, covering Python fundamentals, exploratory data analysis, data visualisation, and predictive modelling.

---

## Projects

### 01 · Data Structures and Functions in Python
**`notebooks/01_data_structures/`**

Core Python data structures and function writing — tuples, sets, lists, dictionaries, control flow, and reusable functions.

**Skills:** Python · Tuples · Sets · Dictionaries · If/Else · Functions

---

### 02 · Exploring and Analyzing Data with Pandas
**`notebooks/02_pandas_eda/`**

EDA and data manipulation on an employee dataset. Covers the full data cleaning pipeline — missing value handling, column transformation, filtering, and group aggregation.

**Skills:** Pandas · Data Cleaning · Missing Values · GroupBy · DataFrame Transformation

---

### 03 · Sales Dataset EDA
**`notebooks/03_sales_eda/`**

Retail transaction data analysis across three related tables (Sales, Invoice, Product). Merges datasets, builds visualisations, and identifies sales trends by category and country.

**Skills:** Multi-table Merge · Matplotlib · Seaborn · Correlation Heatmap · Pivot Table

> ⚠️ Built in Microsoft Fabric (Synapse). Data file: `data/online_sales_retailer_1.xlsx`

---

### 04 · House Price Prediction with Multiple Linear Regression
**`notebooks/04_house_price_mlr/`**

MLR model to predict house prices from features including square footage, bedrooms, bathrooms, garage size, and location score. Evaluated with R² and RMSE metrics.

**Skills:** scikit-learn · MLR · Feature Analysis · R² · RMSE · Seaborn

> ⚠️ Loads data from Azure Blob Storage. To run locally, use `pd.read_csv('house_sales_prediction.csv')`.

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Visualisation |
| scikit-learn | Machine learning |
| Microsoft Fabric | Cloud notebook environment |

---

## Setup

```bash
git clone https://github.com/<your-username>/python-data-portfolio.git
cd python-data-portfolio
pip install -r requirements.txt
jupyter notebook
```
