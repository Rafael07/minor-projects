# Retail Metrics Analysis Project

## Business Understanding

### Retail Store Objective

A retail store aims to enhance performance tracking and decision-making by deriving key metrics from available client and sales databases. The metrics include determining the department with the most sales, calculating the average price with shipping by department, analyzing sales patterns by month, evaluating the average income by sales channel, and deriving the average customer age based on specific flags.

## Data Understanding

### Data Sources

1. **Client Base:**
   - Contains customer information, including age and other relevant attributes.

2. **Sales Base:**
   - Includes sales transactions data with insights into departments, prices, shipping, and sales channels.

## Data Preparation

### Business Premises

1. **Handling Missing States:**
   - For sales without a specified state, consider them as MS state.
   - In cases of missing prices, consider using the mean price for imputation.

2. **Price Feature Consideration:**
   - Ensure that the price feature does not surpass the price with shipping feature for accurate financial analysis.
   
## Data Exploration

### Metrics Definition

1. **Departmental Performance:**
   - Identify the department contributing the most to overall sales.

2. **Financial Insights:**
   - Calculate the average price, including shipping costs, for each department.
   - Evaluate the average income associated with each sales channel for strategic channel optimization.

3. **Temporal Analysis:**
   - Explore and visualize the monthly sales patterns to identify peak and off-peak periods.

4. **Customer Demographics:**
   - Derive the average age of customers based on specific flags for targeted marketing insights.

## Conclusion

Through comprehensive data understanding, preparation, and exploration, the project aims to deliver actionable insights derived from client and sales databases. Explore the analysis notebooks for detailed breakdowns of each stage and gain a holistic understanding of the retail landscape.
