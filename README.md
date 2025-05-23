# 😷 Face Mask Detection with Live Alert System

## 📌 Project Overview
This project detects whether a person is wearing a face mask in real-time using a webcam. It leverages deep learning (CNN) for classification and OpenCV with Haar Cascade classifiers for face detection. A live alert system is triggered when a person without a mask is detected. Optionally, the system can be deployed using Flask.

---

## 🎯 Objective
To develop a real-time, webcam-based application that can:
- Detect faces using Haar Cascades.
- Classify whether a face is wearing a mask or not.
- Alert when a person is detected without a mask.


---

## 🛠️ Tools & Technologies Used
- **Python**
- **OpenCV** – face detection and video stream
- **TensorFlow / Keras** – CNN model training
- **Haar Cascades** – face detection
- **NumPy, scikit-learn** – data processing and model evaluation
- **Jupyter Notebook** – development environment
- **Flask** *(optional)* – web deployment

---

## 📁 Project Structure
FaceMaskDetection/
├── dataset/
│ ├── with_mask/
│ └── without_mask/
├── haarcascade/
│ └── haarcascade_frontalface_default.xml
├── model/
│ └── mask_detector_model.h5
├── 1_data_preprocessing.ipynb
├── 2_model_training.ipynb
├── 3_real_time_detection.ipynb
├── README.md
└── requirements.txt


---

## 🔍 How It Works
1. **Preprocessing** – Load, grayscale, and resize images.
2. **Model Training** – Train a CNN classifier to detect mask usage.
3. **Face Detection** – Detect faces using Haar Cascades in real-time.
4. **Mask Classification** – Use the trained model to classify the detected face.
5. **Alert System** – Print/log alert when a person is not wearing a mask.

---

🔹 Step 3: Run Each Jupyter Notebook
1_data_preprocessing.ipynb – preprocess dataset

2_model_training.ipynb – train and save the model

3_real_time_detection.ipynb – run real-time mask detection



AUTHOR :HRIDIKA



