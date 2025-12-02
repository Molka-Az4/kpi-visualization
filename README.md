# ⚡ KPI Visualization Dashboard – Energy Consumption Analysis

This project is a complete KPI visualization notebook developed in **Google Colab**.  
It analyzes historical energy consumption sessions and generates insights related to usage patterns, demand behavior, and system performance.

The notebook provides a modular structure, with each section dedicated to a specific KPI or operational metric.

---

## 📊 **Key Metrics & Visualizations**

### 1️⃣ Peak Demand Time
Identifies when energy usage is at its highest by:
- Analyzing session start timestamps  
- Cleaning missing or null data  
- Plotting usage curves across different time periods  

This helps detect **rush hours**, load peaks, and charging behavior patterns.

---

### 2️⃣ Availability
Evaluates system or plug availability through:
- Missing session intervals  
- Drop-off periods  
- Data gaps  
- Interval-based analysis  

Useful for assessing the **operational reliability** of the service.

---

### 3️⃣ Power Delivered
Quantifies energy delivered to users by:
- Summing `energy_wh`  
- Analyzing distribution  
- Identifying abnormal consumption patterns  

Helps determine **energy usage efficiency** and system load.

---

### 4️⃣ Plug-in Time
Measures how long users keep the system engaged:
- Start vs Stop timestamps  
- Session duration analysis  
- Outlier removal  

Supports operational optimization and **resource occupancy planning**.

---

### 5️⃣ Total Charging Sessions
Calculates total sessions over time, including:
- Daily totals  
- Weekly/monthly trends  
- Session distribution by plug or station  

Offers a high-level view of **service demand evolution**.

---

### 6️⃣ Energy Consumption
Aggregates delivered energy to visualize:
- Consumption trends  
- Seasonal patterns  
- High-usage segments  

Depending on the dataset, this can be used to predict future consumption and optimize infrastructure.

---

## 🧹 **Data Cleaning Steps**
Throughout the notebook, you will find structured preprocessing such as:

- Handling missing timestamps (`start`, `stop`)  
- Removing invalid or incomplete sessions  
- Converting datetime columns  
- Computing derived metrics (duration, energy per session, etc.)  

This improves the **accuracy and reliability** of all KPIs.

---

## 🛠️ **Tools & Technologies**

| Component | Description |
|----------|-------------|
| **Python** | Primary language |
| **Pandas** | Data manipulation & cleaning |
| **Matplotlib / Seaborn** | Visualization |
| **Google Colab** | Execution environment |
| **CSV dataset** | Historical energy consumption |

---

## ▶️ **How to Run the Notebook**

1. Download the notebook:  
   `KPI's_visualizations.ipynb`

2. Open it in Google Colab:  
   https://colab.research.google.com/

3. Upload your dataset and update the path if needed:  
   ```python
   data = pd.read_csv("/content/historical_consumption.csv")
