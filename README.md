# -Nigeria-E-Payment-Channel-Analysis-2020-2024-
This project analyzes Nigeria’s electronic payment channels (2020–2024) using CBN data to uncover growth trends, market share, and correlations. Findings show strong digital adoption, led by mobile and internet banking, while traditional channels decline. Insights guide policy, fintech growth, and inclusion efforts.
Project Overview

This project analyzes Nigeria’s electronic payment ecosystem from 2020–2024 using data sourced 
from the Central Bank of Nigeria (CBN).
It explores growth dynamics, digital adoption trends, and correlations among payment channels 
such as POS, ATM, Mobile, Internet, and NIP.

Dataset Overview
Feature	Description
Source	Central Bank of Nigeria (CBN) E-payment Statistics
Period Covered	2020–2024 (H1 2024 inclusive)
Metrics	Transaction Value (₦ trillions)
Channels	POS, ATM, Internet Banking, Mobile Banking, USSD, NIP
Methodology
# Core steps followed in the notebook
1. Data import and cleaning using pandas
2. Normalization (values converted to trillions)
3. Growth rate & CAGR computation
4. Correlation matrix & heatmap visualization
5. Channel mix evolution via stacked area charts
6. Market share table for 2024

Key Insights

Growth Drivers: Mobile and Internet banking recorded the strongest CAGR (2020–2024), reflecting Nigeria’s rapid digital finance expansion.

Declining Channels: ATM and POS usage stagnated as customers shifted to mobile-based platforms.

High Correlation: Internet and Mobile channels show strong positive correlation, suggesting synchronized adoption trends.

Market Leadership: NIBSS Instant Payment (NIP) remains dominant with the highest transaction share in 2024.

Visual Highlights

Total Transaction Value Over Time


Channel Mix Evolution (Stacked Area Chart)


Correlation Heatmap


CAGR by Channel (Growth Ranking)


2024 Market Share by Channel


SWOT Analysis
Strengths	Weaknesses
Rapid digital adoption	Network instability and limited infrastructure
Fintech innovation ecosystem	Unequal adoption across regions
Opportunities	Threats
Expansion of digital inclusion	Cybersecurity and fraud risks
Policy reforms promoting cashless economy	Economic instability affecting growth
Recommendations

Enhance digital infrastructure and improve network reliability.
Strengthen fraud detection systems and cybersecurity frameworks.
Encourage fintech–bank collaborations for inclusive financial services.
Support data-driven policymaking to ensure sustainable growth.

Skills Demonstrated

Advanced data wrangling using pandas & numpy

Data visualization using matplotlib & seaborn

Growth and CAGR computation

Correlation and trend analysis

Business intelligence storytelling

📂 Project Structure
Nigeria_EPayment_Analysis/
│
├── data/
│   ├── cbn_epayment_data.csv
│
├── plots/
│   ├── total_value.png
│   ├── channel_mix.png
│   ├── correlation_heatmap.png
│   ├── cagr_growth.png
│   └── market_share.png
│
├── Nigeria_EPayment_Analysis.ipynb
└── README.md

License

This project is for educational and portfolio purposes only.
Data © Central Bank of Nigeria (CBN) — all rights reserved.

