
📊 Naukri Job Market Analysis 


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

## **📂 Repository Structure**  
```
📁 Naukri_Job_Analysis/  
├── data/  
│   └── Naukri.csv  
├── notebooks/  
│   ├── Data_Preprocessing.ipynb  
│   ├── EDA.ipynb  
│   └── Model_Training.ipynb  
├── models/  
│   └── random_forest_model.pkl  
├── app/  
│   └── streamlit_app.py  
└── README.md  
```

---

## **🔗 Get Started**  
```bash
streamlit run app/streamlit_app.py
```

---

**📧 Contact:** [Your Email] | **🔗 LinkedIn:** [Your Profile]  

---  

🚀 **Happy Job Hunting!** 🚀  

---

### **Key Highlights**  
✅ **Finance & Analytics roles dominate**  
✅ **Python, SQL, Financial Skills** are critical  
✅ **Random Forest** outperformed other models  
✅ **Streamlit** makes insights accessible  

---

This version uses **bold headings** (**`** **`) for better readability while keeping the structure clean and professional. Let me know if you'd like any refinements!
