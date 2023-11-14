# Project Title: Retail Flower Sales Forecasting

**Author: Fernando Cely**

---

## Executive Summary

This project focuses on predicting flower sales at a retailer to minimize waste and enhance profitability through improved sales forecasts.

## Please note Keys and passwords were removed before pusblishing to Git, As some of the APIs are paid and the sales info is confidential, replace with your own 
---

## Rationale

This initiative aims to enhance sales predictions by employing time series analysis and integrating exogenous variables such as fuel prices, weather conditions, truck occupation, and GDP.

---

## Research Question

How can we refine sales predictions by incorporating time series analysis and leveraging exogenous variables like fuel prices, weather, truck occupation, and GDP?

---

## Data Sources

- **Historical Sales:** Sales data categorized by store and product for 188 stores.
- **Fuel Prices:** Obtained through an API, categorized by region.
- **Weather Data:** Fetched via an API, focusing on Seattle in this instance.
- **Pending Sources:** Yet to acquire GDP data and truck occupation indicators for a comprehensive economic outlook.

---

## Methodology

The chosen methodology for the forecasting model is SARIMAX. Given the highly seasonal nature of flower sales influenced by yearly cycles and key holidays, SARIMAX is preferred, especially when integrating exogenous factors.

---

## Results

The forecast model is a work in progress, with ongoing efforts to enhance accuracy, identify optimal hyperparameters, and complete the list of exogenous variables. The goal is to finalize these improvements in the next deliverable.

---

## Next Steps

1. **Extend Testing:** Implement the model across multiple stores for a more comprehensive assessment.
2. **Aggregate Sales Data:** Consider combining historical sales data from all stores and use the collective forecast as an additional exogenous variable to account for regional trends.
3. **Complete Exogenous Variables:** Acquire remaining exogenous variables through APIs for a fully automated model.
4. **Database Integration:** Develop a mechanism to submit results to an SQL database, facilitating easy access and utilization by the company.

---

## Outline of Project

- [Link to Notebook 1](https://github.com/fcely/CapstoneAI/blob/main/SalesProjections.ipynb)

---

## Contact and Further Information

For inquiries or additional information, please contact Fernando Cely at [fcely@me.com](mailto:fcely@me.com).


