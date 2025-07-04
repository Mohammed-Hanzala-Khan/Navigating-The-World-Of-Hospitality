# Hospitality-Data-Analysis

*Driving Data-Driven Decisions in Hotel Management Using Power BI, SAS Viya, and Python*

## Tools & Technologies Used

- **Power BI** for interactive dashboards and visualization
- **SAS Viya** for advanced data cleaning and analytics
- **Python** for descriptive statistics and preparation
- **Excel** for initial data cleaning

---

## Table of Contents

- [Project Objective](#project-objective)
- [Dataset](#dataset)
- [Dataset Cleaning](#dataset-cleaning)
- [Visualization & Analysis](#visualization--analysis)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Future Work](#future-work)

---

## Key Results

- Analyzed **119,390 hotel bookings** to extract customer and operational insights.
- Built **four interactive Power BI dashboards** (Product, Customer, Customer Behavior, Hospitality).
- Identified peak seasons, ADR patterns, and customer retention behavior.
- Recommended **data-driven strategies** for pricing, inventory, and customer experience enhancement.

---

## Dashboard Preview

### **Product Analysis Dashboard**

An interactive dashboard was created to analyze the distribution of city and resort hotels, market segments, customer wait times by arrival month, and room type preferences. A Geo Map displays the global distribution and booking volumes for each hotel type, while a TreeMap visualizes customer wait times across market segments. Bar charts highlight peak booking months and the most popular room types by segment and country.

![Image](https://github.com/Mohammed-Hanzala-Khan/Navigating-The-World-Of-Hospitality/blob/main/Dashboards/Product%20Analysis%20Dashboard.png)

---

### **Customer Analysis Dashboard**

An interactive Customer Analysis Dashboard visualizes hotel bookings by customer type and market segment over the years. It includes bar charts showing annual customer distribution, a pie chart for market segment share, and a line graph tracking ADR trends over time. Additional charts display the counts of adults, children, and babies across segments, providing clear insights into guest distribution and evolving booking dynamics.

![Image](https://github.com/Mohammed-Hanzala-Khan/Navigating-The-World-Of-Hospitality/blob/main/Dashboards/Customer%20Analysis%20Dashboard.png)

---

### Customer Behaviour Dashboard

A dynamic Customer Behavior Dashboard using a Butterfly Graph, TreeMap, Heat Map, and Bar Graph to analyze booking patterns, cancellations, changes, and retention across market segments. The Butterfly Graph and TreeMap highlight cancellation patterns by customer type, the Heat Map reveals which segments are prone to booking changes, and the Bar Graph tracks retention trends over the years for clear, actionable insights.

![Image](https://github.com/Mohammed-Hanzala-Khan/Navigating-The-World-Of-Hospitality/blob/main/Dashboards/Customer%20Behaviour%20Dashboard.png)

---

### Hospitality Dashboard

The Hospitality Dashboard leverages customer data to assess revenue and satisfaction using clear bar graphs. It analyzes ADR distribution across deposit types, identifies peak months for bookings, tracks meal type popularity, and explores the correlation between lead time and ADR for actionable operational insights.

![Image](https://github.com/Mohammed-Hanzala-Khan/Navigating-The-World-Of-Hospitality/blob/main/Dashboards/Hospitality%20Dashboard.png)

---

## Project Objective

To leverage business analytics and data visualization in uncovering customer behavior, seasonality trends, and operational insights in the hospitality industry, enabling **data-driven decisions for pricing, inventory, and customer satisfaction improvements.**

---

## Dataset

### Source

A hotel booking dataset with **119,390 records** including:

- Booking details (dates, lead time, ADR)
- Market segment, customer type, country
- Room type, deposit type, cancellation
- Meal type, special requests, stay length

---

## Dataset Cleaning

Performed using **Excel** and **SAS Viya**:
- Converted 3-letter country codes to 2-letter codes for SAS mapping.
- Removed outliers in ADR (>198) and lead time (>354).
- Transformed numeric to categorical for dashboard filtering.
- Removed duplicates and corrected inconsistencies for analysis readiness.

---

## Visualization & Analysis

### Power BI Dashboards

- **Product Analysis Dashboard:** Shows hotel type distribution, peak months, room popularity, and geo-distribution of bookings.
- **Customer Analysis Dashboard:** Visualizes customer types, market segments, and ADR trends over years.
- **Customer Behavior Dashboard:** Analyzes cancellations, booking changes, and retention rates across segments.
- **Hospitality Dashboard:** Examines ADR by deposit type, meal preferences, lead time correlation, and monthly booking trends.

### Python Descriptive Statistics

- Used `.describe()` to calculate **mean ADR (101.8)** and **mean lead time (104 days)**.
- Established baselines for dashboards and insight generation.

---

## Key Insights

- **Global Distribution:** City hotels are globally spread (Angola, Canada, Brazil, Russia, China, Australia), while resorts are Europe-focused, with **Portugal as the busiest location**.
- **Seasonality:** Peak waiting list months are April, May, January (City Hotels), and October, December (Resorts).
- **Room Preference:** **Room Type A** dominates city hotel bookings, **Room Type E** is most popular in resorts.
- **Customer Trends:** Sharp increase in transient customers and online bookings, showing a shift towards flexibility and convenience.
- **Retention:** Corporate customers have the highest repeat rates (**27.8%**), while online bookings show low retention (**1.09%**).
- **Pricing Patterns:** ADR decreases as lead time increases; "No deposit" bookings yield the highest ADR.
- **Cancellation Risks:** Contract customers, especially under group segments, exhibit the highest cancellation rates.

---

## Recommendations

- **Optimize Inventory:** Increase availability of high-demand rooms (e.g., Room Type A).
- **Boost Off-Season Occupancy:** Offer discounts, loyalty programs, and promotions during low seasons.
- **Improve Booking Experience:** Build a responsive, intuitive online booking system for rising transient and online customers.
- **Recover Lost Segments:** Tailor marketing to contract and group customers, collaborating with agencies to regain this segment.
- **Dynamic Pricing:** Use AI-powered models to adjust ADR based on demand and seasonality, improving financial performance.
- **Enhance Service Quality:** Train staff for handling booking changes efficiently, ensuring smooth guest experiences and loyalty.

---

## Future Work

- Deploy **predictive models** for cancellation and ADR forecasting using regression and ensemble methods.
- Integrate **real-time booking data** into dashboards for operational insights.
- Conduct **feature engineering and hyperparameter tuning** for improved model accuracy.
- Expand into **revenue forecasting** and dynamic pricing simulations for management teams.

---
