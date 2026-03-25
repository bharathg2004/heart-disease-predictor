# ❤️ Heart Disease Prediction App

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)
![ML](https://img.shields.io/badge/Model-KNN-green)
![Status](https://img.shields.io/badge/Status-Active-success)

A **Machine Learning powered web application** that predicts the likelihood of heart disease using user health parameters. Built with an intuitive UI using Streamlit.

---
 Live Demo:

https://heart-disease-predictor-ysd5tnez6ns2myr6zpungs.streamlit.app/

---
##  App Preview:

<img width="461" height="741" alt="image" src="https://github.com/user-attachments/assets/c6cce365-d223-4014-bcaa-7cf553df1954" />
<img width="461" height="746" alt="image" src="https://github.com/user-attachments/assets/5f2080c6-ef65-454b-a83b-9acab66aa9ee" />

##  Features:

 Real-time heart disease prediction
 Clean and interactive UI
 Fast and lightweight model
 Easy to use for anyone
 Built for learning + real-world use

---

##  Tech Stack:

| Category      | Technology Used |
| ------------- | --------------- |
| Language      | Python          |
| Frontend      | Streamlit       |
| ML Library    | Scikit-learn    |
| Model Storage | Joblib          |
| Data Handling | Pandas, NumPy   |

---

##  Project Structure:

```id="c32h7u"
heart-disease-predictor/
│
├── app.py                 # Streamlit UI
├── KNN_heart.pkl          # Trained ML model
├── requirements.txt       # Dependencies
├── README.md              # Documentation
└── assets/                # Images (screenshots)
```

---

##  Installation & Setup:

###  1. Clone Repository

```id="07e92n"
git clone https://github.com/bharathg2004/heart-disease-predictor.git
cd heart-disease-predictor
```

###  2. Install Dependencies

```id="1mf50h"
pip install -r requirements.txt
```

###  3. Run App

```id="tfqn4p"
streamlit run app.py
```

---

##  Input Features

The model considers the following medical parameters:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression

---

##  Prediction Output

| Output | Meaning                |
| ------ | ---------------------- |
| 0      | No Heart Disease       |
| 1      | Heart Disease Detected |

---

##  Model Information

* Algorithm: **K-Nearest Neighbors (KNN)**
* Saved using: **Joblib**
* Trained on: *(Mention dataset name if known — e.g., UCI Heart Dataset)*

---

##  Future Enhancements

 Add multiple ML models (Random Forest, XGBoost)
 Improve UI/UX design
 Add visualization dashboard
 Deploy with authentication system
 Integrate real-time health APIs

---

##  Deployment Options

You can deploy this app easily using:

* Streamlit Cloud
* Render
* Hugging Face Spaces

---

##  Acknowledgements

* Dataset: *heart.csv*
* Built as part of Machine Learning practice

---

##  Author

**Bharath G**
 Computer Science Engineering Student
 Interested in AI, ML, Web Development & Robotics

---


---

## 📬 Contact

Feel free to connect or reach out for collaboration!
