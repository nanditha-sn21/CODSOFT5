# 💳 Credit Card Fraud Detection (Internship Task 5)

This project detects **fraudulent credit card transactions** using **Machine Learning in Python**.  

---

## 📊 Dataset
- Dataset: [Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- Features:  
  - Time  
  - Amount  
  - 28 anonymized numerical features (V1–V28)  
- Target:  
  - Class (0 → Legitimate, 1 → Fraudulent)  

---

## ⚙️ Workflow
1. Load dataset with Pandas  
2. Data exploration & class distribution analysis  
3. Train-Test split  
4. Feature scaling using **StandardScaler**  
5. Model training with **Random Forest Classifier**  
6. Model evaluation using:
   - Precision  
   - Recall  
   - F1-Score  
   - Confusion Matrix  

---

## 🚀 How to Run
1. Open the notebook in **Google Colab** or Jupyter Notebook  
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn seaborn matplotlib

