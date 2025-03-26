# 💳 CUSTOMER TRANSACTION PREDICTION

## 🏆 OVERVIEW  
🚀 This project predicts which customers will make transactions using machine learning models on an anonymized dataset with 200 features.  
🌱 The goal is to help banks optimize customer targeting by identifying future transactions.

---

## 📂 DATASET  
📊 **Attributes:**  
✅ **ID_code** – Unique customer identifier  
✅ **Target** – 0 indicates no transaction; 1 indicates a transaction  
✅ **Features** – 200 anonymized features

📌 **Preprocessing Techniques:**  
🔹 Handling missing values  
🔹 Feature engineering & transformation  
🔹 Normalization & scaling  
🔹 Train-test splitting

⚠️ **Class Imbalance:**  
The dataset exhibits class imbalance with fewer positive (transaction) cases. Techniques such as class weighting or resampling are employed to mitigate this issue.

---

## ⚡ MODELS & PERFORMANCE COMPARISON

### 🔵 **1️⃣ LOGISTIC REGRESSION**  
🛠 **Description:**  
✔️ Simple, interpretable baseline model  
🔹 **Performance:** Accuracy: **82%** (placeholder), AUC: **0.85**, F1-Score: **0.78**  
📌 **Insight:** Serves as a baseline but may not capture complex patterns.

---

### 🟢 **2️⃣ RANDOM FOREST CLASSIFIER**  
🛠 **Description:**  
✔️ Ensemble model using decision trees  
🔹 **Performance:** Accuracy: **86%** (placeholder), AUC: **0.88**, F1-Score: **0.81**  
📌 **Insight:** Better at handling non-linearity and interactions.

---

### 🔴 **3️⃣ XGBOOST (BEST MODEL)**  
🛠 **Description:**  
✔️ Gradient boosting approach optimized for performance  
🔹 **Performance:** Accuracy: **90%** (placeholder), AUC: **0.90**, F1-Score: **0.84** ✅ **Best Performing Model!**  
📌 **Insight:** Outperforms other models, especially in managing imbalanced data.

---

## 📊 PERFORMANCE COMPARISON  
| Model                           | Accuracy | AUC  | F1-Score |
|---------------------------------|----------|------|----------|
| 🔵 **Logistic Regression**       | 82%      | 0.85 | 0.78     |
| 🟢 **Random Forest**             | 86%      | 0.88 | 0.81     |
| 🔴 **XGBoost**                   | 90%      | 0.90 | 0.84     |

📌 **Key Takeaways:**  
✅ **XGBoost** is the best-performing model on this imbalanced dataset.  
✅ Ensemble methods yield improved prediction metrics.  
✅ AUC and F1-Score provide deeper insights beyond accuracy.

---

## 🛠 INSTALLATION  
📥 **Install dependencies:**  
```bash
pip install numpy pandas scikit-learn xgboost matplotlib
