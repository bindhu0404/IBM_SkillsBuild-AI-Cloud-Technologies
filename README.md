# Power System Fault Detection and Classification 🔌

This project presents a machine learning-based solution for detecting and classifying faults in power distribution systems. By analyzing electrical measurement data—specifically voltage and current phasors—the model can accurately identify various fault types and distinguish them from normal operating conditions. The trained model is deployed using IBM Watsonx.ai on IBM Cloud, enabling scalable, real-time predictions via API.

---

## 📍 Objective

To develop a reliable fault classification system that can assist in the rapid identification of issues within a power grid, minimizing downtime and supporting grid stability.

---

## 🧠 Model Details

- **Algorithm Used:** Random Forest Classifier  
- **Purpose:** Multiclass classification of power system states  
- **Classes Predicted:**  
  - Line-to-Ground Fault  
  - Line-to-Line Fault  
  - Three-Phase Fault  
  - Normal Operation

---

## 📁 Dataset

- **Source:** [Power System Faults Dataset on Kaggle](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)  
- The dataset includes phasor readings under different fault conditions and normal states.

---

## 🛠️ Technologies Used

- Python 3.10+  
- pandas, numpy, scikit-learn  
- IBM Watsonx.ai (for deployment)  
- IBM Cloud Lite (for hosting model APIs)

---

## 🚀 Deployment

The final model was deployed using IBM Watsonx.ai, generating a REST API endpoint for real-time fault classification. The deployment allows external systems to interact with the model using live or batch inputs.

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision & Recall  
- Confusion Matrix  
- Prediction Confidence Scores

---
