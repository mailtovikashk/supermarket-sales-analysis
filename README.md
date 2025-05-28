# supermarket-sales-analysis
Mini-project analyzing 3-day supermarket sales data using Python and Pandas.
# 🛒 Supermarket Sales Analysis

This mini-project is a simple data analysis of a 3-day supermarket sales dataset using Python and Pandas.

## 📊 Dataset

The dataset contains sales records of two products — Apples and Bananas — over three days. Each entry includes:
- Date
- Product
- Units Sold
- Price per Unit
- Total Sales (calculated)

## 🧠 Key Insights

- Basic data manipulation using `pandas`
- Simple sales analysis over a time series
- Demonstration of Excel and CSV data formats

## 📁 Files Included

- `supermarket_sales_analysis.xlsx`
- `supermarket_sales_analysis.csv`

## 🔧 Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook / Colab (for analysis)

## 💡 Future Work

- Expand with daily summaries
- Add visualizations (e.g., matplotlib or seaborn)
- Upload Jupyter Notebook version of analysis

---

### 🚀 How to Run
You can open the CSV/Excel in Excel or import it into Python using:

```python
import pandas as pd
df = pd.read_csv("supermarket_sales_analysis.csv")
print(df.head())
