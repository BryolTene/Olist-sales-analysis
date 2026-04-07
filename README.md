# Olist Sales Analysis
### End-to-end sales data analysis — Brazilian E-Commerce

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Project Overview

End-to-end analysis of the Olist Brazilian E-Commerce dataset from Kaggle.
This project covers the full data pipeline from raw data to machine learning predictions.

---

## Project Structure

    olist-sales-analysis/
    │
    ├── data/
    │   ├── raw/          # Original CSV files from Kaggle
    │   ├── cleaned/      # Cleaned individual tables
    │   └── gold/         # Final enriched master table
    │
    ├── olist_sales_analysis.ipynb   # Main notebook
    ├── requirements.txt             # Dependencies
    └── README.md                    # Project documentation

---

## Project Steps

| Step | Section |
|------|---------|
| 1 | Data Collection & Loading |
| 2 | Data Cleaning & Validation |
| 3 | Feature Engineering |
| 4 | KPI Analysis |
| 5 | RFM & Cohort Analysis |
| 6 | Delivery vs Satisfaction Correlation |
| 7 | Visualizations & Executive Dashboard |
| 8 | Machine Learning |
| 9 | Insights & Business Recommendations |

---

## Key Results

| KPI | Value |
|-----|-------|
| Total Revenue | R$ 15,843,553 |
| Total Orders | 98,666 |
| Avg Order Value | R$ 180 |
| Total Customers | 95,420 |
| Avg Delivery Time | 12 days |
| Delay Rate | 6.4% |
| Repeat Customer Rate | 6.6% |
| Avg Review Score | 4.03 / 5 |

---

## Machine Learning

| Model | Type | Result |
|-------|------|--------|
| Late Delivery Prediction | Random Forest Classifier | 94% accuracy |
| Review Score Prediction | Random Forest Regressor | R2 0.18 |

---

## Tech Stack

| Tool | Usage |
|------|-------|
| Python 3.13 | Core language |
| pandas | Data manipulation |
| numpy | Numerical computing |
| matplotlib / seaborn | Visualization |
| scikit-learn | Machine Learning |
| kagglehub | Dataset download |
| Jupyter Notebook | Development environment |

---

## Getting Started

    # 1. Clone the repository
    git clone https://github.com/YOUR_USERNAME/olist-sales-analysis.git

    # 2. Create virtual environment
    python3 -m venv sales_analysis
    source sales_analysis/bin/activate

    # 3. Install dependencies
    pip install -r requirements.txt

    # 4. Launch Jupyter
    jupyter notebook

---

## Dataset

The dataset is automatically downloaded from Kaggle via kagglehub.
No manual download required.

Source : https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Author
Bryol Ulrich Tene
GitHub : https://github.com/BryolTene

---

## License
MIT License
