# Coffee_Shop_sales_Analysis_Excel
Comprehensive Excel project analyzing coffee shop sales data with pivot tables and interactive dashboard to reveal key sales trends, product performance, and customer insights.


# Coffee Shop Sales Analysis Excel Project

## Project Overview  
This Excel-based project presents a comprehensive sales analysis for a coffee shop chain, covering transactional data from January to June. The goal is to uncover sales trends, product performance, and customer purchasing patterns through detailed data analysis and interactive visualizations. This project demonstrates data wrangling, pivot table use, and dashboard design skills using Excel.

---

## Dataset Description  
The raw transactional sales data is stored separately in the **dataset.xlsx** workbook, containing granular records with the following fields:

- Transaction ID, Date, Month, Day of Week, Time, Hour  
- Transaction Quantity  
- Store ID and Location  
- Product ID, Unit Price, Product Category, Type, and Detail  
- Calculated Revenue per transaction  

This dataset workbook serves as the foundational data source for analysis and visualization.

---

## Workbooks Overview  

### 1. `dataset.xlsx`  
Contains the **Transactions** worksheet with the raw, detailed sales data. This separation allows managing the large dataset independently from analysis and dashboard files.

### 2. Main Analysis Workbook  
This workbook contains the following sheets that perform analysis and visualization using the data imported or linked from the `dataset.xlsx` file:

- **Analyze (with trailing space)**: Contains pivot table summaries aggregating key metrics such as total revenue by month.  
- **Dashboard**: An interactive visual dashboard presenting KPIs and sales trends, dynamically linked to pivot tables in the Analyze sheet.  
- **Key Insights Found**: A textual summary highlighting major findings from the analysis period (Jan–Jun), including critical trends and actionable insights.

---

## Important Note on Workbook Setup  
Since the **Transactions** data is now in a separate workbook (`dataset.xlsx`), the main analysis workbook imports or links to this data source. This design helps keep the main file lightweight, but note that:

- Excel slicers and pivot tables require data to be accessible within the same workbook or connected via Power Query/Data Model.  
- Some interactivity like slicers may not fully work across separate workbooks unless properly linked through Excel’s Data Model or Power Query.  
- Ensure both workbooks remain in the same folder or linked path to maintain data connections.

---

## Key Insights Summary  
- Monthly revenue trends indicating peak sales periods  
- Most popular products and categories by sales volume  
- Store location performance comparisons  
- Customer buying patterns by day and time  
- Identification of growth opportunities and sales optimization areas

## Dashboard
Here is a snapshot of the interactive dashboard showcasing key sales metrics:

![Dashboard Overview](images/dashBoard.png)

---

## How to Use This Project  
1. Open `dataset.xlsx` to review the detailed raw transactions data.  
2. Open the main analysis workbook to explore aggregated metrics in the **Analyze** sheet.  
3. Use the **Dashboard** sheet for visual summaries and KPIs.  
4. Read the **Key Insights Found** sheet for a narrative overview of results.

---

## Tools & Skills Demonstrated  
- Managing large datasets across multiple workbooks  
- Data import and linking between Excel files  
- Advanced pivot table creation and summarization  
- Dynamic dashboard design and visualization  
- Business data analysis and insight extraction

---

Thank you for viewing this project! Feel free to explore the files and reach out for any questions or collaboration opportunities.

---

*Created by Muhammad Sohaib UL Hassan
