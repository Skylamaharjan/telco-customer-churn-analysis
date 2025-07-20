# Telco Customer Churn Analysis

This project explores customer churn behavior using multiple tools — including **Google Colab (Python)** and **Microsoft Excel** — to identify why customers leave and what can be done to reduce churn.

---

##  Project Goals

- Analyze customer churn trends
- Identify key churn factors (contract type, tenure, gender, etc.)
- Visualize insights using both Python (Colab) and Excel
- Demonstrate cross-platform data analytics skills

---

## Folder Structure
├── data/
│ └── raw/ # Original CSV dataset
├── data_excel/ # Excel workbook used for pivot analysis
├── notebooks/ # Colab Notebook (.ipynb)
├── visuals/ # Charts generated using Python (matplotlib/seaborn)
├── visuals_excel/ # Charts created using Excel (pivot tables)
├── requirements.txt # Python dependencies
└── README.md # Project overview

---

##  Google Colab Python Analysis

The Python-based analysis was done in **Google Colab** using:
- `pandas` for data cleaning
- `seaborn` and `matplotlib` for visualizations
- EDA on churn vs contract type, gender, tenure, and internet service

Notebook: [`Advertising_Analysis.ipynb`](./notebooks/Advertising_Analysis.ipynb)  
Python Visuals: [`visuals/`](./visuals)  

---

##  Excel-Based Analysis

Parallel analysis using **Microsoft Excel** involved:
- Creating pivot tables for segmentation
- Charting churn by contract, gender, tenure, and payment method
- Exporting Excel visuals as `.png` images

Excel Workbook: [`Telco_Customer_Churn_Excel_Workbook.xlsx`](./data_excel/Telco_Customer_Churn_Excel_Workbook.xlsx)  
Excel Visuals: [`visuals_excel/`](./visuals_excel)

---

##  Skills Demonstrated

- Data cleaning & handling missing values
- Exploratory Data Analysis (EDA) across two platforms
- Data visualization using Python and Excel
- GitHub folder structuring & documentation
- Real-world customer analytics using multi-tool approach

---

##  Dataset

Dataset: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
File used: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

---

## Key Insights

- Contract Type: Customers on month-to-month contracts are far more likely to churn than those on longer-term contracts (1 or 2 years). This suggests the need for loyalty programs or incentives to push longer commitments.

- Tenure Group: Customers with 12 months or less of tenure churn at a significantly higher rate than long-term customers. Early onboarding and engagement strategies could reduce early churn.

- Payment Method: Electronic check users have a higher churn rate compared to other payment methods. Encouraging auto-pay options could improve retention.

- Internet Service: Customers with Fiber optic service churn more than those with DSL or no internet. This may point to service quality or pricing issues needing attention.

- Gender: No significant difference observed in churn between male and female customers.

---

## Recommendations

1. Introduce loyalty discounts or benefits for customers who commit to longer contracts.
2. Improve early customer experience (first 6–12 months), perhaps through personalized offers or welcome programs.
3. Incentivize auto-payment options over manual billing to reduce churn from payment-related friction.
4. Investigate satisfaction among Fiber customers— high churn may indicate pricing or quality concerns.

---

## Why This Project Matters

As an aspiring **Marketing Analyst**, this project highlights:
- My ability to interpret customer behavior using different tools
- Analytical thinking and technical execution
- Professional project organization and clear communication of insights

---

## Author

**Skyla Maharjan**  
International MBA Graduate | Future Marketing Analyst  
GitHub: [Skylamaharjan](https://github.com/Skylamaharjan)
LinkedIn:[Skylamaharjan](https://www.linkedin.com/in/skyla-maharjan-5a3b291b1/)
