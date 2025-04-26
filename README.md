# Budget and Forecasting Analysis

## Overview

This project presents a structured approach to forecasting and budgeting based on historical financial data.  
It leverages actual expense data, forecasted projections under varying scenarios, and culminates in a forward-looking Income Statement.

The objective of this analysis is to enable better financial planning, scenario evaluation, and data-driven decision-making for business operations.

---

## Project Structure

| Sheet Name         | Description |
|---------------------|-------------|
| **Actual Expenses** | Historical operating expenses organized monthly by account and department. |
| **Forecast**        | Forecasted operating expenses under best- and worst-case assumptions, based on actuals and projected growth factors. |
| **Income Statement**| Forward-looking financial statement reflecting projected revenue and expenses over a 12-month period. |
| **Visuals**         | Charts and visual summaries for easier interpretation of forecast trends and variances. |

---

## Forecasting Methodology

- **Historical Baseline**:  
  Actual expenses from previous months serve as the baseline for forecasts.

- **Scenario Modeling**:  
  Best-case and worst-case scenarios are defined based on a 30% adjustment factor.  
  These assumptions are applied to actual data to estimate potential outcomes under varying market conditions.

- **Rolling Forecast Approach**:  
  Forecasts dynamically build upon actual data, integrating new results as they become available.

- **Income Statement Projection**:  
  Revenue and expense forecasts feed into a projected Income Statement to model profitability across future periods.

---

## Advanced Formulas and Techniques Used

- **Growth Rate Application**:  
  Applied a fixed growth or adjustment factor (e.g., +30% or -30%) across monthly expense categories using standard multiplication formulas.

- **FORECAST.ETS Function**:  
  Utilized Excel’s `FORECAST.ETS` function for advanced time series forecasting, allowing automatic prediction of future values based on seasonal patterns in historical data.

- **Dynamic Lookups with VLOOKUP**:  
  Implemented `VLOOKUP` functions to dynamically retrieve expense data and account information across datasets, ensuring consistency and minimizing manual errors.

- **Dynamic Range References**:  
  Used dynamic cell referencing to pull and calculate updated values as new months are populated.

- **Scenario Switches**:  
  Embedded best- and worst-case logic to quickly toggle between forecasting outcomes based on defined assumptions.

- **Aggregation Formulas**:  
  Summarized monthly data for annual and quarterly views in the Income Statement using `SUM`, `AVERAGE`, and conditional aggregation formulas.

- **Visual Analytics**:  
  Created dynamic charts linked to forecast and actuals to monitor performance trends and variances in real time.

---

## How to Use

1. **Input Actual Expenses**:  
   Update the `Actual Expenses` tab monthly with real operating expense data.

2. **Adjust Scenario Assumptions**:  
   Modify the growth assumptions (currently set at 30%) in the `Forecast` tab if needed.

3. **Use FORECAST.ETS for Time Series Forecasting**:  
   Apply `FORECAST.ETS` to predict future values based on new historical patterns.

4. **Review Forecast Outputs**:  
   Analyze the updated projections and scenarios within the `Forecast` and `Income Statement` tabs.

5. **Monitor Visualizations**:  
   Refer to the `Visuals` tab for graphical summaries of financial trends.

---

## Future Improvements

- Incorporate more granular revenue forecasting methodologies.
- Automate scenario toggling with drop-down selectors.
- Introduce sensitivity analysis for key variables.
- Enhance forecasting models by integrating external economic indicators.

---

## License

This project is intended for educational and internal use.  
For any inquiries regarding use or adaptation, please contact the repository owner.
"""


