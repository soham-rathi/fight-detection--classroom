# 🚨 Fight Detection System in Classrooms

> Automated real-time fight and violence detection system using Computer Vision to enhance classroom safety.

---

## 📌 Project Overview

This system automatically detects **physical altercations and aggressive behavior** in classroom video feeds. Upon detection, it triggers instant alerts to school/college authorities — enabling faster intervention and improving student safety.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| OpenCV | Video capture & frame processing |
| Computer Vision Models | Aggressive gesture detection |
| Custom Dataset | Trained on fight vs normal activity videos |

---

## 🚀 Features

- ✅ Real-time fight detection from live video feeds
- ✅ Automated alert system for school authorities
- ✅ Distinguishes between normal movement and aggressive gestures
- ✅ Trained on curated video dataset for high accuracy
- ✅ Fast response time for timely intervention

---

## 📂 Project Structure

```
fight-detection-classroom/
│
├── data/               # Video dataset and frames
├── models/             # Trained model weights
├── src/                # Source code
│   ├── preprocess.py   # Frame extraction & preprocessing
│   ├── train.py        # Model training pipeline
│   ├── detect.py       # Real-time detection engine
│   └── alert.py        # Alert notification system
├── results/            # Sample detection outputs
└── README.md
```

---

## 🧠 How It Works

1. **Video Input** — Live camera feed or recorded video is taken as input
2. **Frame Analysis** — Each frame is analyzed for body pose and motion patterns
3. **Fight Detection** — Model classifies whether aggressive behavior is occurring
4. **Alert Trigger** — Automated notification sent to authorities upon detection

---

## 📊 Results

- Successfully detects physical altercations in real-time
- Reduced false positives using multi-frame analysis
- Tested and validated in controlled classroom environment at VIT Pune

---

## 🎯 Use Cases

- School & college campus safety
- Hostel and dormitory monitoring
- Public space security systems

---

## 👨‍💻 Author

**Soham Rathi**
- 📧 soham.rathi23@vit.edu
- 🔗 [LinkedIn] https://www.linkedin.com/in/soham-rathi-54193528a?utm_source=share_via&utm_content=profile&utm_medium=member_android
- 📍 VIT Pune | B.Tech IT | 2027

---

## 📄 License

This project is for educational and research purposes.
