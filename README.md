# 📈 Retail KPI Dashboard

> **Business Question:** How is the business performing across regions and categories — and where are the gaps?

## Overview

An interactive multi-panel dashboard built with Python and Plotly that analyses 4 years of retail sales data across categories, regions, and customer segments. The output is a standalone HTML file you can open in any browser — no server needed.

## Live Dashboard

Open `retail_dashboard.html` in your browser after running the notebook.

## Key Findings

| Finding | Detail |
|---------|--------|
| 📉 Discount cliff | Discounts above 30% consistently produce negative profit |
| 🗺️ Regional gap | West leads with highest margins; Central underperforms |
| 🪑 Loss sub-categories | Tables & Bookcases are profit-negative — need pricing review |
| 💼 Segment split | Consumer segment = 52% of sales but lowest margin per order |

## Dashboard Panels

- **KPI row** — Total Sales, Profit Margin (gauge), Total Orders
- **Monthly trend** — Sales + Profit line chart over time
- **Sub-category profit** — Horizontal bar (red = loss-making)
- **Category split** — Donut chart (Technology / Furniture / Office Supplies)
- **Region comparison** — Bar chart + summary table with margin %
- **Discount vs Profit** — Scatter plot showing correlation
- **Segment mix** — Donut chart by customer type

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Plotly](https://img.shields.io/badge/Plotly-5.x-purple)
![Pandas](https://img.shields.io/badge/Pandas-2.0-lightblue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## Dataset

📥 Download from Kaggle:  
**[Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)**

1. Download `Sample - Superstore.csv`
2. Place in `data/` folder
3. Run the notebook

> Auto-generates sample data if the real dataset is absent.

## How to Run

```bash
git clone https://github.com/JahnaviGangadi/retail-dashboard.git
cd retail-dashboard
pip install -r requirements.txt
jupyter notebook notebooks/retail_dashboard.ipynb
# Then open retail_dashboard.html in your browser
```

## Project Structure

```
retail-dashboard/
├── notebooks/
│   └── retail_dashboard.ipynb
├── data/
│   └── Sample - Superstore.csv   ← Download from Kaggle
├── images/
├── retail_dashboard.html          ← Auto-generated interactive dashboard
├── requirements.txt
└── README.md
```

## Author

**Jahnavi Gangadi** · [LinkedIn](https://linkedin.com/in/jahnavi-gangadi-aa8a06262) · [Kaggle](https://kaggle.com/jahnavigangadi)
