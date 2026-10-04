# Real-Time Image Classification using CNN

This project is a **real-time image classification system** built using Python, OpenCV, and TensorFlow/Keras.

It uses a computer's **webcam** to capture live video and a pre-trained **MobileNetV2 CNN model** to identify objects in the video.

## 🚀 Features

* Real-time image classification using webcam
* Pre-trained MobileNetV2 CNN model
* ImageNet-based object recognition
* Displays predicted object with confidence percentage
* Press **`q`** to exit

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* TensorFlow/Keras
* MobileNetV2
* ImageNet

## 📦 Installation

Install the required libraries:

```bash
pip install opencv-python numpy tensorflow
```

## ▶️ Run the Project

```bash
python3 ImageClassifier.py
```

Make sure your webcam is connected and working.

Press **`q`** to close the application.

## 🔄 Project Flow

```text
Webcam
   ↓
Image Capture
   ↓
Image Preprocessing
   ↓
MobileNetV2 CNN
   ↓
Object Prediction
   ↓
Display Result
```

## 🧠 Model

**MobileNetV2** is a lightweight pre-trained Convolutional Neural Network (CNN) trained on the **ImageNet** dataset.

It can recognize many common objects from images.

## ⚠️ Note

This project performs **image classification**, not object detection. It predicts the main object in the image but does not draw bounding boxes.

## 👨‍💻 Author : - Deep Jadhav
