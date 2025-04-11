# 🏡 Enhanced Airbnb Listing Analysis for New Hosts in New Brunswick

## 📌 Problem Statement  
**What strategies can new Airbnb hosts in New Brunswick use to attract bookings, optimize pricing, and earn positive guest reviews in their first year of operation?**

---

## 🎯 Motivation  
New Airbnb hosts often struggle with setting competitive prices, gaining visibility, and managing guest satisfaction. This project aims to identify success factors that help new hosts thrive in their first year of operation using data-driven techniques.

---

## 🚀 Objectives  
- Identify key success factors for new Airbnb hosts in New Brunswick  
- Provide actionable insights through interactive analysis and machine learning models  
- Analyze how price, reviews, and seasonality influence occupancy  

---

## 📣 Acknowledgements  
This project was developed as part of an academic data science course.  
 🔗 Dataset Source
[![Raw Dataset](https://img.shields.io/badge/Download-Dataset-blue)](https://raw.githubusercontent.com/Naresh-Babu-Nangineedi/datasets/refs/heads/main/listings.csv)

---

## 🛠️ Approach  

The project is structured into the following stages:

1. **Data Collection**  
   - Sourced public Airbnb listings data for New Brunswick  
   - Imported via URL directly into Google Colab  

2. **Data Preprocessing**  
   - Cleaned missing values and formatted price columns  
   - Engineered new features such as occupancy rate  

3. **Exploratory Data Analysis (EDA)**  
   - Analyzed trends between price and occupancy  
   - Explored correlations and visualized review impact  

4. **Feature Engineering**  
   - Created binary target variable for high occupancy listings  
   - Selected features such as price and number of reviews  

5. **Modeling**  
   - Applied **Logistic Regression** (probability-based learning)  
   - Applied **Decision Tree** (information-based learning)  
   - Evaluated performance using accuracy and feature importance  

6. **Interactive Visual Analysis**  
   - Used `ipywidgets` for price range sliders  
   - Visualized how occupancy changes with price  

7. **Sentiment Analysis**  
   - Analyzed guest review sentiments using TextBlob  
   - Visualized overall sentiment distribution  

8. **Time Series Analysis**  
   - Identified seasonal trends in occupancy and pricing  

---

## 🧪 Techniques Used  
- Logistic Regression, Decision Trees  
- Feature Importance (Mutual Information)  
- Sentiment Analysis (TextBlob)  
- Visualizations with Matplotlib, Seaborn, and Folium  
- Interactive widgets using `ipywidgets`  

---

## 📈 Key Takeaways  
- **Price** and **number of reviews** are the most influential features for occupancy  
- **Positive reviews** correlate with higher booking rates  
- **Seasonal analysis** shows peak months in summer and early fall  
- Data-driven pricing strategies can help new hosts gain a competitive edge  

---

## 📂 How to Use  
1. Clone or download this repository  
2. Open the `.ipynb` file in **Google Colab** or **Jupyter Notebook**  
3. Run each cell sequentially to perform the complete analysis  
4. Use the interactive elements to explore price and occupancy dynamics  


