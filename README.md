# Customer Personality Analysis

## Project Overview

This project explores customer purchasing behaviour and marketing campaign performance using Python.

The goal is to identify spending patterns, understand customer characteristics, and analyse factors associated with marketing campaign acceptance.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses the **Customer Personality Analysis** dataset, which contains customer demographic information, household composition, purchasing behaviour, product spending and marketing campaign responses.

The original dataset contains 2,240 customer records and 29 columns.

The dataset was cleaned and prepared for analysis, resulting in a working dataset with 2,236 customer records.

## Project Objectives

- Analyse customer spending patterns across different product categories.
- Explore the relationship between customer income and spending.
- Compare purchasing behaviour across different sales channels.
- Evaluate previous and latest marketing campaign acceptance rates.
- Investigate how customer demographics and household composition relate to campaign responses.
- Identify actionable business insights based on the analysis.

## Methodology

The project was completed using the following steps:

1. **Data Loading and Exploration:** Loaded the dataset using Pandas and examined its structure, dimensions and data types.
2. **Data Quality Assessment:** Identified missing values, duplicate records and potential age outliers.
3. **Data Cleaning:** Converted the customer enrolment date to datetime format, excluded customers older than 100 from the working dataset and replaced missing income values with the median.
4. **Feature Engineering:** Created additional columns, including Age, Age Group, Total Spending, Total Children and Accepted Previous Campaign.
5. **Exploratory Data Analysis (EDA):** Used Pandas, NumPy, Matplotlib and Seaborn to investigate customer spending, purchasing channels and marketing campaign acceptance.
6. **Business Insights:** Interpreted the results and identified potential opportunities for improving marketing strategies.

## Key Findings

- **Product Spending:** Wine was the highest-spending product category, followed by meat products.
- **Income and Spending:** Customer income and total spending showed a strong positive correlation of 0.789.
- **Purchasing Channels:** Physical stores were the most frequently used purchasing channel, followed by online and catalogue purchases.
- **Previous Campaigns:** Campaign 4 had the highest acceptance rate among the five previous campaigns (7.47%).
- **Latest Campaign:** The latest marketing campaign achieved an acceptance rate of 14.94%.
- **Customer Age:** Customers aged 65–75 had the highest acceptance rate for the latest campaign (24.30%).
- **Education:** Customers with a PhD had the highest latest campaign acceptance rate (20.82%).
- **Household Composition:** Customers without children at home had the highest latest campaign acceptance rate (26.53%).


## Business Recommendations

Based on the analysis, the following actions could help improve marketing performance:

1. **Target high-value customers:** Focus on customers with higher incomes, as they tend to spend more and show higher campaign acceptance.
2. **Personalize campaigns by age:** Consider tailored campaigns for customers aged 65–75 and younger adults aged 18–25, who showed relatively high acceptance rates.
3. **Consider household composition:** Customers without children at home showed higher campaign acceptance, suggesting an opportunity for more targeted messaging.
4. **Improve campaign performance:** Investigate why Campaign 2 had the lowest acceptance rate and identify opportunities to improve future campaigns.
5. **Focus on product preferences:** Prioritize wine and meat products in relevant promotions, as these categories generated the highest customer spending.

## Project Structure

```text
Customer_Personality_Analysis/
│
├── data/
│   ├── raw/
│   │   └── marketing_campaign.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── visualizations/
│   └── acceptance_by_household.png
│
└── README.md
```

## Conclusion

This project provided insights into customer purchasing behaviour, spending patterns and marketing campaign performance.

The analysis highlighted relationships between customer characteristics and purchasing behaviour, as well as differences in campaign acceptance across customer groups.

Through this project, I applied Python and data analysis techniques to clean, explore and interpret real-world business data, translating findings into actionable business insights.