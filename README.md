## 📌 Project Title
Blinket Sales Performance & Product Analytics

## 📊 Overview
This project analyzes Blinket's retail sales data to:

Understand item-level and outlet-level sales performance

Clean and prepare data for meaningful insights

Visualize KPIs using Power BI for management and operations

## 📦 Blinket-Sales-EDA
├── Blinket EDA.ipynb             # Python EDA and Data Cleaning
├── Blinket Dataset EDA.xlsx      # Cleaned and processed dataset
├── Blinket Report.pbix           # Power BI Dashboard
├── README.md                     # Project Overview and Documentation

## 🧾 Column Descriptions

| Column Name                   | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ |
| **S.NO**                      | Serial number (index)                                        |
| **Item Fat Content**          | Type of fat content (Low Fat / Regular Fat)                  |
| **Item Identifier**           | Unique item code                                             |
| **Item Type**                 | Category of the item (e.g., Frozen Foods, Dairy)             |
| **Outlet Establishment Year** | Year when the outlet was established                         |
| **Outlet Identifier**         | Unique ID for each store                                     |
| **Outlet Location Type**      | Tier of city (Tier 1, 2, 3)                                  |
| **Outlet Size**               | Size of the outlet (Small, Medium, High)                     |
| **Outlet Type**               | Type of retail format (Grocery Store, Supermarket Type1/2/3) |
| **Item Visibility**           | How visible the item is on the shelf (0 to 1)                |
| **Item Weight**               | Weight of the item (in kg)                                   |
| **Sales**                     | Total sales value of the item                                |
| **Rating**                    | Customer rating of the product (1 to 5)                      |


## 🧹 EDA & Data Cleaning Highlights (Blinket EDA.ipynb)
Standardized Categorical Fields: Cleaned inconsistencies in Item Fat Content
Missing Values: Handled Item Weight nulls with mean/median imputation
Outlier Treatment: Analyzed Item Visibility and Sales distributions
Feature Engineering:
 1.Created new metrics such as Sales per Item Weight
 2.Categorized Item Type groups if needed

## 📈 Power BI Dashboard Summary (Blinket Report.pbix)
Includes interactive visualizations like:

🔹 Total Sales by Item Type

🔹 Outlet Sales Comparison

🔹 Average Rating & Sales Distribution

🔹 Sales Trend by Year of Establishment

🔹 Sales by Outlet Size/Type

Slicers used:

Item Fat Content,Outlet Type,Item Type,Outlet Establishment Year

## KPIs:

Total Sales
Average Rating
Item Category Share

## 💡 Key Insights
Supermarket Type1 outlets contribute the highest sales volume.

Low Fat items are more frequently purchased.

Newer outlets (post-2015) show increasing sales trends.

Items with high visibility do not always correspond to high sales — indicates product placement isn't the only factor.

## 🛠 Tools Used
Python: pandas, matplotlib, seaborn

Power BI: DAX, interactive charts

Excel: Data pre-processing

