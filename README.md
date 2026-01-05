# 🚑 911 Calls Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)

## 📌 Project Overview
This project is an **Exploratory Data Analysis (EDA)** of a massive dataset containing emergency call records. The goal is to uncover hidden trends in 911 calls, such as the most common reasons for emergencies, peak time hours, and location-based hotspots.

Insights from this analysis can help emergency response agencies optimize staffing and resource allocation.

## 📊 Key Insights & Features
* **Data Cleaning:** Extracted specific features from timestamps and standardized column names.
* **Category Analysis:** Identified the top 3 reasons for 911 calls (EMS, Traffic, Fire).
* **Temporal Analysis:** Visualized call volume by Hour, Day, and Month to detect spikes in activity.
* **Heatmaps:** Created correlation heatmaps to show the relationship between day-of-week and hour-of-day.

## 📷 Results & Visualizations
*(Note: These are snapshots from the analysis notebook)*

### 1. Calls by Reason
![Reason Count](![images\911 calls by reason.png](<images/911 calls by reason.png>))
*Insight: EMS (Emergency Medical Services) is the leading cause of 911 calls.*

### 2. Activity Heatmap (Day vs Hour)
![Heatmap](![images/Heatmap for 911 calls.png](<images/Heatmap for 911 calls.png>))
*Insight: The highest volume of calls occurs on weekdays between 4 PM and 6 PM.*

## 🚀 How to Run Locally

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/KSAahil/911-calls-analysis.git](https://github.com/KSAahil/911-calls-analysis.git)
    cd 911-calls-analysis
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook notebooks/analysis.ipynb
    ```

## 📂 Directory Structure
```text
├── data/               # Raw dataset (911.csv)
├── images/             # Visualizations and plots
├── notebooks/          # Jupyter Notebook with full analysis
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation