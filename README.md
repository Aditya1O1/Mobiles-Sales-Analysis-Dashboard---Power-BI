

# 📊 Mobile Sales Analysis Dashboard (Power BI)

This project presents a fully interactive and insightful **Mobile Sales Dashboard** built using **Power BI**. The dashboard allows stakeholders to analyze key sales performance metrics such as total sales, quantity sold, brand performance, payment methods, and regional distribution.

> 🚀 Purpose: To empower data-driven decisions in the mobile retail domain by uncovering actionable insights through intuitive visual storytelling.

---


> 🚧 **Project Development Log – 3-Day Progress**
This project was developed from scratch over a span of 3 days to ensure originality and depth of understanding. Below is a breakdown of the effort and progress made each day:

### 📅 Day 1 – Data Understanding, Cleaning & Measure Setup

- 🧹 Performed essential **ETL operations** before importing into Power BI:
  - Cleaned and standardized categorical fields like the `Day` column (e.g., replacing "Mon", "Tue" with full names like "Monday", "Tuesday").
  - Merged separate `Date`, `Month`, and `Year` columns into a single **custom Date column** using Power Query Editor's `Custom Column` formula.
  - Changed data types appropriately for all columns (e.g., numeric, date, text).
  - Removed redundant columns post-transformation to maintain a tidy and optimized dataset structure.

- 📊 Identified and outlined core business KPIs:
  - `Total Sales`, `Total Quantity`, `Transactions`, and `Average Sales per Transaction`.

- 📥 Imported the transformed dataset into Power BI.
- ➕ Built **4 key DAX measures** to support dashboard insights:
  - `Total Sales` using `SUMX(Units Sold * Price per Unit)`
  - `Total Quantity` using `SUM`
  - `Transactions` using `COUNTROWS`
  - `Average` using `DIVIDE(Total Sales, Transactions)`

- 🧠 Planned the overall dashboard layout structure, including KPI cards, slicers, and supporting visuals across multiple dimensions like City, Brand, Model, and Payment Method.

📸 **Original vs Transformed Data**

Original Data:
![Screenshot (3307)](https://github.com/user-attachments/assets/65bed330-e7f4-47fa-b7a7-833cb98aaf64)

![Screenshot (3308)](https://github.com/user-attachments/assets/f379ffb8-d2f3-4696-b22e-358fe74b020d)

Transformed Data:

![Screenshot (3306)](https://github.com/user-attachments/assets/78a4dad3-5951-452d-8058-050169deda56)


Power BI Dashboard Interface Initial Work:

![Screenshot (3302)](https://github.com/user-attachments/assets/6a2a9dd8-94fa-420b-9e6c-81e718c5f2aa)


### 📅 Day 2 – Dashboard Design and Visual Development
- Added KPI cards for Total Sales, Quantity, Transactions, and Average Sales.
- Created slicers for Month.
- Set up visual styling with a custom color palette and formatting.
- Verified data fields and began placing chart visuals.
![Screenshot (3303)](https://github.com/user-attachments/assets/78565448-428e-4060-92e9-bc4829b2ed10)


### 📅 Day 3 – Final Visuals, Insight Extraction & Polish

- Added all final visuals:
- Created slicers for Mobile Model, Brand, Payment Method, and Day Name.
  - Bar chart: **Total Sales by City**
  - Line chart: **Total Quantity by Day**
  - Pie chart: **Payment Method Distribution**
  - Horizontal bar: **Customer Ratings**
  - Area chart: **Sales by Day Name**
- Applied DAX measures and conditional formatting.
- Extracted actionable insights:
  - Delhi topped sales with ₹18M
  - UPI accounted for 25%+ of total transactions
  - Peak sales recorded on **Friday** (₹10.3M)
- Final alignment, tooltips, and dashboard polish for release.

![Screenshot (3304)](https://github.com/user-attachments/assets/59485e4d-3b27-4c4e-b5e2-42b3395c9a4f)

(Final Dashboard)
![Screenshot (3305)](https://github.com/user-attachments/assets/22163f51-a239-4d89-a676-35119e3db3c7)   


🧠 **Total Effort:** ~15+ hours of hands-on work, entirely original and customized for mobile sales analysis.


---

## 📦 Dataset Overview

The dataset used contains transactional records of mobile sales across different Indian cities, including the following fields:

- `Date` and `Month`
- `City`
- `Mobile Model`
- `Brand`
- `Payment Method`
- `Quantity`
- `Total Sales`
- `Transaction ID`
- `Customer Ratings`

---

## 🧩 Dashboard Components

### 1. **KPI Cards**
Displays high-level business metrics:
- **Total Sales**: ₹57M
- **Total Quantity Sold**: 2K
- **Total Transactions**: 315
- **Average Sales per Transaction**: ₹38K

> 💡 Helps managers get a quick snapshot of business performance.

---

### 2. **Filters / Slicers**
- **Month selector** (vertical slicer for Jan–Dec)
- **Dropdowns for:**
  - Brand
  - Mobile Model
  - Payment Method
  - Day of the Week

> 🎯 Empowers users to explore and drill down data dynamically.

---

### 3. **Visualizations**

#### 📌 Total Sales by City
- **Visual**: Horizontal Bar Chart
- **Insight**: Delhi leads with ₹16M, followed by Mumbai, Hyderabad, and Indore.

#### 📈 Total Quantity by Day
- **Visual**: Line Chart
- **Insight**: Highlights daily quantity trends and peak sales days.

#### ⭐ Customer Ratings
- **Visual**: Bar Chart
- **Insight**: Shows distribution of customer satisfaction levels.

#### 💳 Transactions by Payment Method
- **Visual**: Pie Chart
- **Insight**: UPI (29%) and Credit Cards dominate payment preferences.

#### 📱 Total Sales by Mobile Model
- **Visual**: Horizontal Bar Chart
- **Insight**: Galaxy S21 and iPhone SE are top-performing models.

#### 📅 Total Sales by Day Name
- **Visual**: Area Chart
- **Insight**: Sales peak on Saturdays (₹10M), lowest on Tuesday.

#### 🏷️ Brand-wise Summary Table
- **Columns**: Brand, Total Sales, Quantity, Transactions
- **Insight**: Apple, Samsung, and Vivo lead in total revenue.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query Editor** – for data cleaning and transformation
- **DAX** – for custom KPIs and calculations
- **Data Modeling** – relationships across city, brand, model tables
- **Interactive Visuals** – KPI Cards, Line, Pie, Bar, Area Charts

---

## 📈 Business Insights Derived

- **Regional Targeting**: Delhi has the highest market potential with ₹16M in sales.
- **Payment Trends**: UPI is the most used method, indicating a mobile-first audience.
- **Day Optimization**: Saturday performs best; campaigns can be targeted accordingly.
- **Product Strategy**: Galaxy S21 and iPhone SE are star performers.
- **Customer Satisfaction**: Insights from rating distribution can guide service improvements.

---

## 🤝 Value Delivered

- Simplifies sales performance tracking for non-technical stakeholders.
- Enables management to make quick, data-backed decisions.
- Highlights performance gaps across cities, brands, and days.
- Supports inventory planning and regional marketing strategies.

---

## 📷 Screenshots

> 📌 Add your screenshot in `Screenshots/` folder and update the path below.

![Dashboard Overview]


![Screenshot (3305)](https://github.com/user-attachments/assets/054ea98d-925d-4109-b5f2-df29f1ddd153)

---
## ▶️ How to Use

1. Download or clone this repository.
2. Open `Mobile_Sales_Analysis.pbix` in Power BI Desktop.
3. Connect to the dataset (`sales_data.xlsx`) if required.
4. Use slicers and visuals to explore insights interactively.

---


---

## 📧 Contact

**Aditya Kumar Pandey**  
MCA, IIIT Bhagalpur  
📧 aditya.240201001@iiitbh.ac.in  
📍 Bhagalpur, Bihar, India

---

## 🏷️ Tags
`Power BI` `Data Visualization` `Sales Dashboard` `Mobile Market Analysis` `DAX` `Interactive Reports` `Business Intelligence`



