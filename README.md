# 📊 OTT User Funnel Analysis (Python + Power BI)

This project analyzes the user journey across an OTT streaming platform, from viewing content to completing a paid subscription. Using Python for data cleaning and funnel metric generation, and Power BI for dashboard visualization, we identify key drop-off points and provide business recommendations to improve subscription conversion.

## 🎯 Objective

Understand where users drop off in the subscription process and provide strategies to improve conversion and revenue.

## 📂 Project Structure

```
OTT-Funnel-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_ott_funnel_data.csv
│
├── python_notebooks/
│   └── Funnel Analysis.ipynb
│
├── power_bi_dashboard/
│   └── OTT_Funnel_Analysis.pbix
│
└── report/
    └── Funnel_Analysis_Report.pdf
```

## 🧹 Data Cleaning (Python)

* Removed duplicates and missing values
* Standardized date and event timestamps
* Created funnel stage indicators
* Exported cleaned dataset for Power BI

## 🔻 Funnel Drop-off Summary

| Stage           | Users | Drop % | Insight                                 |
| --------------- | ----- | ------ | --------------------------------------- |
| Visit Content   | 1436  | -      | High awareness and platform reach       |
| Click Subscribe | 360   | 74.9%  | Value not clear, CTA improvement needed |
| Select Plan     | 360   | 0%     | Users who click show intent             |
| Start Payment   | 223   | 38.1%  | Pricing / trust hesitation              |
| Payment Success | 121   | 45.7%  | Payment failures or trust issues        |

## 📈 Power BI Dashboard

* Interactive funnel visualization
* Slicers: Age, Gender, Device Type, Region
* DAX for Drop-off % and Conversion %

## 💡 Key Insights

* Major loss occurs before subscription initiation
* Payment stage also shows high abandonment
* Younger audience shows higher browsing but lower conversion

## ✅ Recommendations

1. Improve subscription CTA and highlight value
2. Simplify login/sign-up (enable Google/Phone login)
3. Improve payment experience (UPI Autopay, trust badges)
4. Offer limited free trial to reduce hesitation
5. Perform A/B testing on signup and payment pages

## 🛠️ Tools Used

| Tool                        | Purpose                                |
| --------------------------- | -------------------------------------- |
| Python                      | Cleaning and transformation            |
| Pandas / NumPy / Matplotlib | Data processing & analysis             |
| Power BI                    | Dashboard & visualization              |
| Git & GitHub                | Version control and portfolio showcase |

## 👤 Author

****Bipin Chauhan ** — Business Analyst**
