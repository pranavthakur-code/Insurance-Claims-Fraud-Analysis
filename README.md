# 🚗 Insurance Claims Fraud Analysis

## 📌 Project Overview
This project focuses on analyzing insurance claim data to identify fraud-related patterns and generate meaningful insights using Exploratory Data Analysis (EDA) and Machine Learning concepts.

The project includes:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Correlation Analysis
- Principal Component Analysis (PCA)
- Fraud Pattern Analysis

The objective is to understand customer claim behavior and detect possible fraudulent activities using data-driven techniques.

---

# 📂 Dataset Information

The dataset contains insurance claim records with features related to:
- Customer demographics
- Claim details
- Incident information
- Vehicle information
- Fraud labels

Target Variable:
- `fraud_reported`
  - Y → Fraud
  - N → Non-Fraud

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Missingno

---

# 📊 Project Workflow

## 1️⃣ Data Preprocessing
- Removed duplicate records
- Handled missing values
- Replaced invalid symbols
- Encoded categorical variables
- Applied feature scaling

---

## 2️⃣ Exploratory Data Analysis (EDA)

Performed analysis on:
- Fraud vs Non-Fraud distribution
- Customer age distribution
- Claim amount analysis
- Gender vs Fraud
- Incident type analysis
- Property damage analysis
- Police report availability
- Time-based analysis

---

## 3️⃣ Correlation Analysis
A heatmap was used to identify relationships between numerical features and understand feature dependency.

---

## 4️⃣ Outlier Detection
Boxplots were used to detect unusual claim values and extreme observations.

---

## 5️⃣ Principal Component Analysis (PCA)
PCA was applied for dimensionality reduction and visualization of fraud vs non-fraud cases.

---

# 📈 Key Insights

- Fraud cases are significantly lower than non-fraud cases.
- Claim amount alone is not a strong fraud indicator.
- Incident type and claim-related features show meaningful patterns.
- Gender does not significantly influence fraud occurrence.
- PCA visualization shows overlap between fraud and non-fraud cases, indicating the complexity of fraud detection.

---

# 🤖 Machine Learning Concepts Used

- Data Preprocessing
- Feature Scaling
- One-Hot Encoding
- PCA (Principal Component Analysis)

---

# 📷 Sample Visualizations

- Fraud vs Non-Fraud Countplot
- Correlation Heatmap
- Claim Amount Distribution
- PCA Visualization
- Age vs Claim Amount Scatter Plot

---

# 🚀 Future Improvements

- Implement fraud classification models
- Handle class imbalance using advanced techniques
- Deploy fraud detection system using Streamlit
- Apply advanced ML algorithms such as:
  - Random Forest
  - XGBoost
  - Neural Networks

---

# 📌 Conclusion

This project demonstrates how data analysis techniques can be used to study insurance claims and identify fraud-related patterns. The analysis highlights the importance of preprocessing, visualization, and dimensionality reduction in understanding complex fraud datasets.

---

# 👨‍💻 Author

**Pranav Thakur**
