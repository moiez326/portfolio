![power of data](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2013.53.07.png)

# Data analysis portfolio
A collection of my data analysis projects. Each project includes a README with context, information, and visualizations:

## Table of Contents
- Nike vs Adidas shoe pricing and rating analysis
  - Project Insights
  - Data Source
  - Repository Structure
  - Conclusions and Recommendations
  - Future Directions
- Bank Loan Default Client Risk Factor Analysis
  - Project Insights
  - Repository Structure
- Shinkansen Travel Experience and Satisfaction Analysis
  - Project Insights
  - Demographic Impact
  - Key Findings
- US Adidas Geo-Spatial Sales and Trends Analysis
  - Project Insights
  - Regional Profit
  - Product Category Insights

## [Nike vs Adidas Shoe Pricing and Rating Analysis](https://github.com/moiez326/Nike_vs_Adidas/tree/main)
![shoes](https://www.vestilanatura.it/wp-content/uploads/2022/06/nike-vs-adidas-competizione-e-rivalita.jpg)

#### Context 
- The "Adidas Sales Analysis" project offers a comprehensive examination of Adidas' sales data in the United States. This analysis aims to decode patterns in sales, understand profitability dynamics, and grasp customer preferences.

### Key insight 
![chart 1](https://github.com/moiez326/Nike_vs_Adidas/blob/main/media/Screenshot%202023-11-28%20at%2013.23.57.png)
  
- Regression analysis shows a weak correlation between price and rating for both brands.
- Adidas exhibits marginally higher average ratings in the \$50 to \$100 price range. Nike, on the other hand, shows greater variability in customer ratings at higher price points.
#### Data Source
The analysis utilizes data from [Kash on Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike), featuring transactional sales data for various Adidas products across different US regions.

#### Repository Structure
- [Raw Data](https://github.com/moiez326/Nike_vs_Adidas/blob/main/data/shoes_raw_data.csv): The initial dataset.
- [Cleaned Data](https://github.com/moiez326/Nike_vs_Adidas/blob/main/data/shoes_cleaned_data.csv): The dataset post-cleaning and preprocessing.

#### Conclusions and Recommendations
- The study has identified pivotal product categories driving sales and profitability and highlighted regional differences in sales performance. Recommendations are provided for pricing strategies and inventory management to enhance Adidas' market position.
- Integrating external data like market trends and customer demographics for a more in-depth analysis.
- Employing machine learning models for predictive sales forecasting and trend analysis.

## [Bank loan default client risk factor analysis](https://github.com/moiez326/loandefault)
![Defaulting loan Analysis](https://media.istockphoto.com/id/1372053987/vector/default-bank-loans-isometric-3d.jpg?s=612x612&w=0&k=20&c=Rqy-n5FhihLGtOf6DtdKjyRI-8l2sRXPYjG69ie79cM=)

#### Context
- The "Global Bank Loan Default Analysis" delves into the complexities of loan defaults, a key aspect of financial risk management. This project investigates various client and loan characteristics to identify the factors that significantly influence loan defaults at Global Bank.

### Key insight  
![Chart 2](https://github.com/moiez326/loandefault/blob/main/media/Screenshot%202023-11-28%20at%2013.37.35.png)

- that loan amount is not a strong predictor of the debt-to-income ratio.
- defaulted loans tend to have a higher debt-to-income ratio, pointing to other contributory factors to loan default.

#### Conclusion and recommendations 
- a refocusing risk assessment process towards the borrower's credit history and the loan's purpose
- By making more categories within the categorical variables, Job and Reasons for loan, Global Bank can have a better picture of who their clients are and why they take out loans to better segment their risk.

## [Shinkansen Travel Experience and Satisfaction Analysis](https://github.com/moiez326/shinkansen)
![N700 series Shinkansen](https://www.japanhouselondon.uk/assets/New-Discover-page/_resampled/FillWyI3MjgiLCI0MDgiXQ/Shinkansen-Landing-page-banner.jpg)

#### Context 
- The "Shinkansen Passenger Satisfaction Analysis" project explores the crucial aspects influencing passenger satisfaction on Japan's renowned bullet train. This analysis is centred on understanding the diverse elements contributing to the overall travel experience.

#### Key insight 
![chart 3](https://github.com/moiez326/shinkansen/blob/main/media/Screenshot%202023-12-06%20at%2011.58.55.png)

- Gender and age significantly impact satisfaction levels. Elderly and younger demographics show differing levels of satisfaction, highlighting a potential need for targeted service improvements.

### Conclusion and recommendations
- Shinkansen should prioritize enhancing marketing strategies for different age and gender groups, especially focusing on the elderly and leisure travellers

## [US Adidas Sales Analysis](https://github.com/moiez326/US-Adidas-sales)
![Adidas logo](https://1000logos.net/wp-content/uploads/2019/06/Adidas-Logo-1991.jpg)

#### Context 
- The "US Adidas Sales Analysis" delves into Adidas's sales data across various U.S. regions, focusing on understanding consumer preferences and uncovering commerce patterns vary across U.S. regions, states, and cities?

#### Repository Structure
- [adidas_EDA.ipynb]: Jupyter notebook containing in-depth EDA and visualizations.
- adidas_csv_master.csv: Raw sales data.
- final_adidas.csv: Cleaned and processed sales data.
- stores.csv: Subset data for Adidas retail stores.
- orders.csv: Subset data for order information.

### Key insight
![chart 4](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2012.04.13.png)

- Women's Street Footwear and Men's Street Footwear are the highest profit categories, particularly in the West region, which leads in operating profits across most product types.
- Men's Apparel has the lowest average operating profit, suggesting it is the least profitable category, especially in the Midwest and Southeast regions.
- The Southeast region shows growth potential, with overall lower profits indicating an opportunity for targeted marketing and sales initiatives.

### Conclusion, and recommendations
- This analysis sheds light on key strengths and growth opportunities in Adidas's U.S. sales. Strategic decisions and marketing efforts informed by these insights can significantly boost regional sales and align with consumer preferences and product category performance.
- further research into the web-shopping experience and creating sales based on customers' preferences and regional segmentation
