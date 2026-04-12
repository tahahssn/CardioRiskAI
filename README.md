# 🫀 CardioRiskAI – Cardiovascular Risk Assessment System

A machine learning-powered web application that predicts the risk of cardiovascular disease based on patient health data. Built with **Python**, **scikit-learn**, and **Streamlit**.

🔗 **Live App:** [cardioriskai.streamlit.app](https://cardioriskai.streamlit.app)

---

## 📌 Features

- **K-Nearest Neighbors (KNN)** classifier for heart disease risk prediction
- **Interactive web interface** built with Streamlit – no technical skills required to use
- **Real-time predictions** based on user input (age, blood pressure, cholesterol, etc.)
- **Preprocessing pipeline** including feature scaling for reliable results
- **Model persistence** using `pickle` (saved KNN model + scaler)

---

## 🛠️ Tech Stack

| Category       | Tools/Libraries                                      |
|----------------|------------------------------------------------------|
| Language       | Python                                               |
| ML Framework   | scikit-learn (KNN)                                   |
| Data Handling  | Pandas, NumPy                                        |
| Visualization  | Matplotlib, Seaborn (in notebook)                    |
| Deployment     | Streamlit                                            |
| Environment    | Jupyter Notebook, Git, GitHub                        |

---

## 📁 Repository Structure
CardioRiskAI/
├── heart.ipynb # Model training & EDA notebook
├── app.py # Streamlit application (main version)
├── app1.py # Streamlit application (alternate version)
├── heart.csv # Dataset
├── KNN_heart.pkl # Trained KNN model
├── scalar.pkl # Fitted scaler for feature normalization
├── columns.pkl # Feature column names
└── requirements.txt # Python dependencies

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/tahahssn/CardioRiskAI.git
   cd CardioRiskAI
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Run the Streamlit app**
    ```bash
   streamlit run app.py

## 📊 Dataset
The model is trained on a cardiovascular disease dataset containing features such as:

- Age, gender, blood pressure (systolic/diastolic)
- Cholesterol levels, blood glucose
- Smoking, alcohol intake, physical activity
- Presence or absence of cardiovascular disease (target)
- Dataset source: heart.csv included in the repository.

## 📈 Model Performance
- Algorithm: K-Nearest Neighbors (KNN)
- Preprocessing: StandardScaler for feature normalization
- Evaluation metrics: Accuracy, confusion matrix, classification report (see notebook for details)

## 👨‍💻 Author
- Syed Muhammad Taha Hassan Shah
- GitHub: tahahssn
- Software Engineering student at UBIT - University Of Karachi
- Passionate about AI & Machine Learning

## 📄 License
This project is open source and available under the MIT License.
