# 🍹 Beverage Sales Analysis | Business Performance & Pricing Strategy

## 🎯 Objective

This project analyzes a beverage sales dataset to understand business performance, customer behavior, and the impact of discount strategies on revenue.

The goal is to identify key drivers of sales and evaluate whether discount policies are effectively increasing revenue or simply boosting volume.

---

## 📊 Dataset

The dataset contains transactional data including:

- Customers (B2B and B2C)
- Products and categories
- Prices and discounts
- Quantities sold
- Regions
- Order dates

The analysis focuses on understanding both **volume dynamics** and **revenue generation**.

---

## ⚙️ Methodology

### 1. Data Cleaning

- Handling missing values  
- Data type conversion  
- Consistency checks (price × quantity × discount)  

---

### 2. Exploratory Data Analysis (EDA)

- Sales evolution over time  
- Revenue distribution by category and product  
- Regional analysis  
- Identification of top-performing products  

---

### 3. Customer Analysis

- B2B vs B2C segmentation  
- Average order value (ticket size)  
- Purchase volume comparison  
- Pareto analysis (customer concentration)  

---

### 4. Discount Analysis

- Discount distribution and frequency  
- Revenue loss due to discounts  
- Discount usage across regions  

---

### 5. Discount vs Revenue Relationship

- Impact of discounts on:
  - Order size  
  - Revenue per order  
  - Total revenue  

- Identification of optimal discount levels  

---

### 6. Product Mix Analysis

- Effect of product composition on revenue  
- Relationship between price and discount  
- Category-level behavior  

---

## 🧠 Key Insights

- 📌 **77% of revenue comes from B2B customers**, driven by high-volume orders  
- 📌 **Top 20% of products generate ~71% of total revenue** → moderate concentration  
- 📌 Customer base is relatively diversified (20% → ~46% revenue)  
- 📌 Discounts:
  - Increase order volume  
  - Do NOT maximize revenue at high levels  
  - Show optimal performance around ~10%  

- 📌 Presence of a **composition effect**:
  - Higher discounts are applied to higher-priced products  
  - This distorts revenue-per-unit analysis  

---

## 📉 Interpretation

The business operates under a **volume-driven model**, where:

- Discounts are used to stimulate demand  
- Revenue growth is not strictly aligned with discount intensity  

👉 The key challenge is balancing **volume vs profitability**

---

## 🧩 Strategic Implications

- Optimize discount levels (avoid excessive discounting)  
- Focus on high-performing products  
- Leverage B2B segment while improving margin efficiency  
- Adjust pricing strategy based on product category and demand  

---

## 🛠️ Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

📁 Project Structure
beverage-sales-analysis/
│
├── analisis_ventas_bebidas.ipynb
├── sample_data.csv (optional)
├── Informe Venta Bebidas.pdf
└── README.md

---

## ▶️ Reproducibility

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn

## 👤 Author

Yeray Martínez  
Master in Big Data & Artificial Intelligence
