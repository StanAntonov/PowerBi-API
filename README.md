# Power BI API Data Integration

A Power BI data connector built with M language that automates extraction, transformation, and loading of financial data from REST APIs.

## Features

- Secure Authentication**: Implements bearer token authentication for API access
- **Automated Data Pipeline**: Transforms raw JSON API responses into structured tables
- **Customizable Output**: Clean, analysis-ready data for Power BI visualization
- **Error Handling**: Robust error handling for API failures and data inconsistencies


## Technologies Used

- **Power BI** (Data Visualization)
- **M Language** (Power Query)
- **REST API** Integration
- **JSON** Data Processing
- **Bearer Token** Authentication


## Setup Instructions

1. **Open Power BI Desktop**
2. **Create New Query** → **Blank Query**
3. **Open Advanced Editor** and paste the M code
4. **Update Credentials** with your API keys, you need to create two parameters for the service name and service key, visible where as documentated in the code within the authentication block in the beginning.
5. **Refresh Data** to load latest information

## Use Cases

- Financial market data analysis
- Real-time commodity pricing dashboards
- Automated reporting from API data sources
- Business intelligence with live data feeds

## Alternative Implementation

Check out the Python version (https://github.com/StanAntonov/API-csvchart) of this project for a code-based approach to the same data pipeline.
