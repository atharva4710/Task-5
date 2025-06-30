
# Task 5: Decision Trees and Random Forests

## 📌 Objective
Learn and implement tree-based models (Decision Tree & Random Forest) for classification using the heart disease dataset.

---

## 🧰 Tools & Libraries
- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn
- Graphviz (for tree visualization - optional)

---

## 📝 Task Workflow

### 1. Data Loading & Preprocessing
- Load the `heart.csv` dataset.
- Split the data into features (X) and target (y).
- Train-Test Split (80-20).

### 2. Decision Tree Classifier
- Train a Decision Tree with controlled `max_depth`.
- Visualize the decision tree using `plot_tree`.
- Evaluate using accuracy score and classification report.

### 3. Random Forest Classifier
- Train a Random Forest with 100 estimators.
- Compare performance against the Decision Tree.
- Analyze feature importance using bar plots.
- Evaluate using accuracy, classification report, and confusion matrix.

### 4. Cross-Validation
- Perform 5-fold cross-validation on both models.
- Compare average CV scores to assess model robustness.

---

## 📈 Output & Visuals
- Decision Tree Visualization
- Confusion Matrix Heatmap
- Feature Importances Bar Chart
- Accuracy & Classification Reports

---

## 📂 Files
- `Task_5_DecisionTree_RandomForest.ipynb` – Jupyter Notebook with full implementation.
- `heart.csv` – Dataset file (input).


---

## ✅ Conclusion
This task demonstrates the power of ensemble learning using Random Forests and the interpretability of Decision Trees. It also highlights the importance of controlling model complexity and evaluating models using cross-validation.

