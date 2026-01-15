# 🚕 OLA-Ride-Data-Analysis-Dashboard

### 1. Project Title / Headline
OLA Ride Data Analysis – Booking, Revenue, Cancellation & Ratings Insights.
An end-to-end analytical dashboard built using SQL, Excel, and Power BI to uncover ride demand patterns, revenue drivers, cancellation behavior and customer/driver satisfaction across multiple vehicle types.

### 2. Short Description / Purpose
The OLA Ride Data Analysis Dashboard is an interactive business intelligence solution designed to analyze large-scale ride-hailing data. It enables stakeholders to monitor booking performance, revenue trends, cancellation reasons, vehicle-wise efficiency, and rating patterns to support data-driven operational and strategic decisions.

### 3. Tech Stack
The dashboard was developed using the following tools and technologies:<br>
🗄️ SQL – Used to extract, transform, and optimize queries on 1M+ ride records.<br>
📊 Power BI Desktop – Primary tool for interactive dashboard creation and storytelling.<br>
📂 Microsoft Excel – Data cleaning, validation, pivot tables, and statistical analysis.<br>
🔄 Power Query – Data transformation, normalization, and preprocessing.<br>
🧠 DAX (Data Analysis Expressions) – Created KPIs, calculated measures, and dynamic filters.<br>
🧩 Data Modeling – Structured relationships between bookings, vehicles, payments, and ratings.<br>
📁 File Formats – .pbix for development and .png for dashboard previews.

### 4. Data Source
Dataset Type: Simulated / Business-style OLA ride booking data.
Data Volume: 1M+ rows of ride-level data.
Key Attributes:
Booking date & time,
Vehicle type,
Booking value & payment method,
Ride distance,
Booking status (Success / Cancelled / Driver Not Found),
Cancellation reasons (Customer & Driver),
Driver & customer ratings

### 5. Features / Highlights
• Business Problem
Ride-hailing platforms face operational challenges such as:
High cancellation rates,
Uneven demand across vehicle types,
Revenue leakage due to failed bookings,
Inconsistent customer and driver experience,
Analyzing raw transactional data makes it difficult to identify actionable insights quickly.

• Goal of the Dashboard
To build a centralized analytical dashboard that:
Tracks overall booking and revenue performance,
Identifies peak demand and ride behavior trends,
Analyzes cancellations by customers and drivers,
Evaluates vehicle-wise efficiency and distance metrics,
Measures customer and driver satisfaction using ratings,

• Walkthrough of Key Visuals
🔹 Overall Performance (Overall Section)
Total Bookings: 20,407,
Total Booking Value: ₹7M,
Booking Status Breakdown:
Successful bookings,
Cancellations by customer,
Cancellations by driver,
Driver not found

Ride Volume Over Time (Line Chart):
Identifies daily demand fluctuations,
Highlights peak and low-demand periods,

🔹 Vehicle Type Analysis (Vehicle Type Section)
Vehicle-wise comparison for:
Total booking value,
Successful booking value,
Average distance travelled,
Total distance covered

Vehicle categories include:
Prime Sedan, Prime SUV, Prime Plus,
Mini, Auto, Bike, E-Bike,
Helps assess which vehicle types drive higher value and efficiency

🔹 Revenue Insights (Revenue Section)
Revenue by Payment Method (Bar Chart):
Cash,
UPI,
Credit Card,
Debit Card

Top 5 Customers Table:
Identifies high-value customers by booking value,
Ride Distance Distribution per Day:
Analyzes operational load and distance trends

🔹 Cancellation Analysis (Cancellation Section)
KPIs:
Total Bookings: 20,407
Successful Bookings: 12,652
Cancelled Bookings: 5,735
Cancellation Rate: 28.1%

Cancelled Rides by Customers (Pie Chart):
Driver not moving toward location,
Driver asked to cancel,
Change of plans,
AC not working,
Wrong address,

Cancelled Rides by Drivers (Pie Chart):
Personal or car-related issues,
Customer-related issues,
Over-capacity or policy violations

🔹 Ratings Analysis (Ratings Section)
Driver Ratings by Vehicle Type,
Customer Ratings by Vehicle Type,
Enables comparison of service quality across different ride categories,
Identifies areas for experience improvement

• Business Impact & Insights
📈 Demand Optimization:
Identified peak ride demand periods, enabling better pricing and fleet allocation strategies

💰 Revenue Growth Potential:
Insights support pricing and operational optimization with an estimated 10–15% revenue improvement potential

❌ Cancellation Reduction:
Root-cause analysis of cancellations helps reduce failed bookings and improve service reliability

⭐ Experience Improvement:
Ratings analysis highlights vehicle categories needing quality enhancement

🧠 End-to-End Analytics Demonstration:
Showcases SQL + Excel + Power BI workflow used in real business scenarios

### 6. Screenshots / Demo
📸 Dashboard Preview
<img width="1389" height="793" alt="OLA Ride Data Analysis Dashboard Screenshot Page 1 (Overall Section)" src="https://github.com/user-attachments/assets/a166c2be-b69d-4abb-a555-1444e7d58365" />
<img width="1370" height="794" alt="OLA Ride Data Analysis Dashboard Screenshot Page 2 (Vehicle Type Section)" src="https://github.com/user-attachments/assets/46fae98e-81db-4cc3-a608-61830e46abad" />
<img width="1389" height="790" alt="OLA Ride Data Analysis Dashboard Screenshot Page 3 (Revenue Section)" src="https://github.com/user-attachments/assets/dc5f658b-0895-4a20-84a3-a549e83a17ae" />
<img width="1392" height="793" alt="OLA Ride Data Analysis Dashboard Screenshot Page 4 (Cancellation Section)" src="https://github.com/user-attachments/assets/9f865d13-bf04-45dd-8fa3-611e9a55f64c" />
<img width="1389" height="794" alt="OLA Ride Data Analysis Dashboard Screenshot Page 5 (Ratings Section)" src="https://github.com/user-attachments/assets/0312a44b-f1df-4c44-ba57-556df8b253ee" />
