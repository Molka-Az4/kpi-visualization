# ⚡ Energy Consumption – KPI Visualization Dashboard  
*A complete analytics project combining Python (Colab) & Power BI*

# 📘 Overview

This project provides an end-to-end analysis of **energy consumption sessions**, using both:

- **Python** (Google Colab) — for data cleaning, KPI extraction, trend analysis  
- **Power BI** — for business user-friendly dashboards and operational insights  

It demonstrates technical skills across data preprocessing, KPI design, visualization, and BI storytelling.

The goal is to help understand **when, how, and how much** energy is consumed — and identify patterns such as peak periods, abnormal behaviors, and usage efficiency.


# 📊 Python KPI Analysis (Google Colab)

The notebook is structured into modular analytical blocks, each focusing on a specific KPI or operational metric.


## 1️⃣ Peak Demand Time
Identifies the periods with highest energy usage by:
- Analyzing session start timestamps  
- Cleaning null or missing values  
- Plotting usage curves over time  

This helps detect **rush hours**, load peaks, and charging behavior patterns.


## 2️⃣ Availability
Evaluates system or plug availability by examining:
- Missing session intervals  
- Drop-off periods  
- Data gaps  
- Interval-based anomalies  

Supports assessment of overall **operational reliability**.


## 3️⃣ Power Delivered
Quantifies delivered energy using:
- Aggregation of `energy_wh`  
- Distribution analysis  
- Outlier detection  

Useful to evaluate **energy efficiency** and load distribution.


## 4️⃣ Plug-in Time
Measures how long users keep the system occupied:
- Duration between start/stop  
- Outlier cleaning  
- Usage interval analysis  

Enables planning of **resource occupancy** and optimization.


## 5️⃣ Total Charging Sessions
Tracks overall system usage:
- Daily/weekly/monthly demand  
- Session distribution by plug or station  
- Long-term trend visualization  

Provides a strategic view of **service demand evolution**.


## 6️⃣ Energy Consumption Trends
Analyzes global consumption variations:
- Seasonal/periodic patterns  
- High-usage segments  
- Energy forecasting foundations  

Helps anticipate future upgrades and constraints.


#  Data Cleaning & Preprocessing

The notebook includes robust data-cleaning steps:
- Handling missing timestamps (`start`, `stop`)  
- Removing invalid or incomplete sessions  
- Datetime normalization & conversions  
- Derived metrics (duration, energy/session, etc.)  

Ensures high-quality, reliable KPIs.


# 🛠 Tools & Technologies Used

| Component | Description |
|----------|-------------|
| **Python** | Main analysis language |
| **Pandas** | Data cleaning & transformation |
| **Matplotlib / Seaborn** | Visualization libraries |
| **Google Colab** | Execution environment |
| **CSV Dataset** | Historical consumption data |

---

# 📊 Power BI KPI Dashboard (Screenshots Only)

To complement the Python KPI analysis, the project includes a **Power BI interactive dashboard** designed for business and operational teams.

### ✔️ Operational Monitoring
- Daily/weekly demand patterns  
- Global consumption overview  
- Detection of sudden usage changes  

### ✔️ KPI Comparison & Trend Tracking
- Power delivered trends  
- Station/plug usage frequency  
- Abnormal consumption identification  

### ✔️ User Behavior Insights
- Plug-in time distribution  
- Session frequency  
- Resource occupancy  

## Dashboard Screenshots

The following visuals are included in the `/powerbi` folder:

Screenshots showcase dashboard pages while protecting sensitive or confidential information.  
The `.pbix` file is **not provided** for data privacy reasons.


## Tools Used for the Dashboard
- **Power BI Desktop**  
- **DAX**  
- **Power Query**  
- **Interactive visuals & slicers**  



