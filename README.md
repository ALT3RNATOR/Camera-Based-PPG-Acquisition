# 📸 Camera-Based PPG Signal Acquisition

This repository presents a **smartphone camera–based photoplethysmography (PPG) signal acquisition system** using green channel intensity extraction from video frames.

The system captures raw PPG signals in real time, excludes warm-up artifacts, stores patient-wise data in CSV format, and provides interactive waveform visualization.


---

## 🔍 Key Features

- 📷 Smartphone / USB camera based PPG acquisition
- 🟢 Green channel intensity extraction (rPPG)
- ⏳ Warm-up time exclusion
- ⏱ Automatic data milestones (90s & 120s) 
- 💾 Patient-wise CSV storage
- 📈 Interactive Plotly visualization
- 📊 Effective sampling rate estimation

---

## 🧠 Working Principle

Photoplethysmography is extracted by computing the **mean intensity of the green channel** from each video frame.  
Green light (~540 nm) exhibits strong absorption by hemoglobin, making it ideal for camera-based PPG extraction.

---
