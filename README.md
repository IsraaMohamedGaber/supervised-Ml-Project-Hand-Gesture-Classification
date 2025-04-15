# supervised-Ml-Project-Hand-Gesture-Classification
Hand Gesture Classification Using MediaPipe Landmarks from the HaGRID Dataset

This project detects hand gestures in real-time using a webcam and classifies them using a machine learning model trained on hand landmark data from **MediaPipe**.

## 🌐 Live Preview

> https://github.com/user-attachments/assets/dd721627-e653-45dc-b975-1e0e4a9dd2dc
 ---


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

## 📁 Download Dataset and Pretrained Model
To download all necessary files (dataset, trained model, additional resources), use the following Google Drive link:

📂 Google Drive Link: [Click Here](https://drive.google.com/drive/folders/1iEuLvwqERhEHTEmC5vn79pMtNRq8X9Ny?usp=sharing)

- After downloading:

- Place the dataset inside the data/ directory.

- Place the trained model (best_model.pkl) inside the models/ directory.

