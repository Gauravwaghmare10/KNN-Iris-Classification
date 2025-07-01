# 🌸 K-Nearest Neighbors (KNN) - Iris Classification

This project implements a K-Nearest Neighbors (KNN) classifier using the classic **Iris dataset**.  
The objective is to classify iris flowers into three species based on petal and sepal measurements.

---

## 📌 Objective

- Build a classification model using KNN.
- Tune the number of neighbors (K) to optimize model performance.
- Evaluate the model using accuracy, confusion matrix, and classification report.

---

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## 🧪 Dataset

- **Name**: Iris Dataset
- **Source**: UCI Machine Learning Repository / scikit-learn / Kaggle
- **Target Classes**:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

| Feature         | Description              |
|----------------|--------------------------|
| SepalLengthCm   | Sepal length in centimeters |
| SepalWidthCm    | Sepal width in centimeters  |
| PetalLengthCm   | Petal length in centimeters |
| PetalWidthCm    | Petal width in centimeters |
| Species         | Class label (target)     |

---

## 🚀 Steps Followed

1. **Manual file upload** in Google Colab (`Iris.csv`)
2. **Data preprocessing**:
   - Dropped unnecessary columns
   - Feature normalization using `StandardScaler`
3. **Train-test split**
4. **Model training** using `KNeighborsClassifier` from scikit-learn
5. **Tuning hyperparameter K** from 1 to 20
6. **Evaluation** using:
   - Accuracy
   - Confusion Matrix (heatmap)
   - Classification Report (Precision, Recall, F1-score)
7. **Visualization**:
   - Accuracy vs K plot
   - Confusion Matrix

---

## 📊 Results

- ✅ Best K found: `K = X` *(replace with your best_k from output)*
- 📈 Accuracy achieved: `YY%`
- 🎯 Model performed with high accuracy across all three classes.

---

## 📎 File Structure

KNN-Iris-Classification/
├── KNN_Iris_Classification.ipynb # Main notebook with full code
├── Iris.csv # Dataset (manually uploaded in Colab)
└── README.md # Project documentation


---

## 👨‍💻 Author

**Gaurav Waghmare**  
GitHub: [@Gauravwaghmare10](https://github.com/Gauravwaghmare10)

---
