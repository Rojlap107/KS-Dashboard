# KS Financial Performance Dashboard

An interactive financial analysis tool and dashboard designed to visualize performance across multiple branches. This project processes raw CSV financial data to generate a comprehensive, user-friendly dashboard for tracking Revenue, COGS, Expenses, and Net Profit.

## 🚀 Features

- **Consolidated Overview**: View the entire organization's financial health in one place.
- **Branch Filtering**: Drill down into specific branch performance with dynamic filtering.
- **Interactive Visualizations**: High-quality Doughnut charts for expense distribution using Chart.js.
- **Detailed Breakdowns**: Tabular views for granular expense tracking and branch comparisons.
- **Responsive Design**: Clean, modern aesthetics built with vanilla CSS that works across devices.

## 🛠️ Project Structure

- `analyze_data.py`: The core Python engine that handles data cleaning, aggregation, and HTML generation.
- `dashboard.html`: The generated interactive dashboard.
- `data/`: Directory containing the source financial CSV files.
- `.gitignore`: Standard project exclusions.

## 📋 Prerequisites

- Python 3.x
- Pandas library

To install dependencies:
```bash
pip install pandas
```

## ⚙️ Usage

1. Place your CSV data in the `data/` folder.
2. Run the analysis script:
```bash
python analyze_data.py
```
3. Open `dashboard.html` in any web browser to view your financial insights.

## 📊 Technologies Used

- **Python**: Data processing and backend logic.
- **Pandas**: Structured data analysis.
- **Chart.js**: Dynamic data visualization.
- **Vanilla CSS & HTML5**: Premium dashboard UI.

---
*Developed for KS Dashboard*
