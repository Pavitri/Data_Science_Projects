# Project 2: Automated Energy Demand Forecasting & Supply-Chain Dashboard 📈🔋

An end-to-end data pipeline that bridges machine learning theory with relational database management systems (RDBMS) to simulate a real-time energy retail distribution network. 

This project transitions classroom concepts of K-Nearest Neighbors (KNN) algorithms into a practical, data-driven supply chain tracking tool.

---

## 🛠️ Tech Stack & Architecture

- **Backend Database:** MySQL managed via phpMyAdmin (Localhost Server)
- **Data Ingestion & Engineering:** Python, Pandas
- **Machine Learning Core:** Scikit-Learn (KNN Regressor)
- **Visualization & UI:** Matplotlib

---

## 📐 Database Schema Design

The foundational relational schema ensures strict referential integrity across operational variables:
1. `Station_Registry`: Classifies distribution nodes by demographics (`Location_Type`: Urban, Highway, Rural) and `Regional_Tier`.
2. `Sales_Transactions`: Tracks high-frequency volumetric sales logs (`Volume_Sold_Liters`) paired with localized fuel identifiers.
3. `Fuel_Pricing`: Maintains historical matrix structures tracking price fluctuations over time per tier.
4. `Inventory_Stock`: Monitors active capacities vs. available stock metrics at every station node.

---

## 🚀 Data Pipeline Workflow


