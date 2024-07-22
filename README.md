# US-Nutrition-Analysis---R

![image](https://github.com/user-attachments/assets/47a5f4fd-8b7a-439b-81b3-c8cac510d7e8)

## Project Overview

This project is a comprehensive analysis of nutrition, physical activity, and obesity trends in the United States. The dataset used in this project is "Nutrition, Physical Activity, and Obesity," which includes information from various states in the US over multiple years. The analysis focuses on creating time series for national trends and comparing two populous states, California and Texas.

##Project Structure
The project is organized into several sections, each addressing different aspects of the analysis. The main sections are:

Data Preparation and Cleaning
National Trends Analysis
State Comparisons
Conclusion

## Data Preparation and Cleaning
The dataset is imported from a CSV file and cleaned to remove duplicate variables and those with excessive missing data. The remaining variables are renamed for clarity. A function is created to calculate the percentage of missing data for each variable, which guides further data cleaning decisions.

##National Trends Analysis
This section constructs time series for the entire US concerning obesity, physical activity, and fruit and vegetable consumption. The data is filtered by location and topic to create specific datasets for each trend.

##Obesity Trend
The obesity trend over the years is visualized using scatter plots and regression analysis. The analysis shows that the obesity score has increased over the years, and this increase is statistically significant.

##Physical Activity Trend
The physical activity trend is analyzed similarly, with additional steps to address varying sample sizes across years. The analysis reveals that physical activity levels have remained stationary over the years.

##Fruit and Vegetable Consumption Trend
The trend for fruit and vegetable consumption is visualized and analyzed, noting the limited years of available data. The analysis indicates no significant growth in fruit and vegetable consumption.

##State Comparisons
This section compares the trends between California and Texas. Data for each state is filtered and analyzed separately.

##Obesity Score Comparison
The obesity scores for California and Texas are compared using scatter plots and regression analysis. The results show that Texas has higher levels of obesity, and while obesity has risen in both states, California has experienced a more pronounced growth.

##Physical Activity and Fruit and Vegetable Consumption Comparisons
Similar analyses are conducted for physical activity and fruit and vegetable consumption scores. The results indicate that physical activity levels have remained constant in Texas but have decreased in California. Fruit and vegetable consumption has not shown significant increases in either state.

##Conclusion
The analysis concludes that:

1. National Trends:

The obesity score has increased over the years.
Physical activity and fruit-vegetable consumption remained stationary.

2.State Comparisons:

Obesity scores have increased over the years, especially in California.
Physical activity scores have decreased in California, remaining constant in Texas.
Fruit-vegetable consumption has not increased significantly in either state.
