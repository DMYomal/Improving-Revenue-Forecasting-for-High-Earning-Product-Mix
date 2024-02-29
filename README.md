This project is regarding the Improving Revenue Forecasting for High Earning Product Mix in Ecommerce with comprehensive approach of machine learing and time series forecasting and sentiment analysis

The code files need to be saved in a script Folder
The data files (.csv) need to be saved in data Folder

Abstract

In the dynamic landscape of 21st-century e-commerce, where consumer behaviors evolve rapidly, 
strategic foresight into future cash flows is imperative for business success. This research employs 
publicly available data from Olist to forecast revenue trends within a defined timeframe. 
Leveraging feature engineering and sentiment analysis (VARDER), the study delves into the 
impact of customer reviews on sales revenue. Employing a multifaceted approach, the forecasting 
techniques encompass traditional forecasting approaches such as Simple Moving Average(SMA), 
univariate time series analysis(ARIMA), multivariate time series analysis(VAR Model), and five
machine learning regression models such as Multiple Linear Regression, Decision Tree, Random 
Forest, XGBoost, and AdaBoost. This comprehensive methodology aims to refine revenue 
forecasting for high-earning product mixes, providing valuable insights for strategic decisionmaking in the competitive e-commerce landscape.

Conclusion

6.1 Summary of Findings

The research focuses on forecasting revenue for the highest-earning product mix on an ecommerce platform using a combination of product category features, time series elements, and 
customer sentiments which successfully fills the research gap. Here, 15 top revenue-generating 
product categories have been identified out of 71 product categories. The sentiment analysis has 
been used to convert the customer sentiment insights to numerical value as a feature engineering 
step and the VADER scoring method has been used. The forecasting approach has been addressed 
by applying both the time series and machine learning models.
Among the time series models, SMA outperformed ARIMA and VAR methods, employing a 4-
week rolling window. The superior performance of SMA can be attributed to the limited 
availability of time series data, encompassing only a 2-year order history. ARIMA and VAR Model 
Approach did not perform well in forecasting, with the multivariate analysis exhibiting the highest 
error among the models. This highlights that SMA performs well on limited time series data.
In the machine learning approach, the multiple linear regression model exhibited superior 
performance on the revenue dataset compared to other models, boasting an overall better MAPE. 
While Random Forest, Decision Tree Model, and XGBoost also demonstrated strong performance 
in revenue forecasting, their RMSE and MAE outperformed the linear regression model. Finally, 
the Random Forest model stood out for its ability to predict company revenue with an accuracy of 
+865.62 and -865.62, emphasizing its importance in achieving higher revenue accuracy.
To merge the customer insight to the revenue forecasting model, the customer sentiments have
been analyzed and new feature engineering step has employed both the VAR model approach and 
machine learning approach. As mentioned before the VAR model did not perform well and with 
the new features and the ML models able to predict better than the traditional forecasting methods.

6.2 What Went Well: Effectiveness and Implication of the Comprehensive Approach

Contemporary e-commerce employs diverse revenue-generating strategies. This study specifically 
focuses on identifying the optimal product mix for maximum revenue, applicable across the ecommerce platform. 
Central to the success of sales and revenue is the customer's perception of the 
platform. Utilizing sentiment analysis of product reviews, an effective method for obtaining 
customer insights, the study integrates these results into model development. This process 
transforms qualitative review data into quantitative insights by confirming its correlation to 
revenue(Figure 27-Heat Map(ML Approach)), successfully bridging the gap in understanding the 
impact of customer perception on e-commerce platform revenue.
This research successfully addresses the gap in revenue forecasting within e-commerce, 
demonstrating the application of both traditional and modern approaches to develop effective 
revenue forecast models. These insights provide valuable considerations for future research. 
Furthermore, the EDA and sentiment analysis of e-commerce data reveal discernible trends in sales 
and revenue, offering valuable insights for strategic decision-making.

6.3 Significance for Business Strategy and Practical Applications in E-commerce

Undoubtedly, e-commerce has emerged as a superior alternative to traditional retail, prompting 
businesses to transition to digital platforms or maintain a hybrid presence. Utilizing time series 
and machine learning algorithms on sales data allows service providers to forecast company 
revenue effectively. Forecasting the future cash flow of the platform is crucial for strategic 
planning, including promotional campaigns, cross-sales, up-sales, and slow-moving, fast-moving 
product classification. Analyzing customer sentiment enables companies to discern customer 
preferences, facilitating solutions to potential challenges. This approach ensures informed 
decision-making for optimized business operations. Additionally, focusing on individual product 
categories or vendors within multivendor platforms can provide valuable insights to support sellers 
in growing their businesses. This targeted approach aids in strategic decision-making for both the 
platform and individual sellers.

6.4 Limitations of the research

A primary limitation of this research is the restricted access to comprehensive e-commerce 
company revenue datasets. Non-disclosure agreements of companies often prevent the sharing of 
platform data with third parties, and the ethical concerns related to customer data further limit its 
disclosure. Additionally, sharing sales data can create a competitive advantage. As a result, the 
research is compelled to utilize publicly available online sales datasets, due to the time duration.
The initial dataset spans three years from 2016 to 2018, but due to inconsistencies in the 2016 data, 
it was excluded from the analysis, resulting in a reliance on a 2-year time series dataset. Time 
series methods, both univariate and multivariate, are highly sensitive to the temporal 
characteristics and history of the data. Due to the limited data and not having a clear pattern both 
ARIMA and VAR models are unable to perform well.
The machine learning forecasting models encompass diverse parameters, influencing the final 
performance. The optimization of these models involves experimenting with various combinations 
of hyperparameters. Methods like grid search, randomized search, Genetic Algorithms, Ensemble 
Methods, etc., are employed for hyperparameter tuning, but they demand significant computational 
power and are time-consuming. This stands out as a primary limitation in tuning machine learning 
models.

6.5 Future improvement and research area

The research highlights a key limitation related to the constrained time series dataset. Utilizing a 
more extensive dataset could significantly enhance the performance of trained models. A larger 
dataset would augment the effectiveness of complex time series models, leading to improved 
forecasting. Additionally, a larger dataset could enhance sentiment analysis by providing a more 
comprehensive range of sentiments.
The VAR model approach incorporates 11 numerical variables, while the machine learning 
approach utilizes 11 numerical variables and 3 categorical variables. However, it is important that 
additional independent variables, such as click rate, daily website visits, product profit margins, 
product discounts, and marketing costs, can significantly impact e-commerce revenue. Expanding
the dataset to include these correlated factors could contribute to comprehensive revenue 
forecasting.
Leveraging hyperparameter tuning methods is a viable strategy for enhancing the forecasting 
performance of machine learning models and addressing overfitting issues. However, running 
algorithms until finding the optimal solution demands significant computational power and can be 
time-consuming. As future studies progress, researchers can explore advanced hyperparameter 
techniques to further improve model accuracy, offering potential avenues for more effective 
forecasting solutions
