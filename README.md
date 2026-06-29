# Python_Project_Bank_Loan_Analysis (Data Analysis Project)

This project analyzes bank loan data using Python to track portfolio performance, assess credit risk, and uncover borrower trends — turning raw financial data into actionable insights that support smarter lending decisions.

### 💻Tech Stack & Tools

The analysis is built entirely in Python, utilizing its core data science libraries:

Pandas: For robust data cleaning, handling missing values, type casting, and KPI derivation.

Matplotlib & Seaborn: For exploratory data analysis (EDA) and crafting high-quality, intuitive visualizations.

Jupyter Notebook: For an interactive, well-documented development and analysis workflow.

### 💼 Business Problem
Managing and evaluating loan portfolio performance is a key challenge for banks without clear visibility into critical metrics like loan applications, funded amounts, repayments, interest rates, and borrower DTI. This project uses Python to compute critical KPIs, classify loans as Good or Bad, and deliver visual insights — helping banks make informed lending decisions.

### 💡 Business Requirement

#### Key Performance Indicators (KPIs) Requirements:

1.	Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications.
   
2.	Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount metric.
   
3.	Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Receive.
   
4.	Average Interest Rate: Calculating the average interest rate across all loans which will provide insights into our lending portfolio's overall cost.
   
5.	Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans.

### Good Loan v Bad Loan KPI’s

#### Good Loan:

1.	Good Loan Application Percentage
   
2.	Good Loan Applications
	
3.	Good Loan Funded Amount

4. Good Loan Total Received Amount
	
#### Bad Loan

1.	Bad Loan Application Percentage

2.	Bad Loan Applications

3.	Bad Loan Funded Amount

4.	Bad Loan Total Received Amount

### 📈 Charts

1.	Monthly Trends by Issue Date (Line/ Area Chart):  To identify seasonality and long-term trends in lending activities

	## Monthly Trends by Issue Date for Total Funded Amount

	<img width="989" height="490" alt="1  Monthly Funded Amount in millions" src="https://github.com/user-attachments/assets/5adae9e4-3ed9-4c02-b5af-2b87d474a8fc" />

   ## Monthly Trends by Issue Date for Total Amount Received

<img width="989" height="490" alt="2 Monthly Trends Total Amount Received" src="https://github.com/user-attachments/assets/ea468383-19fe-4cd6-adbf-7bdd2ebcde81" />

   ## Monthly Trends by Issue Date for Total Loan Applications
   
<img width="989" height="490" alt="3  Monthly Total Loan Applications" src="https://github.com/user-attachments/assets/6f0e8699-eb4b-495a-a1ef-911430b0ee71" />
 
3.	Regional Analysis by State (Bar Chart): To identify regions with significant lending activity and assess regional disparities

  ## Regional Analysis by State for Total Funded Amount

<img width="983" height="790" alt="4  Regional analysis by state total funded amount" src="https://github.com/user-attachments/assets/5fbd3ee2-712f-494e-85e2-fd5cffbf4ba8" />

  ## Regional Analysis by State for Total Amount Received

<img width="983" height="790" alt="5  Regional analysis by state total amount received" src="https://github.com/user-attachments/assets/a4edc319-1d91-47ee-947a-5cd3a58c81f6" />

  ## Regional Analysis by State for Total Loan Applications
  
<img width="989" height="790" alt="6  Regional analysis by state by  loan applications" src="https://github.com/user-attachments/assets/3965f2f4-17d2-408f-9ff5-ac2f7b5ccd5e" />
	
4.	Loan Term Analysis (Donut Chart): To allow the client to understand the distribution of loans across various term lengths.

 ## Loan Term Analysis by Total Funded Amount

<img width="489" height="428" alt="7  Loan term analysis by total funded amount" src="https://github.com/user-attachments/assets/0c462b61-851c-4d42-b976-c4ae3653bfde" />

 ## Loan Term Analysis by Total Amount Received

<img width="491" height="428" alt="8  loan term analysis by amount received" src="https://github.com/user-attachments/assets/8a24483e-2a5b-4202-925e-b7fa7ba883f9" />

 ### Loan Term Analysis by Total Loan Applications

<img width="429" height="428" alt="9  Loan term analysis by loan applications" src="https://github.com/user-attachments/assets/c5fa045e-047f-4515-8dc9-ccb95a366c6b" />
  
5.	Employee Length Analysis (Bar Chart): How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.

 ## Employee Length by Total Funded Amount

<img width="989" height="590" alt="10  employee length total funded amount" src="https://github.com/user-attachments/assets/084c19b1-5ad6-4f3d-805e-0c00539b6975" />

 ## Employee Length by Total Amount Received

<img width="989" height="590" alt="11  employee length amount received" src="https://github.com/user-attachments/assets/d8ec7a1b-a242-42fe-87bc-4fe7793d34d9" />
 
 ## Employee Length by Total Loan Applications

<img width="989" height="590" alt="12  employee length loan applications" src="https://github.com/user-attachments/assets/30ff3fa3-867f-40b4-819f-074dcc28bb3b" />

6.	Loan Purpose Breakdown (Bar Chart): Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.

 ## Loan Purpose by Total Funded Amount

<img width="988" height="590" alt="13  loan purpose total funded amount" src="https://github.com/user-attachments/assets/dffac37d-d9e5-430a-9f0e-07feb1f28d9d" />

 ## Loan Purpose by Total Amount Received

<img width="988" height="590" alt="14  loan purpose amount received" src="https://github.com/user-attachments/assets/fa237451-264c-44d7-88c4-fccc212620f2" />

 ## Loan Purpose by Total Loan Applications
 
<img width="989" height="590" alt="15  loan purpose loan applications" src="https://github.com/user-attachments/assets/ed090276-8da8-438d-b8b3-54d0e9b04cc8" />
	
7.	Home Ownership Analysis (Tree): For a hierarchical view of how home ownership impacts loan applications and disbursements.

 ## Home Ownership by Total Funded Amount

<img width="1038" height="382" alt="image" src="https://github.com/user-attachments/assets/9dca04c8-0a48-477b-8977-7d4b8c3b06b0" />

 ## Home Ownership by Total Amount Received
 
<img width="975" height="370" alt="image" src="https://github.com/user-attachments/assets/82ad5be6-8e4e-4c1c-af50-6e13cb3f361f" />

 ## Home Ownership by Total Loan Applications

<img width="1001" height="403" alt="image" src="https://github.com/user-attachments/assets/487e0c7b-b276-4b8c-81e2-08d8f9b0b2bf" />

    
### Metrics to be shown: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'



# Bank Loan — Executive Analysis Report

> **Data Period:** January 2021 – December 2022

---

## Portfolio KPI Summary

| Metric | Value |
|--------|-------|
| **Total Loan Applications** | 38,576 *(MTD Dec-22: ~4,300+)* |
| **Total Funded Amount** | $435.76M *(MTD: ~$54M)* |
| **Total Amount Received** | $473.07M *(MTD: ~$58M)* |
| **Avg. Interest Rate** | 12.05% |
| **Avg. Debt-to-Income (DTI)** | 13.33% |
| **Net Recovery Surplus** | +$37.3M *(Received vs. Funded)* |
| **Good Loan Rate** | 86.18% *(Fully Paid + Current)* |
| **Bad Loan Rate (Charged Off)** | 13.82% *(5,333 applications)* |

---

## ✅ Good Loan vs. ❌ Bad Loan Breakdown

| Metric | Good Loans | Bad Loans (Charged Off) | Implication |
|--------|------------|-------------------------|-------------|
| Application Count | **33,243** | **5,333** | 1 in ~7 loans defaults |
| Share of Portfolio | **86.18%** | **13.82%** | High default rate vs. industry avg ~5–8% |
| Funded Amount | **~$370.2M** | **~$65.5M** | $65.5M at-risk capital |
| Amount Received | **~$435.8M** | **~$37.3M** | Only 56.9% recovered on bad loans |
| Recovery Rate | **>100%** *(Interest earned)* | **~56.9%** | ~$28.2M unrecovered loss |

---

## 🔍 Key Analytical Insights

### A. Loan Term Risk

| Term | % of Applications | Risk Profile |
|------|-------------------|--------------|
| 36 Months (Short) | ~73% | ✅ Lower default risk |
| 60 Months (Long) | ~27% | ⚠️ Higher default risk — longer exposure |

---

### B. Employment Length & Loan Demand

Borrowers with **10+ years of employment** represent the largest segment of loan applicants and funded amounts, indicating that long-tenure employees are the most active borrowers. However, even this segment carries charged-off cases, suggesting **income stability alone is insufficient** as a risk filter.

---

### C. Loan Purpose Distribution

**Debt consolidation** is the dominant loan purpose — accounting for the largest funded amount and application count by a significant margin, followed by credit card refinancing.

> ⚠️ These two categories together represent **~75%+ of total volume**, concentrating portfolio risk in consumer debt recycling behavior.

---

### D. Home Ownership Impact

- **Mortgage holders** and **renters** make up the bulk of applicants.
- Renters present a **higher risk profile** as they lack collateral-backed stability.
- **Outright home owners** are the lowest-risk segment but represent a small share of the portfolio.

---

### E. Monthly Volume Trend (2021–2022)

Loan applications and funded amounts show a **consistent upward trend** across the 24-month period, with December 2022 recording the highest monthly figures:

- MTD Applications: **~4,300**
- MTD Funded: **~$54M**

> This growth signals expanding credit demand but also **proportionally growing default exposure**.

---

## 💡 Business Recommendations: Reducing Bad Loan Risk

| # | Strategy | Expected Impact |
|---|----------|-----------------|
| **1** | **Tighten DTI Threshold** — Cap approvals at DTI ≤ 35% for 60-month loans. Current avg DTI of 13.33% masks high-risk outliers. | Reduce 60-month default rate; protect $65.5M at-risk capital. |
| **2** | **Interest Rate Risk Pricing** — Introduce tiered interest rates based on credit grade. Charge 2–4% premium on grades D, E, F loans. | Improves P&L on risky loans; current 12.05% avg rate may under-price risk. |
| **3** | **Debt Consolidation Guardrails** — For the dominant debt consolidation segment, require evidence of closed accounts or reduced credit utilization post-loan. | Prevents re-accumulation of debt — a key driver of repeat defaults. |
| **4** | **Early Warning Monitoring** — Flag accounts at 60-day delinquency for proactive outreach and restructuring offers before reaching Charged Off status. | Could recover additional portion of the ~$28.2M unrecovered loss. |
| **5** | **Renter Risk Adjustment** — Apply stricter LTV and income verification for renters. Consider co-signer requirements for loans > $15K. | Mitigates collateral-gap risk; renters are disproportionately represented in defaults. |
| **6** | **State-Level Risk Limits** — Identify top 5 high-volume states and cap month-on-month portfolio growth in states showing higher-than-average charged-off rates. | Geographic concentration risk reduction; prevents regional economic shocks from cascading. |

---

## 📝 Summary 

| ✅ Portfolio Strengths | ⚠️ Risk Concerns |
|------------------------|------------------|
| Net surplus of **$37.3M** (received > funded) | **13.82%** bad loan rate — nearly **2× industry norm** |
| **86.18%** good loan ratio | **$28.2M** in unrecovered capital |
| Consistent YoY volume growth | High concentration in debt consolidation |
| Diversified loan purposes and states | 60-month term loans carry elevated risk |

---

## 🎯 Priority Action

> **Tighten DTI policy on 60-month loans** to target bad loan rate reduction from **13.82% → <8%**

---




