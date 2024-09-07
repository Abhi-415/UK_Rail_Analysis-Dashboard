# UK_Rail_Analysis-Dashboard
## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Analysis & Conclusions](#analysis--conclusions)
  - [Popular Routes](#popular-routes)
  - [Peak Travel Times](#peak-travel-times)
  - [Ticket Type & Class Performance](#ticket-type--class-performance)
  - [On-time Performance & Contributing Factors](#on-time-performance--contributing-factors)
- [Contributing](#contributing)
  
## Project Overview
This project involves the creation of a comprehensive dashboard to analyze key performance indicators (KPIs) for National Rail. The dashboard is designed to help identify popular routes, determine peak travel times, analyze revenue from different ticket types and classes, and diagnose on-time performance and contributing factors to delays and cancellations. 

The dashboard includes calculated measures such as Refunds, Average Refunds, Average Revenue, Refund Rate, Sales Quantity, Total Refunds, and Total Revenue.

## Key Features
- **Popular Routes Analysis**: Identify the top-performing routes in terms of revenue and ticket sales.
- **Peak Travel Times**: Discover the most common travel times based on revenue and ticket sales, segmented by weekdays and weekends.
- **Revenue Breakdown**: Analyze revenue contributions from different ticket types and classes, including insights on refund rates.
- **On-time Performance Diagnosis**: Examine the causes of delays and cancellations, with a focus on contributing factors and their financial impact.

## Technologies Used
- **Power BI**: Dashboard creation and visualization
- **SQL**: Data querying and analysis
- **Python**: Data preprocessing and analysis
- **Excel/CSV**: Data handling and import

## Setup Instructions
1. **Prepare the data**
   - Ensure you have the required dataset (e.g., rail traffic data, ticket sales data).
   - Place the dataset in the appropriate directory.
2. **Open the Dashboard**
   - Open the Power BI dashboard file (NationalRailAnalysis.pbix) in Power BI Desktop.
   - Review and modify the data source paths if necessary to match your system.
## Usage
1. **Open Power BI Desktop** and load the pbix file.
2. **Interact with the Dashboard:**
   - Use filters to adjust the views based on routes, ticket types, time periods, and other criteria.
   - Explore the different tabs for detailed insights:
     - **Route Performance:** View KPIs related to the most popular routes by revenue and ticket sales.
     - **Ticket Analysis:** Dive into the impact of different ticket types and classes on revenue and refunds.
     - **Travel Trends:** Analyze peak travel times and how they vary across weekdays and weekends.
     - **Train Performance:** Examine the on-time performance of trains and the reasons for delays and cancellations.
## Analysis & Conclusions
### Popular Routes
- **Revenue:**
  - London Kings Cross - York
  - Liverpool Lime Street - London Euston
  - London Paddington - Reading
- **Ticket Sales:**
  - Manchester Piccadilly - Liverpool Lime Street
  - London Euston - Birmingham New Street
  - London Kings Cross - York
### Peak Travel Times
- **Revenue:** The most popular time to travel is 08:00, regardless of the day of the week.
- **Ticket Sales:** The most popular time to travel is 18:45. Weekdays dominate both journeys and revenue, highlighting the need to maintain weekday operations.
### Ticket Type & Class Performance
- **Standard Class:** Contributes 80% of total revenue. Increasing first-class passengers could result in higher overall revenue.
- **Advance Tickets:** Provide the majority of revenue but at a lower average per ticket compared to Anytime tickets. Adjustments to advance ticket pricing could improve revenue.
### On-time Performance & Contributing Factors
- **On-time Performance:** Most journeys are on-time, which is a positive takeaway.
- **Contributing Factors:** Weather is the leading cause of delays and cancellations but results in fewer refund requests. Staffing and technical issues contribute significantly to refunds, indicating areas for improvement.
## Contributing
If you'd like to contribute to this project, please fork the repository, create a new branch, and submit a pull request.
