  ACC102 Individual Project

## 1. Project Objective
This project evaluates the financial performance of Tesla, Ford, and General Motors using WRDS (Compustat) data. The aim is to determine which company offers the best investment potential based on profitability, growth, and efficiency.

---

## 2. Data Source
- Source: WRDS Compustat Database  
- Period: 2019–2025  
- Key variables:
  - Revenue (sale)
  - Net Income (ni)
  - Total Assets (at)
  - Fiscal Year (fyear)

---

## 3. Methodology
The analysis was conducted using Python and includes:

### Financial Metrics
- **Profit Margin** = Net Income / Revenue  
- **ROA (Return on Assets)** = Net Income / Total Assets  
- **Revenue Growth** = Year-over-year revenue change  

### Investment Score
Companies were ranked based on:
- Profitability (profit margin)
- Efficiency (ROA)
- Growth (revenue growth)

A combined ranking score was used to determine overall performance.

---

## 4. Key Findings

### 1) Tesla (Strong Growth & Profitability)
- Revenue increased significantly from **24,578 (2019) → 94,827 (2025)**  
- Peak growth: **+70.7% (2021)**  
- Highest average profitability:
  - Avg Profit Margin ≈ **7.3%**
  - Avg ROA ≈ **6.5%**
- Ranked **#1 in investment score (2.33)**

  Interpretation: Tesla shows strong growth and improving profitability, making it the strongest investment candidate.

---

### 2) General Motors (Stable Performance)
- Revenue stable around **137,000 → 185,000**
- Consistent positive net income
- Average:
  - Profit Margin ≈ **5.0%**
  - ROA ≈ **2.9%**

  Interpretation: GM is stable but lacks high growth compared to Tesla.

---

### 3) Ford (High Revenue but Weak Profitability)
- Highest revenue among the three
- However:
  - Negative profit in multiple years (2020, 2022, 2025)
  - 2025 net income: **-8,182**
- Lowest profitability:
  - Avg Profit Margin ≈ **1.7%**

  Interpretation: Ford has scale but poor profitability, making it the weakest investment option.

---

## 5. Final Ranking (2025)

| Rank | Company | Investment Score |
|------|--------|----------------|
| 1 | Tesla | 2.33 |
| 2 | General Motors | 2.00 |
| 3 | Ford | 1.66 |

---

## 6. Files Included
- `acc102_project.ipynb` → Main analysis code  
- `final_analysis.csv` → Full processed dataset  
- `summary_table.csv` → Summary statistics  
- `investment_ranking.csv` → Final ranking results  
- `tesla_ford_gm_financial_data.csv` → Raw extracted data  

---

## 7. How to Run
1. Open the Jupyter Notebook
2. Run all cells sequentially
3. Outputs include:
   - Data tables
   - Financial metrics
   - Graphs comparing performance

---

## 8. Conclusion
Tesla demonstrates the strongest investment potential due to its high growth and improving profitability. General Motors offers stable performance, while Ford underperforms due to weak profitability despite high revenue.

---

## 9. Limitations

This analysis has several limitations. First, the study is based on a limited set of financial variables and does not include other important factors such as market conditions or external economic influences. 

Second, the dataset covers a specific time period and may not fully represent long-term trends. Additionally, some data extraction challenges and technical constraints during the WRDS process may have affected data completeness.

Therefore, the results should be interpreted as a simplified comparison rather than a comprehensive investment recommendation.
