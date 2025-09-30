# Task 6: K-Nearest Neighbors (KNN) Classification (AI & ML Internship)

## 🎯 Objective
Implement the K-Nearest Neighbors (KNN) algorithm for classification using the Iris dataset and evaluate its performance.

## 📂 Dataset
- **Iris Dataset** (Iris.csv)
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target variable: Species (Setosa, Versicolor, Virginica)

## 🛠️ Steps Performed
1. **Loaded and explored dataset**
   - Used Pandas to load and preview data.
   - Checked dataset shape, datatypes, and class distribution.

2. **Prepared features and target variable**
   - Dropped unnecessary column (`Id`).
   - Defined `X` (features) and `y` (target = Species).

3. **Train/test split**
   - Divided dataset into 80% training and 20% testing sets.

4. **Normalized features**
   - Applied `StandardScaler` to scale features for distance-based learning.

5. **Trained KNN classifier**
   - Built model with `K=5` neighbors.
   - Fitted model on training set and predicted test labels.

6. **Evaluated model performance**
   - Calculated accuracy score.
   - Printed classification report (precision, recall, F1-score).
   - Visualized confusion matrix using Seaborn heatmap.

7. **Experimented with different K values**
   - Tested K values from 1 to 15.
   - Plotted K vs Accuracy to choose the best K.

8. **Visualized decision boundaries (optional)**
   - Used only 2 features (Sepal Length & Sepal Width).
   - Plotted classification regions using KNN.

## 📊 Evaluation
- **Accuracy:** High accuracy achieved on Iris dataset.
- **Confusion Matrix:** Clear separation between classes.
- **K vs Accuracy Curve:** Showed optimal K for best performance.

## 🧰 Tools Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📦 Deliverables
- Jupyter Notebook: `task6.ipynb`
- Iris dataset: `Iris.csv`
- README documentation (this file)

