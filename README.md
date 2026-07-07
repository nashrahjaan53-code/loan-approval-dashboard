# Loan Approval Dashboard (Power BI)

An interactive dashboard analyzing loan applicant data — credit score, age, and employment status — against approval outcomes, built to explore what factors are associated with a loan being approved or rejected.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

##  Dashboard Preview

![Dashboard Screenshot](./loan-approval-screenshot.png)

---

##  Business Questions This Answers

- Do higher credit scores correlate with loan approval?
- Does employment status affect approval likelihood?
- What does the age/credit profile look like for approved vs. rejected applicants?
- How is the applicant pool distributed by employment status?

---

##  Key Insights

- **Credit score appears linked to approval outcome**: approved applicants show credit scores in the 89–111 range on the quadrant chart, while the rejected applicant shows a notably higher sum (189) — worth digging into why a higher score didn't guarantee approval, since that's counterintuitive and a good talking point
- **Employment status skews the applicant pool**: roughly two-thirds of applicants (by age-weighted share) are Unemployed vs. one-third Employed
- **The Employment_Status vs Loan_Status view** shows both Employed and Unemployed applicants appearing across Approved and Rejected outcomes — meaning employment status alone doesn't fully determine the result, suggesting credit score or another factor plays a larger role
- **Applicant age in this sample centers around 25**, with a max credit score of 380 and a min of 340

---

##  What's on the Dashboard

- **KPI Cards**: Count of Applicants, Average Age, Max Credit Score, Min Credit Score
- **Interactive Filters**: Age, Employment Status, Credit Score, Loan Status
- **Quadrant/Scatter Chart**: Sum of Credit Score by Loan Status and Applicant — visually separates approved vs. rejected by score
- **Pie Chart**: Age distribution by Employment Status
- **Scatter Chart**: Age vs. Loan Status, colored by outcome
- **Bar Chart**: Applicant count by Employment Status and Loan Status

---

##  Tools & Techniques

- **Power BI** — data modeling, interactive slicers, DAX aggregate measures (Average Age, Max/Min Credit Score)
- **Chart selection strategy**: used a quadrant-style scatter to directly contrast credit score against approval outcome, making outliers (like a high-score rejection) immediately visible rather than buried in a table

---

##  Files

- `loan-approval-dashboard.pbix` — the Power BI file
- `loan-approval-screenshot.png` — dashboard preview

---

##  How to View

1. Download `loan-approval-dashboard.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the Age, Employment Status, Credit Score, and Loan Status filters to explore the data

---

