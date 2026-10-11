# PY2026 CMS Marketplace Data Notes

## 1. OEP State, Metal Level & Enrollment Status PUF
- **Source File**: \data/raw/2026-oep-state-metal-and-enrollment-puf/\
- **Data Grain**: State (\State_Abrvtn\), Metal Level (\Metal_Lvl\), and Enrollment Status (\Enrlmt_Stus\)
- **Key Fields**:
  - Geography & Platform: \State_Abrvtn\, \Pltfrm\
  - Enrollment Counts: \Cnsmr\
  - Financials & Subsidies: \Avg_Prm\, \Avg_Prm_Aftr_APTC\, \APTC_Cnsmr\, \CSR_Cnsmr\
  - Demographics: Age groups (\Age_0_17\ - \Age_GE65\), Race/Ethnicity, Rurality (\Rrl\, \Non_Rrl\)
  - Income Levels: FPL tiers (\FPL_LT100\ through \FPL_GT500\)
- **Data Suppression / Special Handling**: Small cell counts under CMS privacy thresholds may be represented as suppressed values (\*\ or \NR\).

---

## 2. QHP Landscape Individual Market Medical
- **Source File**: \data/raw/individual_market_medical/individual_market_medical.xlsx\
- **Data Grain**: Unique Health Plan per County (\State\ + \County\ + \Plan ID\)
- **Key Fields**:
  - Location: \State\, \County\
  - Plan Details: \Issuer Name\, \Plan ID\, \Plan Marketing Name\, \Plan Type\, \Metal Level\
  - Costs: Base Premiums, Deductibles, Maximum Out-of-Pocket
- **Notes**: Contains plan offering availability across all SBE and FFE individual market counties.
