
---

# HandTalk – Voice for the Voiceless

This project is a **sign language recognition system** that converts hand gestures into text and speech. The aim of the project is to help people who cannot speak communicate with others more easily.

The system captures hand gestures using a **webcam**, processes the image using **computer vision techniques**, and predicts the corresponding alphabet using a **trained CNN model**. The predicted characters can then be combined to form words.

---

# Features

* Real-time hand gesture detection
* Alphabet prediction using CNN model
* Text generation from gestures
* Speech output using text-to-speech
* Data collection script for training the model

---

# Technologies Used

* Python
* OpenCV
* TensorFlow / Keras
* Mediapipe / Cvzone
* NumPy

---

# Project Files

```
handtalk-voice-for-voiceless
│
├── cnn8grps_rad1_model.h5        # Trained CNN model
├── data_collection_binary.py     # Script to collect gesture data
├── data_collection_final.py      # Improved data collection script
├── final_pred.py                 # Main gesture prediction program
├── prediction_wo_gui.py          # Prediction without GUI
├── reference.jpg                 # Gesture reference image
├── white.jpg                     # Background image for processing
└── README.md
```

---

# How the System Works

1. The webcam captures the hand gesture.
2. The image is processed using OpenCV.
3. The trained CNN model predicts the corresponding alphabet.
4. The predicted characters are displayed as text.
5. Text can also be converted to speech.

---

# Running the Project

Install the required libraries:

```
pip install opencv-python tensorflow numpy pyttsx3 cvzone
```

Run the prediction program:

```
python final_pred.py
```

---

# Author

Prachi Ankush

---
