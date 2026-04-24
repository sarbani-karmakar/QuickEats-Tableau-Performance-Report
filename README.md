# QuickEats Food Delivery — Tableau Performance Report

## Overview
Built a three-page interactive Tableau report for QuickEats, a food delivery platform, analyzing operations, customer satisfaction, and cuisine performance across 45,000+ orders.

## Live Dashboard
[View Interactive Report on Tableau Public](https://public.tableau.com/app/profile/sarbani.karmakar/viz/Revisedgraded1bassignment/CustomerCuisineInsights)

## Pages Built
- **Page 1: Executive Summary:** KPI banner (Total Revenue, Orders, Delivery Time, Satisfaction Rate), orders by day, revenue by cuisine, satisfaction breakdown
- **Page 2: Operations Deep Dive:** Restaurant performance table with conditional formatting, delivery efficiency breakdown by day, custom tooltips showing top 3 restaurants per segment
- **Page 3: Customer & Cuisine Insights:** Satisfaction by cuisine, cost vs. rating scatter plot, order cost distribution histogram, unsatisfied customer feedback table

## Calculated Fields Created
- Order Cost Category (Low / Medium / High): percentile-based
- Customer Satisfaction (Satisfied / Neutral / Unsatisfied): rating-based
- Delivery Efficiency (Fast / Standard / Slow): time-based
- Satisfaction Rate measure (% satisfied orders)

## Key Findings
- Overall satisfaction rate: 97% across all cuisines
- Peak order days: Wednesday (7,093) and Friday (7,031)
- Top volume restaurants: Food Fiesta, Street Spice, Green Bowl
- Drinks category has lowest satisfaction (0.9683) despite high revenue
- Strategic recommendation: Express Delivery pilot + Drinks experience
  improvement

## Files
- `Revised_graded_1b_assignment.twbx`: Tableau packaged workbook
- `Revised_Analysis_1b_Assignment.docx`: Strategic analysis document
- `Revised_1_b_Assignment.xlsx`: Source dataset

## Tools Used
Tableau Desktop, Calculated Fields, Action Filters, Parameters,
Conditional Formatting, Custom Tooltips

## Result: 9.8/10
