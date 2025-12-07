# uber-data-analytics-powerbi
Power BI dashboard analyzing Uber ride data to uncover trip patterns, cancellation trends, customer experience, and revenue insights. Includes data preparation in Power Query, DAX-based KPIs, and multi-page interactive reporting.
1. Project Overview -
   This project focuses on analyzing Uber ride data to identify key operational insights such as peak demand trends, ride category performance, cancellation patterns, and customer experience scoring. The goal is to help business stakeholders improve service efficiency, customer satisfaction, and revenue performance.
2. Data Cleaning & Preparation (Power Query) - 
   Performed data preparation steps in Power Query, including:
   Formatting date/time fields
   Standardizing column types
   Handling missing or inconsistent values
   Creating relationships for a clean data model
   Preparing the dataset for DAX calculations and dashboarding
3. Dashboard Features - 
   The dashboard includes multiple analytical views covering:
   - Trip Analysis
     Total trips
     Trips by category (UberX, UberXL, etc.)
     Peak hours and peak days
     Distance and trip duration trends
   - Revenue Insights
     Revenue by category
     Revenue by time period
     Top revenue-generating ride types
     Average fare per trip
   - Cancellation Analysis
     Driver vs. customer cancellations
     Cancellation reasons
     Category-wise cancellation rate
     Impact of cancellations on daily operations
   - Customer Experience
     Ride ratings
     Average experience score
     Category-level rating comparison
4. DAX Measures Created - 
   Key measures developed using DAX include:
   Total Trips
   Total Revenue
   Average Rating
   Cancellation Rate
   Trips by Category
   Experience Score
5. Key Insights - 
  - Overview Page
   •	Booking & GMV Trends: Line and bar charts show monthly ride and revenue fluctuations.
   •	Revenue by Payment Method: Highlights UPI as the top contributor.
   •	Ratings Summary: Displays average customer and driver satisfaction.
  - Performance Page
    •	Fulfillment Funnel: Visualizes total bookings through completion and cancellation stages.
    •	Hourly Heatmap: Shows when cancellations spike during the day.
    •	VTAT/CTAT Trends: Identify time slots impacting trip duration and on-time pickups.
    •	Efficiency by Corridor: Highlights corridors with higher fulfillment efficiency.
  - Cancellation Page
    •	Efficiency by Corridor: Highlights corridors with higher fulfillment efficiency.
    •	Root Cause Discovery: Pinpoints top cancellation reasons (e.g., “Customer-related issues”).
    •	Money Impact: Shows direct GMV loss due to cancellations.
  - Experience Page
    •	Ratings Distribution: Bar chart compares ratings across vehicle types.
    •	Low Rating by Zone: Identifies areas with frequent poor experiences.
    •	Experience Change Chart: Tracks shifts from negative to positive experiences.
  - Revenue Page
    •	Top Revenue Corridors: Ranks locations contributing most GMV.
    •	Revenue by Vehicle Type: Identifies Auto and Bike as leading categories.
    •	Revenue per Payment Method: Confirms UPI as highest grossing mode.
    •	Profitability Curve: Shows long-distance rides generate better margins.
6. Recommended Action - 
    •	Drivers cancel most rides (72%) - Give rewards to reliable drivers and warn frequent cancellers.
    •	More cancellations in evening hours - Offer extra pay or bonuses for drivers at peak hours.
    •	Many customer-related cancellations - Improve pickup info and add quick driver contact option.
    •	Low ratings in some areas - Train drivers and fix pickup issues in those zones
    •	Long pickup delays - Improve map routes and pickup time accuracy.
    •	Some routes lose more money - Give incentives for top loss routes to increase trips.
    •	UPI gives highest revenue - Promote UPI payments with discounts or rewards.
    •	Long trips earn more profit - Give loyalty points or offers for long rides.


   
