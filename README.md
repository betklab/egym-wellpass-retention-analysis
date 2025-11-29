# EGYM Wellpass Retention & Engagement Analysis

##  Project Overview
This project explores user check-in data from EGYM Wellpass (Sep–Oct 2023) to uncover key drivers of member engagement and retention.  
The analysis applies the data science workflow — from cleaning and exploratory analysis to KPI definition and business insights.

---

##  Objectives
- Identify engagement and retention patterns among new Wellpass members.
- Define leading and lagging KPIs to monitor activation and retention.
- Provide actionable recommendations for improving user retention.

---

##  Key Insights (Summary)
- **High first-week activity** strongly predicts long-term retention.  
- **App-based check-ins (QT_APP_QR_CODE)** correlate with higher engagement.  
- **Tech and consulting industries** show higher median check-ins per user.  


---

## Repository Structure
├── data/
│ ├── raw/ # Original dataset or dataset link
│ └── processed/ # Cleaned data used in analysis
├── notebooks/
│ └── EGYM_Wellpass_EDA.ipynb
├── reports/
│ ├── EGYM_Wellpass_Insights.pdf
│ └── visuals/
├── requirements.txt
└── README.md


---

## How to Run the Analysis

### Prerequisites
Install dependencies:
```bash
pip install -r requirements.txt

Run the Notebook

Open in Jupyter or Google Colab:

jupyter notebook notebooks/EGYM_Wellpass_EDA.ipynb
