# 🎚 AirTune : Hand Gesture Volume Control  

> **Contactless audio control** — adjust your system volume using nothing but your fingers 🖐️🎵  

---

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange?style=for-the-badge)
![PyCaw](https://img.shields.io/badge/PyCaw-Audio%20Control-yellow?style=for-the-badge)

---

## 🧠 About the Project  

**AirTune** is a **gesture-driven system volume controller** that lets you adjust your computer’s audio using only your hand gestures in front of a webcam.  

- ✋ Detects your **thumb & index finger** in real time  
- 🎚 Changes **volume level** based on the distance between them  
- 📊 Displays **live volume bar and percentage**  
- ⚡ Built with **OpenCV**, **MediaPipe**, **PyCaw**, and **Streamlit**  

Perfect for:  
- 🎤 Presenters & teachers (hands-free audio control)  
- 🎮 Gamers & music enthusiasts  
- 🧑‍💻 Developers exploring **gesture recognition + system integration**  

---

## 🔍 Use Case  

- Adjust volume **without touching the keyboard or mouse**  
- Useful in **COVID-safe setups** for contactless control  
- Adds a **cool AI-powered feature** to your system 👨‍💻  

---

## ⚙️ Tech Stack  

- **Streamlit** — Web interface for running & visualizing  
- **OpenCV** — Video capture and drawing  
- **MediaPipe** — Real-time hand tracking  
- **NumPy** — Math operations  
- **PyCaw** — System-level volume control on Windows  

---

## 🚀 How It Works  

1. 🎥 Captures **live feed** from your webcam  
2. ✋ Detects **hand landmarks** using **MediaPipe**  
3. 📏 Calculates distance between **thumb & index finger**  
4. 🎚 Maps distance → volume range using **interpolation**  
5. 🔊 Adjusts system volume with **PyCaw**  
6. 📊 Displays volume percentage and live video in a **Streamlit dashboard**  

