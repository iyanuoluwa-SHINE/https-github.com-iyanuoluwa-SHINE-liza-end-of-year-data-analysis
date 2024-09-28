### https-github.com-iyanuoluwa-SHINE-liza-end-of-year-data-analysis

 ## End of the year sales analysis of different countries

### DATA OVERVIEW
This report provides an analysis of the annual sales performance across multiple countries, capturing key insights into market trends, regional growth, and product sales. The focus is on understanding global sales dynamics, identifying top-performing regions, and evaluating sales channels and product categories.

### DATASOURCES [DATA-SOURCES]


## DATASOURCES
The report’s insights were derived from a combination of internal and external data sources, ensuring a comprehensive analysis

### i *Company Sales Database*: Aggregated sales data from all business units across different countries.

### ii *CRM Systems: Customer* transaction and interaction data for customer behavior insights.

### iii *commerce Platform Analytics*: Data on online sales, customer journeys, and product performance.




## TOOLS USED 
### - Powerbi for data cleaning,data analysis and visualisation [Download Here]_(https://www.microsoft.com/en-us/power-platform/products/power-bi).
  1. data cleaning
  2. for analysis
  3. for data visualization

### - Github for portfolio building

### IN DATA CLEANING AND PREPARATIONS
in the initial phase of data cleaning and preparations ,we performed the following actions;

Data loading and Insppection

Handling missing Variables 

Data cleaning and formatting

### Exploratory data analysis

 EDA involved the exploring of the data to answer some questions  about the data such as;

-What Is The Total Product Sales

-Total Sales Per Year

-Total Profit By Segment

### Data analysis
This is where we incclude some basic lines of code or queries;


```POWER BI
total sales = SUM(financials[ Sales])

total profit = SUM(financials[Profit])

sum by segment = CALCULATE(SUM(financials[ Sales]),ALLEXCEPT(financials,financials[Segment]))
```

### Data visualization


 
