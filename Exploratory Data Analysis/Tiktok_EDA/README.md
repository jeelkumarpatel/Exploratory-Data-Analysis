# Key insights from EDA
The exploratory data analysis revealed many considerations for the classification model, including missing values, “claims” to “opinions” balance, and overall distribution of data variables. The two key insights from this analysis were:

Null values
Over 200 null values were found in 7 different columns. As a result, future modeling should consider the null values to avoid making insights that would assume complete data. Further analysis is necessary to investigate the reason for these null values, and their impact on future statistical analysis or model building.

Skewed data distribution
Video view and like counts are all concentrated on low end of 1,000 for opinions. Therefore, the data distribution is right-skewed, which will inform the models and model types that will be built.
