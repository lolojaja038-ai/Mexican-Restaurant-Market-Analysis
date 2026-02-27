# Mexican-Restaurant-Market-Analysis
Power BI Analysis of Mexican Restaurant Market Analysis: Identifying Investment Opportunities

Project Overview

In 2012, a comprehensive customer survey was conducted across various cities in Mexico to capture data on restaurant ratings, consumer demographics, and culinary preferences.
I transformed this raw survey data into an interactive Power BI dashboard. The primary objective of this project is to uncover actionable market insights that will guide business entrepreneurs and investors in making data-backed decisions on where to allocate their capital in the restaurant industry.

Data Preparation & Modeling
To ensure accuracy before analysis, the raw dataset underwent rigorous cleaning and structuring using Power Query:

 * Data Transformation: I replaced missing values in critical categorical columns (like Occupation and Budget) to ensure no data was dropped. I removed redundant columns (e.g., highly null Zip Codes) to optimize performance.
   
 * Feature Engineering: I created a custom conditional column to group individual consumer ages into logical demographic brackets (18-30, 31-50, 51-70, 71-90) for cleaner visualization.
   
 * Data Modeling: I built a robust Star Schema in Power BI. I established a centralized Ratings fact table connected to distinct dimension tables (Consumers, Restaurants, Cuisines). I also implemented bi-directional cross-filtering to accurately map consumer preferences against actual restaurant ratings.
   
Executive Insights & Business Questions Answered
1. What can you learn from the highest-rated restaurants? Do consumer preferences have an effect on ratings?

 * Insight: The data reveals a surprising trend: the vast majority of the top 10 highest-rated restaurants in this market do not serve alcohol.
   
 * Effect of Preference: Consumer preference heavily dictates the rating ceiling. When filtering average ratings by cuisine type, specific niches like Coffee Shops, Mediterranean, and Family-style restaurants naturally score significantly higher (averaging between 1.5 to 1.7 out of 2.0) compared to standard Fast Food or Pizzerias (which hover near 1.0).
   
2. What are the consumer demographics? Does this indicate a bias in the data sample?
   
 * Insight: The consumer base is overwhelmingly young and academic. Over 80% of the respondents are students, and the dominant age bracket is 18–30 years old. The majority also report operating on a "Medium" to "Low" budget.
   
 * Bias: Yes, there is a massive demographic bias. The survey heavily represents young adults rather than corporate professionals, families, or older demographics. Therefore, any business strategy derived from this data must be specifically targeted at the young-adult and student market.
   
3. Are there any demand & supply gaps that you can exploit in the market?
   
 * Insight: By comparing what consumers explicitly prefer (Demand) against what the current restaurants offer (Supply), several clear gaps emerged:
   * The Opportunity (High Demand / Low Supply): Pizzerias and Coffee Shops rank in the top 5 most desired cuisines by consumers. However, there is a severe lack of supply for both in the current market.
     
   * The Saturated Market: Mexican food is the most demanded, but it is heavily oversupplied. The competition here is fierce.
     
   * The Investment Trap: The market has a high supply of Bars, Fast Food, and Breweries, yet these do not appear anywhere near the top of what consumers actually want.
     
4. If you were to invest in a restaurant, which characteristics would you be looking for?
   
If I were advising an investment group entering this specific market, my data-backed recommendation would be to open a Coffee Shop or a Pizzeria targeted at young adults (18-30), operating with a medium price point, and explicitly without an alcohol license.

The Business Case:
 * It exploits a proven gap in the market where consumer demand heavily outweighs the current supply.
   
 * It perfectly aligns with the demographic bias of the city (young students with medium budgets).
   
 * It avoids the high overhead and licensing costs of serving alcohol, which the data proves is entirely unnecessary to achieve a top-tier customer rating in this region.
   
Dashboard Preview


Tools Used
 * Power BI: Data visualization, interactive dashboard creation, and DAX metric calculations.
   
 * Power Query: ETL processes, data cleaning, and conditional column mapping.

