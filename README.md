# Portfolio

# Investment Strategy Optimization: Predicting Retail Chain Profitability

This project leverages machine learning and financial analytics to forecast store profitability for InstaMart, a supermarket chain. The analysis helps guide investment and expansion decisions by identifying key factors that drive revenue performance across store locations, sizes, and city tiers. By applying Linear Regression and Random Forest models, this project provides data-driven insights into optimizing future investments.

---

## **Project Overview**
This study examines:
- Profitability drivers across different store attributes, including location, size, and type.
- Investment decision-making by identifying high-performing stores and those with growth potential.
- Forecasting future revenue to support expansion and strategic business planning.

Key methodologies include:
- **Data Preprocessing**: Feature engineering to create relevant financial indicators, such as store age.
- **Exploratory Data Analysis**: Statistical insights to determine the impact of store characteristics on profitability.
- **Machine Learning Models**: Linear Regression and Random Forest to predict store revenue and guide investment decisions.

  ---

## **Key Features**
- **Revenue Forecasting**: Predictive models to estimate store profitability for strategic investment.
- **Investment Decision Optimization**: Identification of high-revenue stores for expansion and underperforming stores for improvement.
- **Financial Insights Dashboard**: Visualizations of profitability trends to support data-driven decision-making.

  ---

## **Key Insights**
- Store age and location significantly impact profitability, with **Tier 2 cities generating the highest revenue**.
- Supermarket chains with **medium-sized locations perform better** than small or large stores.
- Random Forest outperforms Linear Regression, capturing non-linear relationships in profitability trends.
- Investment strategies should **prioritize expanding in Tier 2 cities** and **optimizing high-revenue stores** for long-term growth.

  ---

## **Repository Contents**
- **Data**: Processed datasets in CSV format, ready for analysis.
  - `supermarket_data.csv`
- **Code**: Python scripts for statistical analysis and machine learning models.
  - `investment_strategy_analysis.ipynb`: Jupyter Notebook for for forecasting and model evaluation.
- **Figures**: Visualizations showcasing revenue trends and investment recommendations.
  - `profitability_by_store_type.png`
  - `investment_recommendations.png`
- **Documentation**: Detailed workflow and methodologies used in the analysis.

---

## **How to Use This Repository**
Clone the repository to your local machine:
 ```bash
   git clone https://github.com/aekamban/investment-strategy-analysis.git
```

🚀 Explore how data science drives smarter investment decisions in the retail sector!

---

# Climate Data Analysis: Coastal vs. Inland Regions in the Northeastern U.S.

This project explores a decade of climate trends (2013–2023) using NOAA's GSOD data to compare temperature and precipitation patterns between coastal and inland regions of the Northeastern United States. The analysis combines ArcGIS visualizations, statistical techniques, and storytelling to provide actionable insights into regional climate dynamics.

---

## **Project Overview**
This study examines:
- How average temperatures and precipitation patterns differ between coastal and inland areas.
- Seasonal trends and the impact of geographic proximity to the ocean on climate variability.

Key methodologies include:
- **Geospatial Analysis**: ArcGIS StoryMap to visualize temperature and precipitation trends.
- **Statistical Testing**: ANOVA and post-hoc pairwise t-tests to identify significant differences.
- **Cluster Analysis**: PCA and KMeans to explore relationships between climate variables.

---

## **Key Features**
- **Interactive ArcGIS StoryMap**: A dynamic narrative showcasing the spatial and seasonal differences in climate patterns.
- **Statistical Analysis**: Results from ANOVA, t-tests, and clustering highlight the statistical differences between coastal and inland regions.
- **Geospatial Visualizations**: Maps and graphs illustrating trends in temperature, wind speed, and precipitation across a decade.

---

## **Key Insights**
- Coastal regions exhibit **higher mean temperatures** and **less variability**, driven by oceanic moderation.
- Inland regions show **greater temperature extremes**, particularly during winter and fall.
- Seasonal differences are statistically significant, with **winter** showing the largest coastal-inland gap (**ΔT = 9.8°F**).

---

## **Repository Contents**
- **Data**: Processed datasets in CSV format, ready for analysis.
  - `processed_temperature_data.csv`
  - `precipitation_data_by_season.csv`
- **Code**: Python scripts for statistical analysis and visualization.
  - `climate_data_analysis.ipynb`: Jupyter Notebook for PCA, t-tests, and ANOVA.
- **Figures**: High-quality visuals exported from ArcGIS and analysis tools.
  - `temperature_trends_by_season.png`
  - `clustered_temperature_boxplot.png`
- **Documentation**: Step-by-step analysis workflow and methodology.

---

## **Access the Interactive Map**
Explore the climate trends in detail with our ArcGIS StoryMap:
[**ArcGIS StoryMap: Coastal vs. Inland Climate Trends**](https://storymaps.arcgis.com/stories/c77afddb483b4505aeb5386bebe24a83)

---

## **How to Use This Repository**
Clone the repository to your local machine:
   ```bash
   git clone https://github.com/aekamban/climate-data-analysis.git
```

---

# Business Data Analysis: Optimizing Restaurant Demand Forecasting and Customer Experience

This project focuses on analyzing customer order data from a food aggregator platform to identify demand trends across various restaurants and improve business decision-making. Leveraging PostgreSQL, Python, and Tableau, this analysis provides actionable insights to optimize restaurant partnerships and enhance customer experience.

---

## **Project Overview**
This study examines:
- Demand trends for restaurants across different time periods and locations.
- Customer ordering behavior based on preferences, delivery times, and ratings.
- Operational efficiency improvements to reduce delivery times and cancellations.

Key methodologies include:
- **Data Processing**: Using PostgreSQL for data extraction, cleaning, and transformation.
- **Exploratory Data Analysis**: Python (Pandas, NumPy) to uncover demand trends and performance insights.
- **Data Visualization**: Tableau dashboards to present key findings and actionable insights.

---

## **Key Features**
- **Demand Trend Analysis**: Identification of peak demand times and high-performing restaurant categories.
- **Customer Segmentation**: Insights into ordering behavior to optimize marketing strategies.
- **Operational Efficiency Optimization**: Recommendations to improve delivery times and customer satisfaction.

---

## **Key Insights**
- Peak demand occurs during lunch hours on weekdays, with specific cuisine types driving high order volumes.
- Restaurants with the highest ratings tend to experience lower order cancellations and higher repeat customers.
- Optimizing delivery routes based on order clusters can reduce average delivery time by 15%.

---

## **Repository Contents**
- **Data**: Processed dataset in CSV format, ready for analysis.
  - `restaurant_orders_data.csv`
- **Code**: Python scripts for statistical analysis and visualization.
  - `business_data_analysis.ipynb`: Jupyter Notebook covering data processing and insights.
- **Figures**: Visualizations showcasing demand trends and operational performance.
  - `demand_by_cuisine_type.png`
  - `customer_retention_analysis.png`
- **Documentation**: Detailed workflow and methodologies used in the analysis.

---

## **Access the Interactive Dashboard**
Explore the demand trends and insights through our interactive Tableau dashboard:
[**Business Tableau Dashboard: Optimizing Restaurant Demand Forecasting and Customer Experience**](https://storymaps.arcgis.com/stories/c77afddb483b4505aeb5386bebe24a83)

---

## **How to Use This Repository**
Clone the repository to your local machine:
   ```bash
   git clone https://github.com/aekamban/business-data-analysis.git
```

