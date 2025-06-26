# Driver_Drowsiness_Detection_
PROJECT CATEGORY
# 🛑 Driver Drowsiness Detection using Computer Vision

🚗💤 Prevent accidents. Save lives.

![Drowsiness Detection Preview](media/demo.gif)

---

## 📍 Overview

Driver drowsiness is a **major cause of road accidents** globally. This project uses **real-time computer vision** and **deep learning** to monitor a driver's eye state and issue alerts if signs of fatigue are detected.

> Your seatbelt saves you during a crash.  
> This AI prevents it from happening.

---

## 📹 Demo Preview

![Preview of Detection](media/preview.png)

The system uses webcam feed to monitor the driver’s:
- Eye blinking rate
- Eye closure duration
- Yawning (optional upgrade)

If eyes remain closed beyond a safe threshold, an alarm is triggered to wake the driver.

---

## 🧠 Tech Stack

| Component       | Tech Used                           |
|-----------------|-------------------------------------|
| Language        | Python                              |
| Computer Vision | OpenCV                              |
| Face Detection  | Haar Cascades or Dlib               |
| Eye Detection   | CNN Model / EAR (Eye Aspect Ratio)  |
| Alert System    | Pygame / OS Audio / Text-to-Speech  |
| UI (Optional)   | Streamlit or Tkinter                |

---

## 📁 Project Structure


Driver_Drowsiness_Detection/
│
├── media/ # Images & GIFs for README
├── haarcascade/ # Haar cascade models
├── model/ # Pretrained CNN model (if used)
├── main.py # Entry point script
├── utils.py # EAR calculations, helper methods
├── alarm.wav # Alert sound
└── README.md


🧪 How It Works
Eye Aspect Ratio (EAR)




Computes the vertical vs horizontal eye distance

If EAR < threshold for certain frames → eyes are considered closed




🚨 Features
✅ Real-time eye tracking
✅ Alarm system when eyes closed too long
✅ Lightweight — runs on laptops and Raspberry Pi
✅ Optional CNN model for increased accuracy
✅ Can be extended with yawning or head-tilt detection





🌐 Applications
Automotive safety systems

Fleet management software

Industrial machine operators

Public transport monitoring

Sleep study research






📌 Future Enhancements
Add mobile app integration (Android/iOS)

Use YOLOv8 for improved face/eye detection

Track head nodding or yawning for multi-signal fatigue detection

Add real-time alert dashboard for fleet companies






👨‍💻 Author
Crafted with vision and vigilance by ✨ ANURAG SAINI ✨





⭐ Support
IF YOU APPRECIATE MY WORK PLEASE GIVE STAR ⭐

Your support keeps innovation alive and roads safer.
