# Megaline: Consumer Behavior & Revenue Analysis 📱📊

## Project Overview
This project analyzes subscriber behavior, consumption patterns, and revenue streams for Megaline to identify the factors that drive plan profitability. Our goal is to provide a data-driven foundation for the company's commercial strategy by transforming raw usage logs into actionable insights.

The analysis bridges the gap between raw data auditing and strategic business intelligence, ensuring that all findings are backed by statistical rigor.

## 🚀 Key Features
- **Data Engineering:** Consolidated 5 independent datasets into a unified analytical engine.
- **Behavioral Profiling:** Calculated monthly usage (calls, SMS, GB) and revenue per user, accounting for plan overages.
- **Statistical Analysis:** Identification and handling of outliers to ensure clean, representative distributions.
- **Comparative Study:** Analyzed the performance differences between the **Smart** and **Ultra** plans.

## 📈 Main Findings
1. **Usage Patterns:** Users on the Smart plan tend to exceed their limits more frequently, generating significant overage revenue.
2. **Revenue Drivers:** Internet consumption is the primary factor driving extra charges across both plans.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, Numpy).
- **Visualization:** Matplotlib, Seaborn.
- **Statistics:** SciPy (Outlier detection and data distribution analysis).

## 📂 Project Structure
- `megaline_consumer_behavior_analysis.ipynb`: Main notebook with cleaning, analysis, and visualizations.
- `data/`: Original files (calls, internet, messages, plans, users).
- `requirements.txt`: List of dependencies.

## ⚙️ How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook to see the full transformation from raw logs to business insights.

Analysis by **Fiorella Trigo M.** *Part 1 of the Megaline Optimization Series*