# crispy-adventure

# Fuel Inventory Management Optimization Project

This project focuses on optimizing fuel inventory management for gas stations by analyzing real-world datasets. The goal is to propose cost-effective strategies for fuel replenishment, maximize supplier discounts, and maintain sufficient inventory levels to avoid stockouts. All analyses were conducted using Python and data analysis libraries.

---

## Project Overview

Efficient fuel inventory management is critical for gas station operations. Decisions on replenishment frequency and quantity can significantly impact profitability. This project addresses key business questions related to purchasing patterns, inventory trends, and cost optimization.

### **Business Questions Addressed**
1. **Evaluate Current Inventory Management Practices**:
   - Analyze existing fuel inventory trends and ordering patterns.
   - Quantify cost savings from supplier discounts.

2. **Recommend Improved Ordering Strategies**:
   - Propose optimized ordering quantities to reduce costs.
   - Estimate maximum potential savings based on historical data.

3. **Identify the Best Day for Fuel Orders**:
   - Analyze price trends by day of the week to identify the most cost-effective purchasing day.

4. **Assess the Feasibility of Adding Tanks**:
   - Evaluate whether increasing tank capacity at specific locations could improve cost efficiency.

---

## Datasets

The analysis is based on the following datasets:
- **Locations.csv**: Details of gas station locations (IDs, names, addresses, coordinates).
- **Tanks.csv**: Tank-specific information, including type and capacity.
- **Invoices.csv**: Historical fuel purchase records.
- **Fuel_Level_Part_1.csv & Fuel_Level_Part_2.csv**: Fuel inventory levels at different timestamps.

> **Note**: All datasets have been obfuscated to protect proprietary information.

---

## Methodology

1. **Data Preprocessing**:
   - Merged and cleaned multiple datasets.
   - Handled missing values and prepared data for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized fuel inventory trends over time.
   - Identified stations with efficient practices and those at risk of stockouts.

3. **Optimization Models**:
   - Calculated potential cost savings by optimizing order quantities.
   - Assessed the financial feasibility of adding new tanks.

4. **Business Recommendations**:
   - Proposed strategies to improve inventory policies and reduce costs.

---

## Results

- Significant savings can be achieved by optimizing fuel order quantities and timing.
- Inventory trends reveal critical inefficiencies in certain locations.
- The addition of tank capacity at specific sites may yield long-term benefits.

---

## Technologies Used

- **Python Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `numpy` for numerical computations.
