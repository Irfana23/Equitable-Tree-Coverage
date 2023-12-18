# Equitable-Tree-Coverage

The project aimed to assess and predict the tree canopy coverage across various neighborhoods in Austin, Texas, with a focus on achieving equity in urban green spaces. It involved the analysis of geospatial data encompassing census tract information and tree canopy coverage. 

## Steps taken to complete the project 
## Data Collection and preparation:
Utilized GeoPandas and Python libraries to process geospatial data, integrating census tract demographics and tree canopy datasets for analysis.
Features considered included race/ethnicity percentages, median household income, and impervious surface area.

## Regression Modeling (Initial Phase):
Initially approached the problem as a regression task, aiming to predict tree canopy coverage percentages.
Employed various regression models (e.g., Linear Regression, Random Forest) but found low predictive accuracy (<20%), highlighting the challenge in accurately predicting canopy coverage solely through regression.

## Classification Transformation and Analysis:
Transformed the problem into a classification task, binarizing the target variable based on a 30% canopy cover threshold.
Classification models (e.g., Logistic Regression, Gradient Boosting) demonstrated improved performance compared to regression models, highlighting race/ethnicity as a significant predictor of canopy cover.

## Key Insights and Recommendations:
Discovered that race/ethnicity demographics were stronger indicators than income levels for predicting tree canopy coverage, emphasizing the need for equitable tree planting strategies.
Highlighted that neighborhoods with higher Hispanic/Latino or Black/African American populations should be prioritized for tree planting initiatives to achieve more equitable canopy coverage.

## Conclusion
The project provided actionable insights indicating the dominance of race/ethnicity demographics over income in predicting tree canopy coverage. These findings are crucial for urban planners and policymakers, suggesting targeted strategies to ensure equitable distribution of green spaces in Austin's diverse neighborhoods.
