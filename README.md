# 🏠 Airbnb Data Analysis Project

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on Airbnb listing data to uncover meaningful business insights that can help Airbnb optimize pricing strategies, understand customer preferences, and identify high-performing neighborhoods.

Using Python, Pandas, Matplotlib, and Seaborn, the dataset was cleaned, transformed, and visualized to answer key business questions related to listing prices, room types, neighborhood distribution, and customer reviews.

---

## 🎯 Business Questions Addressed

* What is the distribution of Airbnb listing prices?
* How are different room types distributed?
* How are listings distributed across neighborhoods?
* What is the relationship between price and room type?
* How has the number of reviews changed over time?

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains Airbnb listing information, including:

* Listing Name
* Host Name
* Room Type
* Price
* Service Fee
* Neighborhood Group
* Number of Reviews
* Reviews Per Month
* Last Review Date
* Availability Information

---

## 🧹 Data Cleaning Process

The following preprocessing steps were performed:

### 1. Missing Value Handling

* Converted `last review` column to datetime format.
* Filled missing values in:

  * `reviews per month` → 0
  * `last review` → earliest available review date
* Removed records with missing listing names and host names.

### 2. Data Type Conversion

* Removed `$` symbols from:

  * Price
  * Service Fee
* Converted them into numeric format.

### 3. Duplicate Removal

* Removed duplicate records to improve data quality.

### 4. Feature Selection

* Dropped irrelevant columns:

  * `license`
  * `house_rules`

---

## 📊 Exploratory Data Analysis

### 1️⃣ Distribution of Listing Prices

**Objective:** Understand pricing patterns across Airbnb listings.

**Visualization:** Histogram with KDE curve

**Insights:**

* Most listings fall within a lower-to-mid price range.
* A small number of premium listings create a right-skewed distribution.
* Pricing outliers are present.

---

### 2️⃣ Room Type Distribution

**Objective:** Identify the most common accommodation types.

**Visualization:** Count Plot

**Insights:**

* Entire homes/apartments dominate the platform.
* Private rooms form a significant portion of listings.
* Shared rooms have the lowest availability.

---

### 3️⃣ Neighborhood Analysis

**Objective:** Discover which neighborhoods have the highest number of listings.

**Visualization:** Horizontal Count Plot

**Insights:**

* Certain neighborhood groups contribute a majority of listings.
* High-density listing areas indicate stronger Airbnb activity.
* Useful for market expansion and promotional campaigns.

---

### 4️⃣ Price vs Room Type Analysis

**Objective:** Compare pricing across room categories.

**Visualization:** Box Plot

**Insights:**

* Entire homes/apartments generally command higher prices.
* Private rooms offer more affordable options.
* Significant price variation exists within each room type.

---

### 5️⃣ Reviews Over Time

**Objective:** Analyze customer engagement trends.

**Visualization:** Line Chart

**Insights:**

* Reviews fluctuate over time.
* Peaks indicate periods of increased bookings and activity.
* Useful for understanding seasonality and demand patterns.

---

## 📈 Key Findings

✔ Airbnb pricing is heavily skewed toward lower-priced listings.

✔ Entire homes/apartments are the most popular listing type.

✔ Some neighborhoods significantly outperform others in listing volume.

✔ Room type strongly influences pricing.

✔ Customer engagement trends can be tracked effectively through review activity over time.

---

## 🚀 Business Impact

The insights generated from this analysis can help Airbnb:

* Optimize pricing strategies.
* Improve market segmentation.
* Identify high-demand neighborhoods.
* Enhance customer experience.
* Support data-driven business growth decisions.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Airbnb-Data-Analysis.git
```

2. Install dependencies

```bash
pip install pandas matplotlib seaborn
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```bash
AirbubDa.ipynb
```

5. Run all cells.

---

## 📷 Sample Visualizations

* Distribution of Listing Prices
* Room Type Distribution
* Neighborhood Analysis
* Price vs Room Type Comparison
* Reviews Trend Analysis

---

