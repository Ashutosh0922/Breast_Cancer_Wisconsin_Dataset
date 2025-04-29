# Breast_Cancer_Wisconsin_Dataset

# Logistic Regression Binary Classification 

## Objective
Build a binary classification model using **Logistic Regression** to predict whether a tumor is **malignant (M)** or **benign (B)** based on diagnostic measurements.

## Dataset
- **Source:** Breast Cancer Wisconsin Diagnostic Dataset
- **Features:** Various medical metrics like radius, texture, perimeter, area, smoothness, etc.
- **Target:** `diagnosis` (converted to binary: M = 1, B = 0)

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## Step-by-Step Process

### 1. Data Preprocessing
- Loaded the dataset using `pandas`
- Dropped unnecessary columns: `id`, `Unnamed: 32`
- Converted categorical `diagnosis` column to binary values (M → 1, B → 0)

### 2. Train/Test Split & Feature Scaling
- Split the dataset into training and testing sets (80/20 split)
- Standardized the features using `StandardScaler` to improve model performance

### 3. Model Building
- Built a **Logistic Regression** model using Scikit-learn
- Trained the model on the standardized training data

### 4. Model Evaluation
- Evaluated performance using:
  - **Confusion Matrix**
  - **Precision & Recall**
  - **ROC-AUC Score**
- Plotted the **ROC Curve**

### 5. Threshold Tuning and Sigmoid Explanation
- Tuned classification threshold manually (e.g., 0.6 instead of default 0.5)
- Explained and visualized the **Sigmoid Function** used in logistic regression

---

## Results
- The model effectively distinguishes between benign and malignant tumors.
- ROC-AUC and confusion matrix evaluations indicate strong classification performance.

---

## Visuals Included
- Confusion Matrix output
- ROC Curve
- Sigmoid Function Plot

---

## Conclusion
This project demonstrates how logistic regression can be applied to medical diagnostic data to build an interpretable and efficient binary classifier. Adjusting the threshold and understanding sigmoid function helps fine-tune predictions and improve decision-making in sensitive applications like healthcare.

