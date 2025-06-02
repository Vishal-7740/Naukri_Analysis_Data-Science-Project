
# **📊 Naukri Job Market Analysis**  
# **Project Overview**
This project analyzes job postings from Naukri.com to uncover trends in hiring patterns, in-demand skills, salary distributions, and experience requirements. The goal is to provide data-driven insights for job seekers and HR professionals to make informed career and recruitment decisions.



---

## **🎯 Key Objectives**  
✔ **Analyze job postings** to identify market trends  
✔ **Extract insights** on top companies, skills, experience, and salaries  
✔ **Help job seekers** align skills with industry demands  
✔ **Assist HR professionals** in benchmarking hiring trends  

---

## **📂 Dataset**  
📌 **Source:** `Naukri.csv`  
📌 **Size:** **560 job listings**  
📌 **Key Features:**  
- **Company**  
- **Experience** (Years)  
- **Location**  
- **Ratings**  
- **Salary** (Range)  
- **Skills**  
- **Job Title**  

---

## **🔍 Methodology**  

### **1. Data Preprocessing**  
- Handled **missing values, duplicates, and inconsistent formats**  
- Cleaned **salary ranges, experience fields, and multi-value skills**  
- Standardized **categorical data** for analysis  

### **2. Exploratory Data Analysis (EDA)**  
🔹 **Univariate Analysis** (Single-variable trends)  
🔹 **Bivariate Analysis** (Relationships between variables)  

### **3. Feature Engineering**  
- Extracted **skills** using tokenization and keyword matching  
- Encoded **categorical variables** (Label Encoding)  
- Normalized **numerical features** (Standard Scaler)  

### **4. Model Building & Evaluation**  
- **Algorithms Tested:**  
  - **Logistic Regression**  
  - **Random Forest**  
  - **SVM**  
  - **Gradient Boosting**  
- **Best Model:** **Random Forest** (tuned with `GridSearchCV`)  
- **Evaluation Metrics:**  
  - **Accuracy Score**  
  - **Precision, Recall, F1-Score**  

### **5. Model Deployment**  
- Built a **Streamlit interface** for real-time predictions  

---

## **💡 Key Insights**  

### **📌 Hiring Trends**  
- **Top Companies:** **Accenture (30%)**, Oracle (10%), BNY Mellon (6.7%)  
- **Most In-Demand Roles:**  
  - **Finance Analyst (43.3%)**  
  - **Senior Analyst**  
  - **Research Analyst**  

### **📌 Skills in Demand**  
- **Technical:** Python, SQL, Machine Learning, AWS  
- **Finance:** Financial Analysis, Financial Reporting  

### **📌 Salary & Ratings**  
- **Salary:** Mostly **Medium-range**  
- **Company Ratings:** **4.0–4.5** (fewer reviews for highly-rated firms)  

---

## **⚠ Challenges Faced**  
- **Inconsistent Data Formats**  
- **High Dimensionality**  
- **Limited Skill Extraction**  
- **Overfitting Risk**  

---

## **🚀 Future Improvements**  
- **Advanced NLP for Skill Extraction**  
- **Handling Class Imbalance**  
- **Cloud Integration**  

---


```

---



### **Key Highlights**  
✅ **Finance & Analytics roles dominate**  
✅ **Python, SQL, Financial Skills** are critical  
✅ **Random Forest** outperformed other models  
✅ **Streamlit** makes insights accessible  

---

