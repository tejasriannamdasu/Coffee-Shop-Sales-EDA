# ☕ Coffee Shop Sales - Exploratory Data Analysis (EDA)

A complete, industry-style Exploratory Data Analysis on a Coffee Shop Sales dataset (three NYC store locations, Jan-Jun 2023 transactions), covering data cleaning, feature engineering, univariate/bivariate/multivariate analysis, outlier detection, and data-driven business insights and recommendations.

## 📌 Project Overview

This project analyzes transaction-level coffee shop sales data to uncover patterns in customer purchasing behavior, peak business hours, top-performing products, and store performance — and translates those patterns into actionable business recommendations.

## 📂 Dataset

`coffee_shop_sales.csv` — transaction-level records with the following columns:

| Column | Description |
|---|---|
| transaction_id | Unique transaction identifier |
| transaction_date | Date of transaction |
| transaction_time | Time of transaction |
| transaction_qty | Quantity of items purchased |
| store_id / store_location | Store identifier and location |
| product_id | Product identifier |
| unit_price | Price per unit ($) |
| product_category | High-level product category (Coffee, Tea, Bakery, etc.) |
| product_type | Product sub-type |
| product_detail | Specific product name |

> If you have your own Coffee Shop Sales file, just replace `coffee_shop_sales.csv` — the notebook works unchanged as long as column names match.

## 🔍 What's Inside the Notebook

- Data loading, inspection, cleaning (missing values, duplicates)
- Datetime conversion & feature engineering (Revenue, Month, Day, Hour, Weekday)
- Univariate analysis (distributions, frequency counts)
- Bivariate analysis (category/store/hour/weekday vs revenue)
- Multivariate analysis (correlation heatmap, pairplot, pivot tables, grouped heatmaps)
- Outlier detection using the IQR method
- 20 business insights
- 11 actionable business recommendations
- Final report / conclusion

## 📁 Folder Structure

```
coffee-shop-sales-eda/
│
├── Coffee Shop Sales EDA.ipynb    # Main analysis notebook
├── coffee_shop_sales.csv          # Dataset
├── requirements.txt               # Python dependencies
├── .gitignore
└── README.md
```

## ⚙️ Setup & Usage

```bash
git clone https://github.com/<your-username>/coffee-shop-sales-eda.git
cd coffee-shop-sales-eda
pip install -r requirements.txt
jupyter notebook "Coffee Shop Sales EDA.ipynb"
```

## 🛠️ Tools & Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Key Insights (Sample)

- Coffee is the top revenue and volume driver across all stores.
- Morning hours (7-10 AM) are the peak business period.
- Lower Manhattan is the best-performing store location.
- Revenue trends upward from January to June.
- Weekday sales outperform weekend sales.

## 📈 Future Scope

- Sales/demand forecasting with time-series models
- Customer segmentation (RFM analysis)
- Interactive Power BI / Tableau / Streamlit dashboard
- A/B testing of proposed promotions

## 👤 Author

Your Name — Data Analyst / Software Engineering Intern Candidate

---

### 📄 Resume-Ready Project Description

- Performed end-to-end Exploratory Data Analysis on a 10,000+ transaction coffee shop sales dataset using Python (Pandas, NumPy, Matplotlib, Seaborn), covering data cleaning, feature engineering, and outlier detection.
- Conducted univariate, bivariate, and multivariate analysis, building 20+ visualizations to uncover sales trends across product categories, store locations, and time (hour/day/month).
- Derived 20 data-driven business insights and 11 actionable recommendations (e.g., peak-hour combo offers, store-level strategy, loyalty programs) to support revenue growth.
- Delivered a well-documented, GitHub-ready analytics project following clean code and PEP8 standards, suitable for a data analyst/BI portfolio.

### 📝 GitHub Repository Description (2-3 lines)

End-to-end Exploratory Data Analysis of coffee shop sales data using Python, Pandas, and Seaborn — including data cleaning, time-based feature engineering, 20+ visualizations, and actionable business insights on top products, peak hours, and store performance.
