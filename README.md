# Analysis of AG Superstore Sales Data
![](store.jpg)

---

## Introduction

This analysis involves in-depth business scrutiny of the sales data of AG Superstore to showcase important insights which can help in maximizing profit and sales in general.  The Sales data contains attributes of almost 10,000 Sales orders such as Row ID,	Order ID,	Order Date,	Ship Date,	Ship Mode,	Customer ID,	Customer Name,	Segment,	Country,	City,	State,	Postal Code,	Region,	Product ID,	Category,	Sub-Category,	Product Name,	Sales,	Quantity,	Discount, and	Profit spread out into individual columns. 

Kindly feel free to interact with data (https://github.com/SeunA88/Analysis-of-AG-Superstore-Sales-Data/blob/main/Superstore%20data.csv)

Analysis of this data was carried out to acquire some useful insights from the dataset. Firstly, each column was formatted to depict the data therein. The following insights were then obtained from the data using various Excel functions:

1. In which state, Segment and category was the highest profit generated?
2. In which state, Segment and category was the highest unit of goods sold?
3. What are the average sales and profit by categories?
4. What are the total quantities sold by categories and region?
5. What are the total sales and profit by region?
6. What are the total sales and profit by segment?
7. What are the total sales and profit by ship mode?

These acquired insights were further displayed with various visualization tools in Excel. Please find below each analysis alongside some visuals.

## Result of Analysis

-	In which state, Segment and category was the highest profit generated?

This was determined using the VLOOKUP function.

![](Profit.png)

#### Analysis Insight: 
---

-	In which state, Segment and category was the highest unit of goods sold?

This was determined using the VLOOKUP function

![](sales.png)

#### Analysis Insight: 
---

-	What are the average sales and profit by categories?

This was determined using the AVERAGE function in the pivot table "Value" field for each criteria/attribute, with the categories in the "Column" field. A Column chart was used to visualize the insight generated.

![](Categories.png)

#### Analysis Insight: 

-	What are the total quantities sold by categories and region?

This was determined using the SUM function in the pivot table "Value" field for the total quantity sold, with the categories in the "Column" field and region in the "Row" field. A Column chart was used to visualize the insight generated.

![](Quantity_sold.png)

#### Analysis Insight: 
---

- What are the total sales and profit by region? 

This was determined using the SUM function in the pivot table "Value" field for total sales and profit, with the region in the "Column" field. A Column chart was used to visualize the insight generated.

![](Region.png)

#### Analysis Insight: 
---

- What are the total sales and profit by segment?

This was determined using the SUM function in the pivot table "Value" field for total sales and profit, with the segment in the "Column" field. A Column chart was used to visualize the insight generated.

![](Segment.png)

#### Analysis Insight: 
---

- What are the total sales and profit by ship mode?

This was determined using the SUM function in the pivot table "Value" field for total sales and profit, with the Ship mode in the "Column" field. A Column chart was used to visualize the insight generated.

![](Ship_mode.png)

#### Analysis Insight: 
---

## Conclusion
A clear understanding of the present state of health of AG Superstores have been made possible using analysis functions in Excel. Insights generated from these analyses can be chanelled towards promoting sales and making decisions for long term profit and sales maximization by stakeholders.
