# 📘 Books Data Scraping, Analysis, and Dashboard

---

## 🎯 Project Overview
This project demonstrates an end-to-end workflow for data analysis, including:

- Web scraping of product data from [BooksToScrape.com](http://books.toscrape.com)
- Data cleaning and transformation using Python
- Exploratory Data Analysis (EDA) with visualizations
- Creation of an interactive Power BI dashboard to present insights

---

## 🗂️ Project Structure

book_scraping_project/
├── book_scraping_analysis.ipynb # Jupyter Notebook with scraping & EDA
├── books_clean.csv # Cleaned dataset ready for Power BI
├── README.md # Project description
├── dashboard/
│ ├── books_dashboard.pbix # Power BI dashboard file
│ └── dashboard_screenshot.png # Screenshot of the dashboard
└── plots/
├── rating_distribution.png
├── price_distribution.png
└── availability.png


---

## 📂 Dataset Description
**Source:** [BooksToScrape.com](http://books.toscrape.com)  
**Date Collected:** July 2025

**Fields:**
- `Title`: Book title
- `Price`: Price in GBP (£)
- `Rating`: Numeric star rating (1–5)
- `Availability`: Stock status

---

## 🛠️ Technologies Used
- **Python 3**
  - Requests
  - BeautifulSoup
  - Pandas
  - Matplotlib
  - Seaborn
- **Power BI Desktop**

---

## 📊 Exploratory Data Analysis
The notebook includes:
- Rating distribution analysis
- Price histogram
- Stock availability visualization
- Aggregated statistics

Sample visualizations:
<img width="841" height="547" alt="Price_distribution" src="https://github.com/user-attachments/assets/e1e386eb-e142-42bb-9633-d54a7905a1b2" />


<img width="695" height="470" alt="Ratings_distribution" src="https://github.com/user-attachments/assets/697f1e3b-928b-4b4d-9c92-fc50bd173861" />

---

## 📈 Power BI Dashboard
The Power BI dashboard includes:
- Ratings breakdown (pie chart)
- Price distribution (histogram)
- Summary cards for:
  - Total number of books scraped
  - Average price
  - Average rating

<img width="1395" height="742" alt="book_scraping_dashboard" src="https://github.com/user-attachments/assets/19e4cae4-ecad-445d-a3a7-a2d5bcd42aab" />


✅ **See `books_dashboard.pbix` for the live report.**

---

## 📝 Insights Summary
- Most books are rated between 3 and 4 stars.
- Prices range from £10 to £60, with a typical concentration between £20–£40.
- All books scraped were listed as *In Stock*.

---
## 🧩 Future Improvements
- Include book category and description.
- Schedule automated scraping updates.
- Deploy a web dashboard using Streamlit.

---

## 🙋‍♂️ Author
**Hemalatha**  
[Your GitHub](https://github.com/Hema3-gold)

