# Bike Rental Demand Prediction using Linear Regression

## General Information
- **Project Background**: This is my UpGrad data science project to predict bike rental demand for BoomBikes, a bike-sharing service provider in the United States, post Covid.
  - Identify key features impacting rental demand

## Technologies Used
- Python - 3.11
- Pandas - 2.0.1
- NumPy - 1.24.3
- Scikit-learn - 1.2.2
- Matplotlib - 3.7.1
- Seaborn - 0.12.2

## Data Overview
- Dataset: Bike rental data from BoomBikes
- Time Period: 2018-2019
- Features: 
  - Temporal: Date, Season, Month, Year
  - Weather: Temperature, Humidity, Wind Speed
  - Categorical: Holiday, Weekday, Working Day
- Target Variable: Total bike rentals per day

## Methodology
1. **Data Preprocessing**
   - Date feature extraction
   - One-hot encoding of categorical variables
   - Feature scaling
2. **Exploratory Data Analysis**
   - Correlation analysis
   - Distribution of variables
   - Temporal trend visualization
3. **Model Development**
   - Linear Regression
   - Train-test split
   - Feature selection and engineering

## Key Conclusions
1. **Model Performance**
   - R-squared: 0.8581
   - Explains 85.81% of variance in bike rental demand
2. **Feature Impact**
   - Temperature is the most significant predictor
   - Positive correlation with rental demand
3. **Seasonal Variations**
   - Substantial differences in rental patterns across seasons
   - Fall and Winter show higher rental tendencies
4. **Weather Influence**
   - Clear weather strongly encourages bike rentals
   - High humidity and wind speed reduce rental likelihood

## Recommendations for BoomBikes
1. Align marketing strategies with temperature trends
2. Prepare inventory based on seasonal demand variations
3. Develop weather-specific promotional campaigns
4. Focus on improving rental experience during less favorable conditions

## Future Improvements
- Apply advanced regularization techniques
- Explore non-linear modeling approaches
- Incorporate more external features
- Develop more sophisticated feature interactions

## Acknowledgements
- Inspired by machine learning applications in urban mobility
- Dataset provided by BoomBikes
- Guided by data science best practices

### Dataset Citation (as provided to us)
Use of this dataset in publications must cite the following research:

**Publication Reference:**
Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

## Contact
Created by Rahul Udayshankar Sinha (ML 69)
