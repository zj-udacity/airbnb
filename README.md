# Airbnb Data Analysis: Seattle vs. Boston

## Motivation

This project analyzes Airbnb listings, pricing strategies, and stay patterns in Seattle and Boston. The goal is to uncover insights about the correlation between listing features and review scores, the impact of pricing strategies on booking rates, and patterns in guest stay preferences across both cities.

## Libraries Used

- **pandas**: for data manipulation and analysis
- **numpy**: for numerical computations
- **matplotlib** and **seaborn**: for data visualization
- **scikit-learn**: for machine learning and data preprocessing
- **jupyter**: for running and documenting the analysis in a notebook format

## Files in the Repository

- **`boston/`**:
  - **`calendar.csv`**: Data on availability and pricing for Boston Airbnb listings.
  - **`listings.csv`**: Detailed information about each Airbnb listing in Boston, including price, description, and review scores.
  - **`reviews.csv`**: Reviews for each listing in Boston, with detailed comments and reviewer information.
  
- **`seattle/`**:
  - **`calendar.csv`**: Data on availability and pricing for Seattle Airbnb listings.
  - **`listings.csv`**: Detailed information about each Airbnb listing in Seattle, including price, description, and review scores.
  - **`reviews.csv`**: Reviews for each listing in Seattle, with detailed comments and reviewer information.

- **`udacity_project1_airbnb_seattle_boston.ipynb`**:  
  This Jupyter notebook contains the full analysis of the project, including:
  - Data cleaning and preprocessing steps
  - Exploratory data analysis (EDA) on Seattle and Boston listings
  - Analysis of pricing strategies and booking rates
  - Investigation of guest stay preferences in both cities
  - Summary of findings and insights

## Summary of Results

- **Property Type**: Townhomes are more popular in Seattle than in Boston, indicating a difference in guest accommodation preferences between the two cities.
  
- **Bathrooms and Beds**: Listings with more bathrooms and beds are associated with higher review scores. 

- **Host Response Time**: There is a strong correlation between faster response times and higher review scores in both cities. Listings where hosts respond more quickly to inquiries tend to receive better reviews, highlighting the importance of timely communication.
  
- **Pricing Strategies**: Analysis of pricing strategies, such as discounting and premium pricing, shows that Boston's approach to adjusting prices during high-demand periods may be more successful than Seattle's. 

- **Stay Preferences**: Results show that Boston is more favorable for both short-term and long-term visits compared to Seattle in the years 2016-2017. 

## Acknowledgements

- The data used in this project is publicly available through [Airbnb's website](https://www.airbnb.com/).
- This project is part of the Udacity Data Science Nanodegree program.
