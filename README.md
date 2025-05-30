# Classification-with-logistics-regression
# 📝 AI & ML Internship — Task 4: Classification with Logistic Regression

## 📌 Objective
The objective of this task was to build a **binary classifier** using **Logistic Regression** and evaluate it with various performance metrics.

---

## 📚 Tools & Libraries Used
- **Python**
- **Scikit-learn**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **NumPy**

---

## 📊 Dataset
**Breast Cancer Wisconsin Dataset** from `sklearn.datasets`.

---

## 📌 Task Workflow

1. **Data Loading**  
   Loaded the Breast Cancer Wisconsin dataset using `sklearn.datasets`.

2. **Data Splitting & Scaling**  
   - Split dataset into train and test sets (80-20 split).
   - Standardized the feature values using `StandardScaler`.

3. **Model Building**  
   Trained a **Logistic Regression** model on the training data.

4. **Model Evaluation**
   - **Confusion Matrix**
   - **Classification Report** (Precision, Recall, F1-score)
   - **ROC-AUC Score**
   - **ROC Curve Visualization**

5. **Threshold Tuning**
   - Found optimal classification threshold.
   - Compared model performance before and after threshold adjustment.

6. **Sigmoid Function Explanation**
   - Visualized the sigmoid function to understand how logistic regression outputs probabilities.

---

## 📈 Results

- Achieved a high **ROC-AUC score**.
- Improved classification metrics by tuning the decision threshold.
- Visualized model performance with confusion matrices and ROC curves.
- Explained the **sigmoid function**, which converts linear predictions to probabilities in logistic regression.

---

## 📂 Files Included

- `Task4_Logistic_Regression.pdf` — Python code and outputs.
- `README.md` — Project overview and instructions.

---

## 📥 How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <repo-folder>
2. Install required libraries:

     pip install -r 
     requirements.txt


3. Run the Python script or notebook.




---

🙌 Acknowledgements

Elevate AI Labs

Scikit-learn Documentation

Breast Cancer Wisconsin Dataset
