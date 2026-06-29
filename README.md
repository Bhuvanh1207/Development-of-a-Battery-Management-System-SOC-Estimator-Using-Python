
# 🔋 Battery State of Charge (SOC) Estimator

<p align="center">
  <img src="images/banner.png" width="800">
</p>

<p align="center">
  A Python-based Battery Management System (BMS) simulation for estimating battery charge using multiple SOC estimation algorithms.
</p>

---

## 📌 Overview

Battery State of Charge (SOC) estimation is one of the most critical tasks in Battery Management Systems (BMS). This project simulates how real-world EV batteries estimate remaining charge using:

- ⚡ Coulomb Counting
- 🔋 Open Circuit Voltage (OCV) Lookup
- 🧠 Kalman Filter

This project helps understand the practical implementation of battery charge estimation used in Electric Vehicles and Energy Storage Systems.

---

## 🎯 Objectives

✔ Simulate lithium-ion battery discharge  
✔ Implement SOC estimation techniques  
✔ Compare estimation accuracy  
✔ Analyze error in real-time  
✔ Visualize battery performance using graphs  

---

## 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming |
| NumPy | Mathematical operations |
| Matplotlib | Data visualization |
| SciPy | OCV interpolation |

---

## ⚙ Working Principle

### 1️⃣ Coulomb Counting
Tracks current over time:



---

2️⃣ OCV Lookup

Uses battery voltage to estimate SOC.

Voltage ↔ Charge mapping.


---

3️⃣ Kalman Filter

Combines Coulomb Counting + OCV for higher accuracy.


---

📸 Project Screenshots

Code Execution

<img width="1134" height="692" alt="image" src="https://github.com/user-attachments/assets/216e6e30-caf9-4e00-8430-6afde4643b3d" />

---

SOC Estimation Graph

<img width="1567" height="758" alt="image" src="https://github.com/user-attachments/assets/ea190097-1433-4daa-8034-892861438508" />

---

Error Comparison Graph

<img width="1551" height="749" alt="Screenshot 2026-06-29 150324 (1)" src="https://github.com/user-attachments/assets/9fb84f27-7895-4ba7-8398-40092a93427b" />

---

📊 Results

Method	Average Error

Coulomb Counting	0.43%
OCV Lookup	0.61%
Kalman Filter	<1%



---

📂 Folder Structure

Battery-SOC-Estimator/
│── soc_estimator.py
│── soc_results.png
│── soc_log.csv
│── images/
│   ├── banner.png
│   ├── output.png
│   ├── soc_graph.png
│   ├── error_graph.png
│── README.md


---

🚀 How to Run


Install dependencies:

pip install numpy matplotlib scipy

Run project:

python soc_estimator.py


---

🔮 Future Improvements

Temperature-based SOC correction

Battery aging model

Charging cycle simulation

Real-time sensor integration using ESP32

AI-based SOC prediction



---

🌍 Applications

🚗 Electric Vehicles
☀ Solar Energy Storage
🔋 Battery Packs
🏠 UPS Systems
📱 Portable Electronics


---

👨‍💻 Author

Bhuvan h
ECE Student
Interested in Embedded Systems, EV Technology, Battery Systems


---
