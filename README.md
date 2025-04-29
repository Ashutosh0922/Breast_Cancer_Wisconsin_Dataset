# Breast_Cancer_Wisconsin_Dataset

# 🧪 Logistic Regression Classifier:

This project demonstrates how to build a binary classifier using **Logistic Regression** on the Breast Cancer Wisconsin dataset. The goal is to classify tumors as **Malignant (M)** or **Benign (B)** based on various cell nucleus features.

---

## 🛠️ Tools & Libraries Used
- Python 🐍
- Pandas 📊
- Scikit-learn 🤖
- Matplotlib 📈

---

## ✅ Steps Performed

### 1️⃣ Load and Explore Data
- Loaded the dataset using `pandas`
- Dropped unnecessary columns: `id` and `Unnamed: 32`
- Converted `diagnosis` column to binary values:  
  - `M` → 1 (Malignant)  
  - `B` → 0 (Benign)

### 2️⃣ Preprocessing
- Split the data into **training and testing** sets using `train_test_split`
- Standardized feature values using `StandardScaler`

### 3️⃣ Model Training
- Built a **Logistic Regression** model using `LogisticRegression` from `sklearn`
- Trained the model on the training data

### 4️⃣ Evaluation 📊
- Evaluated the model using:
  - **Confusion Matrix**
  - **Precision**
  - **Recall**
  - **ROC-AUC Score**
  - **ROC Curve Plot**

### 5️⃣ Threshold Tuning & Sigmoid 📉
- Demonstrated how to **tune the classification threshold**
- Explained and plotted the **Sigmoid Function** used in Logistic Regression

---

## 📈 Output Examples
- Confusion Matrix
- ROC Curve with AUC
- Sigmoid Curve

---

## 🚀 Conclusion
This project successfully builds a logistic regression classifier for binary tumor diagnosis, highlighting the power of basic ML tools in healthcare prediction tasks.

---

