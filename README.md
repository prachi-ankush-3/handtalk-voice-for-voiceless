# 🤟 HandTalk – Voice for the Voiceless

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv"/>
  <img src="https://img.shields.io/badge/Mediapipe-Hand%20Tracking-0097A7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

<p align="center">
  <b>An AI-powered Sign Language Recognition System that converts hand gestures into text and speech, helping bridge the communication gap for speech and hearing-impaired individuals.</b>
</p>

---

## 📖 About the Project

**HandTalk – Voice for the Voiceless** is a Computer Vision and Deep Learning project that recognizes **American Sign Language (ASL) alphabet gestures** in real time using a webcam.

The system captures hand gestures, detects hand landmarks using **MediaPipe**, processes the image using **OpenCV**, and predicts the corresponding alphabet using a trained **Convolutional Neural Network (CNN)** model. The predicted letters are displayed on the screen and can also be converted into speech using **Text-to-Speech (TTS)**.

This project aims to make communication more accessible and natural for individuals with speech impairments.

---

## ✨ Features

- 🎥 Real-time webcam-based hand gesture detection
- 🤖 AI-powered alphabet recognition using CNN
- ✋ Hand landmark detection with MediaPipe & Cvzone
- 📝 Converts gestures into text
- 🔊 Text-to-Speech output
- 📊 Data collection scripts for model training
- ⚡ Fast and user-friendly interface

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Computer Vision | OpenCV |
| Deep Learning | TensorFlow, Keras |
| Hand Tracking | MediaPipe, Cvzone |
| GUI | CustomTkinter |
| Image Processing | Pillow |
| Speech | pyttsx3 |
| Numerical Computing | NumPy |

---

## 📂 Project Structure

```text
handtalk-voice-for-voiceless/
│
├── cnn8grps_rad1_model.h5          # Trained CNN model
├── data_collection_binary.py       # Binary dataset collection
├── data_collection_final.py        # Improved data collection
├── final_pred.py                   # Main GUI prediction program
├── prediction_wo_gui.py            # Prediction without GUI
├── reference.jpg                   # Gesture reference
├── white.jpg                       # Processing background image
├── requirements.txt                # Required libraries
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/handtalk-voice-for-voiceless.git
cd handtalk-voice-for-voiceless
```

### 2️⃣ Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy opencv-python tensorflow keras mediapipe cvzone pyenchant customtkinter Pillow pyttsx3
```

---

## ▶️ Running the Project

Launch the Sign Language Recognition System:

```bash
python final_pred.py
```

---

## 🧠 How It Works

```text
Webcam
   │
   ▼
Capture Hand Gesture
   │
   ▼
MediaPipe Hand Detection
   │
   ▼
Image Processing (OpenCV)
   │
   ▼
CNN Model Prediction
   │
   ▼
Recognized Alphabet
   │
   ├────────► Display Text
   │
   └────────► Convert to Speech
```

---

## 📸 Output Screenshots

> Add your screenshots here.

### 🏠 Main Interface

<p align="center">
<img src="images/home.png" width="900">
</p>

---

### ✋ Gesture Detection

<p align="center">
<img src="images/detection.png" width="900">
</p>

---

### 🔤 Alphabet Prediction

<p align="center">
<img src="images/prediction.png" width="900">
</p>

---

### 🔊 Speech Output

<p align="center">
<img src="images/output.png" width="900">
</p>

---

## 📦 Requirements

- Python 3.11+
- Webcam
- TensorFlow
- OpenCV
- MediaPipe
- Cvzone
- NumPy
- CustomTkinter
- Pillow
- pyttsx3
- pyenchant

---

## 🎯 Future Enhancements

- ✅ Word and sentence prediction
- ✅ Support for complete sign language vocabulary
- ✅ Improved CNN accuracy
- ✅ Mobile application
- ✅ Multiple language support
- ✅ Cloud deployment

---

## 👩‍💻 Author

**Prachi Ankush**

- 🎓 B.Tech Computer Engineering (Software Engineering)
- 🏫 Vishwakarma Institute of Technology, Pune

---

## ⭐ If you found this project helpful

Give this repository a **⭐ Star** and support the project!

<p align="center">
Made with ❤️ using Python, Computer Vision, and Deep Learning.
</p>
