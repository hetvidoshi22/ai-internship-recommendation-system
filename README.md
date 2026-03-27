# 📊 AI-Based Internship Recommendation System

## 📌 Project Overview

This project focuses on analyzing internship data using Data Mining techniques.
The dataset is preprocessed, explored, and analyzed using machine learning algorithms such as Classification, Association Rule Mining, and Clustering.

---

## 📂 Dataset Description

The dataset contains internship details such as:

* Internship Id
* Company Name
* Internship Location
* Mode (Online / Offline / Hybrid)
* Stipend
* Skills Required
* Experience
* Duration
* Role
* Number of Openings

Total records: **354 entries** 

---

## 🧹 Data Preprocessing

* Created dirty dataset by introducing missing values and duplicates
* Filled missing values (e.g., stipend → ₹0/month, company → Unknown)
* Removed duplicates
* Cleaned text (Role, Mode formatting)
* Converted stipend into numeric (`stipend_clean`)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Internship Mode Distribution

* Online: 141
* Hybrid: 111
* Offline: 102 

### 🔹 Role Distribution

Top roles include:

* UI/UX Design
* Quality Assurance
* Business Development
* Data Science

### 🔹 Location Analysis

* Bengaluru has highest internships
* Followed by Delhi, Hyderabad, Mumbai

### 🔹 Duration Analysis

* Most internships are 2–6 months

### 🔹 Stipend Insights

* Average stipend ≈ ₹37,804
* Maximum stipend ≈ ₹99,521
* Minimum stipend ≈ ₹12,705 

---

## 🤖 Machine Learning Implementation

### 🔹 1. Classification

* Algorithm: Decision Tree
* Goal: Predict internship mode (Online/Offline/Hybrid)
* Features used:

  * Role
  * Location
  * Stipend
  * Duration

---

### 🔹 2. Association Rule Mining

* Algorithm: Apriori
* Metrics:

  * Support
  * Confidence
  * Lift

📌 Purpose:

* Discover relationships between features
* Example:

  * Certain roles are associated with specific durations

---

### 🔹 3. Clustering

* Algorithm: K-Means
* Features:

  * Stipend
  * Duration

📌 Output:

* Internships grouped into clusters:

  * Low stipend
  * Medium stipend
  * High stipend

---

## 📈 Visualizations

* Pie Chart → Internship Mode Distribution
* Bar Graph → Role & Location Distribution
* Feature Importance Graph
* Association Rule Graphs (Support vs Confidence, Lift)
* Clustering Scatter Plot
  
---

## 🎯 Key Insights

* Online internships are most common
* Certain roles dominate the market (UI/UX, QA, Business Dev)
* Internship duration is mostly short-term (2–6 months)
* Stipend varies widely across roles
* Clustering reveals clear grouping based on stipend and duration

---

## 🧠 Conclusion

This project demonstrates how data mining techniques can be applied to real-world internship data.
It helps in understanding patterns, predicting internship types, and grouping similar opportunities effectively.

