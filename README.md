# 🚦 Intelligent Traffic Control Dashboard

**Author:** Aditya Kumar  
**Branch:** CSE AIML, 6th Semester  

---

## Overview
This project is a **real-time multi-junction traffic control dashboard** leveraging **YOLOv8** for vehicle detection, **Reinforcement Learning (RL)** for adaptive traffic signal control, and **Linear Regression** for predictive congestion modeling. It provides live **MJPEG streams**, **alerts**, **line graphs**, and **heatmaps** for traffic monitoring.

---

## Key Features
- Multi-threaded YOLOv8 vehicle detection for cars, bikes, buses, and trucks  
- Adaptive RL-based traffic signal control  
- Predictive congestion modeling using Linear Regression  
- Real-time MJPEG streaming dashboard using Dash and Plotly  
- Alerts for high congestion junctions  
- Thread-safe implementation for multiple junctions  

---

## Tech Stack
- **Python 3.x**  
- **OpenCV, NumPy**  
- **YOLOv8 (Ultralytics)**  
- **Dash, Plotly, Flask**  
- **Scikit-learn (Linear Regression)**  
- **SQLite** for traffic logs  

---

## Demo
Screenshots and GIFs are available in the [GitHub repo](#).  
_(Optional: You can embed images here)_
pip install -r requirements.txt
python traffic_dashboard.py

---
How It Works

Vehicle Detection: YOLOv8 detects cars, bikes, buses, and trucks in real-time.

Adaptive Signal Control: RL agent decides signal timings based on congestion state (LOW, MED, HIGH).

Predictive Modeling: Linear Regression predicts upcoming congestion trends.

Visualization: Live video feed, line graphs, and heatmaps display traffic trends.

Alerts: High congestion triggers visual alerts on the dashboard.

Future Scope

Integrate real city cameras for live traffic monitoring

Multi-agent RL for city-wide junction management

Cloud deployment for scalable, real-time monitoring

License

MIT License © Aditya Kumar

Contact

GitHub: [https://github.com/]

LinkedIn: [https://www.linkedin.com/in/aditya-kumar-31b0452a1/]
## Installation & Usage
1. Clone the repository:  
```bash
git clone <repo-url>
