# ❤️ Heart Disease Classification using Decision Trees & Random Forests

## 📌 Project Overview
This project is part of **Task 5 of the AI & ML Internship**.  
The goal is to build a **binary classifier** to predict the presence of heart disease using the **Heart Disease dataset**.  

We apply:
- Decision Tree Classifier  
- Random Forest Classifier  
- Model evaluation with accuracy, confusion matrix, classification report  
- Cross-validation for robust performance check  
- Feature importance analysis  
- Visualization of decision trees & feature contributions  

---

## 🚀 Run in Google Colab
Click below to open and run the notebook in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1k5Q5Gud0kS3gSMp7PCltwow-sv4jYpt4?authuser=1#scrollTo=e8VFhRITz39m)

---

## 📂 Repository Contents
- `heart.csv` → Dataset used for training & testing  
- `Decision_Tree_Random_Forest.ipynb` → Main Colab notebook with step-by-step implementation  
- `README.md` → Project documentation  
- `screenshots/` → Screenshots containing results
   

---

## 🔎 Steps Performed
1. **Data Loading & Exploration**
   - Checked dataset structure, summary statistics, and missing values  

2. **Data Splitting & Scaling**
   - Train-test split (80/20)  
   - Standardized features using `StandardScaler`  

3. **Decision Tree Model**
   - Built baseline decision tree  
   - Controlled overfitting with `max_depth`  
   - Visualized tree structure  

4. **Random Forest Model**
   - Trained ensemble of decision trees  
   - Improved accuracy & generalization  
   - Extracted feature importance  

5. **Evaluation**
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-score)  
   - ROC-AUC score  
   - 5-fold Cross Validation  

---

## 📊 Results
- **Decision Tree Accuracy (baseline):** `0.9853`
-           precision    recall  f1-score   support

       0       0.97      1.00      0.99       100
       1       1.00      0.97      0.99       105

accuracy                           0.99       205
macro avg 0.99 0.99 0.99 205
weighted avg 0.99 0.99 0.99 205


- **Decision Tree Accuracy (max_depth=4):** `0.8390`  

- **Random Forest Accuracy:** `1.0`  
          precision    recall  f1-score   support

       0       1.00      1.00      1.00       100
       1       1.00      1.00      1.00       105

accuracy                           1.00       205
macro avg 1.00 1.00 1.00 205
weighted avg 1.00 1.00 1.00 205


- **Cross-validation scores:** `[1.0, 1.0, 1.0, 1.0, 0.9853]`  
- **Average CV Accuracy:** `0.9971`  

---

## 🛠️ Tools & Libraries
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 🧾 Key Learnings
- Decision Trees can overfit; tuning hyperparameters like `max_depth` helps reduce it  
- Random Forests are more robust and generalize better by combining multiple trees  
- Feature importance helps interpret model predictions  
- Cross-validation ensures model performance is consistent across splits  

---

👩‍💻 **Author**  
Samruddhee Sapkale  
📅 *October 2025*  



