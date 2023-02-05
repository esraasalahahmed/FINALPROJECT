                            
                               ####   Stock index prices and Macroeconomic factors   #### 
                                         
The aim of this project is to analyze how major macroeconomic factors can affect the movement of stock index price.

BACKGROUND

There are many factors affect the movement of stock index price, and it depends also on the type of stock index. I am foucsing here on major macroeconomic factors such as Inflation Rate, Exchange Rate, Unemployment Rate, GDP growth, Oil Prices, and Percapita income.

DATA

I am using data from Kaggle and World Bank where I scraped some features. The data covers the timeframe from 1980 to 2020, and contains data for 8 countries ( China, France, Germany, India, Japan, Spain, United Kingdom and United States of America) and one special administrative region (Hong Kong). Major macroeconomic variables include: Inflation rate, Exchange rate, Per capita income , Unemployment rate, Manufacturing output, GDP growth and Oil prices. The target variable is stock index price.

DATA PROCESSING

. Data Loading and Scraping.

. Standarizing Headers, Checking info and Dtypes.

. Merge the two datasets.

. Checking and Dealing with NaN values.

. Perform EDA Explanatory Data Analysis Graphically

. Splitting between Numerical and Categorical Variables to perform Deeper cleaning.

. Concatenating cleaned data as a new Dataset.

. Building a Linear Regression Model and compare the score with other Regression Models

. Saving the cleaned Data to export to Tableau.

. Tableau Data Visualizations: https://public.tableau.com/views/final-project_16753400533390/IndexpriceperCountry?:language=en-GB&:display_count=n&:origin=viz_share_link

CONCLUSION & USEFUL INSIGHTS

The Linear Model shows that indeed these macroeconomic factors have a significant impact on the movement of the stock index price. The score is 0.80 for the linear regression model. However, the relationship between stock indices and some macroeconomic factors include some ambiguity.
For example, Oil Prices and Index price move togeather in the same direction, dispite the presumption that they are negetavily correlated. Also Exchange rate showed different direction of correlation. These results can be attributed to many different factors and depends on the counties included in the analysis.

Neverthless, one should pay attention to that the impact can also come from the target variable , meaning that there is an interdependancy between these variables. In addition, not all the factors have a direct relationship with the target as this was the case with Gross Domestic Produc (GDP).
