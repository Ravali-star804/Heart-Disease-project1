# Heart Disease Prediction Project

This project uses machine learning models to predict the presence of heart disease based on various health parameters.

## 🔍 Problem Statement
Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely treatment and reduce risk.

## 📊 Dataset Features
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Max heart rate achieved
- Exercise induced angina
- ST depression, etc.

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

## 🧠 Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Accuracy Comparison

## 📈 Output
Model performance evaluated using confusion matrix, accuracy, and classification report.

## 📁 Dataset Usage in Colab

You can load the Excel file in Google Colab using `pandas.read_excel()` as shown below:

```python
import pandas as pd

# If using from ZIP and extracted manually
df = pd.read_excel("/content/Heart_disease_excel/heart.xlsx")  # adjust the path and filename as needed

# If uploaded directly into Colab or the repo
df = pd.read_excel("heart.xlsx")

## 👩‍💻 Author
**Ravali Ambadi**  
Aspiring Data Scientist  
[LinkedIn](https://www.linkedin.com/in/ravali-ambadi-872772187)

