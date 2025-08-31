# 🚀 Machine Learning Projects  

Welcome to my **Machine Learning Projects Repository**!  
Here, you’ll find code implementations, datasets, and visualizations for different ML projects.  

---

## 📂 Projects  

<details>
<summary>🧬 Cancer Classification using Regularized Logistic Regression</summary>

📓 **File:** `Cancer.ipynb`  
📂 **Dataset:** `cancer_data.csv`  

### 🔹 Project Overview  
This project implements **Logistic Regression with Regularization** to classify **Breast Cancer** based on 30 features.  
The model was trained using **Gradient Descent** and achieved up to **99% accuracy** on test data.  

---

### 📌 Steps Performed
1. 📥 **Data Loading**: Loaded dataset using **Pandas** (`cancer_data.csv`) into  
   - `X`: 30 feature columns  
   - `y`: diagnosis (Malignant/Benign)  

2. ⚙️ **Preprocessing**:  
   - Normalized features using **Scikit-learn**  
   - Split dataset into **80% training** and **20% testing**  

3. 📊 **Model Initialization**:  
   - Set initial **weights = 0** and **bias = 0**  
   - Defined **Sigmoid function** for probability estimation  

4. 🔄 **Training (Gradient Descent)**:  
   - Computed **Cost function** with regularization  
   - Updated weights and bias iteratively  
   - Stored values in **cost_history**  

5. ✅ **Prediction & Evaluation**:  
   - Trained model on training data  
   - Predicted on test set with **~99% accuracy**  

6. 🎨 **Visualization**:  
   - Plotted **Linear Decision Boundary**  
   - Plotted **Cost function vs Iterations**  

---

### 📌 To-Do  
- [ ] 🔮 Implement **Polynomial Feature Mapping** for nonlinear decision boundaries  
- [ ] 📈 Add **ROC Curve & AUC Score** for better evaluation  
- [ ] 🤖 Compare Logistic Regression with other ML models (SVM, Random Forest, Neural Networks)  

</details>

---

<details>
<summary>📊 Future Project 1 – Coming Soon</summary>

🚧 **Work in Progress...**

</details>

<details>
<summary>🤖 Future Project 2 – Coming Soon</summary>

🚧 **Work in Progress...**

</details>

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **NumPy** & **Pandas** (Data Handling)  
- **Matplotlib** (Visualizations)  
- **Scikit-learn** (Preprocessing, Train-Test Split)  
