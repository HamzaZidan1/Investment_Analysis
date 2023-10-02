
# Data Analysis for Investment Strategies: A Case Study for Investgenics

## Introduction
This notebook is dedicated to solving business problems for Investgenics. The primary objective is to utilize data analysis, specifically using Pandas, to provide insights into which investment option among gold, oil, or stocks is the most stable. The analysis further delves into the volume of stocks sold and pinpoints the stocks with the highest and lowest volumes. This is intended to assist investors in making informed decisions for maximum returns with minimized risks.

## Contents
- ## I have been tasked with solving crucial business problems for Investgenics. In this module, I will be using my Pandas knowledge to analyze data and help the firm answer important questions. Specifically, I will be helping investors decide which of the three investment options - gold, oil, or stocks - is the most stable. To achieve this goal, I will be looking at data on the volume of stocks sold and identifying which stocks were sold with the highest and lowest volumes. This will help investors make informed decisions about where to invest their money for maximum returns with minimum risk.
- #
- ### 2. Create a subset DataFrame based on gold_stocks_price.csv
- ### Based on the data, it appears that gold prices are generally higher than oil prices, with a mean opening price of 149.03 for gold and 96.20 for oil. The range of prices for gold is also higher than for oil, with a maximum opening price of 173.20 for gold and 110.28 for oil. Both datasets show some variation in price, with standard deviations of around 17 for gold and 7 for oil. Additionally, there were no missing values for either dataset, and the subsetted dataframes contained 500 rows each. Overall, it appears that gold may be a more stable investment option than oil, but further analysis would be needed to make a conclusive decision between gold, oil, and stocks.
- ### To determine the daily average price of gold and oil in USD, I can use the mean() function in Pandas to calculate the average of each row (axis=1). I will then create a new column to insert the daily average price and view the DataFrame.
- ### To convert the daily average price of gold and oil to GBP, we can use a lambda function to multiply the values by the exchange rate of 0.8 (1 USD = 0.8 GBP). We will create a new column to insert the converted values and view the DataFrame.
- ### To compare the average gold and oil price in GBP, we can create subsets of the DataFrames with only the date and average price in GBP, and then merge the two DataFrames on the date column.
- ### To summarize, in this module, we will be using Seaborn and Matplotlib to visualize and analyze the data for the following business questions:
- ### Outlier analysis
- ### Create pairplots

## Summary
The preliminary analysis suggests that gold prices are generally higher than oil prices. Both datasets exhibit variation in prices, and there are no missing values for either dataset. Further exploration is encouraged to draw a more comprehensive conclusion on the investment options among gold, oil, and stocks.

---

*Note: For detailed analysis, observations, and code, please refer to the notebook.*

