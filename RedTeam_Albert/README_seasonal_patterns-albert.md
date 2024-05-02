# Seasonal Analysis of Shark Attacks 🦈

This component of the project focuses on identifying seasonal patterns in shark attacks globally. The analysis aims to determine if there are particular seasons during which shark attacks are more frequent, based on the hemisphere and local seasonal timelines.

## Data Preparation 📊

1. **Read Saved Data:** 
   - The cleaned data frame from the shark attack analysis was initially saved as a CSV file from a Jupyter notebook in the main branch of our repository.
   - This CSV file is then imported back into a new Jupyter notebook for further analysis, ensuring data consistency and accessibility.

2. **Data Cleaning and Formatting:**
   - The first column, originally unnamed, is renamed to 'index'.
   - The 'date' column, which had reverted to an object datatype, is converted to 'datetime' format for accurate time series analysis.

3. **Column Management:**
   - A new column for 'hemisphere' is added based on the country to categorize data into Northern and Southern hemispheres.
   - The 'season' column is determined using a custom function that maps the date and hemisphere to their respective seasons.

## Analysis 🔍

1. **Season Assignment:**
   - Each record is assigned a season based on its date and corresponding hemisphere.

2. **Data Grouping and Aggregation:**
   - The data is grouped by season to calculate the count of attacks per season.
   - Further grouping by month is done to observe monthly trends.

3. **Mapping Months:**
   - Numeric month values are converted to their respective names (e.g., 1 to January, 2 to February, etc.) for better readability in visualizations.

## Visualizations 📉

1. **Bar Graph - Shark Attacks by Month:**
   - Displays the frequency of attacks across different months.

2. **Bar Graph - Shark Attacks by Season:**
   - Illustrates the distribution of attacks across seasons.

3. **Time Series Analysis and Moving Average:**
   - Analyzes trends over the years to identify any increasing or decreasing trends in shark attack occurrences.

4. **Linear Regression:**
   - A linear regression model to analyze trends in shark attacks over time.

## Conclusion 📝

This analysis provides insights into how shark attacks vary with seasons and could help in better understanding the temporal patterns of shark encounters globally.

## Repository 🌐

All code and datasets are maintained in the [Shark-Analysis-Team GitHub Repository](https://github.com/CourtneyCole123/Shark-Analysis-Team/tree/main).

