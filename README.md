# Diwali Sales Analysis

## Overview
This project analyzes Diwali sales data to uncover key trends and insights that can improve customer experience and help businesses better understand their customer base. The analysis focuses on various demographic attributes, including **gender**, **age**, **marital status**, **occupation**, and **product categories**, to identify purchasing patterns and customer preferences during the Diwali festival period.

## Objective
The main objective of this analysis is to:
- Identify demographic trends related to purchasing behaviors during Diwali.
- Understand how customer attributes like gender, age, marital status, occupation, and location influence sales.
- Provide actionable insights that can help businesses enhance their marketing strategies and improve customer targeting.

## Methodology

The analysis follows these key steps:

1. **Data Cleaning**:
   - The data was cleaned by removing irrelevant and blank columns.
   - Null values were handled by dropping rows with missing values.
   - The data types of relevant columns (e.g., `Amount`) were converted to the correct format for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - **Gender**: Analyzed the gender-based purchasing patterns, highlighting that female customers tend to have higher purchasing power.
   - **Age Group**: Analyzed the relationship between age groups and sales, finding that the age group of 26-35 years, particularly women, makes the most significant purchases.
   - **State**: Investigated sales by state to identify the regions with the highest sales volume and amounts.
   - **Marital Status**: Explored the relationship between marital status and purchasing behavior, showing that married women have higher purchasing power.
   - **Occupation**: Analyzed the influence of occupation on purchasing patterns, finding that people working in sectors like IT, Healthcare, and Aviation tend to buy more during the Diwali period.
   - **Product Category**: Identified the top-performing product categories, such as Food, Clothing, and Electronics, based on sales volume and amount.

3. **Visualizations**:
   Various visualizations were created to represent the data and findings:
   - **Count plots** for gender, age group, marital status, occupation, and product categories.
   - **Bar plots** to compare total sales by gender, age group, state, and occupation.
   - **Top-selling products**: Bar charts to visualize the most popular products based on sales and orders.

## Key Insights

1. **Gender-based Insights**:
   - Female customers represent the majority of sales, both in terms of the number of orders and the total amount spent.
   - The purchasing power of women during Diwali is significantly higher than that of men.
     ![image](https://github.com/user-attachments/assets/76349a18-1cfd-4efe-9214-ed4b6ac4bca9)


2. **Age-based Insights**:
   - The **26-35 years** age group, particularly females, contributes the highest to the total sales amount.
   - Other age groups also show significant sales activity, but the 26-35 age group remains dominant.
     ![image](https://github.com/user-attachments/assets/91dceddc-094b-4f37-a045-678307568093)

3. **State-based Insights**:
   - **Uttar Pradesh**, **Maharashtra**, and **Karnataka** are the top states contributing to total sales during Diwali.
   - These states also show high order volumes, with a notable increase in the average amount spent.
     ![image](https://github.com/user-attachments/assets/e6f049ba-94ca-44ac-af0c-954c78b2c158)

4. **Marital Status and Occupation**:
   - **Married women** have higher purchasing power, and their spending significantly impacts the overall sales during Diwali.
   - Occupations in sectors like **IT**, **Healthcare**, and **Aviation** show strong correlations with higher sales.
     ![image](https://github.com/user-attachments/assets/f2d605c6-b7a4-4434-8eed-dd4b66e9399a)

5. **Product Categories**:
   - The top-selling categories during Diwali are **Food**, **Clothing**, and **Electronics**, which dominate the total sales volume.
   - Certain products within these categories, such as electronics and clothing, are especially popular during the festival.
     ![image](https://github.com/user-attachments/assets/6ef65d37-080b-4f65-b381-74dddf556a62)

## Conclusion

Based on the analysis, the ideal target customers for Diwali marketing campaigns are **married women aged 26-35** from **UP, Maharashtra, and Karnataka**, working in **IT, Healthcare, and Aviation** sectors. These customers show the highest engagement and spending in **Food, Clothing, and Electronics** categories during the Diwali festival.

This analysis provides businesses with valuable insights for improving their customer targeting, personalizing marketing strategies, and optimizing product offerings during Diwali.

## Project Structure

- **Diwali_Sales_Analysis.ipynb**: The Jupyter notebook that contains the entire data analysis, visualizations, and insights.
- **Diwali Sales Data.csv**: The dataset used for the analysis.
## Visualizations Included

The project includes the following types of visualizations:
1. **Gender Distribution**: Count plot showing the distribution of male and female customers.
2. **Age vs Purchase Amount**: Bar plot showing the total amount spent by different age groups.
3. **State-based Sales Trends**: Bar plot showing the top states by sales amount and order volume.
4. **Occupation and Spending**: Bar plot analyzing spending based on customer occupations.
5. **Product Category Analysis**: Visualizations showing which product categories had the highest sales.

## Next Steps for Improvement

- **Time Series Analysis**: Analyze sales trends over time, focusing on daily or weekly patterns during the Diwali season.
- **Customer Segmentation**: Implement clustering techniques (e.g., K-means) to segment customers based on their purchasing behavior.
- **Sales Prediction**: Use machine learning models to predict future sales or identify which customers are more likely to make a purchase.

### Notes for Interviewers:

- This project demonstrates proficiency in **data cleaning**, **exploratory data analysis (EDA)**, and **data visualization**.
- The findings from this analysis can help businesses make informed decisions regarding **target marketing**, **product offerings**, and **region-specific strategies** for the Diwali season.
- The code is organized and well-documented, with clear visualizations to support the insights derived from the data.
