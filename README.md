# 🛒 E-Commerce Conversion Funnel Analysis

An end-to-end data analysis project investigating customer journey patterns, drop-off bottlenecks, and high-performing product categories using Python, Pandas, and Plotly.



## 📊 Executive Summary

This project analyzes user event logs from an e-commerce platform to map out the conversion funnel (`view` ➔ `cart` ➔ `purchase`). 

### Key Findings
* **Primary Bottleneck:** There is a **96.7% drop-off rate** between initial product views and add-to-cart events.
* **Direct Purchase Behavior:** Purchase counts exceed cart additions (**-69.2% drop-off**), highlighting strong user adoption of single-click "Buy Now" options.
* **Top Revenue Category:** `electronics.smartphone` dominates engagement with **23,631 views** and **624 purchases**.



## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Plotly Express



## 📈 Methodology & Workflow

1. **Data Ingestion:** Loaded event data and evaluated unique user sessions across funnel stages.
2. **Funnel Visualization:** Modeled stage progression and calculated step-by-step conversion percentages using Plotly.
3. **Category Breakdown:** Grouped purchases and views by category code to isolate high-performing segments.
4. **Drop-off Calculation:** Calculated loss percentages across consecutive funnel stages to detect checkout friction.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/@lavanyamakireddy1/ecommerce_funnel_analysis.git](https://github.com/lavanyamakireddy1/ecommerce_funnel_analysis.git)
