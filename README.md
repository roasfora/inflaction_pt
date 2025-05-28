# 📈 Inflation in Portugal (2019–2025)

This project presents a data analysis of year-over-year (YoY) inflation trends in Portugal from 2019 to 2025, using official statistics from **INE (Instituto Nacional de Estatística)**. It includes visualizations and correlation analysis across different components of inflation, such as total inflation, core inflation (excluding food and energy), goods, and services.

---

## 📊 Project Overview

The goal of this analysis is to:

- Understand inflation trends over time.
- Compare inflation dynamics between goods, services, and total inflation.
- Explore the relationship between different inflation components through correlation analysis.

---

## 📂 Dataset

- **Source:** Instituto Nacional de Estatística (INE), Portugal  
- **File:** `inflacao_yoy_com_grupos_2019_2025.csv`  
- **Columns:**
  - `Month`: Date in YYYY-MM format
  - `Total`: Total YoY inflation rate
  - `Excluindo Alimentos e Energia`: Inflation excluding food and energy (core inflation)
  - `Bens`: Inflation for goods
  - `Serviços`: Inflation for services

---

## 🧪 Requirements

Install the required Python libraries:

```bash
pip install pandas matplotlib seaborn
