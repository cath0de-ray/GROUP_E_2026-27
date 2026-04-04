# Project VITALIS: AI-Driven Acoustic Triage Node
**An Edge-AI Stethoscope Attachment for Rapid Pulmonary Diagnostics**

![Project Status](https://img.shields.io/badge/Status-Prototype_Development-blue)
![AI Accuracy](https://img.shields.io/badge/AI_Accuracy-80.7%25-green)
![Grade](https://img.shields.io/badge/Academic_Level-12th_Grade-purple)
![License](https://img.shields.io/badge/License-Apache_2.0-red)

## 🩺 Project Overview
VITALIS (Ventilation & Internal Lung Integrated System) is a low-cost, offline AI diagnostic tool. It utilizes an **ESP32** and an **INMP441 I2S Microphone** to perform real-time classification of respiratory sounds.

This project is designed for 12th-grade CBSE AI Practical (2026-27) and serves as a modular attachment for standard stethoscopes to assist NGO field workers in resource-depleted environments.

## 🧠 Neural Network Performance
The model is trained on the HLS-CMDS clinical dataset using Mel Frequency Cepstral Coefficients (MFCC) for feature extraction.

### Validation Results
* **Overall Accuracy:** 80.7%
* **Normal Lung Precision:** 96.2%
* **Training Depth:** 600 Epochs

### Evidence of Training
![Edge Impulse Accuracy Report](accuracy_report.png)
> *Figure 1: Confusion Matrix validating the model's high reliability in identifying healthy vs. anomalous respiratory cycles.*

---

## 🛠️ Hardware Stack (BOM)
* **MCU:** ESP32 DevKit V1 (38-pin Type-C)
* **Sensor:** INMP441 I2S Digital MEMS Microphone
* **Display:** 0.96" I2C OLED (SSD1306)
* **Acoustics:** Standard Stethoscope + Custom 3D Printed/PVC T-junction

---

## ⚖️ Licensing & Legal Notice

### Software & Hardware License
This project is licensed under the **Apache License, Version 2.0**.
* **Patent Protection:** This license provides an explicit grant of patent rights from contributors to users.
* **Legal Shield:** It contains a patent retaliation clause to protect the developer from meritless patent litigation.

### Dataset Attribution (Academic Citation)
The training data is derived from the **HLS-CMDS Dataset**. Per the author's requirements, all derivatives must cite:
> **Citation:** Y. Torabi, S. Shirani and J. P. Reilly, "Descriptor: Heart and Lung Sounds Dataset Recorded from a Clinical Manikin using Digital Stethoscope (HLS-CMDS)," in IEEE Data Descriptions, 2025. © 2024 Yasaman Torabi.

---

## 📄 Apache License 2.0 (Summary)
Copyright 2026 Pradhumya Singh Yadav

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

---
**Developer:** Pradhumya Singh Yadav  
**School:** Jagran Public School, Noida  
**Focus:** Sustainable Medical Innovation (SDG 3, 9, 10)