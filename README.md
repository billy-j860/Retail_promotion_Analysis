# Retail_promotion_Analysis
This project analyzes the effectiveness of promotional campaigns on retail sales across different stores and product families. We investigate how promotions impact sales performance by using a dataset that includes daily sales data, store information, product categories, and promotion details.

### The dataset used in this project includes the following key information:
- Date of sales
- Store number
- Product family
- Sales amount
- Number of items on promotion
  
## Project Goals
1. Evaluate the overall impact of promotions on sales
2. Identify which product families benefit most from promotions
3. Analyze how different stores respond to promotional activities
4. Uncover temporal patterns in promotion effectiveness

## Link to dataset
https://www.kaggle.com/c/store-sales-time-series-forecasting/data?select=train.csv

## Methodology
The analysis uses Python, leveraging libraries such as pandas for data manipulation, matplotlib and seaborn for visualization, and scipy for statistical testing. Key steps include:
- Exploratory Data Analysis (EDA)
- Statistical comparison of promoted vs. non-promoted item sales
- Time series analysis of sales trends
- Store and product family comparative analysis
## Key Findings
- There are seasonal peaks during ceratin months like December suggesting holiday shopping influence
- weekends(Sartuday and Sunday) have significantly higher sales compared to week days (Monday to Friday) indicating customers preference to shop more during the weekend
- Some stores consistently experience higher sales than others which might be influenced by factors like foot traffic or area demographics
- Food products sell more than products in other categories like sanitary and clothing and home appliances showing a higher preference of products of certain category
- The scatter plot indicates that higher numbers of items on promotion correlate with increased sales, suggesting that promotions effectively drive sales volume. However the correlation is weak at 0.09 meaning promotions alone may not be sufficient to drive significant increases in sales.
