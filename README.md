# Toronto_Auto_Theft

The objective of this project is to leverage Power BI for data cleaning, ensuring consistency by correcting data types and addressing any corrupted entries.
The focus is on summarizing and analyzing auto-theft data, uncovering insights into neighborhood clusters, property-type distributions, and theft patterns across various times—such as days of the week and hourly trends.
These insights will allow us to identify patterns and better understand the characteristics of high-theft areas.
The data was obtained from Toronto Police Service Public Safety Portal https://data.torontopolice.on.ca/datasets/TorontoPS::auto-theft-open-data/about

## Methodology

Leveraged Power BI query to correct column data types (transform the data) and employed DAX to incorporate national holidays, summarizing auto-theft trends by day of the year. 
Developed interactive visualizations and ARCGIS maps to effectively present these insights in a clear and engaging manner.

## Results

1. West Humber-Clairville reports the highest number of auto-thefts, totaling 2,507 incidents.
2. Residential locations account for the majority of thefts, with single-family homes making up 35% of total thefts, while only 7.5% occur at commercial locations, highlighting a significant contrast in targeted areas.
3. In West Humber-Clairville, 51.74% of auto-thefts occur in parking lots, underscoring a prominent hotspot within the neighborhood.
   
![image](https://github.com/user-attachments/assets/1580d1bb-5f52-496b-a5c3-2067acfa5a91)

### Hourly and Daily Trends

4. Auto-thefts dropped sharply by 52.5% during COVID-19 (2020) compared to 2023, the year with the highest reported incidents.  
5. Thanksgiving Weekend saw the highest spike in thefts, with a 200% increase.  
6. The peak hour for auto-thefts was around 10 PM, accounting for 9% of total incidents.  
7. Thursdays experienced the highest frequency of thefts, contributing to 16% of overall cases.

![image](https://github.com/user-attachments/assets/0ca670d9-ee9e-434d-9d2d-a8b31fb5bc81)

### Location Clusters

8. Major neighborhood clusters were identified around Downsview Airport and Toronto Pearson International Airport, contributing to nearly 10% of all auto-thefts.  
9. Additional significant clusters include the areas around the Toronto Zoo, Etobicoke City Centre and Wexford-MAryvale Neighborhoods.

![image](https://github.com/user-attachments/assets/db6ccd00-e17a-4212-8c3f-5e397da16237)


