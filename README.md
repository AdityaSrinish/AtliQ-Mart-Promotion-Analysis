# 🛒 AtliQ Mart: Festive Promotions Analysis (Diwali & Sankranti)
<p align="center">
  <img src="https://img.shields.io/badge/SQL-Advanced-orange?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Retail%20Analytics-Data%20Insights-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Business%20Intelligence-Optimization-green?style=for-the-badge" />
</p>

---

## 🏮 Project Overview
During the high-stakes festive seasons of **Diwali 2023** and **Sankranti 2024**, AtliQ Mart launched massive promotional campaigns. This project dives into the data to separate the "hype" from the "harvest"—analyzing which promotions actually drove incremental growth and which fell flat.

### 🎯 The Mission
To transition from gut-feeling marketing to **data-backed strategy** by analyzing sales, store performance, and promotion types across thousands of transactions.

---

## 🛠️ Data Architecture
The analysis is powered by a robust relational schema consisting of:
* **`fact_events`**: The core transaction data for promotions.
* **`dim_products`**: Product details and categories.
* **`dim_stores`**: Geographical distribution of 50+ stores.
* **`sales_summary`**: Aggregated performance metrics.

---

## 🗝️ Business Requests & SQL Solutions
I solved five critical business requests using optimized SQL queries:
1.  **High-Value Heroes:** Identified products with a base price > 500 featured in 'BOGOF' promotions.
2.  **City Presence:** Mapped the store distribution across cities to identify market density.
3.  **Revenue Impact:** Calculated Total Revenue before vs. after campaigns to measure gross impact.
4.  **The Diwali Surge:** Analyzed Incremental Sold Quantity (ISU%) to see which products moved fastest during the festival of lights.
5.  **Top 5 Ranker:** Ranked products by Incremental Revenue (IR%) to identify the real profit drivers.

---

## 📈 Advanced Analytics & Deep Dives

### 🏪 Store Performance Analysis
* **Top 10 vs. Bottom 10:** Identified efficiency gaps between high-performing urban stores and underperforming outlets.
* **City-wise Trends:** Uncovered why certain cities respond better to specific categories.

### 🎟️ Promotion Type Effectiveness
* **BOGOF vs. Cashback:** Analyzed which promotion type strikes the best balance between volume and margin.
* **The BOGOF Caveat:** *Note: Handled discrepancies in BOGOF data quantity to ensure the analysis remained as accurate as possible despite database limitations.*

### 📦 Category & Product Insights
* **High-Lifting Categories:** Discovered which categories (e.g., Electronics vs. Grocery) are most "promotion-responsive."
* **Correlation Analysis:** Investigated how specific product categories align with different discount models.

---

## 📝 Key Learnings
* **Handling Real-world Data Gaps:** Developed workarounds for the BOGOF quantity limitation to maintain analysis integrity.
* **Metric Design:** Mastered the calculation of **ISU (Incremental Sold Units)** and **IR (Incremental Revenue)**.
* **Retail Strategy:** Gained deep insights into festive demand planning and inventory management.

---

## 📂 Project Structure
* `Datasets/`: Raw CSV/Excel data sources.
* `SQL Ad hoc Requests/`: Optimized scripts for the 5 business requests.
* `AtliQ Mart.pbix`: Visual dashboard representing the data (LFS).
* `EER Diagram.mwb`: Relation between the table in the database

---

## 🌐 Connect with Me

I am a Data Analytics professional passionate about turning complex data into visual stories. If you have questions about this project or want to discuss Data Analytics, Business Intelligence, or Automation—let's connect!

<p align="left">
  <a href="https://www.linkedin.com/in/adityasrinish/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/AdityaSrinish" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:adityasrinish3107@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

### 📁 My Portfolio
> **[Visit My Digital Portfolio 🚀](https://www.datascienceportfol.io/adityasrinish)**
> *Check out my other projects, including SQL challenges, N8n automation workflows, and my visual-first approach to data.*

---

<p align="center">
  <i>"Transforming numbers into narratives, one dashboard at a time."</i><br>
  📍 Vijayawada, India
</p>
