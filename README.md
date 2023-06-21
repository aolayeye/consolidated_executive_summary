# consolidated_executive_summary

### Analyses 1 - Descriptive Analysis
#### Executive Summary
Our Exploratory Data Analysis (EDA) of NYC real estate markets, particularly Richmond Hill in Queens, revealed key trends and insights. Residential sales lead the market, accounting for $145.3 billion in Queens, with Richmond Hill standing out at $4.56 billion. Sales distribution in 2021 showed a significant upsurge during the summer months, hinting at heightened real estate activities during this period. We also observed a positive correlation between property size and sale value, with larger, high-end properties influencing the average prices.

The EDA also assessed the five-year sales transaction growth rate, Compound Annual Growth Rate (CAGR), and total revenue. Positive sales transaction growth trend was noticeable from 2017-2021 across NYC, Queens, and Richmond Hill. Queens and Richmond Hill demonstrated a CAGR of 4.96% and 4.76%, respectively, from 2003-2021, indicating steady growth over this timeframe. Richmond Hill registered a notable total revenue of $1.7 million in 2021, ranking second in Queens borough.

Our analysis suggests that Richmond Hill is a good new real estate office location. We must examine additional factors in more detail to make an informed decision. Specifically, we should look at metrics like property age, sale price per square foot, sale price per unit, and days on the market. These data points can give us deeper insights into the local real estate market. Additionally, we should consider operational costs, potential competition, and how our strategic objectives align with company goals. While we can use growth predictions and the CAGR to guide our analysis, we should be cautious since past performance doesn't always predict future results. Considering all these factors, we can determine if Richmond Hill is the right place to establish our new real estate office.

### Analysis 2 - Descriptive Analysis
#### Executive Summary
Our analysis of Richmond Hill's real estate market compared to other Queens neighborhoods and insights from the "NYC Real Estate Expansion: Analytics for Location and Specialization" report shows that opening a new real estate brokerage office in Richmond Hill is feasible and potentially profitable. Here are the key findings:
Trend Analysis: The average sale price per square foot in Richmond Hill has consistently increased over the past few decades, reaching $285.52. This trend indicates a growing and resilient real estate market.
Comparative Market Evaluation: Richmond Hill is a more affordable option than other neighborhoods in Queens, with an average sale price per square foot of $285.52 compared to Queens' average of $335.81. The market has the potential to attract investors.
Market Stability: The real estate market in Richmond Hill is more stable than other Queens neighborhoods, with a lower standard deviation in prices ($72.12 versus $91.41). This stability reduces investment risks and is attractive to prospective homeowners.
Market Position: While the average sale price per square foot in Richmond Hill is lower than the Queens average, it offers an affordability advantage that could attract diverse clients.

Richmond Hill's affordable real estate market is consistently growing and stable, making it attractive to home buyers and investors. However, it's important to remember that external factors like economic fluctuations, policy changes, or unforeseen events can impact the market's stability and growth trends. Additional analyses such as Time Series Forecasting, Spatial Analysis, Multiple Regression Analysis, Cluster Analysis, and Market Demand Analysis can help confirm Richmond Hill's potential for a new brokerage office.

### Analysis 3 - Descriptive and Diagnostic Analysis
#### Executive Summary
This analysis aimed to provide valuable insights for establishing new real estate brokerage offices in New York City, explicitly focusing on Richmond Hill's viability as a potential location. The analysis used a two-pronged approach to categorize neighborhoods based on their real estate market dynamics and compare Richmond Hill's residential property prices to other neighborhoods.

In the first phase, we grouped neighborhoods into two clusters using the K-means clustering algorithm based on median sale price, number of sales, and price per square foot. Cluster 1 (red) included neighborhoods with higher median sale prices, fewer sales, and a higher price per square foot, while Cluster 2 (blue) contained neighborhoods with lower median sale prices, more sales, and a lower price per square foot. We found Richmond Hill classified as part of Cluster 2.
The second phase involved comparing Richmond Hill's residential property prices to other neighborhoods using Welch's t-tests. The results indicated that Richmond Hill's property prices were lower than neighborhoods such as Jamaica, Jamaica Hills, Jamaica Estates, Forest Hills, and Kew Gardens but higher than Jamaica Bay (Queens) and South Jamaica. There is no significant difference in the mean sale price of properties in Richmond Hill and that of Ozone Park, while its property prices were significantly lower than Woodhaven's.

Overall, the results confirm our previous analyses’ findings and suggest that Richmond Hill could be a good location for a new real estate brokerage office. Despite the potential for lower commission amounts due to relatively lower property prices, the neighborhood's vibrant real estate market and affordability compared to surrounding areas could attract more potential buyers and facilitate more transactions.

### Analysis 4 - Predictive Analytics
#### Executive Summary
The project focused on identifying influential price factors, predicting future sales, and recognizing potential discrepancies in property valuations. We used several models:

ETS:
This model revealed that residential real estate sales in Richmond Hill have been consistently increasing since 2009. The ETS model predicted a continued rise in total sales for the next eight quarters, ranging from approximately $82.9 million in Q2 of 2022 to $87.7 million in Q1 of 2024. Despite having a higher AIC and BIC than the ARIMA model, we selected the ETS model due to its better forecast accuracy regarding MAE, RMSE, and MAPE.

Multiple Regression Models:
The first model considered time and seasonality and suggested that these variables could explain about 64.45% of sales variation. The second model found that Sale Date, Year Built, Gross Square Feet, and Number of Units were significant predictors of the sale price. Building Type was less significant, with specific building codes considered redundant. These variables explained about 69% of the sales variation. By analyzing p-values, we identified the most and least useful predictors, providing insights for decision-making regarding which property attributes significantly impact sale prices. The residual analysis showed that some properties sold for less or more than the predicted prices. 

This information can guide investment decisions and provide insights to clients. However, these insights should be supplemented with a comprehensive understanding of local market dynamics and other property-specific factors not included in the models. These insights suggest that Richmond Hill could be a good location for a new brokerage. However, it's essential to remember that these models and their results only capture part of the full complexity of the real estate market. Local market conditions, macroeconomic trends, and unexpected events could impact sales and prices, suggesting the need for ongoing analysis and monitoring.

### Analysis 5 - Prescriptive Analysis
#### Executive Summary
Our business case has systematically progressed through descriptive, diagnostic, predictive, and prescriptive analytics. We began with a comprehensive understanding of our historical data, where we identified key trends and patterns. We then diagnosed the causes of these patterns and used this understanding to predict future outcomes. Our cluster analysis, hypothesis testing, and predictive modeling consistently identified Richmond Hill as a unique opportunity due to its stable, low-price points compared to other neighborhoods.

In this prescriptive step, we developed an optimization model to guide our strategic decision to open a new brokerage in Richmond Hill. Our model optimized three key decision variables - commission rate, number of employees, and office size - and maximized our profit's NPV over eight quarters from 2022 Q1 to 2023 Q4. The model's results suggest a strategic roadmap for our new brokerage. We should maintain a commission rate of around 0.045 to attract a larger market share. The number of employees should remain constant at 1, which is sufficient to handle the market activity in Richmond Hill. The office size should stay constant at the minimum required size of 375 square feet to minimize rent and utility costs. With these recommendations, we expect to generate a total discounted profit of $1,443,088.49 and 6.75% market penetration over eight quarters.

In conclusion, prescriptive analytics has provided valuable insights to guide our decision-making, optimize our operations and achieve our financial goals. However, it's important to note that these recommendations rely on the current market conditions and our understanding of our variables. As with any model, monitoring performance and updating as necessary to reflect changing market conditions and new data is crucial. This ongoing commitment to data-driven decision-making will be vital to our sustained success in the Richmond Hill real estate market.
