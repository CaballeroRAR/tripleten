# tripleten Trabajos de práctica en TripleTen

### 1 # Video Game Sales Analysis Notebook
## Overview  
This Jupyter notebook provides a comprehensive analysis of video game sales data. The analysis covers data preparation, cleaning, and exploratory analysis to understand trends in video game releases, sales, and ratings across different platforms, genres, and regions.

## Key Features  
- **Data Preparation**: Handles missing values, converts data types, and standardizes column names  
- **Exploratory Analysis**: Examines game release trends, regional sales, and score correlations  
- **Visualizations**: Uses matplotlib and seaborn to create insightful plots  
- **Statistical Insights**: Provides summaries and correlations for data understanding  

## Dataset  
`games.csv` containing:  
- Game titles, platforms, release years  
- Sales data (NA, EU, JP, Other regions)  
- Critic scores, user scores, and ratings  

## Dependencies  
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 2 # Megaline Cellphone Service Analysis

## Project Overview
Analysis of customer behavior data for Megaline's two prepaid plans (Surf and Ultimate) to determine which plan generates more revenue. The analysis examines 500 customer records from 2018.

## Data Sources
- `megaline_calls.csv`: Call records

## Key Features
- Data cleaning and transformation
- Usage pattern analysis (calls, messages, data)
- Revenue calculation (base fees + overage charges)
- Plan comparison metrics

## Plan Details

### Surf Plan
- Monthly fee: $20
- Includes: 500 minutes, 50 SMS, 15GB data
- Overage charges:
  - $0.03 per minute
  - $0.03 per SMS  
  - $10 per GB

### Ultimate Plan
- Monthly fee: $70  
- Includes: 3000 minutes, 1000 SMS, 30GB data
- Overage charges:
  - $0.01 per minute
  - $0.01 per SMS
  - $7 per GB

## Usage
Run the Jupyter notebook `notebook_cellphone_service_analysis.ipynb` to:
1. Load and clean the data
2. Calculate monthly usage per customer
3. Compute revenue by plan
4. Generate comparative analysis

## Dependencies
- Python 
- pandas
- numpy  
- matplotlib
- seaborn
- scipy
