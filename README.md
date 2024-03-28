# Bike Sales Analysis

### Project Overview
---
This data analysis project aims to provide insights into the sales performance of a Bicycle company in the year 2021. By analysing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.


![Sales Summary](https://github.com/TeniOT/Excel-visual/assets/164643376/5346f317-04a4-49b5-abf5-df3d79f4a07c)



### Data Sources 
Sales Data: The primary dataset used for this analysis is the "bike sales.csv" file, containing detailed information about each sale made by the company.

### Tools
- Excel - Data cleaning
  - [Download Here](https://skillsforall.com/launch?id=1b81c11b-147b-49aa-8f87-a3469f24d280&tab=curriculum&view=98cbced0-abf6-53ca-b984-ef587df3e600)

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
   - The Extract, Transform and Load (ETL) process.
2. Data cleaning and formatting.
   - Fixing and Removing Duplicates.
   - Handling missing values.
   - Conditional Formatting.
   - Data Parsing from Text to Column.
   ```Excel
     =TRIM()
     =LEN()
   ``` 

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
What is the Average Cost?
What is the Average Revenue?
Determine the purchasing patterns of different demographic groups to identify areas to concentrate marketing efforts

### Data Analysis
```Excel
=VLOOKUP()
=XLOOKUP()
=IF(ISNA(VLOOKUP()),"Unique","Duplicate")
```
- Pivot Table to Select Data for Analysis
- Addressing Anomalies in data
  - Use a Scatter Chart to Find Outliers
```Excel
  =LARGE()
  =SMALL()
```

### Results/Findings
The analysis results are summarised as follows:
- Average Cost = £26479
- Average Revenue = £43764
- The youth age group is globally the poorest area of sales.
- Female adults are buying the most product and should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions: the company can develop business decisions in relation to:
- Invest in marketing and promotions in youth age group globally.
- Focus on promoting sales in Australia for the male youth and in France for adult males.
- Implement a customer segmentation strategy to target Female adults effectively.
- Implement strategies to develop business decisions for sales in the United Kingdom as it has only one successful market category in the Youth

#### References
1. Microsoft 365 OneDrive
2. [Cisco Skills for All](https://skillsforall.com/)
3. [Her Data Project](https://www.youtube.com/watch?v=0N9xekdKCwk)
