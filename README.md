
# ❤️ Predicting Heart Disease using Ensemble Learning

This project applies supervised machine learning techniques — with a focus on **ensemble methods** — to predict the presence of heart disease based on patient health data.

## 📌 Overview

Heart disease is one of the leading causes of death globally. Early detection using predictive modeling can assist in timely intervention and potentially save lives.

This project explores:
- Data preprocessing and feature engineering
- Training multiple ensemble classifiers (Random Forest, Gradient Boosting, Voting Classifier)
- Evaluating performance using accuracy, precision, recall, F1-score, and ROC-AUC
- Visualizing results and decision boundaries

## 🧠 Machine Learning Techniques Used

- **Random Forest**
- **Gradient Boosting**
- **Voting Classifier** (Hard and Soft voting)
- Comparison with base models: Logistic Regression, SVM, Decision Tree

## 📊 Dataset

- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- Features: 13 attributes (age, sex, chest pain type, resting blood pressure, cholesterol, etc.)
- Target: Presence of heart disease (binary classification)

## 🧹 Preprocessing Steps

- Handling missing/null values
- Label encoding for categorical features
- Feature scaling using StandardScaler
- Splitting data into training and testing sets

## 📈 Evaluation Metrics

- Confusion Matrix
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC Score
- Feature Importance Plot

## 📁 Project Structure

```
📦 Predicting-Heart-Disease-Ensemble-learning
├── heart_disease_ensemble.ipynb       # Main Jupyter notebook
├── heart.csv                          # Dataset file
├── README.md                          # Project documentation
```

## 🖼️ Sample Results

- Random Forest Accuracy: **~88%**
- Gradient Boosting ROC-AUC: **~91%**
- Voting Classifier performed best on overall metrics

## 📌 Requirements

Install required libraries using:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/josephadel25/Predicting-Heart-Disease-Ensemble-learning.git
   ```
2. Open `heart_disease_ensemble.ipynb` in Jupyter Notebook or VSCode.
3. Run all cells step-by-step to see preprocessing, training, and results.

## 🙋‍♂️ Author

👤 **Joseph Adel**  
📫 [LinkedIn](https://www.linkedin.com/in/joseph-adel-b17b7725a) | [GitHub](https://github.com/josephadel25)

## 📄 License

This project is licensed under the MIT License.
