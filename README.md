# Objective:

In this project, the goal is to assess the housing price drivers and valuation modeling for Chandler, AZ real estate using Redfin data scrapped the listing from Redfin.com by beautifulsoup. 

Focus: Single-family homes in Chandler, AZ

Data source: Redfin listings (scraped)

Key limitation: School district data not included, which may influence pricing variance

Methodology:
Data scraping using BeautifulSoup

Data cleaning and preprocessing

Exploratory data analysis (price distribution, correlations)

Feature importance analysis

Predictive modeling using:

Random Forest

XGBoost

The analysis will address the following aspects:

Price distribution analysis across buyer and seller perspectives

Identification of pricing patterns and potential mispricing across ZIP codes

Evaluation of key property features influencing housing price variation

Features that could affect pricing not included in this analysis:

School District: This analysis does not take school districts into consideration as it could affect the housing price.

# Findings:
Square footage is the most significant feature influencing home prices, followed by the age of the property.

Most homes in Chandler are priced between $400K and $800K.

Random Forest and XGBoost models achieved strong predictive performance, with R² scores between 85% and 87%.

Homes without HOA tend to fall between $375K–$800K, while homes with HOA generally cluster between $400K–$650K.

# Summary:
As of July 2025:

ZIP codes 85225 and 85249 show higher variability in pricing, with model predictions indicating potential misalignment between listing prices and estimated property values.These areas also reflect different pricing distributions, suggesting localized differences in buyer demand and pricing behavior.

Both XGBoost and Random Forest models identify square footage as the most influential feature in determining home price, highlighting strong sensitivity of pricing to home size across Chandler.

Homes with larger square footage show greater variance between predicted and actual pricing, which may indicate areas for further investigation into pricing efficiency.
