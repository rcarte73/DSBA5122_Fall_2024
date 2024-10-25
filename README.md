# Human Trafficking Trends Analysis Dashboard

## Tableau Public Link
[[https://public.tableau.com/views/Midterminprogress/Home?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link](https://public.tableau.com/app/profile/rebecca.carter7015/viz/Midterminprogress/Home)](https://public.tableau.com/views/Midterminprogress/ProsecutionandConvictionRates?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Introduction
This project presents a comprehensive Tableau dashboard analyzing human trafficking trends globally and regionally, with a specific focus on the United States. The dashboard leverages UNODC trafficking data to visualize key metrics, including victim demographics by gender and age, as well as prosecution and conviction rates. The primary objective is to provide insights into global and U.S. trafficking patterns, demographic distributions, and legal response effectiveness. By integrating interactive visuals, this project enables users to explore trafficking data across multiple dimensions, supporting a deeper understanding of regional and temporal trends in trafficking cases.

## Data/Operation Abstraction Design

### Key Visualizations
**Global and Regional Trends** A map with gradient colors and circle sizes to represent the intensity of trafficking incidents by country and region. This layered approach allows users to quickly identify high-incidence areas both visually and quantitatively.
**Gender and Age Distributions** A line graph offer insights into gender and age demographics of trafficking victims, providing an interactive exploration of vulnerable populations over time.
**Prosecution and Conviction Rates** A combined bar chart and line graph show prosecuted versus convicted cases over time. The bar chart represents prosecutions, while the line overlays convictions, allowing for an intuitive comparison of legal outcomes and the progression from prosecution to conviction.
A heat map visualizes the percentage of prosecuted cases that resulted in convictions, highlighting regions or periods with higher or lower conviction rates among prosecuted cases.

These visualizations collectively provide a clear abstraction of the trafficking process, from detection to legal outcomes. Calculated fields, such as conviction rates and demographic totals, ensure consistent aggregation across years, countries, and categories, while interactive filters and calculated fields support dynamic comparisons across multiple dimensions.

## Future Enhancements:
Advanced Filtering Options: Incorporating multi-level drill-down capabilities for specific states or local regions within the U.S. would allow for more detailed geographic insights.
Predictive Analytics: Introducing trend forecasting for prosecution and conviction rates could help anticipate future changes and identify emerging trends in trafficking cases.

## Data UNODC - Metadata Information
- **DataSource**Trafficking in Persons
The tables include figures on detected trafficking victims and persons convicted of
trafficking in persons at national, regional and global level. National data are
submitted by Member States to UNODC through the United Nations Questionnaire
for the Global Report on Trafficking in Persons (GLOTIP) or other means.
Dataset characteristics
<Strong>Access link: https://dataunodc.un.org/dp-trafficking-persons</Strong>
Last update: 24/01/2023
Base period: Calendar Year
Data source(s): National data on trafficking in persons collected through the GLOTIP. Please see
below for National data collection sources.
Contact
United Nations Office on Drugs and Crime
Email: unodc-ddds@un.org 
