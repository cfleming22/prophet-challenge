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
   - [To be completed after analysis]

2. Seasonality Insights
   - [To be completed after analysis]

3. Stock Price Relationships
   - [To be completed after analysis]

4. Future Predictions
   - [To be completed after analysis]

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

## Support
For questions or issues:
1. Raise an issue in the repository
2. Contact instructional staff
3. Utilize provided support services
