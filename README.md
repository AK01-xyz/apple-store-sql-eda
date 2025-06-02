# 📱 Apple Store EDA using SQLite

## 📌 Objective
Perform exploratory data analysis (EDA) on Apple Store app data using SQL to uncover insights into app genres, ratings, pricing, description length, and more.

---

## 📁 Dataset Description

The data comes from two main tables:

- `AppleStore`: Contains details about app names, genres, ratings, price, etc.
- `appleStore_description_combined`: Merged table from four sources containing app descriptions.

---

## 🛠️ Tools Used

- SQLite (via [sqliteonline.com](https://sqliteonline.com))
- SQL (for queries and analysis)

---

## 📊 Key Exploratory Steps

1.  Checked for duplicate or missing app IDs  
2.  Identified missing values in key fields  
3.  Counted number of apps per genre  
4.  Calculated rating stats: min, max, and average  
5.  Compared ratings between paid vs free apps  
6.  Analyzed language support vs rating  
7.  Found genres with the lowest average ratings  
8.  Studied description length vs user ratings  
9.  Listed top-rated apps per genre  

---

## 🔍 Interesting Insights

- **Paid apps** tend to have slightly higher average ratings than free apps.
- Apps supporting **more languages (>30)** often get better ratings.
- Genres like **Productivity and Finance** have relatively lower average user ratings.
- Longer app descriptions are **positively correlated** with higher user ratings.
- For each genre, we ranked the **top-rated apps** using SQL `RANK()` function.

---

## 📁 Files Included

- `AppleStore_EDA.sql`: Complete SQL script used for analysis
- `screenshot.png`: SQLiteOnline final output
- `README.md`: Project documentation

---

## 📎 How to Run

1. Open [sqliteonline.com](https://sqliteonline.com)
2. Select SQLite → Paste the code from `AppleStore_EDA.sql`
3. Run queries step-by-step to explore the data

---

## ✅ Conclusion

This project demonstrates the power of SQL in performing EDA. With just SQL queries and a simple browser-based tool, we extracted deep insights into app behavior on the Apple Store.

---
