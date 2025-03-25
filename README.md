# FBI-Crime-Rate-Analysis-
FBI Crime Rate Analysis - Power BI Report
Project Overview
This dashboard is designed to help stakeholders gain an in-depth understanding of crime trends through interactive visualizations. It empowers law enforcement, policymakers, and the general public to explore crime data based on different filters like time, location, and crime type. The goal is to make crime data more actionable and accessible, aiding in decision-making and resource allocation.
Data Source
The dataset is sourced from FBI crime reports, containing details such as incident type, year, month, day, hour, neighbourhood and more.
 
Key Components & How to Use
1.	Total Incidents Display
o	Description: A large card displaying the total number of recorded crime incidents, which dynamically updates as filters are applied.
o	Usage: The total count of incidents will change according to the filters selected, offering a quick overview of crime volume based on the chosen criteria.
o	DAX Formula: Total Incidents = COUNT('Train'[TYPE])
2.	Filters Panel
o	Description: Dropdown filters at the top allow users to filter crime data by various categories, such as:
	Incident Type
	Year
	Month
	Day
	Hour
	Hundred Block
	Neighborhood
o	Usage: Select a value from any filter, and the dashboard will update instantly. Multiple filters can be combined for a more refined analysis.
3.	Area Chart (Year)
o	Purpose: Displays crime trends over the years, allowing users to track fluctuations and patterns in crime rates.
o	Usage: Visualize the rise or decline in crime incidents over time. This helps to highlight trends such as a recent increase in crime after years of decline.
4.	Bar Chart (Hour)
o	Purpose: Displays the number of crime incidents by hour, helping to identify peak crime hours.
o	Usage: Identify when crime incidents occur most frequently, allowing law enforcement to focus resources during peak times.
o	Key Insights: Crime activity peaks in late evening and nighttime, with early morning hours seeing fewer incidents.
5.	Tree Map (Month)
o	Purpose: Breaks down crime incidents by month, showing the distribution of crime over the course of the year.
o	Usage: Helps identify the months with the highest crime rates, assisting in seasonal trend analysis and resource planning.
6.	Slicers
o	Purpose: Offers filters for categories such as Year, Month, Quarter, Crime Type, and Hundred Block.
o	Usage: Use the slicers to drill down into specific periods, crime types, or areas for a tailored analysis.
7.	Map (Crime Density)
o	Purpose: A geographic visualization showing crime locations on a map to identify crime hotspots.
o	Usage: Visualize crime density across different geographic areas, pinpointing areas that may require targeted interventions.
8.	Pie Chart (Neighbourhood Crime Analysis)
o	Purpose: Displays crime distribution by neighbourhood.
o	Usage: Identify which neighbourhoods report the highest or lowest crime rates, aiding in prioritizing interventions or resource allocation.
o	Key Insights: Certain neighbourhoods (e.g., the Central Business District) have significantly higher crime rates.


Conclusion
This dashboard is an essential tool for analyzing crime trends through interactive, real-time visualizations. It provides stakeholders with valuable insights to identify high-risk areas, make informed decisions, and develop strategies for reducing crime and improving community safety. Through the use of filters, drilldowns, and geographic analysis, this tool empowers users to act proactively in addressing crime-related challenges.

![Image](https://github.com/user-attachments/assets/8c4b5b58-9ee6-4f9a-801f-fd79575d1f68) 
