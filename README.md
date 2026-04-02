# 📊 Financial KPI Automation

> Python tool that automates financial KPI calculation and reporting — transforms raw data into formatted Excel reports. Built for Finance & Brand strategy analysis.

---

## 🧠 Overview

In finance roles, a significant portion of time is spent manually cleaning data, calculating KPIs, and formatting Excel reports. This project automates that entire workflow using Python.

Given raw financial data (revenues, costs, investments, etc.), this tool:
- Cleans and validates the input data
- Calculates key financial KPIs automatically
- Exports a professionally formatted Excel report ready to present

Built as part of my work in **Brand Finance at Belcorp**, where data-driven decisions require fast, accurate, and repeatable financial analysis.

---

## 📌 KPIs Calculated

| KPI | Formula | Why it matters |
|-----|---------|----------------|
| **Gross Margin** | (Revenue - COGS) / Revenue | Measures production efficiency |
| **EBITDA Margin** | EBITDA / Revenue | Core profitability indicator |
| **ROI** | (Net Profit / Investment) × 100 | Evaluates return on investment |
| **Revenue Growth (YoY)** | (Current - Previous) / Previous × 100 | Tracks business momentum |
| **Operating Expense Ratio** | OpEx / Revenue | Controls cost structure |
| **Net Profit Margin** | Net Profit / Revenue | Overall bottom-line performance |

---

## 🗂️ Project Structure

```
financial-kpi-automation/
│
├── data/
│   └── sample_financial_data.csv     # Sample input data
│
├── outputs/
│   └── kpi_report.xlsx               # Generated Excel report
│
├── financial_kpi_automation.ipynb    # Main Jupyter Notebook
├── requirements.txt                  # Python dependencies
└── README.md
```

---

## ⚙️ Technologies Used

| Tool | Purpose |
|------|---------|
| `Python 3.10+` | Core language |
| `pandas` | Data manipulation and KPI calculation |
| `openpyxl` | Excel report generation with formatting |
| `matplotlib` | KPI visualization charts |
| `numpy` | Numerical calculations |
| `Jupyter Notebook` | Interactive analysis environment |

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/insightdive/financial-kpi-automation.git
cd financial-kpi-automation
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add your data
Replace `data/sample_financial_data.csv` with your own financial data, or use the sample provided.

### 4. Run the notebook
```bash
jupyter notebook financial_kpi_automation.ipynb
```

### 5. Get your report
The formatted Excel report will be saved automatically in `/outputs/kpi_report.xlsx`.

---

## 📥 Input Format

The tool expects a CSV file with the following columns:

```
period, revenue, cogs, operating_expenses, ebitda, net_profit, investment
```

Example:
```
period,     revenue,  cogs,    operating_expenses, ebitda,  net_profit, investment
2024-Q1,    500000,   300000,  80000,              120000,  90000,      200000
2024-Q2,    550000,   320000,  85000,              145000,  110000,     200000
2024-Q3,    610000,   350000,  90000,              170000,  130000,     200000
2024-Q4,    680000,   380000,  95000,              205000,  160000,     200000
```

---

## 📤 Output — Excel Report

The generated report includes:

- ✅ **KPI Summary Table** — all metrics per period, color-coded by performance
- 📈 **Revenue & EBITDA Trend Chart** — quarterly evolution
- 🔴🟡🟢 **Conditional formatting** — highlights underperforming KPIs automatically
- 📋 **Executive Summary sheet** — key takeaways ready to present

---

## 💡 Key Learnings & Applications

This project reflects skills directly applied in **Brand Finance** contexts:

- Automating repetitive Excel workflows with Python saves hours of manual work
- Standardized KPI calculation eliminates human error in financial modeling
- Formatted outputs are presentation-ready for stakeholders and leadership
- Easily adaptable to brand-specific metrics (Brand Equity, Share of Voice ROI, etc.)

---

## 🔄 Future Improvements

- [ ] Add Power BI integration (export data model compatible with `.pbix`)
- [ ] Support multi-brand or multi-category comparison
- [ ] Add brand-specific KPIs (Brand Value, Royalty Rate, Brand Contribution)
- [ ] Dashboard version using `Streamlit`
- [ ] Automated email report delivery with `smtplib`

---

## 👩‍💼 About the Author

**Nicole Espinoza** — Brand Finance Intern at Belcorp | Finance student at PUCP (Top 3%)

Passionate about combining financial strategy with data tools to drive brand decisions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicole%20Espinoza-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/tu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-insightdive-black?style=flat&logo=github)](https://github.com/insightdive)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
