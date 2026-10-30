# 🌟 Oasis Infobyte Internship Projects (OIBSIP) — Data Analytics

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
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
| **Task 2** | *Upcoming Internship Task* | Data Analytics | ⏳ Pending | `TBD` |
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

### Summary of Key Findings:
1. **Premium Tier Dominance:** The $500 unit price tier accounts for **54.3% of total revenue ($247,500)** from only 19.9% of transactions.
2. **Seasonal Volatility:** Annual peak in **May 2023 ($53,150)** and Q4 holiday surge (**$126,190** in Q4); annual low in **September 2023 ($23,620)**.
3. **Weekly Dynamics:** **Saturday** is the highest-grossing trading day (**$78,815; AOV $525.43**), while **Thursday** is the slowest (**$53,835**).
4. **Demographic Balance:** Near 50/50 gender parity with identical basket sizes (AOV difference < $1.20). Shoppers aged 36–64 generate **59.9%** of revenue, while young adults (18–25) record the highest Average Order Value (**$500.30**).

*For the complete analysis, 16-section notebook walkthrough, and 5 actionable business recommendations, see the [Task 1 Documentation](OIBSIP_DataAnalytics_Task1_EDA_RetailSales/README.md).*

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
pip install -r OIBSIP_DataAnalytics_Task1_EDA_RetailSales/requirements.txt
```

### 4. Launch the Task 1 Notebook
```bash
jupyter notebook OIBSIP_DataAnalytics_Task1_EDA_RetailSales/notebooks/EDA_Retail_Sales_Analysis.ipynb
```

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
