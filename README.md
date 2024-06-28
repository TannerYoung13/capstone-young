# Data Analytics Capstone Project
# Tanner Young
## https://github.com/TannerYoung13/capstone-young
## https://www.overleaf.com/read/bhpmysqkxcfy#1dc6f2
## https://www.linkedin.com/in/tanneryoung13/

# Overview
The objective of this project is to analyze life expectancy and identify trends based on various socioeconomic and health-related factors. Life expectancy is a critical indicator of a population's overall health and well-being, reflecting the average number of years a person can expect to live based on current mortality rates. This analysis leverages the Life\_Expectancy\_Data.csv dataset, which encompasses data collected over several years from multiple countries. The dataset includes a range of variables such as GDP, adult mortality rates, access to basic sanitation, and immunization coverage, among others. 

# Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Necessary Python libraries (listed in requirements.txt)

# Installation
1. Clone the repository:
   git clone https://github.com/TannerYoung13/capstone-young
2. Install required packages: pip install -r requirements.txt

# How to create a Jupyter Notebook
1. Open Terminal: Ctrl+ or select Terminal > New Terminal.
2. Install Jupyter: pip install jupyter
3. Create a New Notebook: Press Ctrl+Shift+P to open the Command Palette.
Type Jupyter: Create New Blank Notebook and select it.
4. Run a Code Cell: Enter the following code in the first cell:
print("Hello, Jupyter Notebook in VS Code!")
Run the cell by clicking the Run button (play icon) next to the cell or by pressing Shift+Enter.

# Data set
The data set is from Kaggle and can be downloaded here: https://www.kaggle.com/datasets/arunjangir245/life-expectancy-data/data

# EDA
Exploratory Data Analysis Techniques used:
1. Statistics (mean, average, std)
2. Bar graphs
3. Correlation Heat maps
4. Line plots
5. Scatter plots
6. Histogram

The Correlation Heat Map showed that schooling and income had a high (.73 and .72) correlation with life expectancy. 
The scatter and line plot showed that Developed countries had a significant gap between Developing countries in terms of life expectancy.

# Machine Learning 
1. The Random Forest Regressor was used due to its robustness and ability to handle various data types.
2. The data was split into training and testing sets, standardized, and the model was evaluated using metrics like R-squared.

## Results
The project demonstrated that socio-economic and health-related factors significantly influence life expectancy. The Random Forest model was effective in predicting life expectancy, with income composition of resources (.72 correlation), HIV/AIDS percentage (.2 importance), and schooling  (.73 correlation) emerging as key predictors. The correlation heat map produced a correlation with income composition of resources at .72 correlation and schooling at .73 correlation. These findings suggest that improving economic conditions and access to education and healthcare can positively impact life expectancy. 