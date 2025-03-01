# 📡 Telecom Cell Outage & Degradation Detection Using Machine Learning  

![Project Overview](https://github.com/A-Shenawy/Telecom-Cell-Outage-Degradation-Using-Machine-Learning/blob/main/CDD-COD-COC.PNG)  

## 📌 Project Overview  
This project focuses on detecting **cell outages** and classifying **network degradations** in a **telecom network** using **machine learning**. By leveraging **network KPIs, alarms, and performance metrics**, the system identifies anomalies affecting cell performance and suggests corrective actions.  

### 🎯 Objectives  
✅ Detect **cell outages** in a telecom network.  
✅ Classify **degradation types** (coverage issues, interference, hardware failure).  
✅ Develop a compensation method via **antenna tilting** to mitigate service impact.  
✅ Implement **machine learning models** to automate the detection process.  

---

## 📊 Dataset & Features  
- **Data Sources**:  
  - 📡 **Network KPIs** (RSRP, SINR, Call Drops)  
  - 🚨 **Cell Alarms & Event Logs**  
  - 📈 **Traffic & Coverage Data**  
  - 🛰 **Antenna Configuration Data**  

- **Feature Engineering**:  
  - Signal Strength (RSRP, RSSI, SINR)  
  - Call Drop Rate & Handover Success Rate  
  - Interference Levels & Congestion Metrics  
  - Temporal Patterns (Time-Based Outages)  

---

## 🛠️ Methodology  

### 1️⃣ Data Preprocessing & Augmentation  
🔹 **Handling missing values & outliers**  
🔹 **Feature extraction** from network performance metrics  
🔹 **Time-series analysis** for detecting patterns  

### 2️⃣ Machine Learning Models  
- **Outage Detection**: Anomaly detection using **Random Forest, Isolation Forest, and XGBoost**.  
- **Degradation Classification**: Multi-class classification using **Support Vector Machines (SVM) & Neural Networks**.  

### 3️⃣ Compensation via Antenna Tilting  
- Optimization algorithm for **adaptive antenna tilt adjustments** to compensate for detected outages.  

---

## 📈 Results & Performance  
📌 **Outage detection accuracy**: **~92%**  
📌 **Degradation classification F1-score**: **~88%**  
📌 **Reduced false alarms** by **25%**, improving network efficiency  

---

## 🚀 Future Improvements  
🔹 **Integrate real-time monitoring** for live cell outage detection  
🔹 **Explore deep learning models** (LSTMs, Transformers) for sequential outage patterns  
🔹 **Expand dataset** with more environmental & weather factors  

---

## 📦 Installation & Usage  

### 🔧 Prerequisites  
Make sure you have the following installed:  
- 🐍 Python 3.x  
- 📦 Scikit-Learn, Pandas, NumPy  
- 📊 Matplotlib & Seaborn (for visualization)  
- 🤖 TensorFlow/PyTorch (if using deep learning models)  

### 🚀 Steps to Run the Project  
1️⃣ **Clone the repository**  
   ```bash
   git clone https://github.com/A-Shenawy/Telecom-Cell-Outage-Degradation-Using-Machine-Learning.git
   cd Telecom-Cell-Outage-Degradation-Using-Machine-Learning
