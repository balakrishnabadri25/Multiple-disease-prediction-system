# 🩺 Multiple Disease Prediction System  

A web-based application built using **Streamlit** and **Machine Learning models** to predict multiple diseases (Diabetes, Heart Disease, and Parkinson’s Disease) from medical data.  

---

## 🚀 Features  
- ✅ Predicts **Diabetes** using Logistic Regression  
- ✅ Predicts **Heart Disease** using Support Vector Machine (SVM)  
- ✅ Predicts **Parkinson’s Disease** using Support Vector Machine (SVM)  
- ✅ Simple and interactive **Streamlit UI**  
- ✅ Organized **multi-page navigation** with `streamlit-option-menu`  
- ✅ Lightweight and fast — works locally in your browser  

---

## 📊 Datasets Used  

This project uses three well-known medical datasets from the **UCI Machine Learning Repository / Kaggle**:

### 1. Diabetes Dataset  
- **File:** `diabetes.csv`  
- **Source:** [Pima Indians Diabetes Database – Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)  
- **Description:** Medical diagnostic data to predict whether a patient has diabetes.  
- **Key Features:**  
  - `Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age`  
- **Target:** `Outcome` (1 → Diabetic, 0 → Non-Diabetic)  

### 2. Heart Disease Dataset  
- **File:** `heart.csv`  
- **Source:** [Cleveland Heart Disease Dataset – UCI](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Description:** Clinical data to determine the presence of heart disease.  
- **Key Features:**  
  - `age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal`  
- **Target:** `target` (1 → Heart Disease Present, 0 → No Disease)  

### 3. Parkinson’s Disease Dataset  
- **File:** `parkinsons.csv`  
- **Source:** [Parkinson’s Dataset – UCI](https://archive.ics.uci.edu/ml/datasets/parkinsons)  
- **Description:** Voice measurements used to detect Parkinson’s disease.  
- **Key Features:**  
  - `MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), MDVP:Shimmer, NHR, HNR, ...`  
- **Target:** `status` (1 → Parkinson’s, 0 → Healthy)  

---

## 🧠 Models Used  

- **Logistic Regression** → Diabetes prediction  
- **Support Vector Machine (SVM)** → Heart Disease prediction  
- **Support Vector Machine (SVM)** → Parkinson’s prediction  

---

## ⚙️ Installation & Setup  

### 1. Clone the Repository  
```bash
git clone https://github.com/shaadclt/Multiple-Disease-Prediction-System.git
cd Multiple-Disease-Prediction-System
2. Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is missing, install manually:

bash
Copy
Edit
pip install streamlit scikit-learn pandas numpy streamlit-option-menu
4. Run the App
bash
Copy
Edit
streamlit run multiplediseaseprediction.py

📌 Project Structure
bash
Copy
Edit
├── multiplediseaseprediction.py   # Main Streamlit app
├── diabetes.csv                   # Diabetes dataset
├── heart.csv                      # Heart Disease dataset
├── parkinsons.csv                  # Parkinson’s dataset
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation

🛠️ Tech Stack

Python 3.x

Streamlit (Frontend UI)

scikit-learn (Machine Learning models)

pandas, numpy (Data processing)

✨ Future Improvements
Add more diseases for prediction

Improve accuracy with advanced ML/DL models

Deploy the app online (Streamlit Cloud / Heroku / AWS)

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📜 License
This project is open-source and available under the MIT License.
