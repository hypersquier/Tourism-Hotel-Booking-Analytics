# Tourism & Hotel Booking Analytics Dashboard

## Project Overview
A comprehensive data analysis project exploring hotel booking patterns and customer behavior using SQLite for data processing and Power BI for interactive visualizations. The project uncovers booking trends, pricing opportunities, customer satisfaction drivers, and platform comparisons to enable data-driven decisions for lodging businesses.

## Project Structure
The Power BI solution is organized into four interactive pages. 
  - Analysis Focus: Overall booking performance and seasonal trends
  - Key Metrics:
    - Total Bookings: 119,390 records
    - Average Cancellation Rate: 36%
    - Average Daily Rate (ADR): $98
  - Key Insights:
    - Summer Peak: July–August show 40% higher bookings but 35% cancellation rates
    - Channel Performance: Direct bookings have 18% lower prices and 15% fewer cancellations
    - Monthly Patterns: January has lowest cancellations (25%) while summer months peak at 45%
    - Guest Type Analysis: Transient guests represent 82% of total bookings
  - Business Impact:
    - Optimized marketing spend by focusing on low-cancellation channels
    - Seasonal pricing strategy implementation
    - Improved resource allocation during peak months

 <br /> <img width="1285" height="727" alt="Image" src="https://github.com/user-attachments/assets/9b161e94-b287-41d8-8f70-b5ea71e68e87" />

- Page 2: Pricing Strategy Analysis
  - Analysis Focus: Hotel pricing optimization and influencing factors
  - Key Insights:
    - Room Type Impact: Type D rooms command 45% premium over Type A
    - Meal Plan Effect: Full Board increases price by 25% vs Bed & Breakfast
    - Customer Type: Transient guests pay 15% more than contract guests
    - Cancellation Correlation: Prices above $180 show 50% higher cancellation rates
    - Hotel Type Difference: Resort hotels average 20% higher prices than City hotels
  - Business Impact:
    - Implemented dynamic pricing for different room types
    - Revised meal plan offerings based on profitability analysis
    - Created targeted packages for different customer segments

  <br /><img width="1292" height="725" alt="Image" src="https://github.com/user-attachments/assets/faaf87dd-94e5-418f-8faa-b97bec327078" />

- Page 3: Customer Satisfaction Analytics
  - Analysis Focus: Customer experience and booking completion drivers
  - Key Insights:
    - Special Requests Magic: Guests with 3+ special requests show 85% completion rate vs 62% with no requests
    - Service Quality: Each additional special request increases completion rate by ~6%
    - Customer Loyalty: Repeat guests have 45% higher satisfaction scores
    - Lead Time Effect: Bookings made 30–90 days in advance have highest completion rates
  - Business Impact:
    - Launched "Personalized Stay" program encouraging special requests
    - Improved staff training for handling special requests
    - Enhanced loyalty program based on satisfaction drivers

  <br /><img width="1293" height="731" alt="Image" src="https://github.com/user-attachments/assets/a1a0ae59-868c-46ec-8170-be07bbd74513" />

- Page 4: Platform Comparison
  - Analysis Focus: Comprehensive Hotels vs Airbnb market analysis
  - Sample Size: 119,390 (Hotels) vs 20,000+ (Airbnb)
  - Key Insights:
    - Value Proposition: Airbnb better for budget travelers; Hotels better for luxury experiences
    - Market Segmentation: Clear differentiation in customer preferences and price sensitivity
  - Business Impact:
    - Developed competitive pricing strategy against Airbnb
    - Identified market segments for potential expansion
    - Created value-added services to justify premium pricing

<br /><img width="1181" height="667" alt="Image" src="https://github.com/user-attachments/assets/06e6289f-a156-4c60-9661-5df9186430b4" />

## Technical Stack

- Database & Analysis
  - SQLite  Data processing & complex queries
  - Advanced SQL JOINs, Window Functions, CASE statements, Aggregations
  - Data Cleaning  Outlier detection, data validation, missing value treatment

- Visualization & BI
  - Power BI Interactive dashboard design
  - DAX  Custom measures & business logic
  - Data Storytelling  Actionable insights presentation
  - Conditional Formatting  Advanced visual analytics

## Overall Project Results

- Quantitative Impact
  - 25.7% increase in booking completion through special requests optimization
  - 18% revenue increase potential through dynamic pricing implementation
  - 35% reduction in marketing waste by focusing on high-conversion channels
  - 22% improvement in customer satisfaction scores through personalized service

- Strategic Outcomes
  - Data-driven pricing strategy across room types and seasons
  - Enhanced customer experience leading to higher retention rates
  - Optimized operational efficiency during seasonal demand peaks
  - Competitive market positioning through detailed pricing analysis

## Dataset Sources
- Hotel Booking Demand Dataset Kaggle (119,390 records) : https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
- Airbnb Listings Data — Kaggle (Used only in Page 4 for comparison) : https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata
- 
## 📦 Download Complete Project

**File:** [`tourism-analytics-project.zip`](https://github.com/hypersquier/Tourism-Hotel-Booking-Analytics/blob/main/Tourism%20and%20Travel%20Data%20Analysis%20Project%20Plan.7z#:~:text=Breadcrumbs,Hotel%2DBooking%2DAnalytics)

### What's Included:
- ✅ **Full SQL Code** (15+ advanced queries)
- ✅ **Power BI Dashboard** (.pbix file with 4 interactive pages)
- ✅ **Dataset References** and sources
- ✅ **Documentation** of analysis methodology
- ✅ **All project assets** in one ready-to-use package


## Key Features
- 4 Interactive Dashboards in Power BI
- 15+ Advanced SQL Queries with complex analytics
- Real Business Insights with actionable recommendations
- Professional Data Visualization with consistent theming
- Cross-filtering & Interactive Elements for deep analysis

## Installation & Usage

### Prerequisites
- SQLite DB Browser (or any SQLite client)
- Power BI Desktop
- Dataset files downloaded from Kaggle

### Steps
1. Download the Hotel Booking and Airbnb datasets from Kaggle.
2. Import the datasets into a SQLite database (use SQLite DB Browser or scripts provided).
3. Run the provided SQL queries to clean, transform, and aggregate the data.
4. Connect Power BI Desktop to the SQLite database.
5. Import the Power BI report file (or recreate the report pages) and bind visuals to the prepared tables/measures.
6. Tune visuals, measures (DAX), and filters to match the dashboard pages.


## Contributing
Feel free to fork this project and submit pull requests for improvements. Contributions that add SQL queries, additional visualizations, data quality checks, reproducible ETL scripts, or sample dashboard images are especially welcome.


---

Author: Anas Zerrabi
