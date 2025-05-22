# ❤️ Health Monitoring and Heart Stroke Prediction using IoT & Machine Learning

A real-time health monitoring system that integrates **IoT sensors** with **machine learning algorithms** to predict cardiac diseases and stroke risk. This end-to-end project demonstrates the fusion of embedded systems, real-time data acquisition, and predictive analytics to support proactive healthcare solutions.

---

## 🎯 Project Objective

To design a scalable, real-time health monitoring platform that:
- Collects physiological signals using IoT devices (ESP8266, pulse oximeter, BP monitor)
- Transmits and visualizes data through a web interface
- Applies ML models to predict potential cardiac events with high precision

---

## 🔑 Key Features

- 📡 **Real-Time IoT Integration**: Live data collected from pulse oximeters and blood pressure sensors using an ESP8266 module.
- 🧠 **ML-Based Cardiac Prediction**: Trained multiple models (SVM, Random Forest, etc.) on real-world clinical datasets.
- 🌐 **Web Interface**: Live dashboard displays health metrics and prediction outcomes.
- ✅ **High Accuracy**: Achieved up to **96% accuracy** in predicting heart stroke likelihood.

---

## 📶 System Architecture

### 🔁 Data Pipeline
1. 🩺 **Sensor Input**: Pulse oximeter & BP monitor capture real-time health stats
2. 📲 **ESP8266 Transmission**: Sends data over WiFi to server
3. 🧠 **ML Inference Engine**: Runs trained models to evaluate health risks
4. 🖥️ **Web Interface**: Displays analytics and prediction results to users

![Circuit Design](https://github.com/Chetansai11/Health-Monitoring-and-Heart-Stroke-Prediction/blob/main/circuit.png)  
*Figure 1: ESP8266-based IoT hardware setup*

---

## 🧠 Machine Learning Pipeline

| Step              | Details                                     |
|-------------------|---------------------------------------------|
| **Algorithms**     | Regression, Decision Tree, SVM, Random Forest |
| **Dataset**        | Clinical health datasets from public archives |
| **Preprocessing**  | Null removal, encoding, normalization        |
| **Evaluation**     | Accuracy, Precision, Recall, F1-score        |

📈 **Model Accuracy**: **96%** (Random Forest best performing)

---

## 💻 Web Dashboard

Displays real-time sensor data and ML-predicted risk levels.

![Website Interface](https://github.com/Chetansai11/Health-Monitoring-and-Heart-Stroke-Prediction/blob/main/website%20layout.png)  
*Figure 2: Live data monitoring & cardiac risk output*

---

## 📊 Results

| Feature                   | Outcome                              |
|---------------------------|--------------------------------------|
| Real-Time Monitoring      | ✅ Stable WiFi data flow via ESP8266 |
| Prediction Accuracy       | ✅ Up to **96%** on test set         |
| UI & Visualization        | ✅ Clear, minimal web dashboard       |
| Sensor Integration        | ✅ Accurate data collection and sync  |

---

## 🛠️ Tech Stack

- **Languages**: Python, C++ (Arduino), HTML/CSS (Web)
- **Libraries**: scikit-learn, pandas, NumPy, Flask, OpenCV (optional for UI)
- **Hardware**: ESP8266, Pulse Oximeter, Blood Pressure Sensor, Breadboard
- **Communication**: Serial & Wi-Fi using HTTP/UDP protocols

---

## 🧪 Future Enhancements

- 🧠 Add deep learning models (LSTM/CNN) for time-series health trend analysis
- 🛡️ Include emergency alert systems via SMS/email on threshold breach
- ⚙️ Enhance sensor accuracy with medical-grade hardware
- 📈 Deploy as a cloud-hosted platform with patient history tracking

---

## 📬 Contact

**Chetan Sai Borra**  
📧 sai311235@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/chetan-sai-16a252251/)

> *A practical application of AI + IoT for early cardiac intervention and remote patient monitoring—bridging the gap between wearable data and real-time clinical insight.*
