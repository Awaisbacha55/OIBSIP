# 🌟 Oasis Infobyte Internship Projects (OIBSIP) — Data Analytics

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.3%2B-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.24%2B-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7%2B-11557c.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12%2B-4c72b0.svg)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Internship Overview

- **Organization:** Oasis Infobyte (OIBSIP)
- **Domain:** Data Analytics
- **Intern:** Muhammad Awais
- **Repository:** [Awaisbacha55/OIBSIP](https://github.com/Awaisbacha55/OIBSIP)

This repository contains all the completed tasks for the **Oasis Infobyte Data Analytics Internship**. Each task is organized in a self-contained directory with its dataset, executed Jupyter Notebook, high-resolution exported visualizations, and detailed documentation.

---

## 📋 Table of Internship Tasks

| Task # | Task Title | Domain | Status | Project Directory |
| :---: | :--- | :--- | :---: | :--- |
| **Task 1** | **Exploratory Data Analysis (EDA) on Retail Sales Data** | Exploratory Data Analysis | ✅ Completed | [`OIBSIP_DataAnalytics_Task1_EDA_RetailSales/`](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/) |
| **Task 2** | **Customer Segmentation Analysis using K-Means & RFM** | Machine Learning & Clustering | ✅ Completed | [`OIBSIP_DataAnalytics_Task2_CustomerSegmentation/`](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/) |
| **Task 3** | *Upcoming Internship Task* | Data Analytics | ⏳ Pending | `TBD` |

---

## 📊 Task 1 Spotlight: EDA on Retail Sales Data

- **Directory:** [`OIBSIP_DataAnalytics_Task1_EDA_RetailSales/`](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/)
- **Master Notebook:** [`EDA_Retail_Sales_Analysis.ipynb`](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/notebooks/EDA_Retail_Sales_Analysis.ipynb)
- **Dataset:** 1,000 real-world retail transactions from Kaggle (spanning 2023–2024).

### Key Highlights & Visualizations

| Monthly Sales Trends & Order Volume | Customer Age Distribution & Cohort Spend |
| :---: | :---: |
| ![Monthly Sales Trend](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/images/charts/monthly_sales_trend.png) | ![Customer Demographics](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/images/charts/customer_demographics.png) |

| Product Category Performance | Numerical Correlation Heatmap |
| :---: | :---: |
| ![Category Revenue](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/images/charts/category_revenue.png) | ![Correlation Heatmap](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/images/charts/correlation_heatmap.png) |

*For the complete analysis, 16-section notebook walkthrough, and 5 actionable business recommendations, see the [Task 1 Documentation](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/README.md).*

---

## 🎯 Task 2 Spotlight: Customer Segmentation Analysis

- **Directory:** [`OIBSIP_DataAnalytics_Task2_CustomerSegmentation/`](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/)
- **Master Notebook:** [`Customer_Segmentation_Analysis.ipynb`](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/notebooks/Customer_Segmentation_Analysis.ipynb)
- **Segmentation Output:** [`customer_segments.csv`](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/outputs/customer_segments.csv)
- **Dataset:** Real-world UCI Online Retail dataset (541k transactions, 4,339 unique customers).

### Key Highlights & Visualizations

| Optimal Cluster Selection (Elbow Method) | Customer Distribution & Revenue Share |
| :---: | :---: |
| ![Elbow Method](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/images/charts/elbow_method.png) | ![Customer Distribution](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/images/charts/customer_distribution.png) |

| Recency vs. Purchase Frequency | Frequency vs. Monetary Spend |
| :---: | :---: |
| ![Recency vs Frequency](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/images/charts/cluster_scatter_rf.png) | ![Frequency vs Monetary](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/images/charts/cluster_scatter_fm.png) |

### Customer Segments Identified:
1. **Champions / High-Value Loyalists (16.4% headcount, 61.4% revenue):** Mean Recency 12.1 days, ~16 orders, £6,500+ spend. Priority for VIP loyalty rewards.
2. **Potential Loyalists / Regulars (26.9% headcount, 21.9% revenue):** Mean Recency 71.8 days, ~4 orders, £581 AOV. Prime candidates for cross-selling and tier upgrades.
3. **New / Recent Shoppers (19.3% headcount, 5.8% revenue):** Mean Recency 17.6 days, ~2 orders, £278 AOV. Targeted with welcome sequences and 2nd-purchase discounts.
4. **At-Risk / Lapsed Customers (37.4% headcount, 10.9% revenue):** Mean Recency 181.5 days, ~1.3 orders. Targets for "We Miss You" win-back incentives.

*For the complete analysis, 18-section notebook walkthrough, and marketing playbooks, see the [Task 2 Documentation](OIBSIP_DataAnalytics_Task2_CustomerSegmentation/README.md).*

---

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Awaisbacha55/OIBSIP.git
cd OIBSIP
```

### 2. Set Up a Virtual Environment
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r OIBSIP_DataAnalytics_Task2_CustomerSegmentation/requirements.txt
```

### 4. Launch the Task Notebooks
```bash
# Task 1 Notebook
jupyter notebook OIBSIP_DataAnalytics_Task1_EDA_RetailSales/notebooks/EDA_Retail_Sales_Analysis.ipynb

# Task 2 Notebook
jupyter notebook OIBSIP_DataAnalytics_Task2_CustomerSegmentation/notebooks/Customer_Segmentation_Analysis.ipynb
```

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
