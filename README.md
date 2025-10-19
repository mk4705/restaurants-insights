# 🍽️ Restaurant Data Analysis & Modeling — Internship Project  

> A **Machine Learning internship project @ Cognifyz Technologies** focused on extracting insights and building predictive models from restaurant data.

---

## 📂 Overview  
This repository showcases three end-to-end **machine learning tasks** built around a real-world restaurant dataset.  
Each task demonstrates different ML problem types — **regression, recommendation, and classification** — along with data preprocessing, feature engineering, and model evaluation.

---

## 📊 Dataset Description  
The dataset includes a variety of restaurant-related attributes:

| Category | Features |
|-----------|-----------|
| **General Info** | Restaurant Name, Cuisines, City, Locality |
| **Pricing & Services** | Average Cost for Two, Price Range, Has Table Booking, Has Online Delivery |
| **Ratings** | Aggregate Rating, Rating Text, Votes |

---

## 🧩 Task 1 — Predictive Modeling of Restaurant Ratings  

**🎯 Objective:**  
Predict the *aggregate rating* of a restaurant based on its attributes.  

**⚙️ Approach:**  
- Cleaned and encoded categorical features (e.g., booking, delivery options).  
- Selected key predictors influencing ratings.  
- Trained models:  
  - **Linear Regression**  
  - **Random Forest Regressor**  
- Evaluated with **R², MAE, MSE, and RMSE**.  

**✅ Results:**  
- **Random Forest Regressor** achieved superior performance with higher accuracy and lower errors.  
- Demonstrated the effectiveness of ensemble learning for prediction tasks.

---

## 🧮 Task 2 — Content-Based Restaurant Recommendation System  

**🎯 Objective:**  
Recommend restaurants similar to a chosen one using their features.  

**⚙️ Approach:**  
- Used **Cuisines, Price Range, and Ratings** as core similarity factors.  
- Combined them into unified text data.  
- Applied **TF-IDF Vectorization** for numerical representation.  
- Computed **Cosine Similarity** to rank similar restaurants.  

**✅ Results:**  
- Generated **highly relevant restaurant recommendations** sharing similar cuisines, costs, and ratings.  
- Built a reusable recommendation function with clear interpretability.

---

## 🍜 Task 3 — Cuisine Type Classification  

**🎯 Objective:**  
Predict the *primary cuisine type* of a restaurant (multi-class classification).  

**⚙️ Approach:**  
- Treated the *Cuisines* column as the target variable.  
- Applied models:  
  - **Logistic Regression**  
  - **Random Forest Classifier**  
- Evaluated using **Classification Report** and **Confusion Matrix**.  

**⚠️ Challenges:**  
- Dataset showed **heavy class imbalance**, with a few cuisines dominating.  
- Models tended to favor majority classes.  

**✅ Results:**  
- Highlighted real-world limitations of imbalanced data.  
- Provided insight into data preprocessing strategies and performance optimization.

---

## 🧭 Key Learnings  

- Hands-on experience with **Regression, Recommendation, and Classification**.  
- Understood the role of **feature engineering** and **data quality** in ML performance.  
- Discovered how **Random Forest** consistently delivers balanced results across diverse tasks.  

---

## 🧰 Tech Stack  

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python |
| **Libraries** | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |
