# zomato-eda
zomata EDA PROJECT
This project performs an in-depth Exploratory Data Analysis (EDA) on Zomato restaurant data to uncover insights into customer ratings, popular cuisines, service types, and cost patterns. Using Python, Pandas, and Seaborn, it highlights key trends to support better business and customer decisions in the food delivery ecosystem.
🍽️ Zomato Restaurant EDA Project
📌 Project Overview
This project aims to perform Exploratory Data Analysis (EDA) on the Zomato restaurant dataset to understand factors influencing customer ratings, restaurant popularity, and service preferences.
##Dataset 
<ahref> :https://github.com/raseena123-a/zomato-eda</ahref>
🎯 Purpose
To explore Zomato’s restaurant data and uncover patterns in ratings, cost, cuisines, and locations, helping improve decision-making for customers and businesses.

❓ Key Questions
What factors affect restaurant ratings?

Do online ordering or table booking options impact ratings?

Which cuisines and locations are most popular?

How does cost vary across restaurants?

What are the most common service types?

📥 Data Collection
Source: Zomato dataset (zomato.csv)

Format: CSV (extracted from a ZIP file)

Key Columns: name, rate, cost, location, cuisines, online_order, book_table, votes, dish_liked, etc.

🧹 Data Cleaning
Removed duplicates

Handled missing values (e.g., in rate, cost, cuisines)

Converted cost to numeric

Cleaned rate column (removed 'NEW', 'nan', etc.)

Renamed columns for easier handling

📊 Data Analysis Procedure & Methods (Short)
Tools Used: Python, Pandas, Seaborn, Matplotlib

Approach:

Univariate analysis of individual features (like rate, cost, location)

Bivariate analysis (e.g., rate vs cost, rate vs online_order)

Visualized top cuisines, cities, and service types using bar plots, box plots, and scatter plots

📈 Key Insights
Restaurants offering online ordering or table booking generally have higher ratings.

Most common cuisines are North Indian, Chinese, and Fast Food.

Areas like BTM, HSR, and Indiranagar have the highest number of restaurants.

Both low-cost and high-cost restaurants receive good ratings, indicating no strong correlation between cost and rating.

📝 Conclusion
This EDA project provided insights into customer behavior, restaurant offerings, and preferences using Zomato data. It can help food platforms and restaurant owners improve strategies for better service and engagement.
