# New-York-City-Airbnb-Analysis

## Overview
This Power BI project offers a comprehensive analysis of Airbnb listings in New York City from 2011 to 2019. The primary objective is to explore key trends in pricing, availability, occupancy rates, and revenue generation across various neighborhoods and room types. This analysis serves as a valuable resource for stakeholders, including potential hosts aiming to optimize pricing strategies and guests seeking the best deals.

## Table of Contents
1. Dataset Overview
2. Data Preprocessing
3. Key Insights
4. Strategic Recommendations
5. Interactive Features
6. How to Use the Report
7. Conclusion
8. Key Files in the Repository
9. Contact Information

## Dataset Overview
The dataset used for this analysis is the New York City Airbnb Open Data obtained from Kaggle. It includes detailed information on:

* Listings: ID, host name, and host ID.
* Geographical Data: Latitude, longitude, neighborhood, and neighborhood group.
* Pricing and Availability: Room type, price, minimum nights, and number of reviews.
* Reviews: Last review date, review frequency, and overall scores.
The data spans over 8 years, allowing for a comprehensive temporal analysis of the Airbnb market in New York City. Various data quality checks were performed to ensure accuracy and relevance.

## Data Preprocessing
Several preprocessing steps were conducted to prepare the dataset for visualization in Power BI:

- Handling Missing Values: Imputed missing data in columns like reviews_per_month using median values and removed irrelevant rows.
- Data Cleaning: Eliminated duplicate entries and outliers to ensure data consistency.
- Data Transformation: Created calculated columns and measures such as "Total Revenue," "Occupancy Rate," "Average Price per Neighborhood," and "Price Category" for deeper insights.
- Data Normalization: Applied normalization techniques to standardize data across different columns for better comparison and visualization.
  
These preprocessing steps helped structure the data to enhance the visualization experience, ensuring meaningful and actionable insights.

## Key Insights
The report is structured into multiple pages, each focusing on specific areas of analysis:

### 1. **Cover Page**
- Provides an overview of the project, its scope, and the analysis period.
- Includes a clickable button for navigating to the "Key Metrics" page.

  
![Cover page](https://github.com/user-attachments/assets/308c4492-d3c9-4596-b4ee-a2cc7cbab50e)

  
### 2. **Key Metrics Page**
1. **Annual Revenue Growth Over Time:**
- The line chart shows a dramatic increase in total revenue, especially from 2017 to 2019, indicating rapid market growth.
- *Insight:* This growth may be attributed to rising popularity, increased tourism, and more listings or higher pricing.
2. **Revenue Breakdown by Room Type:**
- Bar chart shows 'Entire home/apt' listings account for over 70% of total revenue, suggesting travelers prefer private accommodations.
- *Insight:* Hosts should consider offering entire homes or apartments to maximize earnings.
3. **Revenue Distribution by Neighborhood and Price Category:**
- Decomposition tree highlights Manhattan and Brooklyn as top-performing neighborhoods, especially in the 'High' price category.
- *Insight:* Location is crucial in pricing and revenue. Hosts in less popular neighborhoods could use competitive pricing or unique offerings to attract guests.
4. **Top Earning Hosts: Revenue, Price, and Listing Count:**
- The table displays the highest revenue-generating hosts, with diverse pricing and listing strategies.
- *Insight:* Different strategies like scaling multiple listings or optimizing fewer high-value properties can be successful depending on market positioning.
5. **KPI Tiles:**
- Displays key metrics like total revenue, occupancy rate, total listings, and average price per neighborhood.


![Key metrics](https://github.com/user-attachments/assets/19c6976e-d7b3-4d32-89d7-f88d01e73fc6)


### 3. **Detailed Analysis**
1. **Geospatial Revenue Distribution Across New York City:**
- Map visual shows Manhattan, Brooklyn, and Queens dominate in terms of revenue.
- *Insight:* Neighborhood popularity correlates with proximity to attractions, transportation hubs, and business districts.
2. **Room Type Pricing and Availability Across Neighborhood Groups:**
- Bar chart and line graph show a correlation between room type pricing and availability across neighborhoods.
- *Insight:* Opportunities may exist for price optimization or luxury offerings in underperforming areas.
3. **Market Share of Occupancy Rates by Neighborhood Group:**
- Pie chart shows Manhattan has the highest occupancy rate, followed by Brooklyn and Queens.
- *Insight:* Location significantly drives occupancy and pricing power.
4. **Host Listing Dynamics: Price vs. Volume Analysis**
- Scatter plot indicates diverse pricing strategies among hosts.
- *Insight:* A mixed approach of volume-based or premium pricing can help hosts optimize their strategies.

  
![Detailed analysis](https://github.com/user-attachments/assets/e2d9fb5e-d0a5-46f4-a70f-48fffea32599)


### 4. **Executive Summary**
This Power BI report provides a comprehensive analysis of Airbnb listings in New York City from 2011 to 2019. Key insights and strategic recommendations are summarized below:
- Revenue Trends: There is a notable surge in total revenue from 2017 to 2019, signaling strong growth in Airbnb's market share.
- Top Neighborhoods: Manhattan and Brooklyn consistently rank as the highest-revenue neighborhoods, particularly in the premium price category.

![Executive summary](https://github.com/user-attachments/assets/4b23475f-7662-49f3-b317-aea4bfe695b9)


## Strategic Recommendations
1. **Expand Inventory in High-Performing Neighborhoods:** Focus on areas like Midtown and Lower Manhattan for favorable demand and pricing.
2. **Optimize Room Type Offerings:** Increase investment in exclusive properties and reduce shared room offerings with limited demand.
3. **Implement Dynamic Pricing Strategies:** Adjust prices during peak seasons and major events based on seasonal trends.
4. **Leverage Data-Driven Marketing:** Target underperforming neighborhoods using data insights to highlight unique features.
5. **Diversify Across Emerging Areas:** Explore opportunities in emerging neighborhoods like parts of Queens and Staten Island.

## Interactive Features
The report includes interactive elements to enhance user experience:
* Buttons and Bookmarks: For easy navigation between pages.
* Filters: Dynamic filters for Year, Neighborhood, Room Type, and Price Category.
* Custom Tooltips and Drill-Throughs: Provide detailed information on hover and drill-through for more granular details.

## How to Use the Report
Users can navigate through the report using buttons on the left panel. Filters can be applied to refine data, and hovering over visuals reveals additional information through tooltips.

## Conclusion
The New York City Airbnb market presents significant growth potential. By strategically expanding in high-revenue neighborhoods, optimizing property types, and leveraging data for targeted marketing, stakeholders can enhance profitability and capture a larger market share. Future analyses could explore seasonal patterns, guest demographics, and policy impacts on short-term rentals for a more granular growth strategy.

## Key Files in the Repository
- README.md: Provides an overview of the project, the objectives, and the steps followed in the analysis.
- NYC Airbnb Listings Project.pbix: The main Power BI file containing all the visuals and interactive elements.
- NYC Airbnb Listings Project.pdf: PDF report summarizing the project.
- Images: A collection of screenshots of the dashboard and key visuals to provide a quick overview to viewers.
- NYC Airbnb Listings Project.mp4: Video file explaining the key visualizations, insights, and interactivity in the Power BI report. 

## Contact Information
For further information or questions, please contact: Email: deepthydevadasan@gmail.com
