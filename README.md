# 📦 Supply Chain Analytics – Beauty & Haircare Products

This project analyzes the supply chain performance of a beauty and fashion startup, focusing on skincare, haircare, and cosmetics. The goal is to uncover patterns in revenue, inventory efficiency, cost trade-offs, and quality control using data-driven techniques.

---

## 🎯 Project Objective

Gain actionable insights across the supply chain — including profitability, inventory risks, logistics costs, and defect rates — using Python analytics and visualizations. The aim is to support strategic decision-making in restocking, carrier optimization, and product quality improvement.

---

## 📂 Dataset

The dataset includes product-level transactional, manufacturing, and logistics data. Key columns:

- `Product type`: Category (skincare, haircare, cosmetics)  
- `SKU`: Stock Keeping Unit  
- `Revenue generated`, `Price`, `Number of products sold`  
- `Stock levels`, `Order quantities`, `Lead time`  
- `Manufacturing costs`, `Shipping costs`, `Shipping carriers`  
- `Defect rates`, `Transportation modes`  

---

## 🧪 Methods Used

- Descriptive statistics  
- Grouped aggregations (by product, SKU, carrier)  
- Inventory turnover calculations  
- Risk flagging (stockouts & overstock)  
- Visual analysis using interactive plots  
- Trendline regressions (e.g., lead time vs defect rates)  

---

## 🗂️ Project Structure

├── SCA_BeautyProducts.ipynb # Main analysis notebook
├── supply_chain_data.csv # Dataset (if included)
├── README.md # Project documentation
├── .gitignore # Files to exclude from Git
├── requirements.txt # Required Python packages
└── LICENSE # License information


---

## 📈 Key Results

- **Skincare** is the highest revenue contributor; **cosmetics** yield the best profit margins.  
- SKUs like `SKU34` and `SKU47` are at high risk of stockouts.  
- Carrier B generates the most revenue but is also the most expensive.  
- Haircare products have the **highest defect rates** and longer lead times.  
- Road transportation is linked to more damaged goods compared to air.  

---

## 🛠️ Tools & Libraries

- Python  
- pandas, numpy  
- plotly (interactive visualizations)  
- Jupyter Notebook  

---

## 🚀 Use Cases

- Inventory optimization: Flag stockout/overstock risk SKUs.  
- Profitability insights by product and channel.  
- Carrier selection based on cost vs revenue trade-off.  
- Defect rate analysis for supplier or logistics improvements.  
- Business intelligence reporting for supply chain teams.  

---
