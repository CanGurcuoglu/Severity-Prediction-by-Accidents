# 🚦 US Traffic Accidents Analysis & Severity Prediction

This project analyzes a dataset of US traffic accidents to predict the severity of an accident based on weather conditions, location, and time. It employs various Machine Learning algorithms and handles class imbalance using SMOTE techniques.

## 🎯 Project Goal
* To analyze the correlation between environmental factors (weather, road conditions) and accident severity.
* To build a robust predictive model that can classify accident severity (1-4).
* To visualize accident hotspots using geospatial data.

## 🛠️ Technologies & Techniques
* **Python Libraries:** Pandas, Scikit-learn, XGBoost, Seaborn, Folium.
* **Data Processing:** Cleaning missing values, Feature Engineering.
* **Imbalance Handling:** Utilized **SMOTE** (Synthetic Minority Over-sampling Technique) and **Class Weights** to handle imbalanced severity classes.
* **Models Compared:** Random Forest, XGBoost, Logistic Regression, Decision Tree, KNN.

## 📊 Results & Key Findings
* **Random Forest with SMOTE** achieved the highest accuracy of **~97.6%**.
* **XGBoost** followed closely with ~90% accuracy.
* Weather conditions and time of day showed significant correlation with accident severity.

## 📸 Visualizations
| Confusion Matrix (RF) | Feature Importance |
|:---------------------:|:------------------:|
| ![CM](link_to_image)  | ![FeatureImp](link_to_image) |

## 🗺️ Geospatial Analysis
Clustering techniques (K-Means & DBSCAN) were used to identify accident hotspots.
![Map](link_to_map_image)

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run `analysis.ipynb`