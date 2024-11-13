# Restaurant Insights Analytics

This project explores and analyzes restaurant-related data to provide actionable insights into customer preferences, restaurant ratings, pricing strategies, and predictive modeling. It aims to develop a foundational understanding of data analysis techniques, followed by advanced analysis and predictive modeling to gain insights into customer behavior and restaurant performance.
## Table of Contents 
- Project Overview
- Problem Statement
- Objectives
- Data Analysis & Methodology
- Insights & Results
- Predictive Modeling
- Data Visualizations
-  Usage
- Contributing
- Reference



## Project Overview
This project leverages data science techniques to analyze and predict restaurant ratings, customer preferences, and other key restaurant features. The project follows a multi-level approach:

1. **Data Exploration and Analysis:** Understand the structure, address missing values, and explore basic statistical properties.
2. **Advanced Analysis:** Investigate customer preferences, services like table booking and online delivery, and conduct feature engineering.
3. **Predictive Modeling and Insights:** Build regression models to predict restaurant ratings and perform feature relationship analysis.


## Problem Statement
**Level 1: Data Exploration and Analysis**
- **Objective:**

  Gain foundational skills in data exploration, descriptive analysis, and geospatial insights for a restaurant dataset.
- **Tasks:**

   Explore data structure, address missing values, and perform data conversions.
   Analyze distributions of categorical variables, calculate statistical measures, and identify top cuisines and cities.
- **Significance:**

Develop foundational data science skills for the restaurant industry and support data-driven decision-making.

**Level 2: Advanced Analysis**

- **Objective:**

 Enhance insights from the restaurant dataset by investigating table bookings, delivery services, pricing strategies, and feature engineering.

- **Tasks:**

 Analyze table booking and online delivery services.
Identify price range distributions, average ratings, and other customer insights.
Use feature engineering techniques to add new intelligence to the dataset.

- **Significance:**

Gain deeper insights into restaurant services, pricing, and customer preferences.

**Level 3: Predictive Modeling and Insights**

- **Objective:**

Use predictive models and customer preference analysis to extract deeper insights from the dataset.

- **Tasks:**

Build regression models to predict restaurant ratings.
Visualize and interpret relationships between cuisine types and ratings.
Evaluate and compare predictive models.

- **Significance:**

Support data-driven decision-making with predictive modeling, offering insights into customer preferences and restaurant ratings.

## Data Analysis & Methodology
### Data Overview:

-  The dataset contains 9,551 restaurant records with 21 columns, including attributes such as Restaurant Name, Location, Cuisine, Ratings, Price Range, and more.
-  Data preprocessing was performed to clean missing values, convert data types, and handle outliers where necessary.
### Key Insights from Data Exploration:

 - **Missing Values:** Minimal null values were detected, primarily within the 'Cuisines' column.
-  **Popular Cities:** Cities like New Delhi, Gurgaon, and Noida exhibited the highest concentration of restaurants.
-  **Cuisines:** The most popular cuisines include North Indian and Chinese.
- **Geospatial Insights:** North America and India had the largest restaurant presence, with New Delhi leading in restaurant count.
  
### Descriptive Insights:

- **Ratings:** The 'Aggregate rating' column displayed a balanced distribution.
- **Table Booking and Delivery:**
   - 12.12% of restaurants offered table bookings.
   - 25.66% provided online delivery services.
 
# Insights & Results
## Key Observations:

- **Restaurant Ratings:**

  - The average restaurant rating is around 3.8 (on a scale of 5), with variation observed across different cuisines and price ranges.
  - Restaurants with table booking or online delivery tend to have higher ratings.
   
- **Cuisine Trends:**

  - North Indian and Chinese cuisines were the most popular, while Italian and Hawaiian had the highest average ratings.

- **Price Range vs. Ratings:**

  - Mid-range restaurants (₹500-₹1000) had the highest average ratings, whereas high-end restaurants (₹1000+) showed more variation.

- **Geospatial Insights:**

  - New Delhi led in the number of restaurants, followed by Mumbai and Bangalore.
  - The geographic distribution of restaurants showed clusters in urban areas with higher population density.

 ## Predictive Modeling
### Models:

1. **Linear Regression:**
  - A simple regression model was built to predict restaurant ratings based on features like cuisine, location, and price range. The model showed moderate predictive accuracy with an R-squared value of 0.65.

2. **Decision Tree:**
  - The decision tree model identified key features influencing ratings, with price range and cuisine type being the most significant.

3. **Random Forest:**
  - The random forest model outperformed others, achieving an R-squared score of 0.75 and a lower mean squared error (MSE).

## Feature Importance:

 -  **Price Range:** The most significant predictor of restaurant ratings.
 -  **Cuisine Type:** North Indian and Chinese cuisines generally showed higher ratings.
 -  **Services:** Offering table booking and online delivery was positively correlated with higher ratings.

## Data Visualizations

1. **Restaurant Ratings Distribution**
  A histogram shows a negatively skewed distribution, with most ratings clustered around 3.5 to 4.5 stars.
2. **Cuisine vs. Rating Heatmap**
  A heatmap of average ratings across different cuisines highlights that cuisines like Italian, Hawaiian, and Seafood have the highest average ratings.
3. **Price Range vs. Ratings**
  A scatter plot illustrates the correlation between price range and ratings, showing that mid-priced restaurants tend to have more consistent positive reviews.
4. **Geospatial Distribution of Restaurants**
  A map visualization shows the density of restaurants in major cities like New Delhi, Mumbai, and Bangalore


## Usage

**Data Exploration:**
    Open data_analysis.ipynb to perform basic data analysis, such as visualizing distributions, handling missing values, and exploring key insights.

**Predictive Modeling:**
    Open predictive_modeling.ipynb to train regression models and evaluate their performance in predicting restaurant ratings.

## Contributing
If you'd like to contribute, please fork the repository, make changes, and submit a pull request. Contributions are welcome in areas such as:

- Improving data preprocessing techniques
- Enhancing predictive modeling and evaluation
- Adding advanced analysis techniques (e.g., sentiment analysis from reviews)
- Developing more visualizations

## Reference
 - [Cognifyz Technologies Data Science Internship](https://www.cognifyz.com/careers/career.html)
