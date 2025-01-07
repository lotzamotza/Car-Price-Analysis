Car Price Analysis: Predicting Car Values with Machine Learning

This project uses machine learning techniques to analyze factors influencing car prices and predict vehicle values based on mileage, condition, make, and year. The analysis provides actionable insights for both car buyers and sellers by identifying key trends and building a predictive model.

Project Highlights
Objective: Develop a machine learning model to predict car prices and identify the key factors affecting price variability.
    Model Used: Random Forest Regressor
    Performance:
        R² = 0.42
        Mean Absolute Error (MAE) = $4978.39
    Tools & Libraries:
        Python: Pandas, Matplotlib, Seaborn, Scikit-learn
        Data Visualization: Correlation heatmaps, EDA plots
        Machine Learning: Feature engineering, train-test splitting, and model evaluation
        
Key Findings
Mileage has a strong negative correlation with price, with higher mileage reducing car value significantly.
Condition greatly impacts price—vehicles in better condition command higher prices.
The Random Forest model provides moderately accurate predictions, highlighting the need for additional features like brand and location for further improvement.

Features
Data Cleaning: Handled missing values, removed outliers, and processed dates for better model performance.
Exploratory Data Analysis (EDA): Visualized key relationships, such as mileage vs. price and condition vs. price, using scatter plots, boxplots, and heatmaps.
Predictive Modeling: Built and evaluated a Random Forest model to predict car prices, achieving an R² of 0.42.
Actionable Insights: Provided recommendations for car buyers and sellers based on model outputs and trends.

Future Work
Incorporate additional features like brand, location, and seasonal trends to improve model performance.
Explore time-series analysis to capture changes in car prices over time.
Compare Random Forest with other models (e.g., Gradient Boosting, XGBoost) for better predictive accuracy.
