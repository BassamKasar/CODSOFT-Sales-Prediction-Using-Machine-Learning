# Sales Prediction using Python

## Project Description
The goal of this project is to forecast the amount of a product that customers will purchase based on various advertising expenditures (TV, Radio, and Newspaper). Using Machine Learning, we can help businesses optimize their advertising strategies to maximize sales potential.

## Dataset Overview
The dataset used is **advertising.csv**, which contains:
* **TV:** Advertising dollars spent on TV for a single product in a given market.
* **Radio:** Advertising dollars spent on Radio.
* **Newspaper:** Advertising dollars spent on Newspaper.
* **Sales:** Sales of a single product in a given market (Target Variable).

## Key Steps Involved
1. **Data Cleaning:** Checked for null values and outliers.
2. **Exploratory Data Analysis (EDA):** Visualized relationships using Seaborn and Matplotlib. 
   - Found that **TV** advertising has the highest correlation with Sales.
3. **Model Building:** 
   - Algorithm: **Linear Regression**
   - Data Split: 80% Training, 20% Testing.
4. **Evaluation:**
   - **R-Squared:** ~0.906 (90.6% accuracy in explaining variance)
   - **MSE:** ~2.91

## Requirements
* pandas
* matplotlib
* seaborn
* scikit-learn

## Results
The model demonstrates that TV advertising is the most effective channel for this business model. By reallocating budget from newspapers to TV/Radio, the company can likely increase its sales figures.
