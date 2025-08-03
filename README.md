# 🧠 Brain-Controlled Wheelchair using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Arduino](https://img.shields.io/badge/Arduino-Mega%202560-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Prototype-yellow)

---

## 📌 Project Overview

This project combines **electrical engineering principles** and **machine learning** to design a **brain-controlled wheelchair**, enabling mobility assistance through brainwave signals. Using a **NeuroSky Mindwave EEG headset**, brain signals were captured and processed to interpret the user's intent, which was then translated into **wheelchair movement commands** via an **Arduino Mega 2560 microcontroller**.  

While the project achieved **partial success (25% prediction accuracy)**, it highlighted **the complexity of brain signal processing** and the **need for advanced noise filtering and machine learning models** in brain-computer interface (BCI) applications.  

🔗 **GitHub Repository:** [Brain-Controlled Wheelchair](https://github.com/Sufian5642/FYP.git)

---

## 🚀 Key Features

- ✅ Captured real-time **EEG brainwave signals** using NeuroSky Mindwave headset.  
- ✅ Reduced **signal noise by 30%** using advanced filtering and preprocessing techniques.  
- ✅ Developed a **Decision Tree classifier** to predict user intent (forward, left, right, stop).  
- ✅ Integrated machine learning predictions with **Arduino Mega 2560** for wheelchair control.  
- ✅ Provided **hands-free navigation support** for individuals with mobility impairments.  
- ⚠️ **Prototype limitation:** Achieved **25% accuracy** due to high noise levels in EEG signals.  

---

## 🛠️ Tech Stack

- **Programming Languages:**  
  - Python 🐍  
  - MATLAB (signal processing)  
  - Arduino IDE (microcontroller control)  

- **Hardware:**  
  - 🧠 NeuroSky Mindwave EEG Headset  
  - 🔌 Arduino Mega 2560  
  - ⚙️ DC Motors & Wheelchair Chassis  

- **Libraries:**  
  - [Scikit-learn](https://scikit-learn.org/) – Decision Tree model training  
  - [NumPy](https://numpy.org/) – Numerical computations  
  - [Pandas](https://pandas.pydata.org/) – Data manipulation  
  - [Matplotlib](https://matplotlib.org/) – Visualization of signals and predictions  

---

## 📂 Dataset

- EEG signal data collected using **NeuroSky headset** from multiple participants.  
- Brainwave frequency bands:  
  - Alpha, Beta, Theta, Delta waves.  
- Preprocessing steps:
  - Noise reduction (30% improvement).  
  - Feature extraction from EEG signals.  
  - Train-test split for ML modeling.  

---

## ⚙️ Workflow

1. **Signal Acquisition**  
   - Captured EEG brainwave data via NeuroSky headset.

2. **Signal Processing**  
   - Applied **MATLAB-based filtering** to reduce noise.  
   - Extracted frequency features for machine learning.

3. **Model Development**  
   - Trained a **Decision Tree classifier** to predict commands:
     - Forward, Left, Right, Stop.

4. **Hardware Integration**  
   - Sent predicted commands from Python to **Arduino Mega 2560**.  
   - Controlled wheelchair motor movement accordingly.

5. **Testing & Evaluation**  
   - Achieved **25% accuracy**, mainly limited by noisy EEG signals.  

---

## 📊 Results

- ✅ **Successful signal acquisition and hardware integration** with real-time command execution.  
- ✅ **Noise reduced by 30%**, improving signal clarity.  
- ⚠️ Model accuracy remained at **25%**, indicating the need for:
  - More robust noise filtering techniques.
  - Advanced ML models (SVM, Neural Networks).  

---

