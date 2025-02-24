# E-commerce Platform Analysis - Linear Regression

## Project Overview
This project analyzes customer behavior data from an online clothing retailer to determine whether to prioritize development of their mobile app or website based on customer behavior and spending patterns.

## Analysis Goals
- Determine correlation between platform usage and spending
- Compare effectiveness of app vs website 
- Identify factors influencing customer spending
- Guide platform development priorities

## Dataset Description
The dataset contains customer behavior data including:
- Email & Address - Customer identification
- Avatar - UI personalization preference  
- Avg. Session Length - Time spent per shopping session (minutes)
- Time on App - Mobile app usage time (minutes)
- Time on Website - Website usage time (minutes)
- Length of Membership - Customer loyalty duration (years)
- Yearly Amount Spent - Total annual spending (dollars)

## Key Findings

### App vs Website Impact
- Time on App coefficient: 38.79
- Time on Website coefficient: 0.31
- App shows significantly higher revenue impact

### Strategic Recommendations
1. Mobile App Priority
   - Each additional minute on app generates ~38.79
   - Strong correlation with yearly spending
   - Focus on user engagement features

2. Website Improvement Opportunities  
   - Current low coefficient (0.31) indicates underperformance
   - Areas for enhancement:
     - User interface optimization
     - Website loading speed
     - Mobile responsiveness 
     - Checkout process streamlining

3. Long-term Considerations
   - Monitor coefficient changes over time
   - Track user behavior across platforms
   - Evaluate ROI of platform improvements
   - Consider competitive analysis

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy

## Getting Started
1. Clone this repository
2. Make sure you have Anaconda or Miniconda installed
3. Install required environment and packages: `conda env create -f environment.yml`
4. Run the Jupyter notebook: `jupyter notebook`
5. Open `linear_regression_e_commerce_notebook`

## Data Source
The dataset is stored in `data/Ecommerce Customers.csv`
