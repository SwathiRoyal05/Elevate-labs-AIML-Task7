# 🧠 AI & ML Internship - Task 7: Support Vector Machines (SVM)

## ✅ Objective
This task focuses on understanding and applying Support Vector Machines (SVMs) for:
- Binary classification
- Both linear and non-linear decision boundaries
- Hyperparameter tuning using GridSearchCV
- Model evaluation using confusion matrix and classification report

---

## 📂 Dataset Used
**Breast Cancer Wisconsin Dataset**  
- Available directly via `sklearn.datasets`
- Features: 30 real-valued input features
- Target: Binary (malignant = 0, benign = 1)

---

## 🧰 Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib
- (Optional: PCA for dimensionality reduction and visualization)

---

## 🛠️ Steps Followed

1. **Dataset Loading & Preprocessing**
   - Loaded data using `load_breast_cancer()` from sklearn.
   - Normalized features using `StandardScaler`.
   - Split data into train and test sets (80:20).

2. **SVM Model Training**
   - Trained two SVM models using:
     - **Linear kernel**
     - **RBF kernel**
   - Used `SVC()` from `sklearn.svm`.

3. **Visualization**
   - Reduced dimensions using PCA to 2D.
   - Plotted decision boundary using Matplotlib.

4. **Hyperparameter Tuning**
   - Used `GridSearchCV` to tune `C` and `gamma` for RBF kernel.
   - Performed 5-fold cross-validation.

5. **Evaluation**
   - Used confusion matrix and classification report.
   - Reported precision, recall, and F1-score.

---

## 📊 Results

| Kernel | Accuracy | Best Params (C, gamma) |
|--------|----------|------------------------|
| Linear | ~97%     | C=1.0                  |
| RBF    | ~98%     | C=10, gamma=0.01       |

*Confusion matrix and classification report included in the notebook.*

---

## 📚 What I Learned
- How SVM separates data using support vectors and hyperplanes.
- The importance of margin maximization in classification.
- How the kernel trick helps in non-linear separation.
- How to tune SVM parameters (`C`, `gamma`) using `GridSearchCV`.
- PCA for reducing high-dimensional data for visualization.

## Screenshots
![image](https://github.com/user-attachments/assets/9f1e6d36-071a-435c-9235-c4af470d0812)
