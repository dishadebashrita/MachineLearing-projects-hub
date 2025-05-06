# 🍽️ Zomato Data Analysis & Machine Learning Model

This project focuses on data analysis and predictive modeling using a global Zomato restaurant dataset. The goal is to gain insights into restaurant operations, user ratings, and delivery behavior, and to build models that can predict key business metrics.

---

## 📁 Dataset Overview

The dataset contains detailed information on restaurants listed on Zomato across various countries. It includes:

| Column | Description |
|--------|-------------|
| Restaurant ID | Unique identifier for each restaurant |
| Restaurant Name | Name of the restaurant |
| Country Code | Numeric country code |
| City | Location of the restaurant |
| Address | Full address |
| Locality / Locality Verbose | Neighborhood details |
| Longitude / Latitude | Geographical coordinates |
| Cuisines | Type(s) of cuisine offered |
| Average Cost for two | Cost estimate for two people |
| Currency | Local currency used |
| Has Table booking | Availability of table booking |
| Has Online delivery | Availability of online ordering |
| Is delivering now | Real-time delivery status |
| Switch to order menu | Availability of online menu |
| Price range | Price level (1 to 4) |
| Aggregate rating | Overall user rating |
| Rating color / text | Color and label associated with the rating |
| Votes | Number of votes the restaurant has received |

---

## 🎯 Project Objectives

- Explore the Zomato dataset to uncover useful patterns and insights.
- Clean, transform, and prepare data for analysis.
- Perform exploratory data analysis (EDA).
- Build machine learning models to predict key outcomes (e.g., ratings, delivery availability).
- Visualize trends and insights across countries, cities, and cuisines.

---

## 🔍 Exploratory Data Analysis

Key steps and visualizations include:

- Most popular cuisines by country and city
- Top rated restaurants and their common traits
- Correlation between pricing and rating
- Cities and countries with the highest restaurant density
- Restaurant delivery and booking trends
- Heatmaps of restaurant locations

---

## 🤖 Machine Learning Models Used

We applied several machine learning techniques to predict and classify aspects of the restaurant business:

- **Linear Regression** – To predict average cost or rating
- **Random Forest Classifier** – To classify whether a restaurant offers online delivery
- **Logistic Regression** – For binary classification (e.g., Has Table Booking or not)
- **KNN / Decision Trees** – For feature-based classifications

---

## ⚙️ Tech Stack & Libraries

- **Python**
- **Jupyter Notebook**
- **Pandas / NumPy** – Data manipulation
- **Matplotlib / Seaborn / Plotly** – Visualizations
- **Scikit-learn** – Machine learning models and evaluation

---


