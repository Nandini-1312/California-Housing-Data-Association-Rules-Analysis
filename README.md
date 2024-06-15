# California-Housing-Data-Association-Rules-Analysis

Overview

This project applies association rules to the California Housing Data from Kaggle (https://www.kaggle.com/camnugent/california-housing-prices). The goal is to analyze patterns and associations in housing attributes using a binary incidence matrix and association rule mining techniques.

Project Tasks
a. Data Preparation and Binary Incidence Matrix Visualization
    
    Data Loading and Preprocessing:
    
    Read the dataset (housing.csv) and handle missing values in the total_bedrooms attribute by imputing the median.
    Convert numerical variables into categorical bins for creating a binary dataset.
    
    Binary Incidence Matrix:
    
    Transform the preprocessed data into a binary incidence matrix suitable for association rule mining.
    Visualize the binary incidence matrix using item frequency plots to understand frequent itemsets.
    
b. Top Three High Lift Rules

    Implement association rule mining (apriori algorithm) to identify rules with the highest lift.
    Output the top three rules based on lift values that indicate strong associations among housing attributes.
    
c. Top Four Rules According to Confidence

    Evaluate association rules based on confidence to uncover rules with strong predictive power.
    Display the top four rules ranked by confidence that provide insights into attribute relationships within the housing dataset.
    
d. Recommendations for Purchasing an Average Priced Home Near the Ocean

    Utilize association rules to guide recommendations for purchasing a home near the ocean. 
    Identify rules suggesting attributes such as average housing median age (15-30), fewer bedrooms, lower population density, smaller households (1-2 members), and higher median house values 
    (>400,000) in proximity to the ocean.
    
e. Characteristics Associated with Low Population Areas

    Analyze association rules to identify characteristics associated with low population areas in the dataset.
    Highlight attributes such as high median house values (>400,000), fewer bedrooms, very low household sizes (1-2 members), minimal total rooms, and moderate to high median incomes (12-20).
