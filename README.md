# Banking Data Analysis

## Overview
This project conducts a comprehensive analysis of banking customer data to uncover valuable insights about customer behavior, financial product usage, and demographic trends. Using Python and various data analysis libraries, the project explores relationships between customer characteristics and their banking preferences, examining factors such as income levels, age demographics, credit utilization, and risk profiles. The analysis aims to provide actionable insights for customer segmentation, risk assessment, and strategic decision-making in banking operations.


## Analysis Objectives
- Analyze customer demographics and geographic distribution
- Examine relationship between income, age, and banking product usage
- Identify patterns in credit card usage and loan behavior
- Segment customers based on loyalty classification and risk weighting
- Explore correlations between occupation, income bands, and financial products
- Assess customer profitability across different fee structures

## Tools & Technologies
- **Programming Language**: Python
- **Libraries**: 
  - pandas, numpy (data manipulation)
  - matplotlib, seaborn (visualization)
  - pymysql, sqlalchemy (database connectivity)
- **Database**: MySQL


## Key Findings

### Customer Demographics
- **Nationality Distribution**: European customers dominate the mid-income segment, while Asian customers show significant presence across all income bands
- **Income Patterns**: Most customers fall into the low-to-mid income bands, with European customers having the highest representation in mid-income categories
- **Gender Balance**: Relatively balanced gender distribution across nationalities, with slight variations in European and Asian customer segments

### Banking Product Usage
- **Credit Card Behavior**: Most customers hold 1-2 credit cards, with European customers showing highest single credit card ownership
- **Account Preferences**: Strong preference for checking and saving accounts, with most customers maintaining moderate balances
- **Fee Structure**: High fee structure customers are predominantly European, suggesting premium service adoption

### Financial Patterns
- **Income Distribution**: Right-skewed distribution with majority of customers in the $50K-$150K range
- **Savings Behavior**: Most customers maintain modest superannuation savings, indicating potential for retirement planning services
- **Loan Utilization**: Conservative borrowing patterns with most customers having minimal to moderate loan amounts

### Key Correlations
- **Strong Positive Correlations** (0.7+): Bank deposits with checking accounts (0.84), indicating customers who save also maintain active checking
- **Moderate Correlations** (0.3-0.4): Income shows moderate positive correlation with most banking products, suggesting higher income drives product adoption
- **Risk Insights**: Business lending shows positive correlation with multiple account types, indicating business customers are high-value clients




