# 🏍️ Bike Market Analysis

### Web Scraping & Exploratory Data Analysis

## 📌 Project Overview

This project focuses on **Bike Market Analysis** using real-world bike data collected through **web scraping**.

The collected data contains information such as bike name, brand, price, customer ratings, engine capacity, maximum power, braking system, tire type, and other specifications.

The data was cleaned, transformed, and analyzed to identify useful **market trends, pricing patterns, performance relationships, and business insights**.

---

## 🎯 Objectives

* Collect real-world bike data using web scraping
* Extract important bike details
* Clean and preprocess the scraped data
* Standardize maximum power values into BHP
* Analyze bike pricing and brand presence
* Analyze engine capacity and performance
* Understand customer ratings and reviews
* Identify relationships between price and performance
* Generate business insights and recommendations

---

## 🌐 Data Source

**Website:** Flipkart

**Category:** Non-Electric Motorcycles

**Final Dataset:** 263 bike records

**Features:** 11 columns

---

## 📊 Dataset Features

| Feature         | Description                |
| --------------- | -------------------------- |
| Product Name    | Bike model name            |
| Brand           | Manufacturer               |
| Price           | Bike price in INR          |
| Rating          | Customer rating            |
| Total Ratings   | Number of customer ratings |
| Total Reviews   | Number of customer reviews |
| Engine Capacity | Engine size in CC          |
| Maximum Power   | Engine power               |
| Front Brake     | Front braking system       |
| Console Type    | Instrument console         |
| Tire Type       | Type of tire               |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* BeautifulSoup
* Requests
* Selenium
* Jupyter Notebook

---

## 🔄 Project Workflow

```text
Web Scraping
     ↓
Data Collection
     ↓
Raw Dataset
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Business Insights
     ↓
Recommendations
```

---

## 🧹 Data Cleaning & Feature Engineering

The scraped data contained missing values, inconsistent formats, mixed data types, and unnecessary columns.

The following preprocessing steps were performed:

* Handled missing values
* Corrected data types
* Standardized categories
* Removed unnecessary columns
* Extracted power values
* Converted power values into BHP
* Prepared the final analysis-ready dataset

---

## 📈 Exploratory Data Analysis

The following business questions were analyzed:

### 1. Price Distribution

Most bikes are concentrated in the **lower-to-mid price segment**, with fewer premium-priced models.

### 2. Brand Market Presence

**Hero** has the highest number of bike models in the analyzed dataset.

### 3. Average Price by Brand

**Harley Davidson** has the highest average bike price among the analyzed brands.

### 4. Front Brake Distribution

**Disc brakes** are the most commonly listed front braking system.

### 5. Tire Type vs Price

Bikes with **tubeless tires** generally have higher median prices compared with tubed bikes.

### 6. Engine Capacity vs Maximum Power

Engine capacity and maximum power show a **positive relationship**, indicating that higher engine capacity generally results in higher power.

### 7. Price vs Performance

Higher-powered bikes generally tend to have **higher prices**.

---

## 💡 Key Business Insights

* Hero has the highest number of bike listings.
* Harley Davidson has the highest average bike price.
* The **100–200 CC** segment is the most commonly represented.
* Higher engine capacity generally produces higher power.
* Higher-powered bikes generally command higher prices.
* Disc brakes have widespread adoption in the analyzed dataset.
* Tubeless tires are more common among higher-priced models.

---

## 📌 Recommendations

Based on the analysis:

* Focus on the dominant price segment.
* Strengthen mid-range bike models.
* Balance price, performance, and features.
* Improve performance-to-price value.
* Promote highly rated bikes.
* Enhance safety and technology features.
* Maintain competitive pricing.

---

## ⚠️ Challenges Faced

* Dynamic web data
* Inconsistent data formats
* Missing values
* Different power units and formats
* Brand and category standardization
* Data cleaning
* Filtering electric-bike-related records

---

## 📁 Project Structure

```text
bike-market-analysis/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── cleaned/
│
├── notebooks/
│   └── bike_market_analysis.ipynb
│
├── src/
│   ├── scraping.py
│   ├── data_cleaning.py
│   └── analysis.py
│
├── visualizations/
│
└── presentation/
    └── Bike_Market_Analysis.pptx
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project folder

```bash
cd bike-market-analysis
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and run the cells.

---

## 📊 Final Result

The project successfully collected **263 bike listings** and transformed the raw scraped information into an analysis-ready dataset with **11 features**.

The analysis helped identify important relationships between **bike price, engine capacity, maximum power, brands, braking systems, and tire types**.

---

## 👨‍💻 Team

### Kurivella Bala Venkata Mani Kanta

* B.Tech (CSE)
* Data Science Trainee – Innomatics Research Labs

### Sankara P Manohar

* B.Tech (AI & DS)
* Data Science Trainee – Innomatics Research Labs

---

## 🙏 Thank You

**Bike Market Analysis – Turning Real-World Bike Data into Meaningful Market Insights.**
