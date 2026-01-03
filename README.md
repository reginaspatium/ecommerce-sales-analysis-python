# Global E-Commerce Sales Analysis (2010–2017)

## 📝 Project Overview
This project is a comprehensive Exploratory Data Analysis (EDA) of a global retail dataset. The goal was to clean raw data, calculate business KPIs, and identify growth opportunities across different regions, product categories, and sales channels.

## 🛠 Technical Stack & Skills
* **Python**: Pandas for data manipulation, NumPy for calculations.
* **Visualization**: Seaborn, Matplotlib, Plotly (dynamic charts).
* **Data Cleaning**: Handling missing values (Namibia alpha-codes, Antarctica regions), date-time conversion, and outlier detection.
* **Business Metrics**: Calculation of Revenue, Profit, Margin, and Logistics efficiency.

---

## 📊 Key Insights

### 1. Product Performance
* **Most Profitable:** **Cosmetics** is the absolute leader in net profit, despite having lower sales volume than Office Supplies.
* **High Volume vs. Low Margin:** Office Supplies drive the most traffic and revenue but suffer from high unit costs.
* **Underperformer:** Fruits show the lowest profit margins.

### 2. Logistics & Operations
* **Delivery Time:** Average shipping takes **25 days**. 
* **Efficiency:** Logistics in **Croatia and the UK** are the fastest (<20 days), while Hungary exceeds 30 days.
* **Correlation:** Statistical analysis confirmed **no direct correlation** between delivery time and profit per order.

### 3. Geographical Analysis
* **Top Markets:** Andorra, **Ukraine**, and Malta are the most profitable countries in the dataset.
* **Region Dominance:** **Europe** is the primary profit driver, significantly outperforming the Asian market in this period.

### 4. Sales Dynamics
* **Best Days:** Peak profits occur on **Fridays and Mondays**. 
* **Stability:** Sales are perfectly balanced between **Online (49.5%)** and **Offline (50.5%)** channels.

---

## 💡 Strategic Recommendations
* **Marketing Focus:** Increase ad spend on **Cosmetics** to maximize total ROI.
* **Cost Optimization:** Audit logistics and supply chains in Bosnia and the Czech Republic to improve their low margins.
* **Operational Planning:** Scale warehouse staff for Friday/Monday peaks to maintain processing speed.

---
## 📂 Project Structure
* `data/`: Contains `countries.csv`, `events.csv`, and `products.csv`.
* `notebooks/`: [Main Analysis Notebook](./Python_Analysis_Task.ipynb) with full code and visualizations.
