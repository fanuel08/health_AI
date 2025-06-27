# 🧠 AI-Powered Health Monitoring System

This project is an AI-driven health dashboard that monitors real-time data from wearable devices (e.g., smartwatches or fitness trackers). It detects health risks and gives personalized recommendations based on heart rate, oxygen levels, and activity levels.

---

## 🔧 Features

- ✅ Real-time health dashboard (Flask)
- ✅ AI-based anomaly detection (Random Forest)
- ✅ Personalized health advice
- ✅ REST API for external app integration
- ✅ Feedback collection and user testing

---

## 📂 Project Structure

```
afya_monitor/
│
├── app.py                   # Flask dashboard
├── api.py                   # REST API for model predictions
├── model_trainer.py         # Trains and saves Random Forest model
├── weeklong_health_data.csv # Health data from wearables
├── templates/
│   └── index.html           # Web dashboard UI
├── test_pipeline.py         # Unit tests
├── feedback_log.txt         # User feedback
├── requirements.txt         # Python dependencies
└── README.md                # Project overview
```

---

## ⚙️ How to Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/afya_monitor.git
cd afya_monitor
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Dashboard

```bash
python app.py
```

### 4. Test the API

```bash
python api.py
```

---

## 🚑 Model Details

- **Algorithm**: Random Forest Classifier
- **Features Used**: Heart rate, blood oxygen, activity level
- **Label**: Risk classification (Normal or Anomaly)
- **Evaluation**: Precision/Recall prioritized for medical safety
- **Retraining**: Supports future retraining for concept drift

---

## 🔐 Data Privacy

This project follows privacy standards such as:
- **HIPAA** (Health Insurance Portability and Accountability Act)
- **GDPR** (General Data Protection Regulation)

Data is never shared externally and is stored temporarily for model inference only.

---

## 📬 Feedback

Users can submit feedback through the dashboard. Submissions are stored in `feedback_log.txt`.

---

## ✨ Future Improvements

- 📱 Mobile version using Flutter or React Native
- 🔄 Real-time API integration (e.g., Fitbit, Garmin)
- 📊 SMS/Email alerts for critical events
- ☁️ Auto-scaling for hospital deployments

---

## 👤 Maintainer

Built with ❤️ by **Fanuel Kemei** and contributors.
