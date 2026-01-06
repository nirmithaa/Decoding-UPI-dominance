# Decoding-UPI-dominance

# 📊 UPI User Switching Behaviour Analysis

This project analyzes **why users switch between UPI apps** by studying factors such as usability, rewards, security, and technical reliability.  
A machine learning model is built to **predict switching behaviour** and identify key drivers of user churn.

---

## 🎯 Objective

To analyze user switching behaviour among UPI apps and identify the most influential factors affecting user retention using machine learning techniques.

---

## 🗂️ Dataset

- **Source:** Structured survey responses from UPI users  
- **Features:** Demographics, digital familiarity, usability, rewards, security, transaction reliability, and social influence  
- **Target Variable:** Whether the user switched to another UPI app (Yes/No)

---

## 🧪 Methodology

- **Exploratory Data Analysis (EDA):**  
  Distribution analysis, missing value checks, and class balance assessment

- **Data Preprocessing:**  
  - Missing value imputation  
  - One-Hot Encoding for categorical variables  
  - Feature scaling using StandardScaler  
  - Implemented using a Pipeline and ColumnTransformer

- **Train–Test Split:**  
  80:20 stratified sampling

- **Model Used:**  
  Random Forest Classifier

- **Hyperparameter Tuning:**  
  RandomizedSearchCV with 5-fold cross-validation (ROC-AUC optimization)

- **Model Evaluation:**  
  Accuracy, F1-score, ROC-AUC, Confusion Matrix

- **Interpretation:**  
  Feature importance analysis

---

## 🔑 Key Findings

- Security and trust are the strongest drivers of switching behaviour  
- Offers, rewards, and cashbacks significantly influence user movement  
- Poor UI/UX and transaction failures increase switching probability  
- Younger and digitally familiar users are more likely to switch apps  

---

## 💡 Recommendations

- Strengthen security features and communication to build trust  
- Personalize rewards and cashback programs  
- Improve app usability and navigation experience  
- Ensure high transaction success rates and technical stability  

---

## 🏁 Conclusion

The analysis shows that UPI app switching is **not random** but driven by clear and measurable factors.  
By improving trust, usability, reliability, and reward strategies, UPI platforms can significantly reduce user churn and enhance long-term retention.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📌 Future Scope

- Include real-time UPI transaction behaviour data  
- Experiment with advanced ML models for improved accuracy  
- Build a churn prediction dashboard for business use  

---

## 👩‍💻 Author

**Nirmitha Ramakrishna**  
MSc Business Analytics  
Manipal Academy of Higher Education

---

⭐ *If you find this project useful, feel free to star the repository!*  
