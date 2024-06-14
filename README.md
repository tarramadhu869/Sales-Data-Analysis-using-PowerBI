# Sales-Data-Analysis-using-PowerBI

**Sales Analysis:** A deep dive into sales data, aimed at extracting valuable insights to enhance strategic decision-making.

**PURPOSE:**
Analyze sales data to identify trends, top-selling products, and revenue metrics for business decision-making. 

**DESCRIPTION:**
In this project, You will delve into a sizable sales dataset for this assignment in order to glean insightful information. In order to successfully convey your findings, you will compute revenue measures like total sales and profit margins, analyze sales patterns over time, determine the best-selling products, and build infographics. This assignment demonstrates your capacity to work with and extract knowledge from huge datasets, empowering you to provide data-driven suggestions for improving sales tactics.

**COLUMN DESCRIPTION FOR SALES DATA ANALYSIS:**
• ORDER ID
• PRODUCT
• QUANTITY ORDERED
• PRICE EACH
• ORDER DATE
• PURCHASE ADDRESS
• MONTH
• SALES
• CITY
• HOUR

**EXECUTION PART:**

**1.TRANSFORMATION OF DATA**

**STEP 1:** I started by downloading the dataset, uploading it to Power BI using the 'Get Data' option, and then transforming the data.

**STEP 2:** The first row indicates which column headings are to be retained as headers.

**STEP 3:** Select 'Detect Data Type' from the 'Transform' menu after boosting the headers. Each column's data type will be automatically determined by this procedure, and conversions will be made as necessary.

**STEP 4:** Split the datetime into date and time stamp

The aforementioned process starts with selecting the desired column. Following the selection, the option to split the column becomes visible.
• Choose the 'Split Column' option and select the space as the delimiter.
• Upon completing the data transformation, click on 'Close & Apply' located at the top left.
• Remember, this step is crucial after any data transformation process.

**2.VISUALIZATION OF DATA**

1.Sales trend over time using the line chart : Simply click on the Month name and Sales column, drag it to the desired position.
     • To create a Chronological order for the months, follow these steps:
                      1. Select the column containing the months.
                      2. Navigate to the "Column Tools" and choose "Sort Column."
                      3. Select "Sort by Month Number" to sort the months in chronological order.
                      
2.Best selling products using tree map
      • To edit them for background color and font size, access the "Format" option for the visualization and adjust the settings as desired.

3.Top 5 best selling product using stacked bar chart
                      1. To manipulate the visualization, perform the following steps:
                            • Drag and drop the "Product" into the Y-axis.
                            • Place the "Quantity" into the X-axis for appropriate ordering.

4.Top 5 cities by sales using map

5.Weekly sales distribution by weekday using column chart.

6.Slicer is used to make this kind of visual
      • To create a slicer visualization, drag and drop the "Month Name" field into the slicer option. To display the slicer in a vertical 
        list, access the slicer settings and choose the option for a vertical column layout.

7.To find the revenue metrics:
      • Total profit: Sum up the net profit from all sales transactions.
      • Sales quantity: Calculate the total number of units sold
      • Profit margin: Compute the ratio of net profit to total revenue, usually expressed as a percentage.

    Total profit
            1. Select the "Card" visualization type, then drag and drop the "Sales" into the designated field. Convert it to the "SUM" 
               aggregation.
            2. Additionally, adjust the display units to show values in millions,billions, trillions, or hundreds, and customize the number of                 decimal places as needed.

    Sales quantity
            • Select the "Card" visual, then drag and drop the "Quantity Ordered" int the designated field.
            • Access the "Format" option for the visual, and adjust the callout value to change the display unit of the quantity ordered as                   desired.

    Profit margin
            • Click on new measure
            • Find the total cost by using the new measure
            • Find the total sales by using the new measure
            • Find the profit margin by using this formula in the measure.
            • Choose the measure created and place it in the card visual and design using the “Format visual”
    
