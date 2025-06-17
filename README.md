# Interactive Coffee Sales Dashboard (Excel)

This project is an **end-to-end Microsoft Excel solution** for analyzing coffee sales data, transforming raw information into a dynamic and interactive dashboard.

## What I've Done in This Project:

* **Data Integration:** Consolidated sales data from 'Orders', 'Customers', and 'Products' tables.
* **Advanced Data Transformation:**
    * Performed lookups for customer details (name, email, country) and product information (coffee type, roast type, size, unit price).
    * Calculated 'Total Sales' and created user-friendly names for coffee and roast types.
    * Applied custom formatting for dates, sizes, and currency, handling blank values for cleaner data.
* **Structured Data Management:** Converted the raw data into an **Excel Table** for efficient data updates.
* **Dynamic Dashboard Creation:** Designed an interactive dashboard with:
    * Line chart for sales over time (by coffee type).
    * Bar charts for sales by country and top customers.
* **Interactive Controls:** Implemented **slicers** (Roast Type, Size, Loyalty Card) and a **timeline** (Order Date) for dynamic data filtering.
* **Dashboard Aesthetics:** Customized chart designs and control styling for a professional and intuitive user experience.

## Excel Functions & Applications Used:

* **Functions:**
    * `XLOOKUP`
    * `INDEX`
    * `MATCH`
    * `IF`
* **Applications/Features:**
    * Pivot Tables
    * Pivot Charts
    * Slicers
    * Timelines
    * Excel Tables
    * Custom Number Formatting
    * Remove Duplicates
 
  ## Dataset Used
  - <a href="https://github.com/SreeragUnniACCA/Coffee-sales-DA---excel/blob/main/coffeeOrdersData.xlsx"> Dataset </a>
  ## Process
  This project involved a systematic approach, progressing from raw data to a fully interactive dashboard:

1.  **Data Acquisition & Consolidation:** I began by gathering raw sales data from separate `Orders`, `Customers`, and `Products` worksheets. This information was then consolidated into a single, unified dataset within Excel.
2.  **Data Transformation & Cleaning:**
    * **Lookups:** I utilized `XLOOKUP` to efficiently retrieve customer names, email addresses, and countries. For product details like coffee type, roast type, size, and unit price, I employed a dynamic `INDEX/MATCH` formula.
    * **Calculations:** A `Sales` column was calculated by multiplying the `Unit Price` by `Quantity`.
    * **Data Enhancement:** Helper columns were created to convert abbreviated coffee and roast types into their full, more readable names using `IF` functions.
    * **Formatting:** Dates, product sizes (e.g., in kilos), and currency values (USD) were custom formatted for improved clarity. I also addressed blank values resulting from lookups, ensuring a clean dataset.
    * **Deduplication:** A final check was performed to confirm the absence of duplicate entries.
3.  **Data Structuring:** The entire consolidated dataset was converted into an **Excel Table** (using `Ctrl + T`). This crucial step enables dynamic range expansion and ensures seamless, automatic updates for linked pivot tables and charts.
4.  **Dashboard Component Creation:** I then created individual **Pivot Tables** to summarize key sales metrics across various dimensions, such as sales over time, by coffee type, by country, and by customer. These pivot tables served as the foundation for the **Pivot Charts** (line charts and bar charts) that visualize the data.
5.  **Adding Interactivity:** To make the dashboard dynamic, I integrated **Slicers** for filtering data by `Roast Type`, `Package Size`, and `Loyalty Card` status. Additionally, an **Order Date Timeline** was implemented to allow users to easily filter all dashboard visuals by specific date ranges.
6.  **Aesthetic Refinement:** The final step involved customizing the visual appearance of the charts, slicers, and the timeline. This included applying consistent color schemes, fonts, and styling to create a polished, professional, and intuitive user interface.

## Dashboard
- <a href="https://github.com/SreeragUnniACCA/Coffee-sales-DA---excel/blob/main/dashboard.png"> Dashboard </a>
