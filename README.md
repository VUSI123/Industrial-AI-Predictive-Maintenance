# 🤖 Industrial AI Predictive Maintenance System

![MATLAB](https://img.shields.io/badge/MATLAB-App%20Designer-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-blue)
![AI](https://img.shields.io/badge/AI-Predictive%20Maintenance-green)

## 📌 Project Overview

The **Industrial AI Predictive Maintenance System** is an Artificial Intelligence based solution designed to predict machine failures before they occur using industrial sensor data.

The project uses Machine Learning algorithms to analyse machine operating conditions and classify whether a machine is operating normally or is at risk of failure.

A complete MATLAB-based application was developed using **MATLAB App Designer**, allowing users to enter machine sensor measurements and receive an AI-powered maintenance prediction through an interactive dashboard.

This project demonstrates the integration of:

- Industrial IoT concepts
- Machine Learning
- Data Analysis
- Artificial Intelligence
- Software Application Development


---

# 🚀 Key Features

✅ AI-based machine failure prediction

✅ MATLAB App Designer predictive maintenance dashboard

✅ Real-time sensor data input simulation

✅ Random Forest machine learning model deployment

✅ Failure probability estimation

✅ Sensor correlation analysis

✅ Feature importance analysis

✅ Multiple machine learning models evaluated


---

# 🏗️ System Architecture

```
Industrial Sensor Data
          |
          ↓
Data Processing & Analysis
          |
          ↓
Machine Learning Models
          |
          ↓
Random Forest Model Selection
          |
          ↓
MATLAB App Designer Dashboard
          |
          ↓
Machine Health Prediction
```


---

# 🖥️ MATLAB Predictive Maintenance Application

A user-friendly dashboard was created using **MATLAB App Designer**.

The application allows users to enter:

- Air Temperature (K)
- Process Temperature (K)
- Rotational Speed (rpm)
- Torque (Nm)
- Tool Wear (min)


The trained AI model processes the input data and provides:

- Machine health status
- Failure prediction
- Failure probability estimation


Application interface:

```
Industrial AI Predictive Maintenance

Air Temperature        [     ]

Process Temperature    [     ]

Rotational Speed       [     ]

Torque                 [     ]

Tool Wear              [     ]


        [ Predict Failure ]


Prediction:
Machine Status
Failure Probability
```


---

# 🧠 Machine Learning Models Developed

Three different AI models were trained and evaluated:

| Model | Accuracy |
|---|---:|
| Decision Tree | 97.93% |
| Random Forest | 98.73% |
| Artificial Neural Network | 97.70% |


The **Random Forest model** was selected for deployment because it achieved the highest accuracy and provided strong classification performance.


---

# 📊 Random Forest Model Performance

## Evaluation Results

**Accuracy:** 98.73%

**Precision:** 87.06%

**Recall:** 73.27%

**F1 Score:** 79.57%


### Confusion Matrix

```
              Predicted

              0       1

Actual 0     2888    11

Actual 1       27    74
```


---

# 🔍 Feature Importance Analysis

The model was analysed to understand which machine parameters contribute most to failure prediction.

![Random Forest Feature Importance](images/random_forest_feature_importance.png)


Important machine factors include:

- Tool Wear
- Torque
- Rotational Speed
- Temperature conditions


---

# 🛠️ Technologies Used

## Programming & Development

- MATLAB
- MATLAB App Designer
- Git & GitHub


## Artificial Intelligence

- Machine Learning Toolbox
- Deep Learning Toolbox
- Random Forest Classification
- Decision Tree Classification
- Artificial Neural Network


## Industrial Engineering Concepts

- Predictive Maintenance
- Condition Monitoring
- Industrial Sensor Analysis
- Machine Health Prediction


---

# 📂 Project Structure

```
Industrial-AI-Predictive-Maintenance/

│
├── app/
│   └── PredictiveMaintenanceDashboard_v2.mlapp
│
├── models/
│   └── randomForestModel.mat
│
├── images/
│   └── random_forest_feature_importance.png
│
├── data/
│   └── ai4i2020.csv
│
└── README.md
```


---

# 📈 Future Improvements

Future development plans include:

- Integration with real IoT sensors
- Live machine monitoring
- Cloud-based data storage
- Edge AI deployment
- Automated maintenance recommendations
- Integration with PLC/SCADA systems


---

# 👨‍💻 Author

**Vusimuzi Romeo Mtsweni**

Industrial AI | Automation | Embedded Systems | Machine Learning

GitHub:
https://github.com/VUSI123


---

⭐ If you find this project interesting, feel free to explore the repository.