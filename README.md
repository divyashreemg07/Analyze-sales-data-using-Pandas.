# Analyze-sales-data-using-Pandas.

## Project Overview

This project performs exploratory data analysis (EDA) on a sales dataset using Python.It identifies key sales patterns, product performance, pricing influence, and regional sales distribution.

The analysis is implemented in the Jupyter Notebook `sales.ipynb`,using `pandas` for data processing and `matplotlib` for data visualization.

### Technologies Used

-   Python
  
-   Pandas
  
-   Matplotlib
  
-   Jupyter Notebook

#### Dataset Details

The analysis uses `sales_dataset.csv`, which contains:

  Column Name   Description
  ------------- -------------------------
  Product       Product category
  
  Sales         Total revenue generated
  
  Quantity      Units sold
  
  Region        Sales region
  
  Price         Unit price

--> No missing values were found in the dataset.

##### Analysis Performed

1.Total Sales by Product

-   Aggregated sales to determine top-performing products.
-   
-   Observation:
-   
     - Headphones generated the highest overall sales;
       
     - Tablets had the lowest.

2️.Total Sales by Region

-   Grouped by region to identify geographical performance.
  
-   Observation: West region recorded the highest sales share.

3️.Total Quantity Sold per Product

-   Identified which products are sold in the highest volume.

4️.Price vs Sales Scatter Plot

-   Shows how product pricing impacts revenue.
  
-   Observation:A positive correlation exists between price and
  
    sales.

5️.Sales Share by Region

-   Displays percentage contribution of each region.
  
-   Observation:West region dominates total sales.

######  Key Visualizations

-   Price vs Sales Scatter Plot.
  
-   Sales Share Pie Chart.

-   Product & Region Summaries.

####### Conclusion

-   Headphones lead in total sales.
  
-   West region performs the best.
  
-   Higher-priced products bring more revenue.
  
-   Sales distribution is balanced except for West's dominance.

######## How to Run the Notebook

1.  Install requirements:
2.  
        - pip install pandas matplotlib

3.  Launch Jupyter Notebook:

        - Jupyter Notebook

4.  Open `sales.ipynb` and run all cells.
