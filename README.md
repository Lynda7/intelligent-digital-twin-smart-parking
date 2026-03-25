# 🏗️ Intelligent Digital Twin for Smart Parking Optimization

[![IEEE Xplore](https://img.shields.io/badge/IEEE_Xplore-Article-blue?style=for-the-badge&logo=ieee)](https://ieeexplore.ieee.org/document/11412248)
![Award](https://img.shields.io/badge/Award-Best%20Paper%20CINS%202025-gold?style=for-the-badge)
![Specialty](https://img.shields.io/badge/Specialty-AI%20%26%20Data%20Science-green?style=for-the-badge)

> **Final Year Project (PFE) | Engineer's Degree Dissertation**
> This repository presents an award-winning **Intelligent Digital Twin** designed to solve the energy inefficiency of urban parking guidance systems using **Deep Reinforcement Learning**.

---

## 🏆 Honors & Awards
This research was recognized for its innovation and impact:
- 🌟 **BEST PAPER AWARD** at the 3rd International Conference on Computational Intelligence and Network Systems (**CINS 2025**), Dubai, UAE.
- 📄 **Official Publication:** [Read the full paper on IEEE Xplore](https://ieeexplore.ieee.org/document/11412248)

![Best Paper Certificate](./screenshots/best_paper_certificate.png)

---

## 📌 Project Overview
Modern smart parkings use LED-based guidance systems that consume massive amounts of energy. This project introduces a **proactive Digital Twin** orchestrated by a **Reinforcement Learning (RL)** agent.

### 🚀 Key Performance Results
- **81.8% Energy Reduction:** Achieved by learning an optimal load-balancing policy that keeps infrastructure in "standby mode" for as long as possible.
- **60% Search Time Optimization:** Improved user experience through intelligent vehicle distribution.

---

## 🌐 System Architecture
The project features a decoupled architecture ensuring real-time synchronization between the virtual model and the physical simulation.
![Architecture](./screenshots/system_architecture.png)

### 🎨 Digital Twin Interface
The "Quantum Parking Matrix" is a high-fidelity web dashboard (HTML/CSS/JS) that visualizes 150 parking spots and AI decisions in real-time via **MQTT**.
![Interface Preview](./screenshots/dashboard_preview.png)

---

## 🧠 AI Core: Reinforcement Learning (DQN)
The agent (Deep Q-Network) learns to assign vehicles to specific floors to minimize energy-intensive states while maintaining service quality.

### 📊 Performance Metrics
| Learning Convergence | Training KPIs Evolution |
|:---:|:---:|
| ![Rewards](./screenshots/learning_curve.png) | ![KPIs](./screenshots/training_kpis_evolution.png) |
| *Stable convergence achieved after 80 episodes* | *Drastic reduction in variance and failures* |

---

## 📁 Repository Structure
- **`/docs`**: Full dissertation report and Best Paper Award documentation.
- **`/rl-engine`**: Python scripts and Jupyter Notebooks for agent training and traffic simulation.
    - Includes `q_table_final.pkl`: The pre-trained brain of the system.
- **`/ui-digital-twin`**: Source code of the interactive Web Dashboard.
- **`/screenshots`**: Full gallery of research results and UI previews.

## 🛠 Tech Stack
- **AI/ML:** Python 3.9+, Scikit-Learn, NumPy, Pandas.
- **IoT/Network:** MQTT (EMQX), Paho-MQTT, MQTT.js.
- **Frontend:** HTML5, CSS3 (Modern Dark UI), JavaScript.
- **Orchestration:** n8n Workflows.

---
*Developed by Lynda OUALLAM - Academic Year 2024/2025.*  
*Supervised by Dr. Ahcene BOUNCEUR & Pr. Faïçal AZOUAOU.*