# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview
Heart disease is one of the leading causes of death worldwide. Early detection can significantly
improve treatment outcomes.  
This project uses **machine learning techniques** to predict whether a patient has heart disease
based on medical and physiological parameters.

The system analyzes patient data such as age, blood pressure, cholesterol levels, ECG results,
and exercise-related features to make accurate predictions.

---

## 🎯 Objective
- Analyze patient medical data
- Build a machine learning model to predict heart disease
- Evaluate model performance using standard metrics
- Predict heart disease for new patient data

---

## 📂 Dataset Description
The dataset contains patient health records with the following attributes:

| Feature | Description |
|------|------------|
| age | Age of the patient (years) |
| sex | 0 = Female, 1 = Male |
| chest pain type | Type of chest pain (1–4) |
| resting blood pressure | Blood pressure (mm Hg) |
| serum cholesterol | Cholesterol level (mg/dL) |
| fasting blood sugar | >120 mg/dL (1 = True, 0 = False) |
| resting ECG | ECG results (0–2) |
| max heart rate | Maximum heart rate achieved |
| exercise angina | 1 = Yes, 0 = No |
| oldpeak | ST depression |
| ST slope | Slope of ST segment |
| target | 0 = Normal, 1 = Heart Disease |

---

## 🛠️ Technologies Used
- **Python 3.12**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## ⚙️ Project Workflow
1. Data loading and exploration
2. Data preprocessing and cleaning
3. Feature scaling using StandardScaler
4. Model training using Logistic Regression
5. Model evaluation
6. Prediction on new patient data

---

## 🤖 Machine Learning Model
- **Algorithm**: Logistic Regression
- **Type**: Binary Classification
- **Target Variable**: `target`
  - `0` → No Heart Disease
  - `1` → Heart Disease

---

## 📊 Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score

These metrics help assess the effectiveness of the model in predicting heart disease.

---

## 🧪 Sample Prediction
The model can predict heart disease for a new patient by providing medical attributes such as age,
blood pressure, cholesterol, and ECG results.

Example output:
Heart Disease Detected

or

No Heart Disease Detected

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook
jupyter notebook

Open Heart_Disease_Prediction.ipynb and run all cells.



📈 Future Improvements

- Try advanced models (Random Forest, SVM, XGBoost)

- Perform hyperparameter tuning

- Add cross-validation

- Deploy the model using Flask or Streamlit



👨‍⚕️ Use Case

- This project can assist healthcare professionals in:

- Early diagnosis of heart disease

- Decision support systems

- Preventive healthcare analytics



📄 License

This project is for educational and research purposes.



👤 Author

Nikhil Anand
Machine Learning Intern / Student