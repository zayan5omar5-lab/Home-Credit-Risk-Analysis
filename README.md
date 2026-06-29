# Home-Credit-Risk-Analysis
# Home Credit Loan Risk & Behavioral Dashboard

An end-to-end data analytics project focused on evaluating credit risk, analyzing borrower demographics, and uncovering financial behavior patterns using the Home Credit dataset.

## 📊 Dashboard Overview
This multi-page Power BI dashboard is designed with a professional corporate banking aesthetic (Deep Blue & Gold) to assist risk officers in making data-driven credit decisions.

### Project Structure:
1. **HOME CREDIT LOAN RISK OVERVIEW:** A high-level executive summary tracking core KPIs (Total Applications, Default Rates, Income Levels).
2. **HOME CREDIT DEMOGRAPHIC ANALYSIS:** Deep dive into borrower characteristics including age, gender, education, and credit-to-income ratios.
3. **HOME CREDIT RISK & BEHAVIORAL INSIGHTS:** Exploration of financial behaviors, average days delinquent, and external active debts.

---

## 🛠️ Tech Stack & Workflow

### 1. Data Cleaning & Engineering (Python)
- Handled missing values, duplicates, and data type formatting.
- Integrated child and family size columns into the main pipeline.
- Exported clean structured files ready for BI consumption.

### 2. Data Modeling & Transformation (Power Query & DAX)
- Structured a robust data model in Power BI.
- Created advanced DAX measures to track complex risk metrics dynamically:
  - `Default Rate %`
  - `Average Days Delayed`
  - `Maximum Credit Amount`
  - `Total External Active Debt`

---

## 📈 Key Insights Uncovered
- **Risk Metrics:** The overall portfolio default rate stands at **8.08%** across 246K applications.
- **Demographic Triggers:** Lower secondary education levels show a higher propensity for days delinquent compared to academic degree holders.
- **Financial Status:** Clear baseline correlation between elevated credit-to-income ratios and default risks.

## 🚀 How to View
1. Download the `.pbix` file from the `/Dashboard` directory.
2. Open it using Power BI Desktop to interact with the visual filters.
3. Alternatively, check out the full static report in the `/Reports` folder.
