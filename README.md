# EDA-Hospitality-Domain


# 🏨 Hotel Booking Data Analysis (EDA using Python)

## 📌 Project Overview
This project focuses on analyzing hotel booking data to uncover key insights related to occupancy rates, revenue trends, and customer behavior. The objective is to help hotel management make data-driven decisions to improve business performance.

---

## 📂 Dataset Description
The analysis is based on multiple datasets:

- **fact_bookings.csv** → Booking-level data (guests, revenue, platform)
- **fact_aggregated_bookings.csv** → Aggregated booking & capacity data
- **dim_hotels.csv** → Hotel details (city, category)
- **dim_rooms.csv** → Room category mapping
- **dim_date.csv** → Date & time-related information

---

## ⚙️ Tools & Technologies Used
- Python
- Pandas & NumPy (Data manipulation)
- Matplotlib & Seaborn (Visualization)
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1️⃣ Data Import & Exploration
- Loaded multiple datasets using Pandas
- Explored structure using `.head()`, `.info()`, `.describe()`
- Analyzed categorical distributions (booking platform, room category)

---

### 2️⃣ Data Cleaning
- Removed invalid records (e.g., negative number of guests)
- Handled outliers in revenue using statistical method (mean ± 3*std)
- Treated missing values appropriately:
  - Retained missing ratings due to high volume of null values
  - Filled missing capacity using median

---

### 3️⃣ Data Transformation
- Created new feature: **Occupancy Percentage**
  - Formula: successful_bookings / capacity
- Converted occupancy into percentage format
- Merged datasets to enrich data:
  - Room categories → Room class
  - Property details → City & category
  - Date dataset → Weekday vs Weekend

---

### 4️⃣ Exploratory Data Analysis (EDA)
Performed analysis to answer key business questions:

- Average occupancy rate by room category
- Occupancy trends across cities
- Weekend vs weekday performance
- Monthly occupancy trends
- Revenue contribution by city and platform

---

## 📊 Key Insights

- 🟢 **Delhi has the highest occupancy rate (~61%)**, indicating strong demand  
- 🟢 **Weekend occupancy (~72%) is significantly higher than weekdays (~50%)**  
- 🟢 **Mumbai generates the highest revenue among all cities**  
- 🟢 **Premium and Presidential rooms contribute higher revenue**  
- 🟢 Certain booking platforms contribute significantly more bookings  

---

## 💡 Business Recommendations

- 📈 Increase pricing during weekends due to higher demand  
- 📉 Improve weekday occupancy through targeted promotions  
- 🏙 Expand hotel capacity in high-demand cities like Delhi  
- 🛏 Promote premium room categories to maximize revenue  
- 📢 Focus marketing on high-performing booking platforms  

---

## 📌 Conclusion
This analysis provides actionable insights into hotel performance, customer trends, and revenue drivers. These insights can help stakeholders optimize pricing strategies, improve occupancy rates, and enhance overall business efficiency.

---

## 🚀 Future Improvements
- Build an interactive **Power BI dashboard**
- Perform predictive analysis (forecast occupancy/revenue)
- Apply customer segmentation techniques

---

## 📎 Author
**Pruthviraj Kadam**  
Aspiring Data Analyst skilled in Python, SQL, Power BI, Statistics and Data Analysis

