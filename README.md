# Data Wrangling and Model Building for Formula 1
This project focuses on developing a predictive model to estimate Formula 1 race completion times using historical race performance data. The goal was to understand how different race-related factors influence total race time and to build a model that can support data-driven decision-making in a motorsports context.

Multiple datasets were integrated, including qualifying results, lap times, pit stop durations, race results, race status, and race metadata. These datasets were merged and aligned by race and driver to form a consolidated time-series dataset suitable for modeling. Significant effort was spent on data wrangling, including grouping, merging, feature creation, and mathematical extraction of race-level and driver-level metrics.

Extensive data cleansing and transformation was performed to improve data quality. This included dropping unnecessary attributes, handling missing values through both arbitrary and statistical imputation, converting data types, removing invalid target rows, and applying feature selection techniques. Additional feature engineering was carried out to derive meaningful predictors such as average lap times and pit stop impact.

A Random Forest regression model was implemented to predict total race completion time. The model demonstrated the feasibility of using historical performance data for race time prediction. Potential improvements were identified, including enhanced feature selection, polynomial feature creation, winsorisation to cap extreme values, and experimenting with advanced models such as XGBoost with K-Fold and GroupK-Fold validation to reduce data leakage.

**Key Tools & Concepts:** Python, Jupyter Notebook, Pandas, NumPy, data wrangling, multi-source data integration, feature engineering, missing data handling, Random Forest regression, model evaluation, cross-validation, data leakage awareness, XGBoost.
