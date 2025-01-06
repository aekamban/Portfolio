# Portfolio

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
[**ArcGIS StoryMap: Coastal vs. Inland Climate Trends**]([https://storymaps.arcgis.com/stories/c77afddb483b4505aeb5386bebe24a83])

---

## **How to Use This Repository**
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/climate-data-analysis.git
