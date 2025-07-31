# Insurance_Data_Analysis_Dashboard

## Overview

- This project leverages Power BI to provide in-depth analytics on a comprehensive, realistic insurance dataset combining customer demographics, policy information, claims, and feedback.
- The analysis brings actionable insights to optimize claim processing, detect trends in policy purchasing, and uncover service strengths and bottlenecks using actual data.

## Data Sources

- **InsuranceData.csv**: Large-scale (~4,400+ records) synthetic insurance data covering customer, policy, premium, claim status, and demographics.
- **Insurance-Customer-Feedback.xlsx**: Realistic customer feedback text, enabling sentiment and service analysis.
- **Interactive Power BI Dashboard**: All key KPIs and relationships visualized for business users.

## Key Features & Analysis

- **Claims Analysis**:
  - Classification by claim status: Settled, Pending, Rejected.
  - Claim amount distribution by policy type (Auto, Health, Life, Home, Travel).
  - Age group segmentation: Young Adult, Adult, Elder.
  - Gender-based breakdown of claims and coverage.

- **Policy Insights**:
  - Active vs. inactive policy ratios.
  - Premium and coverage analysis across policy types.

- **Customer Demographics**:
  - Age, gender, and customer segmentation visualized against claim likelihood and amount.
  - Understanding of customer groups with higher policy attractiveness.

- **Temporal Patterns**:
  - Policy and claim lifecycle tracking using claim/policy dates.
  - Analysis of peak periods for claims and policy expirations.

- **Customer Sentiment & Service Feedback**:
  - Direct sentiment scoring of each feedback entry (from -1 to +1).
  - Classification into "Excellent," "Needs Improvement," and "Good" services.
  - Sample insights: Most customers value quick and efficient claim settlement; main complaints involve wait times, website usability, and unclear policy terms.

- **KPIs on Dashboard**:
  - Total premium and coverage amounts, total claim amount.
  - Count of active/inactive policies, policy distribution by type.
  - Number of claims by type/status/age group.

## Technical Workflow

- **Power BI ETL**: Data loaded and transformed using Power Query (cleaning, type conversion, date parsing).
- **Data Modeling**: Relationship modeling between policies, claims, customers.
- **DAX Measures**: Custom metrics (e.g., fraud detection, sentiment scores, claim ratios).
- **Visual Design**: Interactive drill-downs, slicers for deep data exploration, KPIs, bar and pie charts, sentiment analysis visuals.

## Takeaways

- Empowers insurance business users to:
  - Spot trends and patterns in successful/failed claims.
  - Make data-driven decisions for risk, pricing, and customer service.
  - Understand the impact of demographic and product design on claim volumes and service satisfaction.
  - Leverage real customer feedback to drive continuous improvement.
- **Real-world application**: From fraud investigation to customer retention initiatives, this dashboard supports a wide range of insurance operations.
