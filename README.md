# Domain: Climate Technology and Environmental Science in Data Science

## Statement of the question of interest
What is the prevalence of extreme temperature events, including extreme cold and extreme heat occurrences, in the United States over a specified time frame (2012 to 2022)?

## Objective:
- This project's primary objective is to comprehensively analyze temperature data collected from various weather stations across the United States. 
- The analysis aims to identify and quantify extreme temperature events, specifically extreme cold and extreme heat occurrences, over a specified time frame. 
- Furthermore, the project seeks to visualize and present the yearly counts of these extreme events.

## Source and a short description of the data:
The data for this project was sourced from various weather stations across the United States, and it spans the time frame from 2012 to 2022. These weather stations provide daily temperature records, including maximum (TMAX) and
minimum (TMIN) temperatures, which are crucial for identifying extreme temperature events. The data was retrieved through a combination of web scraping techniques from a designated URL and API requests to the National Centers for
Environmental Information (NCEI) API. This dataset allows us to comprehensively analyze and visualize extreme temperature events, specifically extreme cold and extreme heat occurrences, over the specified time period. It forms the basis for our investigation into the prevalence and trends of these events, providing valuable insights for climate monitoring and research.

## Possible Sources of Bias
### Geographical Bias
The dataset used in this analysis comprises temperature data from various weather stations across the United States. It's important to note that the distribution of these weather stations may not be uniform across states and regions. Some areas may have a higher density of weather stations than others. This non-uniform distribution can introduce geographical bias into the analysis, as regions with more stations may have a greater influence on the results.

### Data Quality Bias
The accuracy and reliability of temperature data can vary among different weather stations. Some stations may have stringent data quality control measures in place, ensuring highly accurate recordings, while others may lack such
measures. This variability in data quality can introduce bias when identifying extreme temperature events.

### Temporal Bias
The dataset covers a time frame from 2012 to 2022. It's essential to consider the possibility of temporal bias when analyzing long-term trends. For example, improvements in data quality control or changes in station coverage over
the years could impact the identification of extreme events.

### Urban Heat Island Effect
Weather stations located in urban areas may record higher temperatures due to the urban heat island effect. This localized bias can influence the overall analysis of extreme heat events if not appropriately accounted for.

### Station Elevation
Weather stations at varying elevations can record temperature variations due to altitude. It's crucial to be aware of elevation-related bias, particularly when analyzing extreme cold events, as stations at higher elevations
may report colder temperatures. 

### Data Missingness
Missing data can be a challenge, especially during extreme weather conditions. Stations with frequent missing data may underrepresent extreme events, leading to potential bias in the analysis.

### Selection Bias
The choice of percentiles (specifically, the 5th and 95th percentiles) for defining extreme cold and heat events could introduce bias based on the selected thresholds. Alternative threshold choices may yield different results.

### Data Collection Methods
Variations in data collection methods and equipment among weather stations, especially if changes occurred over the years, can introduce bias into the temperature records. Consistency in data collection methods is crucial.

### Location of Stations
The specific locations of weather stations, such as proximity to bodies of water, mountains, or urban areas, can influence temperature records. This location-based bias should be considered when interpreting the results.

### Data Processing
The methods used to process and clean the data can introduce bias if not consistently applied across all stations and years. Transparent and standardized data processing procedures are essential for minimizing this potential
bias.

Acknowledging these possible sources of bias is critical for maintaining the integrity of the analysis and for providing a comprehensive understanding of the limitations associated with the dataset and methodology used in this project
