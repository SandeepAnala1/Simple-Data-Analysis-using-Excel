# Simple-Data-Analysis-using-Excel

# Types of Analysis performed here

## 1. Data Cleaning
- Change data to tabluar format - Ctrl + T
- Set table name, you can use this table name going forward for formulas etc
<img width="603" alt="image" src="https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/803e7c3f-2a45-40b5-bf74-fda5e4008275">

- Expand all columns
- Format the values in the required columns
- Quick tip: Converting normal integers to rupees or any other currency is Ctrl + Shift + 4 | Home ribbon - currency | Ctrl + 1
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/94ea1786-b08f-4809-a7ec-a4e1db5a11d3)

- Create new column with proper header and you can use functions here | I used if function to check the status of purchase
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/d7bb51f6-7e2f-4fe7-82a4-b200518cef6e)

- While writing formula, tab key helps
- To enable filters, Ctrl + Shift + L


## 2. Trend Analysis
- Pivot : A PivotTable in Excel is a powerful data analysis tool that allows you to summarize, analyze, explore, and present your data. It's like a built - in automatic reports
### Steps to Create a PivotTable
    - Select the Data Range: Choose the range of data you want to analyze.
    - Insert PivotTable: Go to the Insert tab and click on PivotTable.
    - Choose the PivotTable Location: Decide whether to place the PivotTable in a new worksheet or an existing one.
    - Configure the PivotTable: Drag and drop fields into the Rows, Columns, Values, and Filters areas to configure the PivotTable.
<img width="706" alt="image" src="https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/0704673c-deb6-47aa-8c8d-6973248db9e6">
- When PivotTables Field is missing, just right click on the values and select show field list
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/1800c847-96ae-4122-a561-52dd57a6c433)

- When you double click on outlier values of purchase amount, you can find the details of specific date
![image](https://github.com/SandeepAnala1Simple-Data-Analysis-using-Excel/assets/163712602/8aa5b953-5200-4086-972a-143787972582)


## 3. Yedukondalu Analysis (kidding, specific person analysis) & it should be dynamic
- COUNTIF: The COUNTIF function in Excel is indeed very handy for counting the number of cells within a range that meet a certain condition
  > =COUNTIFS(Sales[First Name],B1)
- The SUMIFS function in Excel adds up all the values in a range that meet multiple criteria. It is an extension of the SUMIF function, which allows for only a single condition.
  > =SUMIFS(Sales[Purchase Amount],Sales[First Name],B1)
- The MAXIFS function allows you to find the maximum value in a range based on one or more criteria.
  > =MAXIFS(Sales[Purchase Amount],Sales[First Name],B1)
- The FILTER function in Excel is used to filter a range of data based on criteria you define.
  > =FILTER(Sales,Sales[First Name]=B1)
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/2e9b2984-2a44-49e5-afd7-b9859fabfd89)


## 4. Purchase Models
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/44709b76-e426-406a-9743-b46ee90fa702)


## 5. Customer Analysis
- Slicer:
![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/02bffb6b-2690-4139-bc4e-d165bed740fa)

![image](https://github.com/SandeepAnala1/Simple-Data-Analysis-using-Excel/assets/163712602/8de9bc61-8642-4775-8b4d-7de779482a19)

