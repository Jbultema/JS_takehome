# Product Forecasting Data Science Project

## Project Overview
This project focuses on forecasting product demand utilizing advanced data science techniques. It involves assembling a comprehensive dataset from order and item data, followed by exploratory data analysis (EDA) and employing various modeling approaches to predict future demand accurately.

## Project Goals
- To accurately forecast product demand using historical sales data.
- To identify key drivers of product demand through exploratory data analysis.
- To compare the effectiveness of different forecasting models in capturing product demand trends.

## Exploratory Data Analysis (EDA) Approaches
- **Data Quality Assessment**: Evaluation of missing values and outlier detection to ensure data integrity.
- **Univariate and Multivariate Analysis**: Investigation of individual variables and their relationships to understand factors influencing demand.
- **Temporal Analysis**: Examination of seasonal patterns, trends, and the impact of holidays on demand.
- **Visualization**: Use of line plots, violin plots, and distribution plots to visualize sales trends, seasonal patterns, and distribution of sales across different times and categories.

## Modeling Approaches
1. **DataRobot Automated Machine Learning**: Automated feature engineering and model selection for forecasting with the capability to handle various time horizons and incorporate holiday effects.
2. **FB Prophet**: Simplified univariate time series forecasting focusing on trend and seasonal decomposition, highlighting the impact of holidays on sales.
3. **Complex Multi-Series Modeling with DataRobot**: Advanced approach for forecasting each product series independently, utilizing clustering to categorize products based on sales patterns and optimizing models for each cluster.

## Granularity of Modeling
- From single-series aggregated forecasts to complex multi-series approaches, the project explores different levels of granularity, focusing on individual and grouped product demand forecasting to address specific business needs.

## Conclusions and Takeaways
- Commercial customers significantly influence sales patterns, with purchases aligning with US business hours and a pronounced weekly seasonality.
- Distinct seasonal trends and intermittent demand across products necessitate sophisticated modeling and feature engineering approaches.
- Clustering products based on sales patterns enables targeted forecasting, with different clusters exhibiting unique seasonal behaviors.
- The comparison of modeling approaches reveals the trade-offs between simplicity and accuracy, with complex multi-series models offering nuanced insights at the cost of increased complexity.

## Wrapping Up
This project demonstrates the power of combining automated machine learning tools with traditional time series forecasting methods to address the multifaceted challenge of product demand forecasting. The insights gained and the methodologies employed can guide inventory management strategies, product placement, and marketing efforts to align with anticipated demand trends.

## Author
Jarred Bultema, PhD