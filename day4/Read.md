# Day 4/7 – Feature Engineering & Data Transformation 🛠️📊

## 📌 Project Overview
This project is part of my **7-Day Data Analysis Challenge using Python**.  
Day 4 focuses on **Feature Engineering & Data Transformation**, where raw and messy data is converted into meaningful, analysis-ready features.

## 📊 Dataset
**Google Play Store Apps Dataset**  
Source: Kaggle  
https://www.kaggle.com/datasets/lava18/google-play-store-apps

The dataset contains information about Android apps, including ratings, installs, price, size, category, and last updated date.

## 🎯 Objective
- Clean raw app data
- Handle missing and inconsistent values
- Engineer new features for better analysis
- Prepare a business-ready dataset

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  

## 🔧 Key Data Cleaning Steps
- Removed duplicate records
- Handled missing values safely using `.loc`
- Converted object columns into numeric formats
- Ensured datetime consistency without chained assignment issues

## ⚙️ Feature Engineering Performed
- Converted **Installs** from text to numeric
- Converted **Price** from string to float
- Transformed **App Size** into MB
- Extracted **Year** and **Month** from last update date
- Created **Paid vs Free** flag
- Bucketed ratings into categories (Poor, Average, Good, Excellent)

## 📈 Visual Insights
- Distribution of paid vs free apps
- Average rating comparison between paid and free apps
- Top app categories by total installs

## 📁 Output
- Cleaned and feature-engineered dataset exported as CSV
- Ready for further analysis or modeling

## 🧠 Key Learnings
- Feature engineering is a critical step between raw data and insights
- Using `.copy()` and `.loc` avoids chained assignment warnings
- Clean features significantly improve analytical clarity

---

