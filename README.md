# Machine-Learning-Heart Stroke Prediction 

## 🚀 Live Demo  
👉 [Click here to use the App]  https://heartstrokepredictionin.streamlit.app/

<img width="1394" height="910" alt="image" src="https://github.com/user-attachments/assets/44e741a4-9ce1-4b89-b097-0afba7574e05" />

## 💖 Heart Stroke Prediction

This project uses **Machine Learning** to predict the risk of heart stroke based on user inputs like age, gender, blood pressure, glucose level, smoking status, and other key health indicators.

## 📌 Project Overview

The goal of this project is to build an interactive web application using **Streamlit** that predicts whether a person is at risk of a heart stroke. The model was trained using real healthcare data, and the interface allows users to input values and get instant predictions.

## 🧠 Model Used
- Algorithm: **K-Nearest Neighbors (KNN)**
- Preprocessing: StandardScaler and OneHotEncoder
- Evaluation Metric: Accuracy, Precision, Recall
- Saved Files:
  - `knn_heart_model.pkl`: Trained model
  - `heart_scaler.pkl`: Scaler used on numerical features
  - `heart_columns.pkl`: Column order for the input vector

## Performance Metrics
	•	Accuracy: 91%
	•	Confusion Matrix and ROC-AUC Curve provided in Notebook

## 📦 Requirements
	•	Install the required libraries with:
	•	pip install -r requirements.txt
	•	pip install streamlit pandas numpy scikit-learn matplotlib seaborn
 
## 📁 Repository Structure

	•	├── app.py                  # Streamlit frontend
	•	├── knn_heart_model.pkl     # Trained ML model
	•	├── heart_scaler.pkl        # Scaler used in preprocessing
	•	├── heart_columns.pkl       # Feature column list
	•	├── README.md               # Project description
	•	├── requirements.txt        # Python dependencies
	•	│
	•	├── data/                   # (Optional) Folder for raw dataset
	•	│
	•	└── notebook/               # Model training and EDA notebook
## 📚 Future Improvements
	•	Add more ML models (Random Forest, XGBoost)
	•	Feature selection optimization
	•	Deploy via Hugging Face / Streamlit Cloud / Heroku
	•	Add user history tracking and PDF report generation
 
⭐️ Give a Star!

•	If you like this project, consider starring ⭐ it on GitHub!


### 🙋‍♂️ Author

Priya Lamb

B.Tech | AI & Data Science

📧 Email

📌 Linkedin 


