# 🛰️ DisasterVision AI  
### Satellite-Based Real-Time Disaster Detection System using Deep Learning (YOLOv8)

---

## 🌍 Overview

DisasterVision AI is a satellite-based Deep Learning system that analyzes Earth observation images in real-time to detect natural disasters such as:

- 🔥 Wildfires / Forest Fires  
- 🌊 Flooded regions  
- ☁️ Smoke / Early fire indicators  
- 🏚️ Infrastructure damage after disasters  

The system runs AI models on satellite-captured images to identify only critical events and reduce unnecessary data transmission.

---

## 🚨 Problem Statement

Satellites capture massive amounts of Earth imagery every day.

However:
- Most images contain normal terrain (oceans, land, clouds)
- Sending all data to Earth consumes huge bandwidth
- Manual analysis causes delays in disaster response

⏳ Result: Critical disasters may be detected too late.

---

## 💡 Solution

DisasterVision AI brings intelligence to the satellite itself:

- Processes images onboard / near-real-time
- Detects disaster events using YOLOv8
- Filters out normal images
- Transmits only critical alerts + relevant frames

✔️ This reduces bandwidth usage significantly  
✔️ Enables faster disaster response  

---

## 🧠 Tech Stack

- Python  
- YOLOv8 (Ultralytics)  
- OpenCV  
- PyTorch  
- Satellite Imagery Datasets (Sentinel-2 / NASA MODIS)  

---

## ⚙️ System Architecture

Satellite Camera Image  
→ Preprocessing (Image Cleaning)  
→ YOLOv8 Deep Learning Model  
→ Disaster Classification & Detection  
→ Filtering (Important Events Only)  
→ Transmission of Alerts to Ground Station  

---

## 📦 Features

- 🛰️ Satellite image-based analysis  
- 🔥 Fire detection in forests and land regions  
- 🌊 Flood detection using water spread patterns  
- ☁️ Smoke detection for early fire warnings  
- ⚡ Real-time inference using YOLOv8  
- 📡 Sends only critical data to Earth  

---

## 🌍 Real-World Applications

- ISRO / NASA Earth observation systems  
- Disaster monitoring from satellites  
- Early warning systems for governments  
- Climate change monitoring  
- Forest fire prevention systems  
- Flood response and rescue planning  

---

## 📁 Project Structure

DisasterVision-AI/
│
├── models/              # YOLOv8 trained model
├── datasets/            # Satellite image dataset
├── preprocess.py        # Image preprocessing
├── detect.py            # Disaster detection logic
├── app.py               # Demo interface (optional)
├── requirements.txt
└── README.md

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/DisasterVision-AI.git
cd DisasterVision-AI
pip install -r requirements.txt