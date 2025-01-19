# Crude-Oil-Forecasting-using-Excel
Exploring different forecasting techniques and evaluating metrics using excel of Eagle Energy Enterprises, a leader in the oil refining industry. 
The aim is to develop a forecasting system that can predict future crude oil import volumes, allowing the company to better manage operations and mitigate risks.

![image](https://github.com/user-attachments/assets/b4694044-0c88-4bf4-b736-bf0ab0048c54)


## Table of Content

- Project-overview
- Project-objective
- Data-sources
- Methodology 
- Results
- Performance-comparison  
- Key-insights
- Conclusion 


1. ## Project-Overview  
   This section introduces the project, providing context on the importance of crude oil price forecasting. It outlines how price volatility in the crude oil market impacts global economies and industries. The section emphasizes the role of forecasting methods in helping stakeholders make informed decisions, such as inventory planning, production, and investment.

2. ## Project-Objective  
   Here, the objectives of the project are clearly defined. The goal is to determine the most effective forecasting method for crude oil prices using Excel-based techniques. The project seeks to answer key questions, such as:  
   - Which method provides the highest accuracy for crude oil price predictions?  
   - How do different forecasting approaches compare in terms of errors and performance?  
   - What insights can stakeholders gain from the analysis to aid in decision-making?

3. ## Data-Sources  
   This section describes the dataset used in the analysis, including:  
   - The origin of the data (e.g., a public dataset, company records, or industry reports).  
   - Key variables, such as dates, crude oil prices, and any additional contextual data.  
   - Preprocessing steps taken to clean and prepare the data for analysis, such as handling missing values and ensuring data consistency.

4. ## Methodology  
   This section provides an in-depth explanation of the forecasting methods applied:  
   - **Naïve Approach:** A simple method that uses the last observed value as the forecast.  
   - **Moving Average:** Calculates the average of a defined number of recent data points to smooth fluctuations and predict future values.  
   - **Exponential Smoothing:** Assigns exponentially decreasing weights to past observations for more responsive predictions.  
   - **Simple Linear Regression:** Establishes a linear relationship between time and crude oil prices for trend-based forecasting.  

   Additionally, the section introduces the evaluation metrics used to measure the performance of these methods:  
   - **Mean Absolute Deviation (MAD):** Average of the absolute differences between forecasted and actual values.  
   - **Mean Squared Error (MSE):** Average of squared differences between forecasted and actual values, penalizing larger errors.  
   - **Mean Absolute Percentage Error (MAPE):** Measures error as a percentage of actual values, allowing for easier interpretation.  
   - **Accuracy:** The percentage of correctly predicted values relative to actual outcomes.

5. ## Results  
   This section presents a detailed comparison of the four forecasting methods, using a structured table (like the one you provided).  
   - Key observations include which method had the lowest MAD, MSE, and MAPE, as well as the highest accuracy.
  
     ![Screenshot 2025-01-19 204014](https://github.com/user-attachments/assets/41133b7a-a92d-4f5d-906c-d9750898ce45)

   - For instance:  
     - **Moving Average** and **Exponential Smoothing** show higher accuracy (95%) and lower MAPE compared to other methods.  
     - **Naïve Approach** performed reasonably well for its simplicity but had higher errors compared to advanced methods.  
     - **Simple Linear Regression** demonstrated relatively lower accuracy due to its assumptions of linearity.  

6. ## Performance-Comparison  
   This section highlights the performance of the methods using visualizations:

   ![Screenshot 2025-01-19 204042](https://github.com/user-attachments/assets/1bb58f04-0456-4560-86bc-8e4732dcfdf2)

   - Bar charts for **MAD, MSE, MAPE, and Accuracy** comparisons, showing which method excels in each metric.  
   - Observations on the trade-offs between simplicity (e.g., Naïve Approach) and accuracy (e.g., Moving Average).  
   - Discussion on the challenges of each approach and its suitability for different scenarios.  

8. ## key-Insights  
   This section interprets the results and provides actionable insights:  
   - **Moving Average** and **Exponential Smoothing** are more reliable for short-term forecasts due to their ability to smooth out noise.  
   - **Simple Linear Regression** is less suited for crude oil price forecasting, given the non-linear nature of price changes.  
   - The choice of forecasting method should depend on the context, such as data availability, required accuracy, and computational simplicity.

9. ## Conclusion  
   This section wraps up the analysis with final remarks:  
   - A summary of the findings, emphasizing the effectiveness of Moving Average and Exponential Smoothing methods.  
   - Recommendations for using advanced tools (like Python or R) for further exploration, should larger datasets or complex patterns need to be analyzed.  
   - Acknowledgment of the limitations of Excel-based forecasting and the need for more sophisticated methods in certain cases.

