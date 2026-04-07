# Automotive-Market-Analysis-EDA-on-11K-Cars-

🚗 Automotive Market Analysis (EDA on 11K+ Cars)<br>

📌 Overview  <br>

This project performs Exploratory Data Analysis (EDA) on a dataset of 11,914 car listings (1990–2017) to uncover patterns in pricing, performance, fuel efficiency, and market trends.

The goal is to extract actionable insights that help understand how different factors influence car prices and market positioning.

📂 Dataset Information <br>
File: data.csv
Rows: 11,914
Columns: 16
Key Features:
Make, Model, Year
Engine Fuel Type, Engine HP, Engine Cylinders
Transmission Type, Driven Wheels
Vehicle Size, Vehicle Style
Highway MPG, City MPG
Popularity, MSRP (Price)

🎯 Objectives <br>

The analysis is driven by the following key questions:

How does engine horsepower affect price (MSRP)?
Which car brands dominate the market, and are they also the most expensive?
How has fuel efficiency evolved over time?
Does transmission type (Manual vs Automatic) impact price and popularity?
How does price vary across vehicle sizes and styles?

🛠️ Tech Stack <br>
Language: Python
Libraries:
Pandas (Data Manipulation)
NumPy (Numerical Operations)
Matplotlib & Seaborn (Visualization)
Plotly (Interactive Visualization)

🧹 Data Cleaning <br>
Removed missing values in critical columns:
Engine HP
Engine Cylinders
Created a transformed feature:
log_MSRP → to handle skewness in price distribution

📊 Key Visualizations & Insights <br>
1. MSRP Distribution
Highly right-skewed distribution
Majority of cars priced between $20K–$60K
Log transformation reveals a near-normal distribution
2. Engine HP vs MSRP
Strong positive correlation
Higher horsepower → higher price
Luxury vehicles dominate high HP range
3. Top Car Brands
Chevrolet, Ford, Volkswagen dominate in volume
Luxury brands like BMW, Mercedes-Benz show deep segmentation
4. Average Price by Brand
Premium brands have significantly higher average MSRP
High variance within luxury segments
5. Market Segmentation
Clear clustering of:
Budget cars
Mid-range vehicles
Luxury segment

📈 Key Takeaways<br>
Price is heavily influenced by engine performance and vehicle size
Luxury brands focus on high-price, high-performance segments
Mass-market brands dominate in quantity, not price
Industry shows gradual improvement in fuel efficiency over time
