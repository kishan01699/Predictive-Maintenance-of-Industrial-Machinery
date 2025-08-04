# 🔧 Predictive Maintenance Model using IBM Cloud & Watsonx.ai

This project is focused on building a predictive maintenance model for industrial machines to anticipate potential failures before they occur. Using real-time sensor data and machine learning, the model identifies the type of failure (e.g., tool wear, heat dissipation, power failure) to enable proactive maintenance and reduce downtime.

---

## 🚀 Project Overview

## 🚀 Project online deployment link on IBM Cloud.
   https://eu-gb.ml.cloud.ibm.com/ml/v4/deployments/72ba64e8-d360-4ab8-b176-5561192bf109/predictions?version=2021-05-01

- **Problem Statement:**  
  Predict machine failures using sensor data to reduce unplanned downtime and maintenance costs.

- **Objective:**  
  Build a classification model that predicts the type of machine failure based on real-time operational data.

---

## 🧠 Algorithm & Tools Used

- **Machine Learning Algorithm:**  
  Random Forest Classifier (selected via IBM Watsonx.ai after evaluation).

- **AI Platform:**  
  IBM Watsonx.ai Studio

- **Cloud Services:**  
  IBM Cloud (for training, deployment, and evaluation)

- **Data Preprocessing:**  
  IBM Cloud Data Refinery & Watson Studio tools

- **Model Deployment:**  
  IBM Cloud Deployment Spaces (REST API-based)

---

## 📂 Dataset

- **Source:** [Kaggle.com](https://www.kaggle.com/)
- **Features Include:**
  - Unique ID  
  - Machine Type  
  - Air Temperature  
  - Process Temperature  
  - Rotational Speed  
  - Torque  
  - Tool Wear  
  - Failure Type (Target)

---


---

## 🔍 How the Model Works

1. **Training Process:**  
   - The Random Forest model was trained automatically using Watsonx.ai Studio.
   - Historical sensor data was used to classify failures.

2. **Prediction Process:**  
   - The model receives real-time input features (temperature, torque, RPM, etc.).
   - Outputs a predicted failure type with over **90% confidence**.

3. **Deployment:**  
   - The trained model is deployed as an API via IBM Cloud Deployment Spaces.

---

## 📈 Model Evaluation

- Evaluation done using IBM Cloud tools.
- Metrics: Accuracy, Precision, Recall, F1-Score
- Achieved high confidence in predicting specific failure types.

---

## 🔮 Future Scope

- Integration with IoT devices for real-time data streaming.
- Adaptive learning for continuous model improvement.
- Scalable deployment across multiple machines/factories.
- Prescriptive maintenance suggestions alongside failure prediction.

---

## 🙏 Acknowledgements

- **Kaggle.com** – For providing the dataset.
- **IBM Cloud & Watsonx.ai Studio** – For cloud tools, AI model building, and deployment support.
- **Edunet Foundation** – For guidance and mentorship.
- **ChatGPT (OpenAI)** – For technical support and content generation.

---

## 📬 Contact

For questions or collaboration, feel free to open an issue or contact the project maintainer.

---



