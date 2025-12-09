# AI Hand-Tracked 3D Helmet – Computer Vision + Three.js

An **AI-powered real-time 3D interaction system** that allows users to control a futuristic 3D helmet using **hand gestures detected through a webcam**. This project combines **Artificial Intelligence, Computer Vision, and WebGL** to create an immersive, futuristic user experience.

Developed by **Love Patel**, a B.Sc. IT (Honours – AI & ML) student at **Parul University**, this project demonstrates practical implementation of **AI + Web Development + Interactive Graphics**.


---

## 🧠 AI + Computer Vision Features

- ✋ **Real-time Hand Tracking using MediaPipe AI**
- 🪖 **3D Helmet Control with Natural Hand Movements**
- 🖼️ **Upload Any Image & Convert It into a 3D Interactive Object**
- 🧭 **Smooth AI-based Motion Mapping with LERP Smoothing**
- 🛰️ **Auto-Hiding Futuristic Control Panel UI**
- 📷 **Live Webcam Preview for Tracking Feedback**
- 🌌 **Cyberpunk / Sci-Fi Visual Theme**

---

## 🛠 Technology Stack

| Category | Tech |
|----------|------|
| 3D Graphics | Three.js |
| AI Vision | MediaPipe Hand Landmarker |
| Programming | JavaScript, HTML, CSS |
| AI Skills Used | Gesture Recognition, Coordinate Mapping |
| Web Concepts | WebGL, Real-time Rendering |
| UI Design | Glassmorphism, Animated UI |

---

## 🎯 Purpose of the Project

This project was built to:

- Demonstrate **AI-based real-time interaction**
- Apply **Computer Vision in Web Applications**
- Connect **Artificial Intelligence with Creative Front-End Development**
- Strengthen hands-on experience in:
  - AI
  - Machine Learning foundations
  - Cloud + Web deployment ready projects

---

## 🚀 How It Works

1. User allows webcam access
2. AI detects index finger using **MediaPipe Hand Landmarker**
3. Finger position controls **3D rotation of the helmet or image**
4. User can:
   - Upload an image → Converted into a **3D texture plane**
   - Reset back to the **default helmet**
5. All movements are smoothed using **AI-based interpolation**

---

## 🧩 Project Structure

```text
.
├── index.html      # Main UI & layout
├── app.js          # AI logic, Three.js rendering, MediaPipe tracking
└── assets/         # Optional models/textures
