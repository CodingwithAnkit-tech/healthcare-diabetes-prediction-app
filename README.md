# 🏥 Healthcare Predictive Analytics – Disease Detection
## 📌 Project Overview

- Healthcare Predictive Analytics is a machine learning–based project designed to predict the risk of diseases such as diabetes using patient medical data.
The project applies data preprocessing, normalization, classification models, and evaluation techniques to generate meaningful healthcare insights.

- This project was completed as part of my Data Analytics Internship at Codec Technologies, focusing on practical implementation of predictive analytics in healthcare.

# 🎯 Project Objectives

- Predict the likelihood of disease occurrence using medical records
- Normalize and preprocess healthcare data for consistency
- Apply classification algorithms for disease prediction
- Analyze feature importance to identify key health indicators
- Ensure ethical data handling and patient privacy

# 🗂️ Dataset Information

- Source: UCI / Kaggle Healthcare Dataset
- Type: Structured medical data
- Target Variable: Disease outcome (Diabetes: Yes/No)
- Features Include:
- Glucose Level
- Blood Pressure
- BMI
- Age
- Insulin
- Pregnancies

# 🛠️ Technologies & Tools Used

- Programming Language: Python
- Libraries:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Development Environment: VS Code
- Version Control: Git & GitHub

# ⚙️ Project Workflow

- Data Collection
- Load healthcare dataset from CSV files
- Data Preprocessing
- Handle missing values
- Normalize medical records
- Feature scaling for consistency
- Model Training
- Apply classification algorithms (Logistic Regression, etc.)
- Train model using processed data
- Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Performance comparison
- Prediction
- Predict disease risk for new patient data

# 📁 Project Structure

- healthcare-predictive-analytics/
│
├── data/
│   ├── raw/
│   │   └── diabetes.csv
│   ├── processed/
│   │   └── processed.csv
│
├── models/
│   └── model.pkl
│
├── src/
│   ├── app.py
│   ├── data_processing.py
│   ├── train.py
│   ├── predict.py
│   └── evaluate.py
│
├── notebooks/
│
├── examples/
│   └── input.csv
│
├── requirements.txt
├── README.md
└── .gitignore

# ▶️ How to Run the Project

# Clone the repository
git clone https://github.com/your-username/healthcare-predictive-analytics.git

# Navigate to project directory
cd healthcare-predictive-analytics

# Install dependencies
pip install -r requirements.txt

# Train the model
python src/train.py

# Run prediction
python src/predict.py


# ✅ Live Hosted App Link

🔗 Streamlit App:
👉 https://ankit-diabetes-app.streamlit.app

# 🔐 Ethical Considerations & Data Privacy

- Used publicly available datasets only
- No personal or identifiable patient data included
- Predictions are for educational and analytical purposes only
- Highlights importance of responsible AI in healthcare

# 🧠 Key Learnings
- Healthcare data preprocessing techniques
- Feature importance analysis in ML models
- End-to-end ML project structuring
- Ethical handling of sensitive datasets
- Practical application of predictive analytics

# 🏢 Internship Context

This project was completed as part of my Data Analytics Internship at Codec Technologies, where I worked on real-world datasets to build analytical and predictive solutions using Python and machine learning techniques.

# 🌟 Conclusion

Healthcare Predictive Analytics demonstrates how data-driven approaches can support early disease detection and better decision-making in the healthcare domain.

# ✨ Motivation Note (as you like 😉)

Every dataset tells a story — learning to read it can help change lives.

