# Prophet Challenge

## Overview
This repository contains the analysis of MercadoLibre's Google search traffic data and stock price patterns. The analysis aims to identify trends and forecast future patterns using Prophet, helping to understand if search traffic can predict stock trading success.

## Repository Information
- Repository Name: prophet-challenge
- Purpose: Module 8 Challenge Assignment

## Code Attribution
All code in this repository is original work, following the starter code provided in the assignment. The implementation uses standard libraries and follows documented approaches from:
- pandas documentation
- Prophet documentation
- matplotlib documentation

This project analyzes MercadoLibre's Google search traffic data and stock price patterns to identify trends and forecast future patterns using Prophet. The analysis includes examining unusual patterns in hourly search traffic, mining search traffic data for seasonality, relating search traffic to stock price patterns, and creating time series models.

## Requirements
- Python 3.x
- pandas
- prophet
- numpy
- matplotlib

## Data Sources
The analysis uses two main data sources:
1. Google Hourly Search Trends
   - Contains search popularity data for MercadoLibre
   - Hourly frequency
   - Used for pattern and seasonality analysis

2. MercadoLibre Stock Price Data
   - Contains stock price information
   - Hourly frequency
   - Used for financial correlation analysis

## Analysis Components

### 1. Search Traffic Analysis (25 points)
- Data loading and preparation
- May 2020 pattern analysis
- Monthly traffic comparison
- Financial results correlation

### 2. Seasonality Analysis (20 points)
- Hourly traffic patterns
- Day-of-week trends
- Weekly seasonal patterns
- Time-based trend identification

### 3. Stock Price Analysis (35 points)
- Stock data integration
- 2020 market event analysis
- Search trends lag analysis
- Stock volatility calculations
- Return correlations

### 4. Prophet Forecasting (20 points)
- Model preparation
- Forecast generation
- Component analysis
- Pattern identification

## Validation Framework

### Data Validation Checklist
- [ ] CSV files load successfully
- [ ] Data types are correct
- [ ] Date ranges are continuous
- [ ] No missing/null values
- [ ] Data shape matches expectations

### Code Validation Checklist
- [ ] All cells execute without errors
- [ ] Calculations produce expected results
- [ ] Visualizations render properly
- [ ] Documentation is complete
- [ ] Code comments are comprehensive

## Key Findings
The analysis reveals several important insights about MercadoLibre's search traffic and stock performance:

1. Search Traffic Patterns
   - Looking at the hourly trends analysis and Prophet components plot, search traffic peaks during the late night/early morning hours, specifically around midnight to 1 AM.
   - This suggests users are most active in their search behavior during these late hours.
     

2. Seasonality Insights
- The total search traffic for May 2020 was significantly higher than usual
- When compared to the median monthly traffic:
- May 2020 total search traffic was higher than the median monthly traffic
- The ratio shows that May 2020's traffic was approximately 1.08 times higher than the median
- This represents an 8% increase in search traffic compared to the typical monthly traffic
- This increase suggests that the release of MercadoLibre's financial results did generate increased interest and search activity from the public during that period.

Hourly Patterns:
- Search traffic shows strong daily cyclical patterns
- Peak activity occurs during the late night/early morning hours
- Lowest activity is during normal business hours
- This suggests users are most active in searching during non-working hours

Daily Patterns:
- Search traffic varies by day of the week
- Tuesday shows the highest search activity
- Weekend days (Saturday and Sunday) show lower search volumes
This indicates stronger user engagement during weekdays

Weekly/Seasonal Patterns:
- Search traffic shows consistent weekly cycles
- There's a notable seasonal trend throughout the year
- October shows the lowest search activity
- Search activity tends to increase during the winter months
- There's a clear drop in search traffic during holiday periods

3. Stock Price Relationships
- There is no strong predictable relationship between:
- Lagged Search Traffic and Stock Volatility:
- The correlation is very weak, showing that search traffic from the previous hour doesn't have a significant relationship with stock price volatility.

Lagged Search Traffic and Stock Returns:
- Similarly, there is a very weak correlation between lagged search traffic and hourly stock returns.
- This suggests that search trends don't effectively predict stock price movements in the following hour.
- The correlation values are close to zero, indicating that these variables move independently of each other.
- This means that search traffic patterns alone may not be a reliable predictor of either stock volatility or returns in the short term.


## Setup & Usage
1. Clone the repository:
   ```bash
   git clone [cfleming22/prophet-challenge]
   cd prophet-challenge
   ```

2. Install required dependencies:
   ```bash
   pip install pandas prophet numpy matplotlib
   ```

3. Ensure data files are in the Resources directory

4. Open and run forecasting_net_prophet.ipynb:
   - Execute cells sequentially
   - Review validation checkpoints
   - Check visualization outputs
   - Verify written analyses

## Notes & Considerations
- Analysis focuses on 2020 data, particularly the impact of market events
- Prophet model parameters are tuned for hourly data
- Visualizations include comprehensive labels and explanations
- All findings include detailed written interpretations


