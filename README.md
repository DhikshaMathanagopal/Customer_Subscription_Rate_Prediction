# Customer_Subscription_Rate_Prediction
Data mining and predictive analytics project using retail customer shopping trends to enhance subscription rates.

## 📄 Overview
This project focuses on using **data mining and predictive analytics** to enhance customer subscription rates in the retail sector.  
Using the **Customer Shopping Trends Dataset** from Kaggle, it explores customer demographics, purchasing behavior, and engagement patterns to predict the likelihood of subscription using machine learning techniques.

---

## 🧠 Objective
To build an end-to-end predictive model that identifies potential subscribers and provides data-driven insights to optimize marketing and customer retention strategies.

---

## 🧰 Tools & Technologies
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques:**  
  - Exploratory Data Analysis (EDA)  
  - Feature Encoding and Transformation  
  - Classification using Logistic Regression, KNN, and Gaussian Naive Bayes  
  - Dimensionality Reduction with PCA  
- **Environment:** Jupyter Notebook

---

## 📊 Dataset
**Source:** [Customer Shopping Trends Dataset – Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

- Contains **3,900 records** and **18 features** related to customer demographics, purchase patterns, and engagement data.  
- Attributes include: Age, Gender, Purchase Amount, Discount Applied, Frequency of Purchases, Review Ratings, Subscription Status, etc.  
- Balanced dataset suitable for classification and predictive modeling tasks.

---

## 📈 Project Workflow
1. **Data Collection** – Import and review the dataset from Kaggle.  
2. **Data Preprocessing** – Clean missing values, encode categorical features, and scale numeric variables.  
3. **Exploratory Data Analysis (EDA)** – Visualize data distribution, correlations, and customer behavior insights.  
4. **Feature Engineering** – Transform and select key attributes influencing subscription status.  
5. **Modeling** – Train multiple classifiers (KNN, Gaussian Naive Bayes, Logistic Regression).  
6. **Evaluation** – Compare model performance using accuracy, precision, recall, and F1-score.  
7. **Optimization** – Apply PCA to improve model generalization and interpretability.  

---

## 🚀 Results & Insights
- **Best Model:** Logistic Regression (after PCA)  
- **Accuracy:** ~95% across validation and test sets  
- **Key Findings:**
  - Discounts and positive review ratings significantly influence subscription likelihood.  
  - Frequent shoppers and high-spending customers have a higher probability of subscribing.  
  - Seasonal trends and promotions impact conversion rates.  

---

## 💡 Business Impact
- Enables **targeted marketing** and customer segmentation.  
- Improves **subscription conversion rates** through predictive personalization.  
- Supports **data-driven decisions** for campaign optimization and retention strategies.

To install dependencies:
```bash
pip install -r requirements.txt
