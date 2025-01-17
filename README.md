# 🍴 Restaurant Planning and Analysis using Yelp Dataset

## 📖 Overview
This project focuses on identifying the ideal type of cuisine and location for setting up a new restaurant using the Yelp dataset from Kaggle. The analysis includes data exploration, transformation into a database format, and querying to derive actionable insights. A SQL Server database hosted on Azure was used to store the data, and SQL queries were executed to analyze trends and recommendations for restaurant planning.

---

## 🎯 Key Objectives
1. Explore and understand the structure of the Yelp JSON dataset.
2. Convert the JSON data into a format suitable for writing into an Azure SQL Server database.
3. Populate Azure SQL Server tables with data from Yelp.
4. Write and execute SQL queries to derive insights for restaurant planning, such as ideal cuisine types, city trends, and demand patterns.

---

## 🔑 Highlights

### Data Exploration
- **Datasets Analyzed**: 
  - `Business`
  - `Check-in`
  - `Review`
  - `Tip`
  - `User`
- Examined columns, structure, and metadata of JSON files.
- Conducted exploratory analysis to understand location, category, and temporal trends.

### Data Conversion and Database Creation
- Transformed JSON data into Pandas DataFrames for analysis.
- Used SQLAlchemy and PyODBC to connect and write data into Azure SQL Server tables.
- Ensured proper metadata and data type handling, including JSON columns.

### Insights Through SQL Queries
Executed 10 key queries to answer critical questions:
1. **Cuisine Demand**: Identified the most popular cuisines in Illinois cities.
2. **City-Specific Restaurants**: Analyzed restaurants offering Korean cuisine in selected cities.
3. **Reviews Analysis**: Evaluated reviews for specific restaurants to assess customer satisfaction.
4. **Operating Hours**: Extracted restaurant operating hours for better planning.
5. **Late-Night Demand**: Analyzed review text for evidence of demand for late-night services.
6. **Business Density**: Identified the busiest postal codes based on restaurant density.
7. **Customer Ratings**: Calculated average star ratings for specific restaurants.
8. **Tips and Recommendations**: Extracted customer tips for actionable insights.
9. **Attributes Analysis**: Investigated key attributes such as parking availability, seating, and ambiance.
10. **Competitive Landscape**: Assessed nearby restaurant density for strategic location planning.

---

## 🛠 Tools and Technologies
- **Python**: Used libraries such as `pandas`, `numpy`, `sqlalchemy`, and `pyodbc` for data transformation and database connectivity.
- **Azure SQL Server**: Hosted the database and executed SQL queries for analysis.
- **Kaggle**: Served as the platform for data exploration and analysis.
- **Yelp Dataset**: Provided the JSON data for businesses, reviews, check-ins, tips, and users.

---

## 🎨 Visualizations and Outputs
- **Cuisine Trends**: SQL-based outputs highlighting popular cuisines and their city-wise distribution.
- **Operational Insights**: Tables displaying operating hours and demand for late-night services.
- **Customer Feedback**: Reviews and star ratings analyzed for key takeaways.
- **Density Analysis**: Insights into business concentration by postal codes for competitive analysis.

---

## 📈 Conclusion
This project demonstrates the effective use of Yelp data and Azure SQL Server to extract valuable business insights for setting up a restaurant. The analysis helps determine:
- Ideal cuisine types based on customer preferences.
- Optimal locations considering demand and competition.
- Operating hours aligned with customer needs.

The approach combines exploratory data analysis, database transformation, and strategic querying to provide actionable recommendations.

---

## 📂 Repository Contents
- **notebook.ipynb**: Kaggle notebook with code for data exploration, transformation, and SQL queries
- **README.md**: Project documentation

---

## 🚀 How to Run
1. Clone the repository and open the `notebook.ipynb` file in Kaggle or Jupyter Notebook.
2. Ensure the dataset is in the `input` directory as referenced in the notebook.
3. Execute the cells to load, process, and analyze the data.
4. Use the `sql_queries.sql` file to replicate SQL analysis on your own Azure SQL Server instance.

---

## 🔗 Dataset Source
- [Yelp Dataset on Kaggle](https://www.kaggle.com/datasets/yelp-dataset)

---

## 👏 Acknowledgements:
This project is a result of successful collaboration with:
1. Zhuoran Yu
2. Cheng Chen
3. Aamish Samotra
