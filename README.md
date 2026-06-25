# 🏡 Islamabad Property Price Intelligence

An end-to-end Data Science and Machine Learning project analyzing 1,250+ property listings from Islamabad's G-sectors (G-10, G-11, G-13, and G-14). This project demonstrates the complete data science workflow, from data cleaning and feature engineering to predictive modeling, market segmentation, and investment recommendation generation.

## 🎯 Project Objectives

* Predict property prices using machine learning models.
* Classify properties into Budget, Mid-Range, and Premium categories.
* Segment the real estate market using clustering techniques.
* Identify undervalued properties and generate investment recommendations.
* Extract actionable insights from real-world property listing data.

---

## 📊 Dataset

The dataset consists of 1,250+ property listings collected from Zameen.com.

### Key Features

* Property Price (PKR Crore)
* Location (Sector & Sub-Sector)
* Property Size
* Property Type
* Listing Age
* Seller Badge
* Listing URL

---

## ⚙️ Data Processing & Feature Engineering

Key preprocessing steps included:

* Parsing property size into numerical values.
* Extracting sector and sub-sector information.
* Identifying property types from listing titles.
* Converting listing age into numerical features.
* Handling outliers using IQR-based treatment.
* Creating demand and development indicators.

---

## 🤖 Machine Learning Models

### Property Price Prediction

| Model                   | R² Score | RMSE  |
| ----------------------- | -------- | ----- |
| Linear Regression       | 0.455    | 0.090 |
| Random Forest Regressor | 0.885    | 0.041 |

The Random Forest model significantly outperformed Linear Regression and was selected as the final valuation model.

### Price Tier Classification

Properties were categorized into:

* Budget
* Mid-Range
* Premium

A Random Forest Classifier was used to predict property tiers based on engineered features.

---

## 📈 Market Segmentation

Applied K-Means Clustering to identify distinct market segments based on:

* Property size
* Price
* Demand indicators
* Development metrics
* Listing characteristics

The analysis revealed multiple market segments ranging from budget properties in high-demand areas to premium properties in established locations.

---

## 💡 Key Insights

* Property Type was the strongest predictor of price.
* Listing Age showed a strong relationship with price adjustments.
* G-10 sector demonstrated the highest undervaluation signal.
* Commercial properties in high-demand areas offered the strongest value opportunities.
* Random Forest achieved high predictive accuracy for real estate valuation.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* K-Means Clustering
* Random Forest
* PCA
* Jupyter Notebook

---

## 🚀 Future Improvements

* Incorporate property amenities and neighborhood features.
* Add historical transaction data.
* Experiment with XGBoost and Gradient Boosting models.
* Build an interactive dashboard for property valuation.
* Deploy the model as a web application.

---

## 📌 Project Highlights

✅ End-to-End Data Science Workflow

✅ Feature Engineering & Exploratory Data Analysis

✅ Machine Learning for Price Prediction

✅ Classification & Market Segmentation

✅ Data-Driven Investment Recommendations

---

### Author

**[Your Name]**
Data Science Student | Machine Learning Enthusiast | Aspiring Geospatial & Analytics Professional
