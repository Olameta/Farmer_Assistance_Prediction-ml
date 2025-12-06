# Farmer_Assistance_Prediction-ml
Machine learning model for predicting farmer interface needs (Voice vs Standard) using HCI-aware features.
🌾 Farmer Assistance Prediction using Machine Learning

A Human–Computer Interaction (HCI) driven model to determine when farmers need a voice-based AI interface.

This project builds a simple but meaningful machine learning system that predicts whether a farmer is likely to struggle with digital interfaces — and suggests switching to a Voice-First AI Assistant.
It demonstrates the intersection of:

Machine Learning

Adaptive Interfaces

Agricultural Technology

Human-Computer Interaction (HCI)

💡 Problem Statement

Many smallholder farmers—especially those with low literacy or low digital exposure—struggle to use mobile applications meant to help them with planting, crop health, and decision-making.
This system predicts when the UI should automatically switch to a voice-based mode, improving accessibility and reducing cognitive load.

🔍 Features

✔ Simulated farmer dataset (500 samples)
✔ ML model to predict assistance needs
✔ Logistic Regression classifier
✔ Adaptive Interface Logic
✔ Voice-First vs Standard UI Simulation
✔ User Interaction Simulation Script

🧠 Machine Learning Model

The model uses features like:

Age

Literacy level

Farming experience

Tech exposure

Error rate

Task completion time

Native language preference

Target output:

1 → Farmer needs voice assistance  
0 → Standard interface is enough  

🎙 Adaptive UI Logic

If the model predicts 1, the system activates:

Voice-first mode

Slower speaking speed

Local language support (e.g., Yoruba, Hausa, Igbo)

Step-by-step guidance

Error-tolerant interaction

If 0, a fast standard UI is used.

📁 Project Structure
farmer-assistance-prediction-ml/
 ├── notebooks/
 │    └── Farmer Literacy Prediction.ipynb
 ├── README.md
 ├── requirements.txt
 └── .gitignore

▶️ Running the Notebook

Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Then run:
Farmer Literacy Prediction.ipynb

📌 Future Work

Add real-world farmer dataset

Build mobile prototype with adaptive UI

Integrate computer vision crop-analysis

Deploy model as an API

👨‍💻 Author

Olayiwola Abdussomad
B.Tech Computer Science, LAUTECH
Research Focus: HCI + AI Accessibility
