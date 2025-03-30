# Clothing-Store-Sales-Analysis-Excel
Data cleaning | Pivot tables | VLookup

- `Video tutorial link`: https://www.youtube.com/watch?v=gTK5rNhWJyA&list=PLRY-AYJzifh1p1YinaFw-VIqYYsPyRYi4&ab_channel=RishabhMishra
- `Problem statement`: Vrinda Store wants to create an annual sales report for 2022. So that, they can understand their customers and grow more sales in 2023
- `Skills used`: Data cleaning, Data processing, Data analysis, Business Problem Solving

### **`Questions:`**

- Compare the sales and orders using single chart
- Which month got the highest sales and orders?
- Who purchased more - Men or Women in 2022?
- What are different order status in 2022
- List the top 10 states contributing to the sales?
- Relation between age and gender based on number of orders.
- Which channel is contributing to maximum sales?
- Highest selling category?

### **`SOLUTION:`**

**STEP - 1 : Data Cleaning**

- Double click the borders of each column headers to **fit** the content width-wise
- Check if all the columns have consistent data - Null, Duplicate, data-type
- The fastest way of checking this at a glance is by applying **filter** to all the columns and looking at the filter values.

<img width="294" alt="Image" src="https://github.com/user-attachments/assets/787b4cd0-89e1-48a4-889f-b03578b3ef52" />

- Replace the inconsistent data
- Select the value that needs to be changed in the filter→ Select the column → CTRL + F to Replace
    
<img width="386" alt="Image" src="https://github.com/user-attachments/assets/eba9a9ef-3b77-45bf-85f0-8f8bcd23be5d" />

**STEP - 2 : Data Processing**

- Adding columns to analyze data better
- For example: Categorizing age into Senior | Adult | Teenager
  
<img width="389" alt="Image" src="https://github.com/user-attachments/assets/3fc99330-27c4-4c81-b7b1-b1a741d1a00d" />

- For example: Extracting month into a separate column
- This will help us answer month related business question better

<img width="241" alt="Image" src="https://github.com/user-attachments/assets/a214d7bb-774e-499f-9611-cf83459b62ec" />

**STEP 3 - Data Analysis**

- Select all the data (CMD + A) and insert `Pivot Table`
- Pivot table helps us `summarize` the data for selected columns

<img width="302" alt="Image" src="https://github.com/user-attachments/assets/0454e77d-e5ff-4663-8173-cddfdf414b21" />

- You can switch off **Grand Total** from **Design** Tab
- Select the Pivot Table and insert Chart
- Different chart types can be accessed in the Design tab
- Combo type has both lines and bar CHART PROPERTIES

<img width="384" alt="Image" src="https://github.com/user-attachments/assets/acf53d42-8e78-41c0-8dda-8d7b6298ce00" />

- You can add or remove elements in a chart by **Selecting a chart → Design → Chart elements**
- To abbreviate values on axis, select the values and go to **numbers** section on right side panel

