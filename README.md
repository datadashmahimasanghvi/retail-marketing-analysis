# retail-marketing-analysis

Retail analytics using Python: Data cleaning, KPI reporting, visualizations (RFM, revenue, retention)

## 📊 Retail Marketing Analysis

This project uses Python to analyze real-world online retail data. It covers everything from cleaning and preprocessing to KPI calculation and insightful marketing visualizations.

---

## 🧾 Project Overview

- Loads transactional data from `Online Retail.xlsx`
- Cleans data (removes cancellations, negative quantities/prices, missing IDs)
- Computes KPIs and exports clean data as CSV
- Performs EDA & visualization using Python (pandas, matplotlib)
- Saves all final outputs and tables as CSV

---

## 🔍 Key Features & Visualizations

- **Monthly Revenue Trend**  
  Understand seasonal spikes and dips across time.

- **Top Products by Revenue**  
  Identify best-selling items and high-margin goods.

- **Top Countries by Revenue**  
  Spot international market potential outside dominant regions.

- **RFM Segmentation**  
  Segment customers by Recency, Frequency, and Monetary value.

- **Cohort Retention Analysis**  
  Track customer retention month-over-month after first purchase.

---

## 📈 Sample Insights

| KPI                    | Value         |
|------------------------|---------------|
| Unique Customers       | 4,338         |
| Unique Invoices        | 19,960        |
| Total Revenue (GBP)    | ~10.6 Million |
| Time Period Covered    | Dec 2010 – Dec 2011 |

### Business Takeaways:
- Q4 peaks suggest opportunities for seasonal promotions
- Majority of buyers are one-time or low-value; focus needed on retention
- UK dominates sales; room for international growth
- High-value repeat buyers can be nurtured via loyalty perks

---

## 📁 Files in Repository

| File                             | Description                          |
|----------------------------------|--------------------------------------|
| `Online Retail.xlsx`             | Raw transactional dataset            |
| `Online_Retail_Analytics.ipynb` | Main Python notebook                 |
| `online_retail_clean.csv`       | Cleaned transactional data           |
| `online_retail_kpis.csv`        | Summary of key KPIs                  |
| `online_retail_monthly_revenue.csv` | Monthly revenue trend          |
| `online_retail_top_products.csv`    | Top 10 products by revenue       |
| `online_retail_top_countries.csv`   | Top 15 countries by revenue      |
| `online_retail_rfm.csv`             | RFM segmentation table            |
| `online_retail_cohort_retention.csv` | Cohort retention analysis table |

---

## 🛠️ Tools Used

- **Python**  
  `pandas`, `numpy`, `matplotlib`

- **Environment**  
  Jupyter Notebook  
  GitHub for version control

---

## ✅ How to Reproduce

1. Clone this repo:
   ```bash
   git clone https://github.com/mahimashitalsanghvi-art/retail-marketing-analysis.git
   cd retail-marketing-analysis

   
