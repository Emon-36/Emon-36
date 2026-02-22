<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=00E5FF&center=true&vCenter=true&width=700&lines=Edge+AI+%26+Embedded+Systems+Engineer;ML+Deployment+%7C+Microgrid+Control;Rocketry+%7C+Computer+Vision+%7C+IoT)](https://git.io/typing-svg)

```
╔══════════════════════════════════════════════════════════════╗
║  Building intelligent systems at the edge of what's possible ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## Hi, I'm Emon 👋

I'm a 3rd year EEE student at the University of Chittagong who builds **complete AI-powered systems from circuit to interface** — solo. I design the hardware, write the embedded firmware, deploy the ML models, and ship the Android app that controls everything.

My focus is making AI work where it shouldn't — on low-cost, offline, constrained hardware. From running LLMs on a $25 TV box to achieving 125ms object detection on a $25 ARM device, I specialize in turning machine learning into real machine action.

---

## 🛠 What I Do

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded_C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=google-play&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TFLite](https://img.shields.io/badge/Edge_ML-TFLite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/Vision-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Shell_Scripting-%234EAA25.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## 🧠 Core Skills

<div align="center">

| Domain | Stack |
|--------|-------|
| **ML Deployment** | ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) ![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white) |
| **Edge Integration** | ![Armbian](https://img.shields.io/badge/Armbian-E6821E?style=flat-square&logo=armbian&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) |
| **Android UI** | ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **AI/ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **Embedded** | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) |
| **Power Electronics** | ![Inverter](https://img.shields.io/badge/Full_Bridge_Inverter-SPWM-FF6F00?style=flat-square) ![VFD](https://img.shields.io/badge/VFD-Software_Defined-00599C?style=flat-square) |

</div>

---

## 🚀 Featured Projects

---

### ⚡ AI-Powered Smart Solar Microgrid

<img src="https://img.shields.io/badge/Status-Demo--Ready-7fff6b?style=flat-square"/> <img src="https://img.shields.io/badge/Rating-8.5%2F10-FFD700?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-LSTM%20%7C%20TFLite%20%7C%20Android-FF6F00?style=flat-square"/>

> A household-scale, edge-first microgrid blending AI forecasting, battery safety, and real-time control — built with a custom full bridge SPWM inverter and adaptive weather-based charge control.

```
  ☀️ Solar PV
      │
      ▼
┌─────────────────────────────────────────────────┐
│            AI Controller (Edge)                 │
│  ┌────────────┐   ┌──────────────────────────┐  │
│  │ LSTM/TCN/  │   │  Hybrid Rule-AI Logic    │  │
│  │ 1D-CNN     │──▶│  SoC Thresholds          │  │
│  │ Forecaster │   │  Load Priority           │  │
│  └────────────┘   └──────────────────────────┘  │
└────────────────────────┬────────────────────────┘
                         │
         ┌───────────────┼──────────────────┐
         ▼               ▼                  ▼
   🔋 Battery BMS   🌀 TRIAC Fan      📱 Android App
   (Active/Passive) (ZC Detection)   (Jetpack Compose)
   Full Bridge      (PF Correction    Dashboard + E-Stop
   SPWM Inverter    LC Bank)
```

- 🔌 Custom full bridge SPWM inverter (10kHz switching)
- 🌦️ Adaptive weather-based charge control (feedforward + feedback)
- 🔋 Upcycled battery pack with active/passive BMS
- 🤖 LSTM/TCN/1D-CNN models for PV forecasting (TFLite/ONNX)
- 🌀 TRIAC fan control with zero-cross detection & PF correction via switchable LC banks
- 📱 Android app (Jetpack Compose) with dashboard, manual overrides, and emergency stop
- 🛡️ Safety: opto-isolated relays, watchdog heartbeat, fault injection logic
- 🌍 Designed for off-grid and BD rural contexts

[![Repo](https://img.shields.io/badge/GitHub-AI--Microgrid-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36/AI-Microgrid)

---

### 🚀 MARCS — Canard-Based Autonomous Flight Control System

<img src="https://img.shields.io/badge/Status-Active-ff6b35?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-ESP32%20%7C%20Kalman%20%7C%20SSD%20MobileNet-E7352C?style=flat-square"/>

> A canard-based flight control system with onboard AI, dual-mode target acquisition, and a full Android Ground Control Station.

```
         🛰️ Android Ground Control Station
              │   Live Telemetry + GPS Map
              │   Waypoint Planning (Dijkstra)
              │   Live Vision + Object Classification
              ▼
    ┌─────────────────────┐
    │      ESP32-CAM      │  ◀── SSD MobileNet V2 (Onboard)
    │   (Vision Module)   │       Real-time inference
    └──────────┬──────────┘
               │
    ┌──────────▼──────────┐
    │  ESP32 Flight Ctrl  │  ◀── GPS + BMP + Thermal Fusion
    │  Kalman Filter      │       (Kalman Filter)
    │  PID / PN Guidance  │
    │  Canard Actuation   │
    └──────────┬──────────┘
               │
    ┌──────────▼──────────┐
    │ 6x6 Photodiode Array│  ◀── Heat seeking up to 7m
    │ (Custom, No TIA)    │       Spatial summation design
    └─────────────────────┘
```

- 🎯 Custom 6x6 photodiode array — heat seeking up to 7m **without TIA**
- 🤖 Onboard SSD MobileNet V2 inference during flight
- 🧮 Kalman Filter sensor fusion (GPS, BMP, Thermal)
- 🗺️ Waypoint-based autonomous navigation
- 📡 Android GCS with live map, telemetry, and video feed

[![Repo](https://img.shields.io/badge/GitHub-MARCS-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36/Multidimensional-Advanced-Robot-Control-System-MARCS)

---

### 🖥️ Easy Llama Edge — LLMs on 1GB RAM

<img src="https://img.shields.io/badge/Status-Complete-3DDC84?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-llama.cpp%20%7C%20Armbian%20%7C%20Clang-4A90D9?style=flat-square"/>

> Run modern LLMs locally on a $25 Android TV box with only 1GB RAM — no cloud, no subscriptions.

```
  📦 $25 Android TV Box (Allwinner H313)
         │
         ▼
  ┌─────────────────────────────┐
  │     Armbian Linux (CLI)     │
  │  ┌───────────────────────┐  │
  │  │ llama.cpp (Clang opt) │  │
  │  │ 4GB Swap Management   │  │
  │  │ GGUF INT4/INT8 Quant  │  │
  │  └───────────────────────┘  │
  └─────────────────────────────┘
         │
         ▼
  Qwen 2.5 (0.5B): 4.2–5.5 tok/s
  Llama 3.2 (1B):  1.8–2.5 tok/s
```

- ⚡ Clang-optimized ARMv8 binary
- 🧠 Runs Qwen 2.5 (0.5B) and Llama 3.2 (1B)
- 🔒 100% offline — no cloud required
- 📜 One-click setup script

[![Repo](https://img.shields.io/badge/GitHub-Easy--Llama--Edge-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36/easy-llama-edge)

---

### 📱 Smart Hub Pro — IoT Home Automation

<img src="https://img.shields.io/badge/Status-Complete-3DDC84?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-ESP32%20%7C%20Firebase%20%7C%20Jetpack%20Compose-4285F4?style=flat-square"/>

> A complete smart home system with ESP32 Bluetooth provisioning, Firebase backend, and Jetpack Compose UI.

- 📡 ESP32 Bluetooth WiFi provisioning
- 🔥 Firebase real-time sync
- 💡 Bulb, fan, and multi-room control
- ⚡ Energy monitoring with monthly bill estimation
- 🎨 Color-coded room themes

[![Repo](https://img.shields.io/badge/GitHub-SmartHub-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36)

---

### 🔴 Resistor Color Detector

<img src="https://img.shields.io/badge/Status-Complete-3DDC84?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-YOLOv8%20%7C%20OpenCV-5C3EE8?style=flat-square"/>

> Computer vision pipeline for detecting resistor color bands and decoding resistance values.

```
  📷 Camera Input
       │
       ▼
  ┌──────────┐    ┌─────────────────┐    ┌────────────────┐
  │ YOLOv8   │───▶│ OpenCV Post-    │───▶│ Resistance     │
  │ Detection│    │ processing      │    │ Value Decoded  │
  └──────────┘    └─────────────────┘    └────────────────┘
```

[![Repo](https://img.shields.io/badge/GitHub-Resistor--Color--Detector-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36/Resistor-color-detector)

---

### 🤖 Offline RAG Chatbot

<img src="https://img.shields.io/badge/Status-Complete-3DDC84?style=flat-square"/> <img src="https://img.shields.io/badge/Stack-Ollama%20%7C%20RAG%20%7C%20Streamlit-4A90D9?style=flat-square"/>

> Fully offline document chatbot — no cloud, no API keys.

- 🔒 Local-only architecture
- 📄 Upload and chat with your documents
- 🔧 Modular embedding, retrieval, generation pipeline

[![Repo](https://img.shields.io/badge/GitHub-ChatbotUsingLLM-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36/ChatbotUsingLLM)

---

## 🏆 Achievements

<div align="center">

| | Award | Description |
|-|-------|-------------|
| 🥇 | **Champion** — Inter University Business Ideation Competition | Led winning team with scalable tech-driven business model |
| 🎖️ | **Finalist** — Hult Prize On Campus | Top innovator, world's largest student entrepreneurship challenge |
| 💰 | **UIHP Grant — 45,000 BDT** | University Innovation Hub grant for business ideation |

</div>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Emon-36&show_icons=true&theme=github_dark&hide_border=true&accent_color=00e5ff&title_color=00e5ff&icon_color=ff6b35)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Emon-36&layout=compact&theme=github_dark&hide_border=true&title_color=00e5ff)

![GitHub Streak](https://streak-stats.demolab.com?user=Emon-36&theme=github-dark-blue&hide_border=true&ring=00e5ff&fire=ff6b35&currStreakLabel=00e5ff)

</div>

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Md%20Shahariar%20Khan%20Emon-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/md-shahariar-khan-emon-8758a3327)
[![Email](https://img.shields.io/badge/Email-emon23702036%40gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:emon23702036@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Emon--36-181717?style=for-the-badge&logo=github)](https://github.com/Emon-36)

</div>

---

<div align="center">

*"Build at the edge. Think at scale."*

![Wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=120&section=footer)

</div>
