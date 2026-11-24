<div align="center">

# 🎓 ShikshaSetu — AI-Powered Student Retention & Support Platform

[![SIH National Finalist](https://img.shields.io/badge/SIH-National_Level_Finalist-blue?style=for-the-badge&logo=target&logoColor=white)](https://github.com/J-Lochan/ShikshaSetu)
[![Hackathon](https://img.shields.io/badge/Selection-College_Representative_Team-gold?style=for-the-badge&logo=award&logoColor=white)](https://github.com/J-Lochan/ShikshaSetu)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-gray?style=for-the-badge)](LICENSE)

**An intelligent student retention and academic support ecosystem combining a responsive cross-platform Flutter application with machine-learning-driven early dropout prediction.**

> 🇮🇳 **Smart India Hackathon (SIH) — National Level Finalist**  
> Selected as the **official college representative team** after qualifying through competitive campus rounds to represent our institution at the National Level.

---

</div>

## 📌 Project Overview

**ShikshaSetu** ("Bridge to Education") tackles student disengagement and academic dropout rates through early behavioral risk identification and proactive mentorship intervention. 

By unifying student performance metrics, attendance tracking, and predictive machine learning models, ShikshaSetu empowers educators and mentors to intervene before academic distress leads to course failure or dropout.

---

## ✨ Key Platform Features

- 📱 **Cross-Platform Mobile Client:** Clean, intuitive Flutter UI built for iOS and Android with responsive design tokens and reusable widgets.
- 🤖 **Early Risk ML Prediction Engine:** Integrates a trained Random Forest model (`student_risk_model.pkl`) evaluating behavioral, socioeconomic, and academic markers.
- 🤝 **Mentor-Student Intervention Bridge:** Streamlined direct-contact workflows connecting flagged students with assigned faculty mentors.
- 📊 **Academic Progress & Analytics:** Visual performance indicators and goal-tracking dashboards for self-directed student improvement.
- 🔔 **Actionable Alerting:** Timely notifications for academic schedules, intervention recommendations, and milestone tracking.

---

## 🛠️ Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Mobile App (Frontend)** | Flutter, Dart (Stateful/Stateless modular architecture, Provider pattern) |
| **Machine Learning** | Python, Scikit-Learn (`RandomForestClassifier`, `StandardScaler`), Pandas, NumPy |
| **Model Serialization** | Pickle (`student_risk_model.pkl`, `scaler.pkl`) |
| **Deployment Platforms** | Android (APK / AAB), iOS, Web, macOS |

---

## 📂 Repository Structure

```
ShikshaSetu/
├── lib/
│   ├── main.dart                  # Application entry point
│   ├── screens/                   # Modular application views (Profile, Mentor, Home)
│   ├── widgets/                   # Reusable UI component library
│   ├── models/                    # Data transfer objects
│   └── services/                  # Business logic & API bridges
├── student_risk_ml/
│   ├── model.py                   # Model training & preprocessing pipeline
│   ├── student_risk_model.pkl     # Trained Random Forest classifier
│   ├── scaler.pkl                 # Feature scaling parameters
│   └── student_data.csv           # Training dataset & feature markers
├── pubspec.yaml                   # Flutter dependencies & assets
└── README.md
```

---

## 🚀 Getting Started

### 1. Prerequisites
- **Flutter SDK** (v3.10 or higher)
- **Dart SDK** (v3.0 or higher)
- **Android Studio** / **VS Code** with Flutter extensions

### 2. Run Mobile App
```bash
git clone https://github.com/J-Lochan/ShikshaSetu.git
cd ShikshaSetu
flutter pub get
flutter run
```

### 3. Inspect / Retrain the ML Model
```bash
cd student_risk_ml
pip install pandas scikit-learn
python model.py
```

---

## 👥 Authors & Team
**J. Lochan & Team**  
*SIH National Level Finalists & College Representative Team*
- 🐙 **GitHub:** [@J-Lochan](https://github.com/J-Lochan)
- 💼 **LinkedIn:** [Lochan Narayana Rao](https://www.linkedin.com/in/lochan-narayana-rao-janapareddy-a59248293)
- ✉️ **Contact:** [lochannarayanarao@gmail.com](mailto:lochannarayanarao@gmail.com)

---

<div align="center">
  <sub>Built for the Smart India Hackathon (SIH) &bull; Representing College at National Level</sub>
</div>
