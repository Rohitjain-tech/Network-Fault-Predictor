# 🌐 Live Demo  
https://network-fault-predictor-1.onrender.com  

---

# ⚙️ AI Network Fault Prediction System  
### Intelligent Network Monitoring & Fault Detection Tool  

A web-based AI system designed to predict network faults using key parameters like CPU usage, latency, packet loss, and bandwidth.  
The system uses a Bayesian Inference model to analyze network conditions, detect potential faults, and provide actionable suggestions with downloadable reports.

---

# 🚀 Features  

- 🔍 Network Fault Prediction (CPU, Latency, Packet Loss, Bandwidth)  
- 🧠 Bayesian Inference Model (pgmpy)  
- 📊 Fault Probability Calculation (%)  
- ⚠️ Risk Level Indicator (Low / Medium / High)  
- 💡 Intelligent Network Suggestions  
- 📄 Downloadable Text Report  
- 📊 Rule Evaluation Display (Explainable AI)  
- 🌐 Interactive Web Interface  

---

# 🧠 How It Works  

The system uses a Bayesian Network Model:

Input Parameters → Bayesian Model → Probability Calculation → Output Decision  

## Input Parameters  

- CPU Usage  
- Latency  
- Packet Loss  
- Bandwidth  

## AI Processing  

- Takes user input values  
- Applies Bayesian inference using trained model  
- Computes fault probability  
- Generates prediction (Fault / No Fault)  
- Provides risk level and suggestions  

---

# 📊 Rule Evaluation (Explainable AI)  

The system also evaluates logical rules for transparency:

- CPU = High AND Latency = High → Possible Fault  
- Packet Loss = High → Network Issue  
- Bandwidth = Low AND CPU = High → Congestion  
- Latency = High AND Packet Loss = High → Severe Fault  

---

# 📄 Report Generation  

The system generates a downloadable report containing:

- Input parameters  
- Prediction result  
- Fault probability  
- Risk level  
- Suggestions  

---

# 🛠 Tech Stack  

- Backend: Flask (Python)  
- AI Model: pgmpy (Bayesian Network)  
- Frontend: HTML, CSS  
- Deployment: Render  
- Version Control: Git & GitHub  

---

# 📂 Project Structure  

Network-Fault-Prediction/  

├── app.py  
├── predict.py  
├── model.pkl  
├── requirements.txt  
├── Procfile  

├── templates/  
│   └── index.html  

├── static/ (optional)  

├── README.md  
└── .gitignore  

---

# 🎯 Outcome  

The system demonstrates how AI-based probabilistic models can be used for:

- Network fault prediction  
- Performance monitoring  
- Risk analysis  
- Decision support systems  

It helps reduce downtime and improves network reliability.

---

# ⭐ Future Enhancements  

- 📊 Real-time network monitoring integration  
- 📈 Graph visualization of network parameters  
- 🤖 Machine learning-based prediction models  
- ☁ Cloud database integration  
- 📱 Mobile-friendly UI  

---

# 📌 Conclusion  

This project showcases the practical implementation of a Bayesian-based AI system for network fault prediction.  
It combines probabilistic reasoning with a user-friendly interface to provide accurate predictions and useful recommendations.

---

# 👨‍💻 Author  

Rohit Ubale  
