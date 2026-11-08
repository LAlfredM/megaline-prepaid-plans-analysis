# Megaline: Prepaid Plans Revenue Analysis

## Project Overview

This project analyzes customer behavior and revenue generation for Megaline, a telecommunications provider offering two prepaid plans: Surf and Ultimate.

Using data from 500 customers during 2018, the analysis evaluates calling, messaging, and internet usage to compare the financial performance of both plans.

## Objectives

- Analyze monthly customer consumption patterns.
- Calculate monthly revenue, including subscription fees and additional usage charges.
- Compare customer behavior and revenue distributions between Surf and Ultimate.
- Evaluate differences in average revenue across plans and geographic regions using statistical hypothesis testing.
- Provide data-driven insights to support marketing decisions.

## Data

The project uses five datasets:

- `megaline_users.csv`: Customer information and subscription details.
- `megaline_calls.csv`: Individual call records.
- `megaline_messages.csv`: Text message records.
- `megaline_internet.csv`: Internet usage sessions.
- `megaline_plans.csv`: Pricing and service limits for each plan.

## Methodology

1. **Data preparation:** Inspecting data types, handling missing values, converting dates, and applying billing rules.
2. **Data aggregation:** Consolidating monthly calls, minutes, messages, and internet usage by customer.
3. **Revenue calculation:** Computing monthly revenue based on subscription fees and additional usage charges.
4. **Exploratory Data Analysis:** Comparing consumption patterns through descriptive statistics, histograms, and boxplots.
5. **Statistical analysis:** Applying Welch's t-tests to evaluate differences in average revenue between plans and geographic regions.

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
megaline-prepaid-plans-analysis/
│
├── Datasets/
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   └── megaline_users.csv
│
├── Notebook/
│   └── megaline-prepaid-plans-analysis.ipynb
│
├── README.md
└── .gitignore
```

## Key Areas of Analysis

- Monthly customer consumption by plan.
- Differences in included service limits and additional usage charges.
- Revenue distributions and customer spending patterns.
- Statistical differences in revenue between subscription plans and geographic regions.

## Conclusions

The analysis examines the revenue performance of both prepaid plans and identifies consumption patterns that can inform marketing and business decisions.

The final recommendations are based on the statistical results and the observed revenue differences between customer groups.