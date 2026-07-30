# Life Insurance Cash Flow Projection & Lapse Risk Analysis

## Project Overview
This project develops a simplified life insurance projection model to evaluate how mortality risk and policyholder lapse behavior affect the profitability of a life insurance contract.

The model simulates annual cash flows, estimates expected death claims using mortality assumptions, and analyzes how early policy termination (lapse) changes future premiums, liabilities, and overall profitability.

## Business Problem
Life insurance companies collect premiums today in exchange for future protection benefits. To ensure profitability and solvency, actuaries must answer several important questions:

* How much premium should be collected?
* How large are expected future claim payments?
* How does mortality risk affect profitability?
* What happens if policyholders stop paying premiums earlier than expected?

This project aims to provide a simplified actuarial framework to explore these questions.

## Project Objectives
The project focuses on three actuarial components:

1. **Mortality Analysis**
   * Import and analyze mortality tables
   * Calculate annual mortality probability ($q_x$)
   * Calculate survival probability
   * Visualize mortality and survival curves

2. **Cash Flow Projection**
   * Project annual premium income
   * Estimate expected death benefit payments
   * Calculate discounted present values
   * Evaluate expected profit and profit margin

3. **Lapse Risk Analysis**
   * Introduce policy lapse assumptions
   * Compare projected cash flows under different lapse scenarios
   * Evaluate the impact of lapse risk on profitability

## Tools & Technologies
* **Programming:** Python
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib
* **Development Environment:** VS Code, Jupyter Notebook
