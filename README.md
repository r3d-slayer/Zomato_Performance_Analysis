# 🍽️ Zomato Performance Analysis

This project focuses on analyzing the Zomato restaurant dataset to uncover insights about restaurant performance, customer preferences, and business trends. It explores various aspects such as ratings, cost distribution, restaurant types, locations, and service offerings like online orders and table bookings.

---

## 📊 Project Overview

The goal of this project is to:
- Perform data cleaning and preprocessing of the Zomato dataset.
- Explore patterns between restaurant ratings, location, and cost.
- Visualize relationships between services (online order, table booking) and restaurant success.
- Identify top-performing and underperforming restaurants in Bangalore.

---

## 🧠 Key Objectives

- Handle missing and inconsistent data (e.g., "Not Rated", "NaN" values).
- Convert categorical columns like `book_table`, `online_order` into numerical form for analysis.
- Extract top 10 locations, cuisines, and restaurant types based on performance metrics.
- Visualize insights using Seaborn and Matplotlib.

---

## 📂 Dataset Information

The dataset includes the following important columns:

| Column | Description |
|--------|--------------|
| `name` | Restaurant name |
| `rate` | Average rating (out of 5) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Average cost for two people |
| `book_table` | Indicates if table booking is available |
| `online_order` | Indicates if online order is available |
| `location` | Area of the restaurant |
| `rest_type` | Type of restaurant |
| `listed_in(type)` | Type of service (e.g., Buffet, Delivery) |

---

## 📈 Analysis Highlights

- **Rating Distribution:** Understand how ratings vary across restaurants.
- **Online Order vs Rating:** Compare average ratings of restaurants with and without online orders.
- **Table Booking Impact:** Analyze if restaurants with table booking options receive higher ratings.
- **Top Locations:** Identify the most popular restaurant locations in Bangalore.
- **Top Restaurant Types:** Visualize which restaurant types attract the highest ratings.

---

## 🧰 Tools & Libraries

- **Python**
- **Pandas** — Data cleaning and manipulation  
- **NumPy** — Numerical analysis  
- **Matplotlib & Seaborn** — Data visualization  
- **Jupyter Notebook** — Interactive analysis  

---

## 🖼️ Output Visuals

Below are some example visualizations generated from this project:

| Visualization | Description |
|----------------|-------------|
| ![Rating Distribution](https://github.com/r3d-slayer/Zomato_Performance_Analysis/blob/e8f7ae4a551a987c71aea0ee19ec6bb726da33e8/images/rating%20distribution.png) | Distribution of Top 10 famous restaurant with ratings |
| ![Top Locations](https://github.com/r3d-slayer/Zomato_Performance_Analysis/blob/313019565152599d570529f1b9bb47ae623dba29/images/top%20locations.png) | Top 10 restaurant locations in Bangalore |
| ![Restaurant Types](https://github.com/r3d-slayer/Zomato_Performance_Analysis/blob/9cd7fb4c679dd3eaa6f0ea365c8aab3a67847334/images/restaurant%20type.png) | Top 10 restaurant types |

*(Place your output plots in an `images/` folder inside the repository.)*

---

## 📌 Insights Summary

- Restaurants offering **online orders** tend to have slightly better ratings.
- **Table booking availability** is correlated with higher customer engagement.
- Certain **locations** and **restaurant types** consistently outperform others.
- High cost doesn’t always guarantee high ratings — value for money matters.

---

## 🏷️ Author

**Shivam Tanwar**  
Frontend Developer & Data Analyst  
📧 tanwarshivam49@gmail.com  

---
