 Project Objective
The goal was to identify factors contributing to poor financial performance and recommend data-driven strategies to improve occupancy, revenue, and pricing alignment across hotel properties.

 Dataset Description
The dataset consists of:

2 Fact Tables:

fact_bookings: Individual booking-level details including check-in/check-out dates, revenue, and booking status

fact_aggregated_bookings: Daily booking summaries per hotel, room type, and capacity

3 Dimension Tables:

dim_hotels: Hotel-level metadata (location, category)

dim_rooms: Room category mapping

dim_date: Calendar reference (week, day type)

 Tools & Technologies
Power BI: For dashboard development, KPI creation, and visualization

Power Query: For data cleaning and transformation

DAX: To compute industry-specific KPIs like ADR, RevPAR, % Utilization, % Cancellation

SQL: For validation of visual metrics and to ensure data accuracy

 Process
Data Cleaning: Removed irrelevant columns, corrected data types, and handled missing values using Power Query.

Data Modeling: Established relationships between dimension and fact tables using appropriate primary and foreign keys.

KPI Creation: Created key hospitality metrics like:

ADR (Average Daily Rate)

RevPAR (Revenue per Available Room)

% Room Utilization

% Cancellations / No-shows / Completed Bookings

SQL Validation: Wrote and executed SQL queries to validate Power BI metrics, ensuring the dashboard’s reliability.

Insight Generation: Performed exploratory data analysis to identify patterns and anomalies in hotel performance.

 Key Insights
Pricing Mismatch: High-rated hotels were underperforming in revenue vs. lower-rated ones, indicating poor value perception and pricing misalignment.

No Dynamic Pricing: ADR and RevPAR trends didn’t align during high-demand periods, suggesting lack of demand-based pricing strategies.

Geographic Trends: Delhi hotels outperformed others in occupancy and ratings — recommended benchmarking these practices across regions.

Low Occupancy Zones: Multiple hotels in Mumbai consistently had <50% occupancy — flagged for possible restructuring or divestment.

 Business Impact
Informed revenue optimization strategies using data-driven insights

Recommended dynamic pricing adoption for better demand capture

Suggested geographic benchmarking to scale best practices

Helped identify cost-heavy underperforming assets for potential divestment

 Learnings
Deepened understanding of hospitality KPIs and their real-world application

Strengthened skills in Power BI data modeling, DAX, and SQL-driven validation

Learned how to align technical output with business value and strategic impact

