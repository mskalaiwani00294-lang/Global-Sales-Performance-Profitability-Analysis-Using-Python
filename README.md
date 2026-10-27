
<img width="1280" height="547" alt="WhatsApp Image 2026-10-05 at 10 45 09 AM" src="https://github.com/user-attachments/assets/073702c4-5ffd-453b-b29f-5be0d2234aa5" />

## 📌 Project Overview

The **Global Sales Performance & Profitability Analysis Using Python** project analyzes 1,000 sales transactions to understand business performance, revenue trends, profitability, regional performance, and product category performance.

This project uses Python for data cleaning, Exploratory Data Analysis (EDA), statistical analysis, data visualization, and revenue forecasting. The insights help businesses understand sales performance, identify profitable product categories, and make data-driven decisions.

## 🎯 Project Objectives

- Analyze total revenue, total cost, and total profit.
- Evaluate sales performance across regions and product categories.
- Calculate profit margins and other key performance indicators (KPIs).
- Identify trends, correlations, and outliers in sales data.
- Forecast revenue for the next six months using time-series forecasting.
- Evaluate forecasting performance using appropriate error metrics.
- Develop actionable business insights and recommendations.

## 🛠️ Tools & Technologies

- **Python** – Data analysis and forecasting
- **Pandas & NumPy** – Data cleaning and numerical analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Model evaluation and Linear Regression
- **Statsmodels** – Time-series forecasting using ARIMA and Holt-Winters
- **Google Looker Studio (Data Studio)** – Interactive dashboard
- **Jupyter Notebook / Google Colab** – Development environment
- **Git & GitHub** – Version control and project documentation

## 📂 Project Workflow

1. **Data Loading:** Import the sales dataset using Pandas.
2. **Data Cleaning:** Check missing values, duplicate records, and data types.
3. **Feature Engineering:** Create Profit Margin, Shipping Days, Order Year, Order Month, and Month Name.
4. **Exploratory Data Analysis:** Analyze numerical distributions, categorical variables, and relationships between business metrics.
5. **Statistical Analysis:** Examine correlation, skewness, kurtosis, and outliers.
6. **Business Analysis:** Calculate KPIs and compare regional and product performance.
7. **Data Visualization:** Create charts to communicate sales trends and business insights.
8. **Revenue Forecasting:** Predict revenue for the next six months using time-series models.
9. **Model Evaluation:** Compare forecasted and actual values using MAE, RMSE, and MAPE.
10. **Dashboard Development:** Present important KPIs and findings in an interactive dashboard.

## 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|---|---|
| Total Revenue | Total sales revenue generated |
| Total Cost | Total cost of sales |
| Total Profit | Revenue minus total cost |
| Profit Margin (%) | Profit as a percentage of revenue |
| Units Sold | Total quantity of products sold |
| Average Unit Price | Average selling price per unit |
| Shipping Days | Time taken to ship orders |

## 📈 Exploratory Data Analysis (EDA)

The project explores the following areas:

- Univariate analysis of sales and profit variables.
- Bivariate analysis of revenue, cost, and profit.
- Multivariate analysis using correlation matrices and heatmaps.
- Distribution analysis using histograms and box plots.
- Outlier detection and treatment using the IQR method.
- Regional and product-category performance comparisons.
- Monthly and yearly revenue trend analysis.

## 🔮 Revenue Forecasting

The project explores forecasting techniques to estimate revenue for the next six months.

**Models considered:**
- Linear Regression – Baseline forecasting model.
- Seasonal Naive Forecast – Seasonal benchmark.
- Holt-Winters Exponential Smoothing – Trend and seasonality-based forecasting.
- ARIMA – Time-series forecasting model.

**Model evaluation metrics:**
- **MAE:** Mean Absolute Error.
- **RMSE:** Root Mean Squared Error.
- **MAPE:** Mean Absolute Percentage Error.

The models should be evaluated on a chronological train-test split. The final forecasting model should be selected based on test-set performance and the suitability of its assumptions for the dataset.

## 💡 Key Business Insights

The analysis identified the following findings from the project:

- Total revenue was approximately **1.23 billion**.
- Total profit was approximately **377.8 million**.
- Overall profit margin was approximately **30.8%**.
- Office Supplies contributed the highest revenue among the displayed product categories.
- Cosmetics generated the highest total profit among the displayed product categories.
- Europe and Sub-Saharan Africa were leading regions in total profit.
- The yearly revenue trend showed a decline toward 2017, which requires further investigation.

*Note: These findings should be verified against the final cleaned dataset and dashboard before publication.*

## ✅ Business Recommendations

1. **Improve profitability:** Focus on high-profit product categories and investigate products with lower profit margins.
2. **Optimize costs:** Review unit costs, shipping expenses, and other cost drivers.
3. **Strengthen regional performance:** Study successful regions and identify opportunities in lower-performing markets.
4. **Monitor sales trends:** Investigate the decline in revenue toward 2017 and identify possible causes.
5. **Improve forecasting:** Compare forecasting models and use validated test results to support inventory and sales planning.
6. **Track KPIs regularly:** Use an interactive dashboard to monitor revenue, profit, and regional performance.

## 📊 Interactive Dashboard

Explore the interactive sales performance dashboard built using Google Looker Studio.

<img width="1045" height="788" alt="1" src="https://github.com/user-attachments/assets/bdbb073d-cf84-459b-961e-5d63b1d641c0" />

🔗 **[View Global Sales Performance Dashboard](https://datastudio.google.com/reporting/b72e264e-8b1a-4637-9274-e1c1b651b857)**

*Ensure that the dashboard sharing permissions allow your intended audience to view it.*

## 📁 Project Structure

```text
Global-Sales-Performance-Analysis/
│
├── Global_Sales_Performance_Analysis.ipynb
├── README.md
├── dataset/
│   └── sales_dataset.csv
└── images/
    └── dashboard_screenshot.png
```

*Update the filenames and folders to match the actual contents of your repository.*

## 🚀 How to Run the Project

1. Clone or download this GitHub repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook in Jupyter or Google Colab.
4. Upload the dataset or update the dataset file path.
5. Run the notebook cells in sequence to reproduce the analysis.

Install the main libraries:

```python
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

## 📚 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Feature Engineering
- Data Visualization
- Business Intelligence
- KPI Analysis
- Time-Series Forecasting
- Forecast Model Evaluation
- Business Insights and Recommendations
- Dashboard Development
- Python Programming

## 👩‍💻 Author

**Kalai Vani**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Data Visualization | Business Intelligence

## ⭐ Conclusion

This project demonstrates how Python-based data analysis and forecasting can turn raw sales data into meaningful business insights. The analysis supports better understanding of revenue, profitability, regional performance, and product trends while providing a foundation for data-driven business decisions.

If you find this project useful, please consider giving the repository a ⭐ star.
