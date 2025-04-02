# supervised-Ml-Project-Hand-Gesture-Classification
Hand Gesture Classification Using MediaPipe Landmarks from the HaGRID Dataset

This project detects hand gestures in real-time using a webcam and classifies them using a machine learning model trained on hand landmark data from **MediaPipe**.

## 📌 Features
- 📷 Real-time hand tracking using **OpenCV** and **MediaPipe**
- 🧠 Machine learning classification using **Random Forest, SVM, and KNN**
- 🎯 Normalization of hand landmarks for accurate prediction
- ✅ Pre-trained model for quick usage

## 🔍 How It Works
- MediaPipe Hands detects 21 hand landmarks from a live webcam feed.
- The landmarks are normalized (relative to the wrist position).
- The trained machine learning model predicts the gesture based on these landmarks.
- The predicted gesture is displayed on the webcam feed. 

## 🎯 Model Training
The model was trained using:

- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

The best-performing model is saved as models/best_model.pkl.
