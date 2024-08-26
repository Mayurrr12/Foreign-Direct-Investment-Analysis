# Foreign-Direct-Investment-Analysis

FDI refers to the residential investment made by a company or government of one country in a business or project of another country. It is related to portfolio investment but differs from it in the sense that it is not only the purchase of stocks and bonds. FDI involves a long-term commitment and oftentimes some level of control over the foreign entity.

The reasons FDI is vital for economic growth are:

* **Capital Inflow**
* **Job Creation**
* **Technology Transfer**
* **Increase in Exports**
* **Tax Revenue**

Overall, FDI can be a potent way of stimulating economic development and increasing the standard of living within a country. However, policies should be instituted whereby FDI is beneficial to both the foreign investor and the host country as well.


### *AIM*

The aim of this project is to analyze sector-wise Foreign Direct Investment (FDI) in India from 2011-12 to 2022-23 to uncover key trends and factors influencing FDI inflows. The study will develop and evaluate forecasting models such as ARIMA, SARIMA, Prophet, and XGBoost to predict future FDI trends, comparing their accuracy using metrics like R², MSE, and MAE. Additionally, sectors will be segmented using K-Means Clustering to provide strategic insights, and the predictive accuracy of Random Forest and Gradient Boosting Regressors will be compared to identify the most reliable model for forecasting FDI. The findings aim to support policymakers and investors in making informed decisions to enhance FDI inflows into India.

### *OBJECTIVES*

1. **Historical Data Analysis**: Analyze sector-wise FDI data in India from 2011-12 to 2022-23, identifying trends, seasonal variations, and key factors influencing FDI inflows across industries.

2. **Exploratory Data Analysis (EDA)**: Conduct in-depth EDA to uncover patterns, trends, anomalies, and outliers in the FDI data, providing a solid foundation for predictive modeling.

3. **Development of Predictive Models**: Build and evaluate time series forecasting models, including ARIMA, SARIMA, Prophet, and XGBoost, to accurately predict future sector-specific FDI trends.

4. **Model Performance Evaluation**: Compare the performance of the forecasting models using metrics such as MSE, R², and MAE to identify the most accurate and reliable model.

5. **Sector Clustering**: Apply K-Means Clustering to classify sectors based on cumulative FDI values, identifying high, moderate, and low investment clusters for strategic decision-making.

6. **Machine Learning Model Assessment**: Evaluate and compare the predictive accuracy of Random Forest and Gradient Boosting Regressors in forecasting historical cumulative FDI, determining which model best captures the underlying trends.
7. **Actionable Insights and Recommendations**: Provide strategic recommendations for policymakers and industry leaders to attract and enhance FDI inflows, based on insights from model evaluations and cluster analysis.

### *Conclusion:*

**Best Performing Model:** Among all the models, the Random forest Regressor and Prophet models stood out for their accuracy and ability to capture the underlying trends in the FDI data. SARIMA also performed well, particularly in sectors with strong seasonal influences.

**Seasonal Adjustments:** Policymakers should consider the seasonal nature of FDI inflows when designing policies or interventions to attract investment, as identified by both the SARIMA and Prophet models.

**Sector-Specific Strategies:** The K-Means clustering analysis suggests that targeted strategies to improve infrastructure and policy frameworks in lower-performing sectors could help attract higher FDI.

**Machine Learning Potential:** The strong performance of XGBoost , SARIMA and random forest highlights the potential for machine learning models to provide more accurate forecasts in complex economic scenarios, though care must be taken to avoid overfitting.
