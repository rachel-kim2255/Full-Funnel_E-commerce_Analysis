# 🛍️ Google Merchandise Store: Full-Funnel E-commerce Analysis
**🛠️ SQL (BigQuery), Python, Google Analytics 4**  
Full-funnel e-commerce analysis of the Google Merchandise Store using GA4 and BigQuery, covering channel acquisition, purchase funnel, device behavior, user retention, and product category performance.
<br>

📎 Rachel Kim  
📅 Date: 2026.03 (Completed)  
📚 Individual Project
<br>

👉 **Tip:** For best experience, open this notebook in **Google Colab** and use the **Table of Contents panel (on the left)** to quickly navigate between sections.  
[Colab Link](https://colab.research.google.com/github/rachel-kim2255/Full-Funnel_E-commerce_Analysis/blob/main/Google_Merchandise_Store_Full_Funnel_E_commerce_Analysis.ipynb)

---

### 📂 Project Objective
- To analyze user behavior and marketing performance of the Google Merchandise Store using two complementary data sources: GA4 Demo Account (UI reference) and BigQuery public dataset (quantitative analysis).
- To identify which channels, devices, and user segments drive the highest conversion, and translate findings into actionable business recommendations.

---

### 📂 Dataset Description
- **Source:** BigQuery Public Dataset — `bigquery-public-data.ga4_obfuscated_sample_ecommerce`
- **Period:** November 2020 – January 2021
- **GA4 Demo Account:** Used for UI reference only (current rolling data)
- **Granularity:** Event-level data including page views, add-to-cart, checkout, and purchase events linked with user, device, and traffic source details.

---

### 📂 Key Analyses Performed
#### 1. Channel-Level User Acquisition & Conversion
- Total users and conversion rate by traffic channel
- Identification of highest and lowest performing channels

#### 2. Purchase Funnel Analysis
- Overall funnel drop-off rates across view_item → add_to_cart → begin_checkout → purchase
- Channel-level funnel comparison to identify where each channel loses users

#### 3. Device-Level Conversion Analysis
- Funnel completion and drop-off rates by device type (desktop, mobile, tablet)
- Identification of device-specific friction points

#### 4. New vs Returning User Analysis
- Conversion rate comparison between new and returning users
- Channel-level returning user rate analysis

#### 5. Purchase Pattern by Day of Week
- Weekday vs weekend purchase volume comparison (PST)
- Identification of peak purchase days for campaign timing

#### 6. Product Category Performance
- Views, purchases, revenue, and view-to-purchase rate by category
- Identification of high-traffic but low-conversion categories

---

### 🛠️ Tools & Technologies
- Google Analytics 4 (Demo Account)
- BigQuery (`bigquery-public-data.ga4_obfuscated_sample_ecommerce`)
- Python (Pandas, Matplotlib, NumPy)
- Google Colab
