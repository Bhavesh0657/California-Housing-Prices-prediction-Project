# California-Housing-Prices-prediction-Project

## Introduction:

This project aims to analyze a dataset containing various features related to housing in California. The dataset includes information such as geographical coordinates, housing median age, total rooms, total bedrooms, population, households, median income, median house value, and ocean proximity.

Features in the dataset can be categorized as follows:

1. Nominal: Ocean Proximity (e.g., "Near Ocean", "Inland", etc.)
2. Ordinal: None
3. Discrete: Housing Median Age, Total Rooms, Total Bedrooms, Population, Households
4. Continuous: Longitude, Latitude, Median Income, Median House Value


# Question-wise Analysis:

1. Average Median Income:
We calculate the average median income and visualize its distribution using appropriate plots to understand its spread across the dataset.
2. Distribution of Housing Median Age:
We draw a plot to visualize the distribution of housing median age, aiming to observe trends or patterns within the dataset.
3. Relationship between Median Income and Median House Values:
Through visualization, we explore how median income and median house values are related, which can provide insights into the housing market dynamics.
4. Handling Missing Values (Deletion):
We create a new dataset by removing examples where total bedrooms are not available, ensuring data integrity.
5. Handling Missing Values (Mean Imputation):
Another dataset is created by filling missing values in total bedrooms with the mean value from the original dataset.
6. Median Value Calculation (User-defined Function):
A user-defined function is created to calculate the median value of the dataset where applicable.
7. Latitude vs Longitude:
We plot latitude versus longitude to visualize the geographical distribution of housing data points.
8. Creating Dataset for 'Near Ocean' Proximity:
A new dataset is formed containing only the examples where ocean proximity is classified as 'Near Ocean'.
9. Mean and Median of Median Income for 'Near Ocean' Data:
We compute the mean and median of the median income for the dataset created in question 8 to understand the income distribution for areas near the ocean.
10. Creating New Column for Total Bedroom Size:
We add a new column named 'total_bedroom_size' based on predefined criteria of small, medium, and large bedroom sizes.
