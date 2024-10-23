This is a Household Power Consumption analysis and prediction project. Here's a brief description:

Project Overview:
- Created by Shaan Ahmed, a BCA student specializing in AI and Data Science
- Uses data from a single household in Sceaux (7km from Paris, France) collected between December 2006 and November 2010
- Main goal is to analyze and predict power consumption patterns using machine learning

Key Components:

1. Data Processing:
- Worked with a large dataset (2,075,259 entries)
- Used pandas and numpy for data manipulation
- Handled missing values and data type conversions
- Created time-based features from date/time data

2. Exploratory Data Analysis (EDA):
- Analyzed power consumption patterns across different time periods
- Created visualizations using matplotlib and seaborn
- Studied relationships between various power consumption metrics
- Generated yearly, monthly, and hourly consumption patterns

3. Features Used:
- Global active power
- Global reactive power
- Voltage
- Global intensity
- Sub-metering readings (1, 2, and 3)
- Time-based features (Day, Month, Year, Hour, Minutes)

4. Machine Learning:
- Implemented Linear Regression model
- Split data into training (67%) and testing (33%) sets
- Applied MinMaxScaler for feature scaling
- Achieved performance metrics:
  - Training Accuracy: 72.06%
  - Testing Accuracy: 71.54%
  - RMSE: 6.78
  - R² Score: 0.715

The project demonstrates a complete machine learning pipeline from data preprocessing to model evaluation, focused on understanding and predicting household electricity consumption patterns.
