# Megaline: Consumer Behavior & Revenue Analysis

## 1. The Problem
Telecom commercial strategies often risk misaligning plan features with actual consumer behavior, resulting in missed revenue opportunities or high subscriber churn. Without consolidating independent operational logs (calls, messages, web traffic) and auditing distribution outliers, a company cannot accurately trace which service segments drive profit overages or calculate true Average Revenue Per User (ARPU).

## 2. Objective
The primary objective of this project is to analyze subscriber consumption patterns and revenue streams across Megaline's offerings (Surf and Ultimate plans). By transforming raw usage logs into audited behavioral profiles, this study establishes an empirical data foundation to optimize commercial targeting, identify core revenue drivers, and understand plan profitability factors.

## 3. Methodology
* **Data Engineering:** Consolidated 5 independent datasets (calls, internet, messages, plans, and users) into a single, unified analytical engine.
* **Behavioral Profiling:** Calculated discrete monthly usage metrics (total call duration, SMS volume, gigabytes consumed) and localized exact revenue per user, factoring in plan thresholds and overage fee structures.
* **Statistical Auditing:** Implemented outlier detection and data distribution analysis via SciPy to isolate behavioral anomalies, ensuring clean and representative statistical metrics.
* **Comparative Study:** Conducted a comprehensive behavioral comparison between the Surf and Ultimate plan customer cohorts to map service consumption trends.

## 4. Findings
* **Overage Dynamics:** Subscribers on the Surf plan (the lower-tier baseline) exceed their contract limitations significantly more often than Ultimate users, generating a substantial and predictable stream of overage revenue.
* **Revenue Drivers:** Internet data consumption was statistically isolated as the primary catalyst driving extra charges across both operational plan segments.
* **Data Consolidation Success:** Merging independent behavioral silos allowed for an end-to-end audit of user activity, proving that operational overages heavily shift baseline ARPU distributions.

## 5. Recommendations
* **Targeted Migration Campaigns:** Leverage the behavioral insights to identify specific high-volume Surf plan users who consistently overpay on gigabyte limits, targeting them with tailored promotional upgrades to the Ultimate tier.
* **Data-Centric Plan Refactoring:** Structure future commercial packages around flexible internet data buffers, since web traffic represents the core driver of modern subscriber spend and operational margin scaling.

## 6. Technologies
* **Language:** Python
* **Data Manipulation & Consolidation:** Pandas, NumPy
* **Statistical Analysis:** SciPy (Outlier detection & data distribution analytics)
* **Visualization:** Matplotlib, Seaborn

---

## Project Structure
```text
├── data/                              # Folder containing original CSV data silos
├── img/                               # Generated data visualizations and charts 
├── notebooks/                         # Analytical environment and distribution processing
├── README.md                          # Project executive summary and documentation
└── requirements.txt                   # Project dependencies

```

---

## Installation & Environment Setup

This project uses an isolated Python environment. To replicate this setup, run the following commands in your terminal:

### 1. Clone the repository

```bash
git clone [https://github.com/fiorellatrigo/megaline_consumer_behavior_analysis](https://github.com/fiorellatrigo/megaline_consumer_behavior_analysis)
cd megaline_consumer_behavior

```

### 2. Create and activate the virtual environment

* **Windows:**

```powershell
python -m venv env
.\env\Scripts\activate

```

* **Mac/Linux:**

```bash
python -m venv env
source env/bin/activate

```

### 3. Install dependencies & Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/megaline_consumer_behavior_analysis.ipynb

```

---

*Analysis by Fiorella Trigo M.* *Part 1 of the Megaline Optimization Series*
