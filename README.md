# EXPLORATORY DATA ANALYSIS – CAR INVENTORY ANALYSIS PROJECT

The Car Inventory Analysis project is designed to explore and analyze key insights from a dataset containing details about various cars, including their make, model, color, mileage, price, and cost. By applying data analysis and visualization techniques using Pandas, Numpy, Matplotlib, and Seaborn, the project aims to uncover trends, relationships, and key patterns within the dataset.

## Objectives 
- Clean and preprocess the dataset to ensure data integrity. 
- Analyze the distribution of car prices to understand pricing trends. 
- Examine how mileage influences the price of a car. 
- Visualize the number of cars available by brand and color. 
- Identify important insights that can help in pricing and inventory management.
  
## Expected Outcomes 

- A comprehensive understanding of the dataset through summary statistics. 
- Clear visual representations of car price distribution, mileage vs. price trends, and car counts by brand and color. 
- Identification of key factors affecting car pricing and inventory trends. 
- Actionable insights for decision-making in car pricing and inventory planning.

## Key Questions 
- What is the general price distribution of cars in the inventory? 
- How does mileage impact the price of a car? 
- Which car brands are most commonly available in the inventory? 
- What are the most popular car colors in the dataset? 
- Are there any noticeable pricing trends based on car make and mileage?


   CAR INVENTORY ANALYSIS PROJECT

  
### Project Overview 

This Data Analysis Project aims to provide insight from a dataset containing details about various cars, including their make, model, color, mileage, price, and cost. The project aims to uncover trends, relationships, and key patterns within the dataset.

### Tools

- Excel [website](https://office.com)
- Jupyter Notebook


### Cleaning and Preprocessing the Dataset
  To ensure data integrity:
  1. Importing Libraries & Loading Dataset
  2. Checking for missing values
  3. Removing duplicates (if any)
  4. Removing unwanted characters from numeric columns and convert to numbers

### Exploratory Data Analysis (EDA)

  Key Questions
  
- What is the general price distribution of cars in the inventory?
- How does mileage impact the price of a car? 
- Which car brands are most commonly available in the inventory? 
- What are the most popular car colors in the dataset? 
- Are there any noticeable pricing trends based on car make and mileage?

### Data Analysis
Code Used

Import Library and Dataset

<pre> import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load the dataset
df = pd.read_excel('Car Inventory.xlsx')  # Ensure the Excel file is in the same folder or provide full path

# Display first few rows
df.head()  </pre>
