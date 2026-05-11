# 💷 Egyptian Currency Recognition System (AI-Powered)

![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-blue)
![Python](https://img.shields.io/badge/Python-3.10-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

The **Egyptian Currency Recognition System** is an AI-powered computer vision project designed to detect and classify Egyptian banknotes in real time using the **YOLOv8** object detection model. The system can recognize multiple currency denominations from live camera input, OR images making it useful for smart financial applications and assistive technologies.

The project was developed using **Python**, **YOLOv8**, **OpenCV**, and **Streamlit**

---

## 🚀 Features

* 💵 Detect Egyptian banknotes in real time
* 📷 Image upload support
* 🧠 YOLOv8 deep learning model
* ⚡ Fast and lightweight inference
* 📊 Confidence score visualization
* 🖥️ Interactive Streamlit web application
* 📦 Easy deployment and customization

---

## 🧠 Model Architecture

The project uses the **YOLOv8 Nano (yolov8n)** model from Ultralytics for efficient and fast object detection.

### Training Configuration

* Model: `yolov8n.pt`
* Image Size: `640x640`
* Framework: Ultralytics YOLOv8
* Training Environment: GPU Accelerated
* Epochs: 50
* Task: Object Detection

---

## 📂 Dataset

The dataset consists of labeled Egyptian currency images covering different denominations under varying:

* Lighting conditions
* Angles and orientations
* Distances
* Backgrounds

### Dataset Split

| Dataset    | Percentage |
| ---------- | ---------- |
| Training   | 70%        |
| Validation | 20%        |
| Testing    | 10%        |

---

## 📊 Model Performance

The trained model achieved high accuracy on the testing dataset.

| Metric    | Score |
| --------- | ----- |
| Precision | 99.8% |
| Recall    | 100%  |
| mAP50     | 99.4% |

---

## 📁 Project Structure

```bash
Egyptian-Currency-Recognition/
│
├── app/
│   └── streamlit_app.py
│
├── models/
│   └── best.pt
│
├── notebooks/
│   ├── Data_Analytics.ipynb
│   ├── Model_Training.ipynb
│   └── Testing.ipynb
│
├── dataset/
│   ├── train/
│   ├── valid/
│   └── test/
│
├── results/
│   ├── confusion_matrix.png
│   ├── results.png
│   └── predictions/
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Egyptian-Currency-Recognition.git
cd Egyptian-Currency-Recognition
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install ultralytics opencv-python streamlit pillow
```

---

## ▶️ Run the Application

Launch the Streamlit app using:

```bash
streamlit run app/streamlit_app.py
```

The application will open in your browser automatically.

---

## 🖼️ Detection Workflow

1. Upload an image or video
2. YOLOv8 processes the input
3. Currency notes are detected and classified
4. Bounding boxes and confidence scores are displayed
5. Final annotated output is shown to the user

---

## 📈 Training Results

### 1. Real-Time Detection

The model accurately detects multiple Egyptian banknotes simultaneously with high confidence.
<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/f7c10953-bffe-4d09-b68e-c0ef08c8d524" />


### 2. Confusion Matrix

The normalized confusion matrix demonstrates near-perfect classification across all classes.
<img width="3000" height="2250" alt="image" src="https://github.com/user-attachments/assets/a0b9b65c-de64-417a-a9ce-500378d1438b" />


### 3. Training Curves

Loss curves show stable convergence while precision and recall rapidly improve during training.
<img width="2250" height="1500" alt="image" src="https://github.com/user-attachments/assets/ff8cf9d9-eb56-45f6-afb6-c118e2d05ab1" />


---

## 🛠️ Technologies Used

* Python
* YOLOv8
* Ultralytics
* OpenCV
* Streamlit
* NumPy
* Matplotlib
* PIL

---

## 📱 Future Improvements

* 📲 Mobile application integration
* 🔊 Voice feedback for visually impaired users
* ☁️ Cloud deployment
* 💳 Support for additional Egyptian currency versions
* 🧾 Currency counting and total calculation

---

## 👨‍💻 Developer

**Sarah El Khouly**
Mechanical Engineering Graduate | Data Science & AI Enthusiast

* LinkedIn: https://www.linkedin.com/in/sarah-el-khouly-423307247/ 
* GitHub: https://github.com/SarahelKhouly-sok 

---

## ⭐ Acknowledgment

Special thanks to the **Ultralytics YOLOv8** team and the open-source AI community for providing powerful tools that made this project possible.
