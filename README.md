# Air-Quality-Index-Analysis


The "Air Quality Index Analysis" project is a comprehensive exploration of air quality parameters with the goal of understanding and predicting the Air Quality Index (AQI) for different cities. The project encompasses a diverse set of features, including city details, date, and various air pollutants such as PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, and Xylene. The target variables are AQI and AQI_Bucket.

1. **Data Collection and Preprocessing:**
   - Data was collected from diverse sources, aggregating information on air quality parameters for various cities.
   - The dataset was preprocessed to handle missing values, outliers, and format inconsistencies.

2. **Exploratory Data Analysis (EDA):**
   - Statistical methods were applied to uncover key characteristics and trends in the data.
   - Visualization tools like Seaborn and Matplotlib were used to create insightful charts and graphs, aiding in the exploration of relationships between variables.

3. **Feature Engineering:**
   - The dataset underwent feature engineering to extract relevant information and enhance the predictive power of the model.


4. **Model Development:**
   - The Seasonal Autoregressive Integrated Moving Average (SARIMA) algorithm was selected to forecast future AQI values. SARIMA is well-suited for time series data and captures both seasonality and trend components.

5. **Model Training and Validation:**
   - The dataset was split into training and validation sets to train the SARIMA model.
   - Model performance was evaluated using appropriate metrics, ensuring its accuracy and reliability.

6. **Forecasting and Future Analysis:**
   - The trained SARIMA model was applied to forecast future AQI values for each city.
   - Insights from the forecasting results were used to understand potential air quality trends and patterns.

7. **Project Conclusion:**
   - The project concludes with a comprehensive analysis of air quality trends, insights from the SARIMA model, and recommendations for improving air quality in specific cities.

The "Air Quality Index Analysis" project provides a valuable tool for policymakers, environmentalists, and city planners to make informed decisions regarding air quality management and public health initiatives.
