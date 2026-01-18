# Real-Time Age, Gender and Female Accessory Detection Using Deep Learning

## 📌 Project Overview
This project presents a real-time computer vision system that performs **face detection, age estimation, gender classification, and female accessory detection** using deep learning techniques. The system integrates multiple models to improve gender prediction accuracy, especially for females, by considering visual accessories such as earrings, necklaces, bangles, and glasses.

The application works in real-time using a webcam and runs entirely offline.

---

## 🎯 Objectives
- Detect human faces in real-time using a webcam.
- Predict **age group** and **gender** from facial images.
- Detect **female accessories** such as earrings, necklaces, bangles, watches, and glasses.
- Improve gender prediction reliability by combining facial features with accessory detection.
- Build an efficient system that runs on standard hardware without GPU dependency.

---

## 🛠 Technologies Used
- **Python**
- **OpenCV**
- **MTCNN** – Face Detection
- **MobileNetV2 (Keras)** – Gender Classification
- **Caffe DNN Models** – Age Prediction
- **YOLOv8** – Jewelry / Accessory Detection
- **TensorFlow & Keras**
- **Ultralytics YOLOv8**

---

## 🧠 System Architecture
1. Webcam captures live video frames.
2. MTCNN detects faces in the frame.
3. MobileNetV2 predicts gender from face images.
4. Caffe-based DNN predicts age group.
5. YOLOv8 detects accessories such as earrings, necklaces, bangles, etc.
6. All predictions are displayed together in real time.


