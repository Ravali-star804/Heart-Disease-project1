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

## 📦 Dataset ZIP File

The dataset used in this project is included as a ZIP file in this repository:

👉 [`PRCP-1016-HeartDiseasePred.zip`](https://github.com/Ravali-star804/Heart-Disease-project1/blob/main/PRCP-1016-HeartDiseasePred.zip)

It contains Excel files with patient health information used to train and test the machine learning models.

### 📥 How to Use:
1. Click the link above and click **"Download"** (use "Raw" to download).
2. Extract the ZIP file on your local system.
3. Upload the required `.xlsx` file into **Google Colab** using the left sidebar.
4. Use the following code in Colab to read it:

```python
import pandas as pd

# After uploading the file manually in Colab
df = pd.read_excel("heart.xlsx")  # change name if different
df.head()


## 👩‍💻 Author
**Ravali Ambadi**  
Aspiring Data Scientist  
[LinkedIn](www.linkedin.com/in/ravali-ambadi-872772187)

