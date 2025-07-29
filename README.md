# TripleTen Practice Projects

---

## 1. Video Game Sales Analysis Notebook

### 📊 Overview  
This Jupyter notebook provides a comprehensive analysis of video game sales data, examining trends across platforms, genres, and regions.

### 🔍 Key Features  
- **Data Preparation**  
  - Handles missing values  
  - Converts data types  
  - Standardizes column names  
- **Exploratory Analysis**  
  - Examines game release trends  
  - Analyzes regional sales patterns  
  - Investigates score correlations  
- **Visualizations**  
  - Creates plots using matplotlib and seaborn  
- **Statistical Insights**  
  - Provides data summaries  
  - Calculates correlations  

### 📂 Dataset  
`games.csv` contains:  
- Game titles  
- Platforms  
- Release years  
- Regional sales (NA, EU, JP, Other)  
- Critic scores  
- User scores  
- Ratings  

### ⚙️ Dependencies  
```bash
pip install pandas numpy matplotlib seaborn scipy
```
## 2. Megaline Cellphone Service Analysis

### 📞 Project Overview
Analysis of customer behavior data for Megaline's two prepaid plans (Surf and Ultimate) to determine which plan generates more revenue. The analysis examines 500 customer records from 2018.

### 📂 Data Sources
- `megaline_calls.csv`: calls, internet usage, messages, plans, users.


### 🔍 Key Features
- **Data Processing**:
  - Cleaning and transformation of raw usage data
  - Monthly aggregation of usage metrics
- **Usage Analysis**:
  - Call duration patterns
  - Message frequency
  - Data consumption trends
- **Revenue Calculation**:
  - Base fee computation
  - Overage charge calculations
- **Comparative Metrics**:
  - Plan adoption rates
  - Revenue per user
  - Usage limit comparisons

### 📋 Plan Specifications

#### Surf Plan ($20/month)
| Feature | Included | Overage Charge |
|---------|----------|----------------|
| Minutes | 500 | $0.03/minute |
| SMS | 50 | $0.03/message |
| Data | 15GB | $10/GB |

#### Ultimate Plan ($70/month)
| Feature | Included | Overage Charge |
|---------|----------|----------------|
| Minutes | 3000 | $0.01/minute |
| SMS | 1000 | $0.01/message |
| Data | 30GB | $7/GB |

### 🛠️ Technical Implementation
```bash
# Required packages
pip install pandas numpy matplotlib seaborn scipy
``` 