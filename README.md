# Customer Churn & Retention Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing customer churn to understand customer retention patterns and identify factors associated with customer attrition. The dataset was cleaned and analyzed using Python and Pandas, and an interactive dashboard was developed in Power BI to present key performance indicators (KPIs) and customer churn patterns.

The dashboard allows users to explore churn across contract types, tenure groups, payment methods, and subscription types.

## 🎯 Project Objectives

- Analyze customer churn and retention.
- Calculate the overall customer churn rate.
- Compare churn across different contract types.
- Understand churn patterns across customer tenure groups.
- Analyze churn by payment method and subscription type.
- Build an interactive Power BI dashboard for business insights.

## 🛠️ Tools & Technologies

- **Python** – Data cleaning and preprocessing
- **Pandas** – Data manipulation and analysis
- **Jupyter Notebook** – Data analysis workflow
- **Power BI** – Interactive dashboard and data visualization
- **CSV / Excel** – Dataset storage and management

## 📊 Dataset Information

- **Total customer records:** 492
- **Total columns:** 23
- **Churned customers:** 116
- **Retained customers:** 374

The dataset contains customer information such as customer ID, gender, location, subscription type, payment method, contract type, internet service, tenure, monthly charges, and churn status.

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Customers | 492 |
| Churned Customers | 116 |
| Retained Customers | 374 |
| Customer Churn Rate | 23.58% |
| Average Monthly Charges | ₹1.36K |

*These values are from the current dashboard. The currency and unit for monthly charges should be verified against the dataset source.*

## 📉 Dashboard Features

The Power BI dashboard includes:

- **Customer Overview:** Total customers, churned customers, retained customers, and churn rate.
- **Contract Analysis:** Comparison of churned customers across contract types.
- **Tenure Analysis:** Examination of churn patterns across customer tenure groups.
- **Payment Method Analysis:** Comparison of churned customers by payment method.
- **Subscription Analysis:** Distribution of churned customers across subscription categories.
- **Interactive Filters:** Filtering by contract type and gender.

Additional churn-rate comparisons can be included to evaluate churn proportions across different customer segments.

## 🔍 Data Cleaning & Analysis

The dataset was processed using Python and Pandas. The main tasks included:

1. Removing leading and trailing spaces from text columns.
2. Standardizing text capitalization.
3. Identifying inconsistent subscription categories.
4. Checking missing values in important columns.
5. Creating tenure groups for customer segmentation.
6. Preparing the cleaned dataset for Power BI visualization.

Missing subscription values were identified for six customer records. These records were retained rather than deleted.

## 💡 Business Value

This dashboard helps explore customer churn patterns and compare customer segments. The analysis can support further investigation into which contract types, tenure groups, payment methods, and subscription categories have higher churn.

The findings can help businesses identify segments that may require closer examination and develop data-driven customer retention strategies.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the Jupyter Notebook containing the data cleaning and analysis.
3. Install the required Python libraries.
4. Run the notebook cells to reproduce the preprocessing steps.
5. Open the Power BI `.pbix` file in Power BI Desktop.
6. Update the dataset path if required and refresh the data.
7. Explore the dashboard using its interactive filters.

### Python Requirements

```bash
pip install pandas numpy matplotlib openpyxl
```

Install only the libraries used by your notebook.

## 📂 Project Structure

```text
Customer-Churn-Analysis/
│
├── data/
│   └── Cleaned_churn_data.csv
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── dashboard/
│   └── Customer_Churn_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

*Update the filenames and folders to match your actual GitHub repository.*

## 🔮 Future Improvements

- Add churn-rate comparisons across customer segments.
- Analyze churn by monthly charge ranges.
- Investigate the relationship between customer tenure and churn.
- Improve data quality checks and missing-value handling.
- Add more interactive filters and drill-down features.
- Develop a predictive model to identify customers at risk of churn, if suitable data is available.

## 👨‍💻 Author

**Neeraj Kumar**

B.Tech – Computer Science and Engineering (AI & ML)

**Skills:** Python | Pandas | SQL | Power BI | Data Analysis

- GitHub: [Neeraj472](https://github.com/Neeraj472)
- LinkedIn: [Add your LinkedIn profile URL]

---

*This project was developed for practical learning and portfolio development in data analytics.*
