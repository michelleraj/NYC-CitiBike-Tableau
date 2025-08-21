# NYC-CitiBike-Tableau

[Link to Tableau Dashboard](https://public.tableau.com/views/NYCCITITRIP/Dashboard2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
# Purpose
This project conducts a comprehensive analysis of NYC Citi Bike trip data to uncover key ridership patterns. The primary objective was to transform raw ridership data into clear, actionable visual intelligence to inform public policy decisions regarding urban mobility, public health, infrastructure investment, and equitable access to transportation services.

The analysis leverages Python (Pandas) for rigorous data cleaning and preparation, ensuring the integrity of the dataset, and Tableau for building an interactive, stakeholder-focused dashboard.

# Dashboard Purpose & Key Questions
The Tableau dashboard is designed to answer critical operational and strategic questions for city planners and Citi Bike management:

System Utilization & Efficiency: How long are bikes typically checked out? This helps in managing bike availability and rebalancing logistics.

Equity and Access: Are there discernible usage patterns across different genders? Understanding these disparities is the first step toward crafting equitable transportation policies.

Operational Planning: When and where is demand highest? Identifying peak usage times and popular stations is crucial for optimizing bike availability, staffing, and infrastructure maintenance.

Customer Segmentation: How do subscription members ("Subscribers") differ from casual users ("Customers") in their usage patterns? This informs marketing strategies and service offerings.

# Methodology & Data Integrity
Data Source: Publicly available Citi Bike System Data.- https://citibikenyc.com/system-data

Tools: Python (Pandas), Jupyter Notebook, Tableau.

Process:

Data Acquisition & Cleaning: The raw data was programmatically cleaned using Pandas to handle missing values, correct data types, and ensure consistency. This meticulous process is foundational for accurate and reliable analysis.

Exploratory Data Analysis (EDA): Initial analysis was performed to understand distributions, identify outliers, and validate the scope of the project.

Visualization Design: Each visualization in the dashboard was intentionally designed to answer a specific statistical question, prioritizing clarity and precision over decorative elements.

# Dashboard Results
## Visualization 1: Checkout Duration Analysis

<img width="891" alt="Screen Shot 2021-10-13 at 6 36 17 PM" src="https://user-images.githubusercontent.com/57809798/137221944-d8d3d56f-69f9-4dfb-97af-316b72a27cb8.png">

Visualization: Histogram of Trip Duration.

Finding: The vast majority of trips (approx. 90%) are under 30 minutes, with a sharp peak in the 5-15 minute range.

Insight: This confirms the system's role primarily for short-distance, point-to-point travel. The dominance of short trips supports the current pricing model and suggests high utility for "last-mile" connections to public transit.


## Visualization 2: Checkout Duration by Gender

<img width="887" alt="Screen Shot 2021-10-13 at 6 36 49 PM" src="https://user-images.githubusercontent.com/57809798/137221983-4da00736-eabd-47e1-84d0-8e69e654a19c.png">


Visualization: Layered histogram segmented by gender.

Finding: While the trip duration distribution is consistent across genders, male riders account for a significantly higher volume of trips.

Insight: This raises important questions about gender parity in cycling. Potential areas for investigation include safety perceptions, helmet availability, and targeted outreach programs to encourage ridership among underrepresented groups.

Visualization 3:Weekly Trip Volume Heatmap


<img width="566" alt="Screen Shot 2021-10-13 at 6 37 26 PM" src="https://user-images.githubusercontent.com/57809798/137222035-add7293e-5eb9-42a8-910b-b354b6af5da7.png">


Visualization: Heatmap of trips by hour and day of the week.

Finding: Pronounced peaks on weekday mornings (8-9 AM) and evenings (5-6 PM). Weekends show a broader peak from 10 AM - 5 PM.

Insight: Clear evidence of a commuter pattern. This data is critical for operational planning (e.g., pre-emptive bike rebalancing before peak hours) and for integrating Citi Bike into the city's overall commuter strategy.

Visualization 4: Weekly Trip Volume by Gender

<img width="891" alt="Screen Shot 2021-10-13 at 6 40 33 PM" src="https://user-images.githubusercontent.com/57809798/137222320-cb21f67c-6328-41aa-9b84-deee0e10cf2e.png">

Visualization: Heatmaps faceted by gender.

Finding: The commuter peak pattern is consistent but more intense for male riders.

Insight: Reinforces the need for deeper qualitative research to understand the barriers to female ridership during traditional commute times.



Visualization 5:User Trips by Gender and Weekday

<img width="370" alt="Screen Shot 2021-10-13 at 6 37 52 PM" src="https://user-images.githubusercontent.com/57809798/137222072-16c7b7f5-5299-4058-884e-a661dd153ed1.png">

Visualization: Heatmap of trips by day, user type, and gender.

Finding: Subscribers are the core user base, driving weekday commute traffic. Casual customer usage is more prominent on weekends. Male subscribers are the most dominant user cohort.

Policy Insight: Highlights two distinct markets: a reliable subscriber base for daily commuting and a customer base for leisure/tourism. Marketing and pricing strategies should be tailored separately to these segments to maximize growth and retention.




Visualization 6: Top Starting Location
<img width="899" alt="Screen Shot 2021-10-13 at 6 52 29 PM" src="https://user-images.githubusercontent.com/57809798/137223354-a08d979b-51be-4071-a779-f045295e5142.png">
Top Starting Locations: A spatial analysis identified the highest-traffic stations (coordinates are 40.7519, -73.977), providing a data-driven basis for prioritizing station expansion, maintenance, and capacity upgrades.

Visualization 7: August Peak Hours
<img width="1043" alt="Screen Shot 2021-10-13 at 6 53 00 PM" src="https://user-images.githubusercontent.com/57809798/137223400-c1fb41dd-8dce-481f-87c2-1b8833d3ade6.png">

August Peak Hours: Quantified the highest demand hour (5-6 PM, n=224,566 rides) and the lowest (4-5 AM), offering precise metrics for capacity planning and resource allocation

# Summary
This analysis successfully transforms NYC Citi Bike data into a clear narrative about urban mobility:

The system is a vital commuter tool, with usage heavily concentrated around traditional work hours.

A significant gender disparity in ridership warrants further investigation to promote equitable access.

Distinct user segments (Subscribers vs. Customers) require differentiated policy and marketing approaches.

The integrity of these insights is built upon a foundation of meticulous data cleaning and validation, ensuring that subsequent reporting and recommendations are both accurate and actionable for public policy decision-makin
