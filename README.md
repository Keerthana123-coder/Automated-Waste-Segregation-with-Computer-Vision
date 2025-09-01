♻️Automated-Waste-Segregation-with-Computer-Vision

Project Description

This project implements an AI-powered waste classification and segregation system using Deep Learning, OpenCV, and MediaPipe.
It classifies waste items into Organic or Recyclable, and uses hand gesture recognition for virtual interaction with colored dustbins displayed on screen.
The system is designed for real-time execution .

🔹 Improvements Over Existing Projects

Most existing waste classification projects stop at static image classification.
This project introduces several unique improvements:

1️⃣ From Static to Real-Time

supports live webcam classification for real-time waste detection.

2️⃣ Gesture-Controlled Virtual Bins

builds a visual dustbin interface and allows gesture-based interaction without mouse/keyboard.

3️⃣ User-Friendly GUI

interactive on-screen 2D dustbins with prediction highlights, making it educational & user-friendly.

4️⃣ Integration of Computer Vision + Deep Learning

 combines CNN classification with OpenCV & MediaPipe for gesture control.

5️⃣ Scalability & Real-World Usability
 modular pipeline that can be extended to more waste types, IoT-based sorting bins, or even robotic integration.


 🔹 Dataset Flow
We used the Waste Classification Dataset
 from Kaggle containing 22,500 images divided into two categories:

Organic 🥬 → food waste, natural materials

Recyclable ♻️ → plastics, metals, paper, glass

📂 Dataset Structure
dataset/
│
├── TRAIN/                 # Training images (85%)
│   ├── Organic/           # Organic waste images
│   └── Recyclable/        # Recyclable waste images
│
├── TEST/                  # Testing images (15%)
│   ├── Organic/
│   └── Recyclable/

