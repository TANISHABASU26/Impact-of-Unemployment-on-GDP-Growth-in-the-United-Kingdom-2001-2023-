# Impact of Unemployment on GDP Growth in the United Kingdom (2001-2023): A Quarterly Data Analysis

## Introduction
The correlation between GDP growth and unemployment holds significant implications for economic policymaking and understanding the productivity of the economy. This study provides insights into the complex relationship between these two variables, where the data is seasonally adjusted and taken in quarters for a better and more comprehensive analysis.

For the past two decades, the United Kingdom has witnessed fluctuations in both unemployment rates and GDP growth percentages. These fluctuations reflect the country's highs and lows amidst several economic, social, and political changes. In recent years, the world has been subjected to a pandemic, making it urgent to examine the reaction and aftereffects of the pandemic on the relationship between these variables.

In this study, the relationship between GDP growth and unemployment is analyzed using linear regression. This approach is fundamental for understanding the extent of the impact of the unemployment rate on GDP growth. Linear regression allows for quantifying and explaining this relationship, making it crucial for answering this research topic. Researchers can ascertain the direction and degree of this association by calculating the regression equation's coefficients, which can offer important information to stakeholders and policymakers. Furthermore, hypothesis testing is made possible by linear regression, enabling researchers to evaluate the statistical significance of the correlation between GDP growth and unemployment. Additionally, linear regression can identify significant trends and patterns in the data by modeling intricate interactions and possibly including non-linear components. This helps us better comprehend the dynamics between these crucial economic variables.

## Econometric Models

### Linear Regression Model
In the research paper “The Effect Of Economic Growth In Relation To Unemployment” by Misini and Badivuku-Pantina (2017), the relationship between unemployment and nominal GDP from 2004 to 2014 is measured using secondary data from the Kosovo Agency of Statistics. The analysis includes descriptive statistics, scatter plot graph analysis, and a simple linear regression model. The timeframe in which the relationship is judged is annual. The results show a negative correlation between unemployment and GDP growth. The regression analysis confirms that a 1% increase in nominal GDP is related to a 0.43% decrease in the unemployment rate, with a significance of 0.013. The findings provide an understanding of the policies required to implement given this inverse relationship between the variables.

### ARIMA Model
In the study paper “Economic Growth Analysis and Forecasting Towards Unemployment Rate” by Sahib and Ibrahim (2022), an ARIMA model was used for the research. The data was collected from the World Development Indicators of the World Bank. The variables included were Malaysia’s annual GDP growth and unemployment rate from 1961 to 2020, resulting in 59 observations. The Box-Jenkins method was applied to ensure time series forecasting. The analysis concluded with the observation of GDP growth trends in terms of graphical representation. The ARIMA model, a statistical tool using past values to forecast future trends, included parameters (p, d, q) representing the autoregressive order, difference degree, and moving average order, respectively. The analysis revealed an inverse relationship between GDP growth and unemployment rate, a direct reference to Okun’s law, indicating how economic problems cause high unemployment rates in Malaysia.

## Data Analysis

### Variables Included
- **Control Variable:**
  - Date: This variable captures the time period from 2001 to 2023, where each year is divided into 4 quarters: January, March, July, and November.

- **Dependent Variable:**
  - GDP Growth Rate Quarterly: Log value of the percentage of growth in GDP accounted for every quarter for the years 2001 to 2023.

- **Independent Variable:**
  - Unemployment Rate: Log value of the percentage of the unemployment rate accounted for every quarter for the years 2001 to 2023.

The dataset includes values from 2001 to 2023 to capture recent trends, and the data for the said time period is readily available.

### Time Series Plot
Before analyzing the variables, it is important to understand the trends. Scatter plots are used for a graphical representation of the variables.

The scatter plot of the GDP growth rate per quarter from 2001 to 2023 reveals several noteworthy observations. Initially, there is an evident increase in the GDP growth rate over time, indicating economic expansion and recovery. The graph displays a cyclical pattern, showing periods of economic cycles such as booms, recessions, and recoveries. Seasonal variation is also evident, with GDP growth rates rising and falling periodically, influenced by economic policies. Overall, the graph shows an upward trend over time.

The scatter plot of the unemployment rate per quarter also reveals important insights. Initially, there is a slow increase in the unemployment rate, indicating economic recession. However, the rate begins to decrease after peaking, indicating improved employment conditions. The graph displays a cyclical pattern and seasonal variation, with the rate rising and falling periodically due to factors such as seasonal industries or hiring practices. Outliers may represent exceptional events or anomalies. Overall, the graph provides a visual representation of unemployment rate variation with different cyclical and seasonal factors included.

### Summary and Regression Table
The first table summarizes the variables in the study, including their mean, standard deviation, and range of observation. The next table shows the regression analysis results. The analysis concludes a significant relationship between quarterly GDP growth rate and unemployment rate, with a p-value of 0.000. The coefficient of the unemployment rate variable is -13096.46, indicating an inverse proportional relationship between GDP growth and unemployment rate. This confirms Okun’s law, indicating that economic problems cause high unemployment rates in the UK. An increase in the unemployment rate will lead to a decrease of 13096.46 units in GDP growth. The intercept term (_cons) has a value of 567251.3, representing the estimated GDP growth rate when the unemployment rate is zero. The R-squared value suggests that 16.66% of the variability in quarterly GDP growth is explained by the unemployment rate, indicating a significant impact.

## Diagnostic Tests
To ensure the stability of the model, several diagnostic tests are performed:

- **Breusch–Pagan/Cook–Weisberg Test (hettest):** Indicates evidence of heteroskedasticity in the residuals with a chi-square test statistic value of 10.67 and a p-value of 0.0011, rejecting the null hypothesis of constant variance.

- **Cameron & Trivedi's Decomposition of IM-Test (imtest):** Signifies heteroskedasticity, skewness, and kurtosis in the data, indicating the presence of heteroskedasticity.

- **Ramsey RESET Test (ovtest):** Detects omitted variable bias with a significantly larger F-statistic than the p-value, rejecting the null hypothesis of no omitted variable bias.

- **Variance Inflation Factor (VIF) Test (vif):** Indicates no multicollinearity among variables with a value of 1.00.

- **Breusch–Godfrey LM Test for Autocorrelation (bgodfrey):** Indicates no serial autocorrelation among variables as the p-value is greater than the chi-square test statistic, failing to reject the null hypothesis.

## Conclusion
Based on the analysis, there is a significant impact of unemployment on GDP growth rate. For a stable economy, unemployment should be controlled. The inverse relationship between these variables suggests that policies addressing unemployment should be considered, as a decrease in unemployment can lead to better GDP growth according to this study.

For further improvement of this model, advanced techniques can be used to address diagnostic issues. Additionally, the impact of different types of unemployment on GDP should be studied to better understand which factors of labor productivity affect GDP the most.

## Bibliography
- Nuwairah Syazwani Mohamed Ally Jinnah Sahib¹, & Norzuria Ibrahim¹. (2022). Economic Growth Analysis and Forecasting Towards Unemployment Rate Using ARIMA Model. Enhanced Knowledge in Sciences and Technology, 2(1), 47-62. DOI: https://doi.org/10.30880/ekst.2022.02.01.047
- Misini, S., & Badivuku-Pantina, M. (2017). The Effect of Economic Growth in Relation to Unemployment. Journal of Economics and Economic Education Research, 18(2), 110. DOI: 10.1533-3604-18-2-110.
- Dataset: Office for National Statistics. (n.d.). Retrieved from https://www.ons.gov.uk/
