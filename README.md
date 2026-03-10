
# AI-Based Real-Time Heart Monitoring System
**Department of Instrumentation and Control, COEP Technological University**

## 📌 Project Overview
This project implements an intelligent cardiac monitoring system using a **1D-Convolutional Neural Network (1D-CNN)**. It is designed to automatically detect and mark the **P-wave** in ECG signals, which is a critical marker for diagnosing various arrhythmias.

## 🚀 Key Features
- **Automated Feature Extraction:** Uses Deep Learning to eliminate the need for manual signal thresholding.
- **Real-Time Simulation:** An inference engine that processes raw ECG streams and highlights P-wave peaks live.
- **Lightweight Architecture:** The trained model is only ~1.4 MB, making it suitable for Edge-AI deployment.
- **Data Source:** Based on the gold-standard MIT-BIH Arrhythmia Database.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Deep Learning:** TensorFlow / Keras
- **Medical Data Handling:** WFDB (Waveform Database) library
- **Visualization:** Matplotlib & Seaborn

## 📂 Repository Structure
- `HMS.ipynb`: Main notebook containing data preprocessing, model training, and evaluation.
- `heart_monitor_model.h5`: The final trained CNN model.
- `100.dat / .hea / .pwave`: Sample patient records for demonstration.

## 📊 Results
- **Training Accuracy:** 100%
- **Inference:** Successfully identifies P-waves in real-time sliding windows of 360 samples (1 second).

## 📝 Future Scope
- Integration with hardware (ESP32/FPGA).
- Detection of QRS and T-wave complexes.
- Development of a mobile-based patient alert system.
