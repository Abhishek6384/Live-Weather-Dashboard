# Live-Weather-Dashboard
Recommended Structure and Order
**1. Live Weather Dashboard**
A concise, descriptive name for the dashboard. Example: ❄️ Snowy Analytics: Global Ski Resort Insights Dashboard A dynamic, interactive data visualization tool built to explore ski resort data worldwide—focusing on regional comparisons, resort attributes, terrain complexity, and skier suitability.

**2. Short Description / Purpose**
Developed a comprehensive Power BI dashboard showcasing real-time weather data for major Indian cities, using an API to extract, transform, and visualize weather and air quality information interactively.


**3. Tech Stack**
The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main da****ta visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.

**4. Data Source**
The data source is a real-time weather API providing current weather, forecast, and air quality data in JSON format for multiple metro cities in India. The data is fetched, transformed, and combined in Power BI for detailed reporting.

**5. Features / Highlights**
Real-time weather and air quality data updates, refreshing four times daily

Detailed forecasts by city with historical and predictive insights

Interactive slicers and KPIs to filter and view data by city and time

Custom visuals including temperature, air quality, and forecast trends

Automated scheduled refresh on Power BI Service ensuring up-to-date data availability

**• Walkthrough of Key Visuals**

City Selector Slicer: Allows users to select one or multiple metro cities to filter the dashboard data interactively, enabling focused analysis on specific locations.
Current Weather Cards: Displays key current weather metrics such as temperature (in Celsius/Fahrenheit), humidity, wind speed, and air quality index through KPI cards with dynamic color coding based on AQI levels.
Air Quality Indicator: A visual displaying the Air Quality Index (AQI) colored with thresholds (Good, Moderate, Poor, etc.) to quickly communicate pollution levels for selected cities.
Weather Forecast Table/Matrix: Shows the weather forecast data for upcoming days with parameters like temperature ranges, precipitation, and conditions, enabling short-term prediction insights.
Trend Line Chart: Visualizes temperature trends or air quality changes over time for selected cities, helping identify patterns or anomalies.
Icons and Images: Weather condition icons dynamically update based on real-time API data, improving visual appeal and clarity of weather states (e.g., sunny, rainy).
Last Refreshed Timestamp: Displays the most recent data refresh time to inform users about the currency of the data being viewed.

**6.Dashboard Preview :**
<img width="1320" height="737" alt="image" src="https://github.com/user-attachments/assets/26eeb23e-ee1d-4603-9ffe-58ebe90748d7" />
