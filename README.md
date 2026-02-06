# 🎓 Student Performance Prediction System

An end-to-end Machine Learning project that predicts student performance based on academic and behavioral features.

## 🚀 Features
- Data analysis using Pandas and Matplotlib
- Machine Learning model training
- Experiment tracking with MLflow
- Web app built using Flask
- Version control with Git and GitHub

## 🛠 Tech Stack
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
- Flask
- MLflow
- Git & GitHub

## 📂 Project Structure
```bash
student-performance-prediction/
│
├── data/
│   └── student_data.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── train.py
│   └── predict.py
│
├── app.py
├── requirements.txt
└── README.md

## ▶️ How to Run This Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/karishmaaraj/student-performance-prediction.git
cd student-performance-prediction

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Train the Machine Learning model
python src/train.py

4️⃣ Run prediction script
python src/predict.py

5️⃣ Start the Flask application
python app.py

Open your browser and go to:
http://127.0.0.1:5000/

## 🔌 API Usage Example

### Endpoint
```
POST /predict
```

### Sample Request (JSON)
```json
{
  "study_hours": 6,
  "attendance": 85,
  "previous_score": 70
}
```

### Sample Response
```json
{
  "predicted_score": 78.5
}
```

### cURL Command
```bash
curl -X POST http://127.0.0.1:5000/predict \
-H "Content-Type: application/json" \
-d '{"study_hours":6,"attendance":85,"previous_score":70}'
```










