# Nigeria-s-Health-Financing-Crisis
A data analysis project examining Nigeria's health financing landscape from 2000 to 2023, using data from the World Bank's Health Nutrition and Population Statistics database.

## Project Overview

This project investigates a central policy question:

**Is Nigeria investing enough in health, and is that investment translating into better outcomes for its citizens?**

The analysis traces public and private health spending trends, identifies who bears the financial burden of healthcare, and evaluates whether spending levels have produced commensurate improvements in health outcomes.

---
## Key Findings

- **Nigeria has never met the Abuja Declaration target** of allocating 15% of the national budget to health. By 2023, government health spending stood at just 4.3% of general government expenditure.
- **Citizens bear an unsustainable burden** — out-of-pocket payments have consistently funded 60–77% of all health spending, far exceeding the WHO's recommended ceiling of 15–20%.
- **Health outcomes are improving, but slowly** — life expectancy rose from 47.1 years (2000) to 54.5 years (2023), and infant mortality fell from 97.1 to 60.1 per 1,000 live births.
- **Universal Health Coverage (UHC) remains critically low** — Nigeria's UHC index of 38–43 out of 100 means the majority of the population still lacks access to essential health services.
- **Health financing is oil-dependent and volatile** — government per capita health spending tracks oil prices, making long-term planning difficult.

---

## Visualisations

The analysis produces six thematic charts:

| Chart | Description |
|-------|-------------|
| 1 | Health expenditure as % of GDP vs Abuja Declaration target |
| 2 | Funding sources breakdown, government, out-of-pocket, external donors |
| 3 | Government budget allocation and per capita health spending |
| 4 | Out-of-pocket spending burden over time |
| 5 | Health outcomes, life expectancy vs infant mortality |
| 6 | Universal Health Coverage (UHC) service coverage index |

---

## Data Source

**World Bank — Health Nutrition and Population Statistics**
- Portal: [https://databank.worldbank.org](https://databank.worldbank.org/source/health-nutrition-and-population-statistics)
- Country: Nigeria
- Period: 2000 – 2023
- Last updated: February 2026

---

## Project Structure

```
nigeria-health-financing-analysis/
│
├── nigeria_health_financing.ipynb        # Main analysis notebook
├── health_data.xlsx                      # Raw dataset from World Bank
├── nigeria_health_financing_dashboard.png  # Final dashboard (auto-generated)
└── README.md
```

---

## Notebook Structure

The notebook is organised into seven sections:

1. **Environment Setup**: library imports
2. **Data Loading & Inspection**: structure, shape, raw preview
3. **Data Cleaning & Preprocessing**: removing metadata rows, handling missing values (`..`), type conversion, column renaming, missing data heatmap
4. **Exploratory Data Analysis**: summary statistics, year-on-year changes, correlation matrix, distributions
5. **Thematic Visualisations**: six individual charts with printed key statistics
6. **Combined Dashboard**: publication-ready 6-panel figure
7. **Key Findings & Policy Implications**: written narrative and summary comparison table (2000 vs 2023)

---

## Tools & Libraries

- **Python 3**
- `pandas` for data manipulation and cleaning
- `numpy` for numerical operations
- `matplotlib`for visualisation
- `seaborn` for correlation heatmap and distribution plots

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nigeria-health-financing-analysis.git
   cd nigeria-health-financing-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook nigeria_health_financing.ipynb
   ```

4. Run all cells top to bottom.

---

## Policy Recommendations

1. **Honour the Abuja Commitment**: progressively increase the health budget share toward 15%, with annual accountability reporting.
2. **Expand the National Health Insurance Authority (NHIA)**: reduce reliance on out-of-pocket payments through pre-payment and risk-pooling.
3. **De-link health financing from oil revenue**: establish a dedicated health stabilisation fund.
4. **Invest in primary healthcare**: redirect resources toward preventive care, which delivers the highest returns for maternal and child health.
5. **Strengthen health data systems**:  improve routine data collection so policy decisions are grounded in timely, complete evidence.

---

*Submitted as part of application to the Centre for Inclusive Social Development (CISD).*
