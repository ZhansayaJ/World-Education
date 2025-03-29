# Global Education Data Analysis and Literacy Rate Prediction

This project analyzes global education indicators and builds a **linear regression model** to predict **Adult Literacy Rate** based on various factors such as government expenditure, pupil-teacher ratios, and enrollment rates.

## Dataset

The dataset `world-education-data.csv` includes:
- Country and year
- Government expenditure on education (as % of GDP)
- Pupil-teacher ratios (primary and secondary)
- Enrollment rates (primary, secondary, tertiary)
- Adult literacy rate (target variable)

## Project Structure

1. **Data Preprocessing**:
   - Load dataset from Google Drive
   - Drop missing values
   - Rename columns for readability

2. **Exploratory Data Analysis**:
   - Histograms of numeric variables
   - Boxplots to detect outliers

3. **Modeling**:
   - Linear regression using `Adult Literacy Rate` as the target
   - Train/test split and performance evaluation (R² score)

4. **Visualization**:
   - Correlation heatmap
   - Predicted vs actual literacy rate scatterplot

