# LendingClub-Risk-Analysis
Financial risk analysis of a $45B loan portfolio using Python (Pandas) and Power BI

Project Overview
Analyzed a large-scale financial dataset containing approximately 2.9 million loan records with a total book value of $44.9 Billion. The goal was to aggregate risk by loan grade and identify trends in interest rates and capital allocation.

Technical Challenges & Solutions
Big Data Processing: Handled a 1.77 GB raw dataset using Python (Pandas).
Memory Management: Implemented chunking to process data in 100,000-row segments, overcoming local system memory constraints.
Data Cleaning: Resolved data integrity issues, including stripping non-numeric characters from interest rate strings and handling NaN values to ensure accurate financial reporting.

Key Insights
Risk vs. Rate: Confirmed the positive correlation between loan grade risk and interest rates across the portfolio.
Volume Distribution: Identified that the majority of capital is deployed in mid-tier risk grades (Grades B and C).
